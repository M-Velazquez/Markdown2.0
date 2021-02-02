# Versión del curso
Versión actual: v1.0.0

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- Letra *italica* de la primer forma.
- Letra _italica_ de la segunda forma.
- Letra **bold o strong** de la primer forma.
- Letra __bold o strong__ de la segunda forma.
- Letra ~~tachada~~.
- Aqui podemos usar letra *italica* pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Makdown](http://www.google.com)

# Imagenes
![Logo github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

#Code snippets
Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Codigo en js
```javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas

| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | Burgos | Documento |
| Tomas | Tompson | Documento |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita

Esto es otro texto que no se relaciona con el texto anterior:
>Esto es otra cita

# Lineas divisoras
Esto es un texto que se será dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos

***

Este es otro texto dividido por guiones bajos.

___

# Saltos de línea

Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro segundo parrafo.
