# estacion_meteorologica_1
Grupo 1 
Alejo Serminatti, Pedro lujan, Alejo Castaño Giovana, Candela Barrionuevo, Felipe Illarraga, Mia Castillo, Kyara Gontero

# 🌦️ Estación de Monitoreo Meteorológico y Ambiental

## 📌 Presentación del proyecto

Nuestro proyecto consiste en el desarrollo de una **estación de monitoreo meteorológico y ambiental** basada en **Arduino Uno**.

El objetivo es medir y visualizar diferentes condiciones del ambiente, como la **temperatura, humedad y calidad del aire**, utilizando sensores electrónicos. Además, el sistema cuenta con indicadores luminosos y una pantalla LCD para mostrar los datos obtenidos y generar alertas cuando se detectan valores fuera de los límites establecidos.

La estación está acompañada por una **maqueta que representa diferentes zonas del ambiente**, permitiendo relacionar los datos obtenidos por los sensores con una representación visual del entorno.

---

## ⚙️ Componentes utilizados

| Componente | Función principal | Conexión |
|---|---|---|
| 🔵 Arduino Uno | Microcontrolador principal | USB / Fuente externa |
| 📺 LCD 16x2 + I2C | Muestra los datos y alertas | SDA / SCL |
| 🌡️ Sensor DHT11 | Mide temperatura y humedad | Pin digital |
| 💨 Sensor MQ-2 | Detecta humo, gases e inflamables | Pin analógico |
| 🔴 LED de calor | Indica temperatura alta | Pin digital 13 + resistencia 220Ω |
| 🔵 LED de frío | Indica temperatura baja | Pin digital 12 + resistencia 220Ω |
| 🔊 Buzzer piezoeléctrico | Emite una alarma sonora | Pin digital 11 |
| 🔌 Protoboard | Permite conectar los componentes | Cableado |
| 🧵 Cables M-M, H-H y M-H | Realizan las conexiones | Según cada componente |

---
Este proyecto fue realizado como una propuesta educativa para aplicar conocimientos de:

💻 Programación 🔌 Electrónica 🌡️ Sensores 🌱 Medio ambiente 🤖 Arduino 🏗️ Diseño y construcción de maquetas
