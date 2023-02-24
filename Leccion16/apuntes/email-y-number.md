# Tipos email y number en formularios en HTML

> Al enviar informacion con caracteres con el metodo GET, HTML utiliza una codificacion de caracteres especiales
> se conoce como **HTML URL encoding**.

**Ejemplo:**

```url
?nombre=Juan+Carlos&apellido=Perez&emailjperez%40email.com
```

Este es un **ejemplo** donde se lleno un formulario con el nombre `Juan Carlos` y el apellido `Perez` con el email `jperez@email.com`

* atributo `step`: ayuda a recibir valores numericos de todo tipo en un `input` de tipo numerico con la cadena `"any"`.

**Ejemplo:**

```html
<label for="edad">Edad:</label>
<br />
<input
  type="number"
  id="edad"
  placeholder="Escribe tu edad"
  required
  step="any"
/>
```
