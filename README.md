 Proyecto Minisumo - La Passione

## 👥 Autores
- **Uriel Ramirez**   
- **Demian Ramirez** 
- **Elías Vázquez**
  
---

## 📖 Introducción#
El proyecto consiste en un robot minisumo autónomo que emplea distintos sensores para orientarse dentro del área de combate.  
- **Sensor frontal**: impulsa al robot hacia adelante para atacar.  
- **Sensores laterales**: permiten reorientarse frente a obstáculos o rivales.  
- **Sensor de piso**: asegura que el robot permanezca dentro de la arena de enfrentamiento.  

En conjunto, se trata de un mecanismo sencillo pero eficaz para la competencia de minisumo.

---

## ⚙️ Esquema en bloques
- Batería
- Sensor lateral
- Microcontrolador (ESP32 S3)
- Sensor frontal
- Sensor de piso
- DRV8833 (Puente H)
- Motores

<img width="512" height="378" alt="unnamed" src="https://github.com/user-attachments/assets/f2dda685-34b7-427a-a42f-2547c1056f64" />


---

## 💰 Componentes y costos aproximados
| Componente                   | Costo (ARS) |
|------------------------------|-------------|
| ESP32 C3 super mini          | 10.000      |
| Batería de Lipo              | 30.040      |
| TCRT5000 (sensor )    | 3.700       |
| AD-32 (sensor) x2      | 2.300       |
| Motores Pololu 250RPM        | 9.800       |
| DRV8833 (puente H)           | 4.000       |
| Carrocería                   | 11.000      |
| hc sr04                    | 3.500  |
| **Total**                    | **76.640**  |

---

## 🎯 Objetivo del Proyecto

El objetivo del robot minisumo *La Passione* es participar en competencias de sumo robótico, 
donde debe detectar, atacar y desplazar a su oponente fuera del área de combate (tatami).  
Para lograrlo, combina distintos sensores y un sistema de control basado en el ESP32 S3:

- **Atacar directamente** cuando el sensor frontal detecta un rival.  
- **Reorientarse** mediante los sensores laterales para enfrentar al oponente de manera estratégica.  
- **Mantenerse dentro del área de combate** gracias al sensor de piso que evita salidas accidentales.

<img width="341" height="512" alt="unnamed (1)" src="https://github.com/user-attachments/assets/821b7ad5-e607-4e03-98af-1e69ae6e1df8" />

 ---  
 
## 📐Diseño

<img width="1042" height="547" alt="Fabulous Snicket-Trug (1)" src="https://github.com/user-attachments/assets/94d34396-2455-48cb-8907-f2a8834b298b" />


(pcb y esquematico proximamente)

