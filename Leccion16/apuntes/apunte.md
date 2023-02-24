# Formularios en HTML

Permiten capturar informacion en una pagina web.

**Ejemplo:**

```html
<form>
      <label for="nombre">Nombre:</label>
      <br />
      <input
        type="text"
        id="nombre"
        name="nombre"
        placeholder="Escribe tu nombre"
        required
      />
      <br />
      <label for="apellido">Apellido:</label>
      <br />
      <input
        type="text"
        id="apellido"
        name="apellido"
        placeholder="Escribe tu apellido"
        required
      />
      <br />
      <input type="submit" value="Enviar" />
      <input type="submit" formnovalidate="formnovalidate" value="Enviar sin validar">
    </form>
```

## Detalles importantes

* etiqueta `input`: permite capturar informacion con el atributo `type` especificas el tipo de dato a capturar es altamente recomendable agregar un `id`.
* etiqueta `label`: para dar una descripcion al dato a enviar el atributo `for` ayuda a relacionar el `label` con el `input` y al dar click al `label` poder llenar directamente el `input`.
* atributo `name`: sirve para que los datos que enviemos aparezcan en la url y asi saber que tipo de dato son **(atributo de la etiqueta input)**.
* atributo `placeholder`: informacion de guia en el `input` **(atributo de la etiqueta input)**.
* atributo `required`: sirve para hacer que un `input` sea obligatorio que tenga un valor antes de enviarse **(atributo de la etiqueta input)**.
* atributo `novalite`: sirve para hacer que el formulario completo no sea validado **(atributo de la etiqueta form)**.
* atributo `value`: informacion que se se vera en el boton en el html **(atributo de la etiqueta input)**.
* atributo `formnovalidate`: Hace que la informacion a enviar no sea validada **(atributo de la etiqueta input)**.
