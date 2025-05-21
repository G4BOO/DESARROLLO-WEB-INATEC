Intrucciones

## Instrucciones

1. **Agrega la etiqueta de viewport**

   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   ```

2. **Define las letras en función de `vw`**  
   En tu CSS, coloca en el `body`:

   ```css
   body {
     font-size: 3vw;
   }
   ```

3. **Coloca los espacios en `vh` y `vw`**  
   Cambia en el `header`:

   ```css
   header {
     padding: 1vh 1vw;
     border-radius: 1vh;
     margin-bottom: 1vh;
   }
   ```

   Cambia en el `footer`:

   ```css
   footer {
     padding-top: 1vw;
     margin-top: 1vw;
   }
   ```

4. **Redimensiona el navegador**  
   Observa cómo se adaptan los tamaños de letras y espacios al cambiar el tamaño de la ventana.
