# Metodo GET y POST HTTP

**Ejemplo de url que se envia al servidor:**

```url
127.0.0.1/index.html?nombre=&apellido=
```

Query string: es la informacion que se envia al servidor.

```url
nombre=&apellido=
```

Empieza **despues de ?**.

Para evitar que se vea la **query string** al enviar la informacion se tiene que cambiar el metodo HTTP
por defecto al crear un `form` se utiliza el metodo GET pero si se llama al atributo `method` desde la etiqueta `form`
podemos cambiar el metodo HTTP.

**Ejemplo:**

```html
<form method="post">
</form>
```
