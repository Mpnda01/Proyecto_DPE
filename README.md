Manipulación con TurtleBot 4 y Brazo Robótico
Objetivo:

Desarrollar un sistema donde el TurtleBot 4, equipado con un brazo robótico, pueda:
Detectar, recoger y trasladar objetos a ubicaciones específicas.
Integrar percepción visual para localizar objetos.
Herramientas:

Backend: ROS 2 Humble (MoveIt, ros2_control).
Frontend: Visualización y control en rviz2.
Otros paquetes ROS 2: Turtlebot4_bringup, OpenCV.
Tareas adicionales:

Configuración del brazo robótico:

Integrar MoveIt para planificar trayectorias del brazo.
Configurar controladores de ros2_control para el brazo y el TurtleBot.
Percepción visual:

Implementar nodos en OpenCV para detectar objetos con cámaras RGB o profundidad.
Calcular las coordenadas de los objetos detectados en el espacio del robot.
Sincronización de navegación y manipulación:

Diseñar nodos para coordinar los movimientos del TurtleBot y el brazo.
Implementar una estrategia para evitar obstáculos mientras transporta objetos.
Pruebas en simulación:

Validar la detección de objetos y la precisión de manipulación en Gazebo o Ignition.
Documentación:

Crear un repositorio en GitHub y Docker que incluya instrucciones detalladas, ejemplos de configuración y métricas de evaluación.
