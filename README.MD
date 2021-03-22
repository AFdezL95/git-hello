#Cabeceras
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

# Formátos de enfasis
- formato *itálica* de la primera forma.
- formato _itálica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aquí podemos *usar formato italico*, pero también **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada(es un ol de HTML).
2. Esto es un item de lista ordenada(es un ol de HTML).
3. Esto es un item de lista ordenada(es un ol de HTML).
- Esto es un item de lista desordenada(es un ul de HTML).
- Esto es un item de lista desordenada(es un ul de HTML).
- Esto es un item de lista desordenada(es un ul de HTML).

# Links
- <a href="http://www.google.com">Esto es un link HTML(markdown soporta HTML)</a>
- [Esto es un link en Markdown](http://wwww.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://image.flaticon.com/icons/png/512/25/25231.png)



# Code Snippets

https://highlightjs.org/static/demo/

Código en JSON:
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
Código en Javascript:

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

# Tablas
| Nombre | Apellido | Documento |
|--------| -------- | --------- |
|Maxi |Burgos | 231548O |
|Tom |Madrid | 245620P |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto ya es otro texto que no se relaciona con la cita anterior porque le hems dado doble enter.

> Esto es otra cita.

# Líneas Divisoras
(Recordar separa con un enter para que no subraye)

Esto es un texto que será dividido por guiones medios

--- 
Esto es un texto que será dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajos.

___

# Saltos de línea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista