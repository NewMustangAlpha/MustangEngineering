# 🤖🇵🇦 🐎 Cónoce a nuestro equipo

Este repositorio contiene el desarrollo del robot para la competencia de WRO 2025. Este utiliza sensores y motores para seguir un trayecto predefinido y cumplir diversas **misiones**. Está diseñado como un proyecto educativo de robótica de nuestra escuela Panamerican School. 

## 🔧 Integrantes

- Sigue líneas negras sobre fondo blanco (o viceversa).
- Usa sensores infrarrojos para detectar la trayectoria.
- Controlado por un microcontrolador (como Arduino Uno).
- Motores DC con control PWM para ajuste de velocidad.
- Soporte para múltiples misiones como:
  - Seguir el circuito completo.
  - Detenerse en zonas de control.
  - Cambiar de dirección en intersecciones.

## 🗂 Diseño del Robot

- `/code/`: Código fuente del robot (Arduino, Python).
- `/docs/`: Diagramas, explicaciones técnicas.
- `/hardware/`: Detalles sobre sensores, motores y esquemas.
- `/missions/`: Descripción detallada de las misiones que debe cumplir el robot.

## 🧠 Evidencias

- Arduino UNO o similar
- Sensores infrarrojos (IR)
- Motores DC con driver L298N
- Batería recargable
- Cables, chasis, y ruedas

## 🚀 Espectativas

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/line-follower-robot.git
   ```
2. Abre la carpeta `code/arduino/` y carga el código en tu placa Arduino.
3. Consulta la carpeta `hardware/` para ver la lista de componentes y esquemas.
4. Usa la carpeta `missions/` para realizar pruebas y retos.

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver [LICENSE](LICENSE) para más detalles.
