# Cabeceras
# Cabecera h1
## Cabecera h2
### Cabecera h3
#### Cabecera h4
##### Cabecera h5
###### Cabecera h6


# Underlines
Underline 1
-------------
Underline 2
=============


# Formatos de énfasis
Formato *itálica* forma 1.\
Formato _itálica_ forma 2.\
Formato **bold o strong** forma 1.\
Formato __bold o strong__ forma 2.\
Formato ~~tachado~~.\
Aquí podemos combinar los formatos *itálica*, **bold** y ~~tachado~~.


# Listas

## Lista ordenada
1. Item 
2. Item 
3. Item 

## Lista desordenada
- Item 
- Item 
- Item 


# Enlaces
<a href="https://www.google.com/">Link html</a> \
[Link en markDown](https://www.google.com/) \
[Link a Index](index.html)


# Imágenes
![Logo Github](https://cdn-icons-png.flaticon.com/512/25/25231.png)



# Code snippets

## JSON
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

## Javascript
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

| Nombre | Apellido | DNI |
| ------ | -------- | --- |
| Maxi | Burgos | 11111111 |
| Tomas | Tompson | 22222222 |
