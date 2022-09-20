# mini-challenge Trabajemos con Listas en Python
## Desafío para la comunidad de Escuela de Datos Vivos

Cuando creamos una lista con strings y aplicamos el método *.sort()* generalmente la lista se ordena alfabéticamente 'bien' 
por ejemplo:

``` python 
lst_frutas = ["anana","manzana","alcachofa","limón","naranja"]
lst_frutas.sort()
print(lst_frutas)
```

``` python
# resultado
['alcachofa', 'ananá', 'limón', 'manzana', 'naranja']
```

## ...Pero ... ¿qué sucede cuando mezclamos minúsculas y mayúsculas?

Para la siguiente lista 
``` python
lst_palabras = ['Antonia','Mariel','Miguel','banana','ananá','Gerardo','naranja','Sofía','Argentina']
print(lst_palabras)
``` 
``` 
['Antonia', 'Mariel', 'Miguel', 'banana', 'ananá', 'Gerardo', 'naranja', 'Sofía', 'Argentina']
``` 
``` 
# ordenamos
lst_palabras.sort()
print(lst_palabras)
``` 

``` 
# resultado
['Antonia',
 'Argentina',
 'Gerardo',
 'Mariel',
 'Miguel',
 'Sofía',
 'ananá', #<-- empieza por a!!! 
 'banana',
 'naranja']
``` 
## ¿Te animas a responder las siguientes preguntas?

1.   ¿Por qué los ordena de esa manera?😱 ¿podrías explicarlo?👨‍🏫👩‍🏫
2.   ¿Python está mal? 🐍
3.   ¿Te animas a ordenar la lista alfabéticamente manteniendo las minúsculas y mayúsculas?🔡🔠 Puedes crear tu propia función que lo resuelva


