# Alcance del Proyecto

--- 

### Objetivo:
  Este año nuestro objetivo es implementar la versión web en español del juego de cartas "La Cosa".
  Las reglas del juego se encuentran en el siguiente [link](https://famaf.aulavirtual.unc.edu.ar/pluginfile.php/27371/mod_resource/content/1/Reglas%20del%20Juego_%20La%20Cosa.pdf).  

---

### Requerimientos Funcionales:
- Cuando el usuario accede al sitio, podrá tanto crear una partida como unirse a una ya existente. Para unirse a una ya existente, habrá una lista que se mostrará por pantalla todas las partidas disponibles.   
- El usuario puede crear una partida. Al hacerlo tendrá que elegir un nombre para la misma y la cantidad máxima (no pueden ser más de 12) y mínima (no menos de 4) jugadores.  
- Al crear una partida, la misma podrá ser pública o privada. En el caso de las privadas, deberá crear una contraseña que será necesaria para unirse a ésta. Si es pública, mientras haya lugar para otro jugador, cualquier usuario se podrá unir.  
- En ambos casos, tanto que cree como se una a una partida, deberá elegir un nombre para identificarse. Este identificador será único para cada jugador dentro de la sala. 
- Cada partida tendrá un lobby donde los jugadores esperarán a que el creador de la sala la comience. Dentro de este lobby los jugadores podrán comunicarse por medio de un chat de texto.  
- El chat se mantedrá desde el lobby hasta la finalización de la partida. Lo que se escriba en él será visible para todos los jugadores de la partida. Es el unico medio de comunicación entre los participantes, no habrá chats privados.  
- Cuando los jugadores se encuentran dentro del lobby, podrán abandonar la partida, siempre y cuando no se haya unido la cantidad minima de jugadores especificada por el creador. Luego de que éste presenta esa cantidad minima, nadie puede abandonar la sala.  
- Existe un módulo dentro del sitio para acceder a las reglas del juego, tanto dentro como fuera de una partida.    

- Una vez iniciada la partida nadie puede abandonar.  
- El jugador que sea la Cosa tendrá la opción de declarar que ya no quedan humanos.  

### Requerimientos NO Funcionales:
- El sistema debe ser lo más intuitivo posible.
- Eficiencia.
- Escalabilidad, ya que tendremos muchas partidas jugandose simultaneamente.