# Radiobuttons y checkboxes en formularios HTML

**Ejemplo de radiobuttons:**

```html
<label>Genero:</label>
<br />
<input
  type="radio"
  id="femenino"
  name="genero"
  value="femenino"
/>
<label for="femenino">Femenino</label>
<input
  type="radio"
  id="masculino"
  name="genero"
  value="masculino"
/>
<label for="masculino">Masculino</label>
<br />
```

**Ejemplo de checkbottons:**

```html
<label for="genero-musical">Genero de musica preferidos:</label>
<br />
<input type="checkbox" id="rock" name="genero-musical" value="rock" />
<label for="genero-musical">Rock</label>
<input type="checkbox" id="pop" name="genero-musical" value="pop" />
<label for="genero-musical">Pop</label>
<input type="checkbox" id="bachata" name="genero-musical" value="bachate" />
<label for="genero-musical">Bachata</label>
<input type="checkbox" id="regional-mexicano" name="genero-musical" value="regional-mexicano" />
<label for="genero-musical">Regional-mexicano</label>
<input type="checkbox" id="otro" name="genero-musical" value="otro" />
<label for="genero-musical">Otro</label>
<br>
```

> La diferencia entre los **radiobuttons** y **checkbottons** es que en este ejemplo el **radiobutton** solo se puede elegir un genero dado que se especifica en el atributo `name` un genero como unico valor en ambos `input` de tipo `radio`, mientras que en el tipo **checkbottons** podemos guardar mas de un tipo de valor aunque usemos el mismo `name` en todas las opciones.
