# Version del curso
Version Actual: 1.2.2


# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underline
Underine 1
----------
Underine 2
==========

# Formatos de endasis
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aquí podemos usar *formato italico*, pero también **bold** y ~~tachado~~

# Listas
### Ordena
1. Esto es un ítem de lista ordenada.
1. Esto es un ítem de lista ordenada.
1. Esto es un ítem de lista ordenada.

### Desordenada
- Esto es un ítem de lista ordenada.
- Esto es un ítem de lista ordenada.
- Esto es un ítem de lista ordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdwon](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

# Code snippets
Codigo en JSON
```JSON
{
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
}
```

# Code snippets
Codigo en Javascript
```Javascript
function $initHighlight(block, cls) {
    try {
        if (cls.search(/\bno\-highlight\b/) != -1)
            return process(block, true, 0x0F) +
                ` class="$(cls)"`;
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

export $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
Juan | Nizama | 88888888 |
Jose | Ramos | 99999999 |

# Citas
Esto es un texto referente a una cita que podremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Lineas divisoras
Esto es un texto que sera dividido por guiones medios.

---
Esti es otro texto dividido por asteriscos.

***

Esti es otro texto dividido por guiones bajos.

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segunfo parrafo.

Esto es nuestro tercer parrafo.
- Lista