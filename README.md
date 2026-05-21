<div align="center">

# Trabajo-BCMS

<h3>Integrantes</h3>

**Sofía Koprcina** &nbsp;•&nbsp; **Ciro Pregot** &nbsp;•&nbsp; **Matías Rubio** &nbsp;•&nbsp; **Benicio Sánchez Mandato**

<h3>Arkanoid</h3>

El juego consiste en controlar una barra horizontal ubicada en la parte inferior de la pantalla que se mueve de izquierda a derecha. El objetivo principal es mantener en juego una bola que rebota constantemente, evitando que caiga fuera de la pantalla, y dirigirla para impactar contra una serie de bloques ubicados en la parte superior. El juego corre en una resolución de **320×240 píxeles con 8 bits por píxel**, desarrollado íntegramente en **lenguaje ensamblador para una arquitectura de 16 bits**.

Cada vez que la bola golpea un bloque, este puede desaparecer o resistir varios impactos dependiendo de sus características. La dirección que toma la bola después de cada rebote depende del punto de contacto con la barra, lo que introduce un componente de control y precisión.

Durante la partida pueden aparecer elementos que modifican el comportamiento del juego, como cambios en el tamaño de la barra, la cantidad de bolas en pantalla o la forma de interactuar con los bloques. El desafío aumenta progresivamente debido a la velocidad de la bola y la complejidad de los niveles. Toda esta lógica —incluyendo la detección de colisiones, el manejo de sprites y la generación de los niveles— se implementa directamente sobre el hardware mediante rutinas en assembler, sin el uso de motores o bibliotecas externas.

En el nivel aparecen también enemigos que se desplazan por la pantalla e interfieren con la trayectoria de la bola, añadiendo una capa adicional de dificultad. El jugador dispone de un número limitado de vidas, perdiéndose una cada vez que la bola cae por la parte inferior sin ser interceptada por la plataforma. La puntuación se acumula en función de la cantidad de bloques destruidos, los enemigos eliminados y las cápsulas recogidas.

</div>