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
# Formatos de Enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** primer forma
- formato __bold o strong__ segunda forma
- formato ~~tachado~~, formato normal.
- Agui podemos usar formato *italica* y tambien **bold** y ~~tachado~~. 
# Listas
1. Esto es un item ordenada
2. Esto es un item ordenada
3. Esto es un item ordenada
- Esto es ub item de lista desordenada
- Esto es ub item de lista desordenada
- Esto es ub item de lista desordenada

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en MarkDown](http:/google.com)
- [Esto es un link index](index.html)

# Imagenes
![Logo GitHub](https://logos-marcas.com/wp-content/uploads/2020/11/GitHub-Logo-650x366.png)

# Code Snippets
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

Codigo en JavaScript
```Javascript
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