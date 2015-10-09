##Test de Conocimientos de Desarrollo Frontend

Preparado por *Alfonso Cabargas*

27 de Agosto de 2015

---

###Antecedentes Generales:

1. ¿Cuál es el navegador que utiliza principalmente para el desarrollo y qué herramientas de desarrollo usa?.
+ Mencione tres formas para disminuir el tiempo de carga de una página (tiempo real o percibido).
+ Si se ha unido a un proyecto y los desarrolladores usan tabs y usted usa espacios, ¿qué hace?.
+ ¿Sabe que es el FOUC? ¿Cómo lo evita?.

---

###Preguntas Específicas de Lenguaje:

####HTML

1. ¿Qué función cumple el `doctype` y cuántos puede nombrar?
+ ¿Para qué son buenos los atributos `data-`?
+ Describa la diferencia entre cookies, sessionStorage y localStorage.
+ ¿Porque es generalmente una buena idea posicionar una etiqueta `<link>` referenciando a CSS entre `<head></head>` y los `<script>`s JavaScript justo antes de `</body>`? 
+ ¿Cuál de estas dos opciones es HTML5 válido?

```html
<input type="submit" disabled="disabled" />
```

```html
<label><input type=checkbox checked name=cheese disabled> Cheese</label>
```

####CSS

1. Describa qué es un archivo "reset" y por qué es útil.
+ Describa qué son los "floats" y su funcionamiento.
+ ¿Cuál es la diferencia entre `inline` y `inline-block`?
+ ¿Cuál es la diferencia entre las posiciones `relative`, `fixed`, `absolute` y `static` para un elemento dado?
+ Explique cómo entiende el box model (modelo de cajas).
+ Describa qué es `@media`, `pseudo-class` y `pseudo-element` y la diferencia entre estas dos últimas.
+ Nombre al menos 5 `pseudo-elements`.

####JavaScript

1. Explique cómo funciona `this` en JavaScript.
+ Explique el termino "event delegation".
+ ¿Cuál es la diferencia entre: `function Person(){}`, `var person = Person()` y `var person = new Person()`?
+ Explique AJAX con tanto detalle como pueda.
+ ¿Cuál es la diferencia entre un "atributo" y una "propiedad"?

---

###Preguntas de VCS (Bonus):

1. ¿Qué sistemas de control de versiones ha usado?
+ ¿Cúal prefiere y porqué?
+ Usted y otro compañero modificaron el mismo archivo, ¿Cómo procede para enviar sus cambios al repositorio?
+ Explique el término `branch` (rama) y `tag` (etiqueta).

---

###Preguntas de Código:

+ ¿Cuál es el resultado de la siguiente sentencia?

```js
 "Diego's house is pretty nice".split("").reverse().join("");
```
+ ¿Cuál es el error en el siguiente código y cómo lo corregiría?

```html
<div id="navigation-path">
	<a class="nav-link" href="http://startupchile.org/demoday">Demo Day</a>
	
<div id="navigation-path">
	<a class="nav-link" href="http://startupchile.org/apply">Apply</a>	
</div>
```

+ ¿Cuál es el valor de `window.foo`?

```js
( window.foo || ( window.foo = "bar" ) );
```

+ ¿Qué output produce el siguiente CSS (ver HTML de ejemplo)?

```css
q::before { 
  content: "«";
  color: blue;
}
q::after { 
  content: "»";
  color: red;
}
```

```html
<q>Luke</q>, dijo, <q>yo soy tu padre</q>.
```