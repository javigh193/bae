
# Tarea 2: Gestión Escuela de Topografía de Madrid

## 1.Indicar las claves candidatas:

Las claves candidatas son aquellas que podrían identificar unívocamente cada tupla. En este caso podrían ser: DNI, el nombre y los apellidos podrían formar una clave  candidata (superclave), pero es peor que el DNI, ya que podrían llegar a existir dos personas con idénticos apellidos y nombres. 

## 2.Comprobar la primera forma normal:

"Una Relación está en 1FN si y sólo si cada atributo es atómico."

En la tabla dada se incumple la 1ª forma normal. Habría que separar en tuplas los distintos valores de 'Código', 'Asignatura' y 'Nota'.

<img src="../img/tarea2.1.png">

Ahora tengo datos repetidos, para evitar esto, separo la tabla en varias tablas:

<img src="tarea2.1.png">
