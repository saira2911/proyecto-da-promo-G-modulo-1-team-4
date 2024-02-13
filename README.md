# proyecto-da-promo-G-modulo-1-team-4
# Desarrollo juegos clásicos Python
## Equipo Codequeens4fun
Somos el equipo Codequeens4fun , formado por Saira Castellano, María Crespo , Fedra Campos y Johanna Roudet.

## Objetivo
Nuestro cliente Adalaber´s Teacher nos solicita la creación de 3 juegos clásicos para implementar en su biblioteca de juegos.

Los 3 juegos elegidos son : Piedra , papel o tijera, Ahorcado y juegos y respuestas (llamado Adalabers Viajeras).

## Herramientas
Para el desarrollo de los mismos , hemos utilizado Python como lenguaje de programación , y la herramienta Visual Studio Code para su codificación.

## Fechas
El proyecto tiene una duración de dos semanas donde se han incluido 2 Sprints . La entrega de la demo se realiza el 14 de Febrero de 2024.

## Ruta de desarrollo
- **Piedra, papel o tijera** :
    #### *Inicio del juego*:  Cuando se inicia el juego, la máquina elige mediante random choice entre las opciones piedra , papel o tijera.
    #### *Elección del jugador*: El jugador elige su movimiento ingresando la palabra piedra, papel o tijera. Si el jugador ingresa un carácter no válido, se le pide que intente de nuevo.
    #### *Número de rondas* : 3
    #### *Determinación del ganador*: Se determina el ganador de la ronda comparando el movimiento del jugador con el de la maquina:
    - Piedra gana a tijera (la piedra rompe la tijera).
    - Tijera gana a papel (las tijeras cortan el papel).
    - Papel gana a piedra (el papel envuelve la piedra).
    - Si ambos jugadores eligen el mismo movimiento, es un  empate. Y no se resta ronda.
    #### *Fin de la partida*: Después de las 3 rondas (almacenadas en una lista), se realiza el recuento de las veces que ha ganado la máquina y el jugador.
    - Si el jugador ganó dos veces de tres, se muestra un mensaje de felicitación.
    - Si la máquina ganó, se muestra un mensaje de ánimo para que el jugador lo intente de nuevo.
- **Ahorcado** :
    #### *Inicio del juego* : La máquina elige de una lista de palabras con random choice la palabra secreta.Creamos una variable para ocultarla.
    #### *Desarrollo del juego* : El jugador debe introducir una letra para validar si se encuentra en la palabra secreta.
    - **Si la elección de la letra es correcta** , se descubre la letra en su posición y la máquina pregunta si se quiere resolver la palabra completa.
    En caso afirmativo, se introduce y si corresponde a la palabra oculta, gana la partida. En caso contrario se inicia otra ronda perdiendo una vida.
    En caso de no saber la palabra , se inicia otra ronda sin perder vidas.
    - **Si la elección de la letra no es la correcta** se pierde una vida y se imprimen las partes del dibujo que define el ahorcado. Se imprimirán sucesivamente en el caso de volver a fallar en cada intento.
    #### *Número de rondas* : 6
    #### *Fin del juego*: La partida finaliza una vez que el jugador consigue adivinar la palabra , o pierde todas las vidas tras las 6 rondas.(Se imprime el dibujo del ahorcado)
- **Adalabers Viajeras** :
    #### *Inicio del juego*: el usuario inicia la partida a través de un input con la selección de uno de los tres paises que se le ofrece.
    #### *Desarrollo del juego*: a través de diferentes input se van formulando diferentes preguntas sobre el país elegido.Mientras el jugador conserve vidas se ejecutarán los siguientes input con sus correspondientes preguntas hasta completar el total de las mismas y ganar la partida.
    #### *Número de vidas* : 4
    #### *Fin del juego* : la partida finaliza una vez que el jugador llega a la última pregunta con al menos una vida o si pierde todas las vidas antes de finalizar el cupo de preguntas. En todos los casos, se imprime un mensaje invitando al jugador a volver a intentarlo.









