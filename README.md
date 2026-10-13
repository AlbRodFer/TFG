# TFG: Control y Simulación de un robot humanoide (STAR_BOT)
En este repositorio se encuentra todo mi progreso sobre el control y simulación del nuevo robot del grupo STAR(Students Team of Advanced Robotics). 

Para conseguir esto debo seguir una serie de pasos, empezando por:

### Cadena cinemática del robot
Se planteará la cinemática directa del robot partiendo desde el sistema global en dos ramas: una hacia los brazos y otra hacia las ruedas.
Partiendo de ahí, se calculará la cinemática inversa del mismo para poder posicionar el robot en cualquier pose alcanzable deseada

### Control de bajo nivel con ROS2_CONTROL
Una vez planteado el movimiento del robot se pasará al control y programación del mismo con las librerías de ros2_control para su uso tanto en simulación en este caso como en la realidad en un futuro no muy lejano

### Simulación en Gazebo Classic
Haciendo uso de ROS2 Humble, Rvizz2 y Gazebo Classic, mostraremos los resultados obtenidos de todo el trabajo previo para verificar que el robot se mueve tal como se especificó

### Por ver...
Partiendo de aqui todas las aplicaciones posibles que se le puedan dar al robot quedan al gusto del consumidor
