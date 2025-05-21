Intrucciones

## Instrucciones

1. **Agrega clases a las imágenes:**

   - A la imagen del primer artículo, agrega la clase `.adaptativa-porcentaje-1`.
   - A la imagen del segundo artículo, agrega la clase `.adaptativa-porcentaje-2`.
   - A la imagen del tercer artículo, agrega la clase `.adaptativa-porcentaje-3`.

2. **Crea los siguientes estilos CSS:**

   ```css
   .adaptativa-porcentaje-1 {
     width: 70%;
   }
   .adaptativa-porcentaje-2 {
     width: 50%;
   }
   .adaptativa-porcentaje-3 {
     width: 20%;
   }
   ```

3. **Observa cómo se adapta la imagen según el tamaño de la ventana del navegador.**

4. **Usa dos puntos de corte (breakpoints):**

   - 600px de ancho
   - 900px de ancho

5. **Oculta el div `#resumen` por defecto:**

   ```css
   #resumen {
     display: none;
   }
   ```

6. **Crea una regla con media query para mostrar el div de resumen al tener más de 600px de ancho:**

   ```css
   @media (min-width: 600px) {
     #resumen {
       display: block;
     }
   }
   ```

7. **Agrega una regla usando media queries para que cuando se tenga más de 600px de ancho se coloque el tamaño de letra a 16px y color rojo:**

   ```css
   @media (min-width: 600px) {
     body {
       font-size: 16px;
       color: red;
     }
   }
   ```

8. **Agrega una regla usando media queries para que cuando se tenga más de 900px de ancho se coloque el tamaño de letra a 14px y color negro:**

   ```css
   @media (min-width: 900px) {
     body {
       font-size: 14px;
       color: black;
     }
   }
   ```

9. **Observa cómo cambian los estilos de acuerdo a los distintos tamaños de pantalla.**
