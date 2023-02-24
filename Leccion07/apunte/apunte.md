# Rutas relativas y rutas absolutas

Ejemplo de un link con ruta relativa:

```html
<a href="contenido.html">Ir a contenido</a>
```

ejemplo de la misma ruta pero ahora absoluta:

```html
<a href="http://localhost:5500/contenido.html">Ir a contenido</a>
```

> solo usar rutas relativas cuando el link va a un recurso de nuestra aplicacion, si el link va a un recurso externo usar una ruta absoluta.

## Manejar rutas absolutas dentro de la aplicacion

Llamar contenido desde una carpeta en la raiz de la aplicacion:

```html
<a href="web/contenido.html">Ir a contenido</a>
```

Y si el index no esta en la raiz:

```html
<a href="/web/contenido.html">Ir a contenido</a>
```

La primera '/' hace que el buscador empieze a buscar desde la raiz de la aplicacion, aunque el index no este en la raiz.

> La carpeta en donde inicia la aplicacion se llama context root o raiz del pyoyecto web.
