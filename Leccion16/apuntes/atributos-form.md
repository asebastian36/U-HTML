# Atributos del elemento form en HTML

> Todos estos atributos son pertenecientes a la etiqueta `form`.

* atributo `action`: podemos indicar que componente del lado del servidor o la url que va a procesar este servidor.
* atributo `target`: podemos indicar que la respuesta del lado del servidor se cargue desde la misma ventana con el argumento `"_self"` o si queremos que la respuesta se muestre en otra ventana podemos usar el argumento `"_blank"`.
* atributo `autocomplete`: nos permite denegar el uso de autocompletados que brinda el navegador.

**Ejemplo de uso de estos atributos:**

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

    </form>
  </body>
</html>
```
