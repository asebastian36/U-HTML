# Elementos select y textArea en HTML

**Ejemplo de uso de select:**

```html
<label for="autos">Marca de autos preferida:</label>
<br />
<select name="autos" id="autos" multiple="true">
  <option value="otro">Otro</option>
  <option value="ford">Ford</option>
  <option value="chevrolet">Chevrolet</option>
  <option value="bmw">BMW</option>
  <option value="toyota" selected="true">Toyota</option>
  <option value="cadillac">Cadillac</option>
  <option value="ninguno">Ninguno</option>
</select>
<br />
```

La etiqueta `select` se utiliza para definir el campo, la etiqueta `option` se utiliza para definir una opcion a enviar el atributo `value` es el valor que se envia al servidor si se elige esa opcion, el atributo `selected` hace que la opcion en la que se aplique se muestre primero en el `select`. Si queremos que nuestro `select` pueda enviar multiples elecciones podemos agregar el atributo `multiple`.

> El enviar multiples argumentos en un `select` funciona de similar manera en el **query string** a un `checkbox`.

**Ejemplo de uso del textArea:**

```html
<!--campo textArea para los comentarios-->
<label for="comentario">Envianos tus comentarios:</label>
<br />
<textarea
  name="comentario"
  id="comentario"
  cols="30"
  rows="10"
  placeholder="escribe tu comentario aqui"
></textarea>
<br />
```

El `textarea` define un recuadro donde colocar texto, el atributo `cols` especifica cuantas columnas tendra visualmente y el atributo `rows` cuantos renglones tendra visualmente.
