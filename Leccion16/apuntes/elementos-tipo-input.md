# Mas elementos de tipo input

* `input` de tipo `reset`: permite reestablecer los valores del formulario a los valores por defecto.
* atributo `readonly`: nos ayuda a mostrar informacion del servidor, pero esta informacion no se podra modificar dado que sera de solo lectura para el usuario, sin embargo esta informacion sera parte de la que se enviara al servidor.
* `input` de tipo `hidden`: es un `input` oculto pero que si se enviara esta informacion al servidor.
* atributo `disabled`: Deshabilita el `input` y ya no sera posible rellenar valores en el y tampoco se enviara informacion de este `input` al servidor.

**Ejemplo del uso de estos atributos:**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Formularios en HTML</title>
  </head>
  <body>
    <h1>Formularios en HTML</h1>
    <!--aqui inicia el formulario-->
    <form method="post" action="mi_servidor" target="_blank" autocomplete="off">
      <label for="Genero musical preferido:">Persona:</label>
      <br />
      <input type="checkbox" id="pop" name="genero-musical" value="pop"/>
      <input type="hidden" id="genero-oculto" name="genero-musical" value="genero-oculto" />
      <label for="probar-campo-desabilitado">Test:</label>
      <br />
      <input
        type="text"
        id="test"
        disabled="true"
        value="1"
      />
      <br />
      <label for="idPersona">Persona:</label>
      <br />
      <input
        type="text"
        id="idPersona"
        readonly="true"
        value="1"
      />
      <br />
      <input type="reset" value="Restablecer" />
    </form>
  </body>
</html>
```
