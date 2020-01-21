# Automatizacion de dibujos para autoCAD
 
 ### ¿Para que sirve?
 
Esta implementación para el software AutoCAD fue desarollado para ahorrar considerablemente el tiempo de trabajo al dibujar la pieza y el margen de error en al dibujar los perfiles conformados a partir de bobinas con forma de C y Z para la sujetacion de las estructuras metalicas tanto en el lateral como en el techo comunmente conocidas como correas conformadas para techo y laterales, estas pueden existir en varios espesores y medidas de pliege ademas tienen orificios para la sujetación con bulones al esqueleto de la estructura los cuales deben tener una medida exacta.
![Image of Yaktocat](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR9dQrBLgtC5Eqjh8C1gA5lJuWf8GljgQMgf-zQa6qO1VyF8J_b&s)


### ¿Que tipos de errores puede disminuir?

al necesitar una riguroza atención en el dibujo ya que 100 milimetros de diferencia puede entorpercer el montaje de un galpon conciderablemente, al hacerse en volumen el margen de perdida monetaria ademas de aumentar los tiempos de entrega por un error de longitudes es muy alto. Por estadistica una persona lleva alrededor de 1 semana para terminar todas las correas de una obra de medidas estandar, gracias a el automatizador de dibujos la tarea se reduce a unas pocas horas.
 
Plano para la conformación de correas
![Image of correas](https://fotos.subefotos.com/c510d6806db57de057ece1d3e686ce3ao.png)
 
 
 ### ¿Como se usa?
 Abrir el template que se subio a este repositorio luego llamar al comando "NETLOAD" en AutoCAD para cargar librerias externas    buscar el archivo .dll que tambien se encuentra en este repositorio si se hizo todo bien ahora solo queda llamar al comando "CREARCORREAS" y dar enter. se les abrira una ventana para iniciar a cargar los parametros una vez este todo se clickea en el boton "Crear" y la pieza se generara aumaticamente con las medidas especificadas.
 
 Los parametros que pide la libreria son:
 * el tipo de correa
 * la longitud que existe entre los ejes de la estructura
 * la medida del solape entre correas de ambos lados lado A(0, 600, 900, 1200) y lado B(0, 600, 900, 1200)
 * tornapunta A(0, 600, 900) y tornapunta B(0, 600, 900)
 * lleva strut(si/no) 
 * ranuras para tillas (0, 1, 2 , 3)
 
 Fragmento de prueba haciendo uso de la libreria.
 
![](https://media.giphy.com/media/MDgLs01wwb94N6OlWT/giphy.gif) 
