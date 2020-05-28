# Version del Curso
Version Actual: v1.3.2

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- letra *italica* de la primer forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~.

# Listas
1. Este es un item lista ordenada.
2. Este es un item lista ordenada.
3. Este es un item lista ordenada.

- Este es un item lista desordenada.
- Este es un item lista desordenada.
- Este es un item lista desordenada.

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markgrown](http://google.com) 
- [Esto es un link en a index](index.html) 

# Imagenes
![Logo Github](https://i.pinimg.com/564x/dc/1a/1a/dc1a1a4287f57e4a80ea5ecfd912ee96.jpg)

# Code Snippets
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

```JavaScript
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
| Nombre   | Apellido   | Documento |
| ------   | --------   | --------- |
| Alfonso  | Calero     | 123124234 |
| Daniela  | Rodriguez  | 098748366 |

# Citas o Blackpood
Esto es un texto referente a una cita que se encuentra abajo
> Esto es una cita.

Esto es otro texto sin relacion con la cita anterior.
> Esta es otra cita.

# Lineas Horizontales
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajos.

___

# Saltos de Linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro segundo parrafo.
- Lista ejemplo diferencia.

#

Soy un readme ejemplo de **MARKGROWN** & Uso de **HIGHLIGHT JS**.
