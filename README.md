# PulpomaticTest

El objeto de la aplicación será seleccionar un punto dentro de un mapa (punto objetivo) y controlar mediante GPS cuando el usuario de la aplicación se acerca al citado punto.

Al abrirse la aplicación te debe mostrarte el mapa de Google Maps centrado en la posición del usuario, con un pin o marcador en su lugar.
La selección del punto objetivo podrá realizarse mediante una caja de búsqueda de dirección, o desplazando el mapa hasta dejar el pin en el punto objetivo.
Debe existir un botón para confirmar el punto objetivo.
Una vez pulsado el punto objetivo se mostrará una caja de texto al pie de la pantalla en la que se indique la distancia del usuario al punto objetivo en línea recta con los siguientes mensajes.
Distancia > 200m: "Estás muy lejos del punto objetivo"
Distancia > 100m y <= 200m: "Estás lejos del punto objetivo"
Distancia > 50m y <= 100m: "Estás próximo al punto objetivo"
Distancia > 10m y <= 50m: "Estás muy próximo al punto objetivo"
Distancia < 10m: "Estás en el punto objetivo" 
Mientras el usuario se mueve, se debe mostrar en el mapa su posición, junto con varios círculos concéntricos en el punto objetivo representando las diferentes áreas de proximidad detalladas en el punto anterior.
Tanto la distancia como el mensaje de información debe actualizarse de manera automática en la caja de texto.
Cuando la aplicación está en segundo plano, debe seguir calculando la distancia al punto objetivo y mostrar un aviso cuando haya superado una barrera de distancia indicando el mensaje que corresponda.
Cada vez que el usuario esté en el rango de menos de 10m del punto objetivo debe publicar un tweet en una cuenta que crees para esta prueba indicando que el usuario está en el punto objetivo, junto con la latitud y longitud del punto objetivo y una captura de mapa donde se indique el punto en cuestión. Si el usuario sale del punto objetivo y vuelve a entrar debe volver a publicar el mensaje en tweet.
Debe aparecer siempre un botón para reiniciar el proceso de la aplicación, para volver a definir una dirección objetivo.

