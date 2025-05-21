Intrucciones

### Instrucciones de estilos responsivos

1. **Estilo para móviles:**  
   Aplica el siguiente CSS para que todas las cajas `.c1`, `.c2`, `.c3`, `.c4`, `.c5` ocupen el 100% del ancho.

   ```css
   .c1,
   .c2,
   .c3,
   .c4,
   .c5 {
     width: 100%;
   }
   ```

2. **Estilo para tabletas:**  
   Usa una media query para que, a partir de 600px de ancho, las cajas `.c2`, `.c3`, `.c4`, `.c5` ocupen el 50% del ancho.

   ```css
   @media (min-width: 600px) {
     .c2,
     .c3,
     .c4,
     .c5 {
       width: 50%;
     }
   }
   ```

3. **Estilo para escritorio:**  
   A partir de 800px de ancho, configura los anchos de las cajas y centra el contenedor:
   ```css
   @media (min-width: 800px) {
     .c1 {
       width: 100%;
     }
     .c2 {
       width: 100%;
     }
     .c3,
     .c4,
     .c5 {
       width: 33.33%;
     }
     .container {
       width: 800px;
       margin-left: auto;
       margin-right: auto;
     }
   }
   ```

Observa cómo cambian las cajas según el tamaño de la pantalla.
