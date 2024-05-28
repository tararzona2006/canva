# Juegos con HTML5

## Elemento Canvas

- El elemento Canvas, junto  el lenguaje JS nos permite crear animaciones y juegos 2d en el navegador

- En el navegador el codigo se interpreta de manera secuencial.

- Para utiliar el codigo JS, debemos esperar a que todos los elementos HTML hayan sido creados antes de ser utilizados.

- Alternativas:
    - Colocar el script en la parte inferior de la pagina.
    - Utilizar un detector de eventos que se indique cuando los elementos han sido creados. (evento onload desde el body o script)

- se crea una variable canvas por medio del identificador de la etiqueta 
- se verifica si la variable se creo correctamente.
- en realidad se trabaja con el **contexto** de canvas 2d. Se crea una variable **ctx** con la cual se manipula canvas.
- se verifica que el contexto se haya credo de manera exitosa dando la bienvenida por medio de un alert(), o advirtiendo un error de creacion de contexto