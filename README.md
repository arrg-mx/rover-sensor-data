# ARRG: Curso ROS2 Humble, 2024-I  - Rover sensor data

## Contenido

- [Desarrollo](#desarrollo)
- [Equipo](#equipo)
- [Referencias](#referencias)

## Desarrollo

**Nota:** En este proyecto **sólo se simulará el flujo y manejo de la información de sensores** agregados al modelo del robot elegido

- [ ] Documentación y justificación de la configuración del robot.
- [ ] Planteamiento de la simulación
	- [ ] Evaluación del material disponible.
  - [ ] Selección de 3 sensores a implementar. *Recomendación:* IMU, Lidar, Camera(s), Ultrasonic
 	- [ ] Implementación del modelo del robot seleccionado.
  	- [ ]  Esquema de paquetes/metapaquete a implementar
  	- [ ]  Diagrama de nodos y tópicos
  	- [ ]  Servicios a implementar
  	- [ ]  Controles a implentales
  	- [ ]  Acciones a implentar
  	- [ ]  Desarrollo de nodos, tópicos, servicios, controles y acciones en Python/C++
- [ ] Simulación
	- [ ] Construcción de la simulación en Gazebo, escena y modelos 3D a implemenatr.
	- [ ] Implemenatción del modelo tridimencional del robot en la simulación
 	- [ ] Interación de rutinas y acciones en el entorno simulado
- [ ] Reporte de resultados finales.

## Equipo

**Integrantes del proyecto:**

| Nombre | Observaciones |
| :----------| :----------- |
| Hernández Trejo Enrique Zoé | *por definir* | 
| Baruc Martínez Velasco | *por definir* | 

## Referencias

### ¿Dónde empezar?

1. **M2020 Perseverance Rover and Helicopter URDF models ** [Github repository](https://github.com/nasa-jpl/m2020-urdf-models) *Sólo modelo* **URDF**
1. *The new NASA-JPL Open-Source Mars Rover is here* [ROS Discourse news](https://discourse.ros.org/t/the-new-nasa-jpl-open-source-mars-rover-is-here/33650/1). Published Sep 20, 2023
  - **JPL Open Source Rover Project** [Github repository](https://github.com/nasa-jpl/open-source-rover). El proyecto contiene la base móvil solamente.
1. *(Proyecto)* **ros-rover** [Github repository](https://github.com/danielsnider/ros-rover). Artículo del proyecto y otros materiales, **sin código fuente**
1. **A Gazebo-ROS simulation of Curiosity Mars Rover v1.0** [Github repository](https://github.com/rivascf/curiosity-mars-rover/)

**Comunidad**

1. **How I Built a Mars Perseverance Rover Replica - Arduino based Project** [YT video](https://www.youtube.com/watch?v=NOZZMsMAGh0)
1. **ROS Lidar sensor and its properties** [YT video](https://www.youtube.com/watch?v=-N4n8-M8f8k)
1. **ROS camera sensor and understanding its properties** [YT video](https://www.youtube.com/watch?v=mG0FHhhfmw8)
1. **Getting Started with ROS2 Navigation - Episode 6 - IMU and IMU Tools** [YT video](https://www.youtube.com/watch?v=GNjN51NvJ6s)
1. **Robótica: Sensor cámara en Gazebo y ROS #1** [YT video](https://www.youtube.com/watch?v=SLe74btrPb8)
1. **How do we add LIDAR to a ROS robot?** [YT video](https://www.youtube.com/watch?v=eJZXRncGaGM)
1. **How to use Cameras in ROS (Sim Camera and Pi Camera)** [YT video](https://www.youtube.com/watch?v=A3nw2M47K50)
1. **ROS and SONARS for OBSTACLE AVOIDANCE | Tutorial #6 | ROS and Raspberry Pi** [YT video](https://www.youtube.com/watch?v=JYnMRKVwBuQ)
1. **Ultrasonic Sensor| ROS | Robot Operating System** [YT video](https://www.youtube.com/watch?v=cRq6Xyvy30I)
1. *RAIN Webinar 13th Aug 2020: UKRAS ROS Nuclear Sensing Workshop* [YT video](https://www.youtube.com/watch?v=rdy53jwjKZA) **Note:** *Radiation sensor in ROS*
1. *ROS EtherCAT communication with SENSO-Joint - reading Torque sensor data* [YT video](https://www.youtube.com/watch?v=1pjTD6svINE)
1. **Chip Robotics IMU sensor (BNO080) running ROS RVIZ** [YT video](https://www.youtube.com/watch?v=2bs6SfOYMgQ)
  -  *chip_imu_driver* [Github repository](https://github.com/chiprobotics/chip_imu_driver)
1. *Gazebo tutorials: Sensors* [YT video](https://www.youtube.com/watch?v=WcFyGPEfhHc)
1. *Roll Pitch Yaw from IMU Sensor and Vizualizing it in RVIZ ROS | MPU6050 | Jetson Nano | I2C* [YT video](https://www.youtube.com/watch?v=a-mfCeykmYw)

---

**Nota:** Usar la siguiente [plantilla](https://github.com/arrg-mx/fmtos-docs/blob/main/fmto-reporte-curso.md) para su reporte así como la [plantilla del repositorio](https://github.com/mrg-mex/mrg-plantilla-repositorio) como una guía para organizar sus archivos y referencia del formato Markdown para diferentes elementos que necesiten integrar en su reporte.
