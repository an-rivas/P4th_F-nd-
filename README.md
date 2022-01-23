# P4th F¡nd잉

Proyecto final para la clase de Laboratorio de Programación Creativa con Processing de la Licenciatura en TICs de la ENES Morelia del semestre 2022-1.
Profesor: Lic. Paulo Jacobo Alonso León
Alumna: Angélica Nayeli Rivas Bedolla.

P4th F¡nd잉 es un juego averiado que evoca a la nostalgia por los juegos retro de computadora. Consta de 4 archivos de extensión PDE, de 9 imágenes prediseñadas de extensión PNG.

El método para lograrlo fue programar una versión disfuncional de un algoritmo popular de inteligencia artificial y una interfaz con bugs para simular un juego averiado causado cuando la máquina está deteriorada. Esto con el propósito de causar un sentimiento de haber encendido una computadora o consola vieja para ver si sigue funcionando.

El algoritmo de inteligencia artificial que usé es A* (a estrella). A* es un algoritmo que hace una búsqueda heurística para encontrar un posible camino entre dos puntos en un mapa con obstáculos, que no se garantiza que sea el óptimo. El algoritmo lo programé para tomar decisiones azarosas para probar a la sociedad que la inteligencia artificial no puede cobrar vida y dominar al mundo, como la mayoría piensa. La inteligencia artificial es solo la máquina siguiendo las órdenes que les damos los humanos y, al ser máquinas, dependen de su constante mantenimiento para seguir funcionales. Así invito a reflexionar sobre las limitaciones de la inteligencia artificial.
El estilo estético propuesto está basado en el juego Buscaminas de 1989, apostando a la nostalgia que este juego provoca a toda una generación, y agregando bugs al funcionamiento para hacerlo ver como si el mecanismo del juego estuviera fallando al igual que el algoritmo.

# Imágenes del funcionamiento del programa

Inicio del programa.

![inicio del programa](https://github.com/an-rivas/P4th_F-nd-/blob/main/images/1.png)

Primer jugada.

![primer jugada](https://github.com/an-rivas/P4th_F-nd-/blob/main/images/2.png)

Después de multiples jugadas y reinicios de tablero.

![después de multiples jugadas y reinicios de tablero](https://github.com/an-rivas/P4th_F-nd-/blob/main/images/3.png)

# Cómo jugar
1. Seleccione el objeto a usar de los botónes de la parte superior
2. Seleccione la casilla del tablero donde quiere que se aplique el objeto.

## Tipos de objetos
1. OBSTACULO posiciona obstáculos (por donde no se puede caminar) en el tablero.
2. PARTIDA posiciona el punto de partida del camino a formar.
3. OBJETIVO posiciona el punto de llegada del camino a formar.
4. BORRAR borrar cualquier objeto que esté en la casilla seleccionada del tablero.

## Botónes de acción
4. EJECUTAR para llamar al algoritmo A*.
5. REINICIAR si quiere borrar todos los objetos que se encuentren en el tablero.
6. PARAR para detener el trazado del camino (este botón no funciona).

# Créditos
A Jakob Fischer por la letra.
A Rey Salcedo Padilla por las clases Pila y Cola.

# Extras
La versión funcional de este juego está en este enlace: <https://github.com/an-rivas/path_finding>
