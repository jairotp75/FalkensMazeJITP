# FalkensMazeJITP

## Autor
Jairo Tucta

## Descripción
Falken'sMaze es una aplicación diseñada para crear y editar laberintos de manera intuitiva y eficiente. Con esta herramienta, se puede diseñar laberintos complejos.

## Funcionamiento
La aplicación tiene un menú principal con las opciones de Archivo y Opciones. En el menú Archivo, los usuarios pueden crear un nuevo laberinto, guardar un laberinto existente o abrir un laberinto guardado de antes. En el menú Opciones, los usuarios pueden seleccionar un sonido para el laberinto y establecer un tiempo para el laberinto.

El laberinto se representa en un "MazeCanvas", que ess el área principal de trabajo donde los usuarios pueden dibujar y diseñar sus laberintos. Cada celda del laberinto puede ser un camino o una pared, y los usuarios pueden cambiar el tipo de celda haciendo clic en ella. El número de filas y columnas pueden ser ajustado por el usuario y este usuario podrá seleccionar diferentes tipos de bloques del "BlocksPanel"y colocarlos en el "MazeCanvas" para crear el laberinto. El  "BlocksPanel" es un panel lateral que contiene diferentes tipos de bloques que los usuarios pueden colocar en el MazeCanvas.

El laberinro contendrá un "MenuBar", que es un menú que se situa en la parte superior de la aplicación que proporciona varias opciones y funcionalidades. Los usuarios pueden crear un nuevo laberinto, guardar su laberinto actual, cargar un laberinto guardado de antes, seleccionar un sonido para el laberinto y establecer un tiempo para el laberinto.

Cuando los usuarios seleccionan Nuevo en el menú Archivo, se muestra un "DialogSize" que permite a los usuarios especificar el tamaño del nuevo laberinto. Cuando los usuarios seleccionan Guardar, se utiliza un "FileChooser" para seleccionar dónde guardar el laberinto. El laberinto se guarda utilizando la clase "Maze", que representa el estado actual del laberinto.
Y por último la aplicación también permite a los usuarios seleccionar un archivo de sonido para su laberinto y establecer un tiempo para su laberinto a través del menú Opciones.


## Imagen de la aplicación
![Captura de Ent Doc3](https://github.com/jairotp75/FalkensMazeJITP/assets/158313902/4387c6e4-6998-4425-8c06-b3c61c096e68)
