# ARRG: Curso ROS2 Humble, 2024-I  - Rover communications and sensor data

## Contenido

- [Desarrollo](#desarrollo)
- [Equipo](#equipo)
- [Referencias](#referencias)

## Desarrollo

**Nota:** En este proyecto **sólo se simulará el flujo y manejo de la información de sensores** agregados al modelo del robot elegido

- [ ] Documentación y justificación de la configuración del robot.
- [ ] Planteamiento de la simulación
	- [ ] Evaluación del material disponible.
  - [ ] Selección de 3 sensores a implementar.
  	- *Recomendación:* IMU, Lidar, Camera(s), Ultrasonic Sensor
   	- *Recomendación:* LoRa con ROS [^1]
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
| Amaya Martínez Yoselin Ivonne | *por definir* |

## Referencias

### ¿Dónde empezar?

### Rover 

*Modelo para simulación*

1. **M2020 Perseverance Rover and Helicopter URDF models ** [Github repository](https://github.com/nasa-jpl/m2020-urdf-models) *Sólo modelo* **URDF**
1. *The new NASA-JPL Open-Source Mars Rover is here* [ROS Discourse news](https://discourse.ros.org/t/the-new-nasa-jpl-open-source-mars-rover-is-here/33650/1). Published Sep 20, 2023
  - **JPL Open Source Rover Project** [Github repository](https://github.com/nasa-jpl/open-source-rover). El proyecto contiene la base móvil solamente.
1. *(Proyecto)* **ros-rover** [Github repository](https://github.com/danielsnider/ros-rover). Artículo del proyecto y otros materiales, **sin código fuente**
1. **A Gazebo-ROS simulation of Curiosity Mars Rover v1.0** [Github repository](https://github.com/rivascf/curiosity-mars-rover/)
1. **How I Built a Mars Perseverance Rover Replica - Arduino based Project** [YT video](https://www.youtube.com/watch?v=NOZZMsMAGh0)
2. **I Built a Mini Mars Rover** [YT video](https://www.youtube.com/watch?v=OB4AxmelKik)
   
### Sensors 

*Ejemplos de posibles sensores para implementar en la simulación*

1. **Sensors supported by ROS** [ROS.org wiki](http://wiki.ros.org/Sensors)

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

### Comms

**LoRa** **Lo**ng-**Ra**nge Radio Communicaitions

[^1]: M. P. Manuel, M. Faied and M. Krishnan, "A Novel LoRa LPWAN-Based Communication Architecture for Search & Rescue Missions," in IEEE Access, vol. 10, pp. 57596-57607, 2022, doi: 10.1109/ACCESS.2022.3178437.

1. **A Novel LoRa LPWAN-Based Communication Architecture for Search & Rescue Missions** [IEEE article](https://ieeexplore.ieee.org/document/9783031) [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9783031)
1. **LoRa Rover** [Github respoitory](https://github.com/luickk/lora_rover_).
   > The Lora Rover is a standard RC car equipped with an lora transmission module with which large distances can be overcome.
   > The range comes with one big disadvantage which is the low bandwith (300 kbps), which is also the challange since the controller only has limited information to
   > operate, and barely no visual information such as a video feed. The system consists of multiple units, the rover itself, a
   > [basestation](https://github.com/cy8berpunk/lora_rover_basestation) tranceiver and the web interface(int the basestation repo).
1. *Ad-hoc LoRa network for stream-based communication* [Github repository](https://github.com/marv1913/lora_multihop)
1. *Long Range Machine Control System Using Multiple LoRa Modules* [blog's post](https://www.instructables.com/Long-Range-Machine-Control-System-Using-Multiple-L/)
1. **LoRa - Long-Range Radio for IoT | Arduino, ESP32, RPI Pico** [YT  video](https://www.youtube.com/watch?v=YQ7aLHCTeeE)

---

**Nota:** Usar la siguiente [plantilla](https://github.com/arrg-mx/fmtos-docs/blob/main/fmto-reporte-curso.md) para su reporte así como la [plantilla del repositorio](https://github.com/mrg-mex/mrg-plantilla-repositorio) como una guía para organizar sus archivos y referencia del formato Markdown para diferentes elementos que necesiten integrar en su reporte.
