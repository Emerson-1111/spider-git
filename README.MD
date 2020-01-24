# cabeceras
# cabecera h1
## cabecera h2
### cabecera h3
#### cabecera h4
##### cabecera h5
###### cabecera h6

# undelines
underline 1
-----------

underline 2
============

# formatos de enfasis
- formato *italica* primera forma.
- formato _italica_ segunda forma.
- formato **bold o strong** primera forma.
- formato __bold o strong__ segunda forma.
- formato ~~tachado~~.

# listas
1. formato lista ordenada.
2. formato lista ordenada.
3. formato lista ordenada.
- formato lista desordenada.
- formato lista desordenada.
- formato lista desordenada.

# links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link Markdown](http://www.google.com)
- [Esto es un link a index](index.html)

# imagenes
![imagen](http://jet-studio.com/images/logos/2/stark.png)

# code snippets
Codigo JSON
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
Codigo Javascript
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