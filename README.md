# Especificacion del proyecto de vacaciones

Se va a desarrollar un juego tipo NES, web que cumple con las siguientes caracteristicas:

# Juego
•	Debe poseer un menu en el que se pueda:
    
    ◦	Iniciar un nuevo juego.
    ◦	Seleccionar la dificultad del juego.
    ◦	Seleccionar el nivel de comienzo.
    ◦	Seleccionar el alias (Nombre).
    ◦	Ver la tabla de puntajes.
    ◦	Salir del juego.

•	El juego va a poseer 10 niveles, cada uno con un enemigo diferente al que derrotar. En el ultimo nivel van a existir dos jefes (mamas).Cada nivel va a consistir en derrotar al jefe. El mapa de juego va a estar montado sobre un grafo no dirigido. El jugador, asi como los jefes se moveran sobre dicho grafo. Los jefes utilizaran el algoritmo de Djstra para encontrar la ruta mas optima para matar al jugador.

•	Los jefes, asi como los jugadores poseeran una barra de vida. Un jugador pierde automaticamente cuando el jefe logra atrapar al jugador. Un jugador perdera un porcentaje de su vida si choca contra:

    ◦	Rayos laser.
    ◦	Enemigos del mapa.
    ◦	Por cada segundo que pasa en el juego. Perdera vida según lo estipule el nivel.

•	En el mapa apareceran pistolas que dispararan en direcciones random por el mapa.

•	El jugador podra disparar proyectiles en linea recta.

•	El jugador acumulara puntos al dispararle ya sea a los enemigos del mapa, al jefe o a las pistolas que apareceran en el mapa.

•	Si un jugador pierde en un nivel, este tendra la posibilidad de reiniciar el nivel o finalizar el juego.

•	Cada jefe según la dificultad del juego se modificaran los siguientes aspectos:
    
    ◦	Vida del jefe.
    ◦	Perdida de vida por unidad de tiempo.
    ◦	Cantidad de enemigos y pistolas en el mapa.
    ◦	Velocidad de las balas.

•	El juego debera guardar la siguiente informacion:

    ◦	Debera guardar el ranking de posiciones, donde tendra un puntaje, tiempo obtenido y un alias (nickname).
    ◦	Debera guardar la informacion de cada partida que se encuentre dentro del ranking. Contendra informacion como: Cantidad de balas      utilizadas, tiempo de duracion, maximo nivel alcanzado, cantidad de veces perdidas.
    ◦	Toda la logica del juego debera ser realizada en un servidor. La pagina web solo se dedicara al front end de la aplicación.
