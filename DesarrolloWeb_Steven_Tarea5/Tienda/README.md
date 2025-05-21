# Instrucciones

## Diagramaciones con Flexbox

### 1. Tres filas con `display: flex`

```css
.contenedor {
  display: flex;
  flex-direction: row;
}
```

### 2. Columnas con la clase `column`

```css
#contenido {
  display: flex;
  flex-direction: column;
}
```

---

## Diagramaciones de "productos destacados"

### Dos columnas (cada producto 50%)

```css
#destacados .contenedor > div {
  text-align: center;
  padding: 10px;
  margin: 10px;
  background-color: white;
  width: 50%;
}
```

### Tres columnas (cada producto 33.3%)

```css
#ofertas .contenedor > div {
  text-align: center;
  padding: 10px;
  margin: 10px;
  background-color: white;
  width: 33.3%;
}
```

### Cuatro columnas (cada producto 25%)

```css
#disponible .contenedor > div {
  text-align: center;
  padding: 10px;
  border: solid 5px coral;
  background-color: white;
  width: 25%;
}
```

---

## Instrucciones de Estilo

- **Título de destacados:**  
   Agrega un selector para el título y aplica sombra con:

  ```css
  text-shadow: 0 0 3px white;
  ```

- **Productos con ofertas:**  
   Aplica sombra de caja simple:

  ```css
  box-shadow: 4px 8px;
  ```

- **Productos disponibles:**  
   Aplica sombra de caja con color específico:

  ```css
  box-shadow: 4px 8px #d46a6a;
  ```

- **Título de las ofertas:**  
   Aplica doble sombra:

  ```css
  text-shadow: 1px 1px 2px white, 0 0 30px #d46a6a;
  ```

- **Productos destacados:**  
   Aplica sombra avanzada:
  ```css
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(255, 255, 0, 0.3);
  ```
