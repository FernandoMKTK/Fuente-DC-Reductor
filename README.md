# Fuente-DC-Reductor
Diseño e implementación de un circuito reductor de voltaje conmutado utilizando Proteus para simulaciones y pruebas.
## Descripción del Proyecto
Este proyecto consiste en el diseño e implementación de una fuente DC reductora de voltaje conmutado, utilizando MOSFETs, diodos, inductores y capacitores. Se realizó la simulación en Proteus para validar su correcto funcionamiento antes de la implementación física.

## Objetivo
El objetivo principal es diseñar una fuente de alimentación eficiente que reduzca un voltaje de entrada a un nivel de voltaje más bajo y estable, minimizando pérdidas de energía y asegurando una regulación precisa mediante técnicas de PWM y retroalimentación.

## Tecnologías y Herramientas Utilizadas
Proteus  (Simulación del circuito)
MOSFETs (Conmutación de voltaje)
Diodo Schottky 1N5822  (Protección contra inversión de corriente)
OpAmp LM741  (Generación de PWM)
Regulador LM2576  (Retroalimentación y regulación de voltaje)

## Estructura del Proyecto
🔹 1. Etapa de Conmutación
Uso de MOSFETs como interruptores electrónicos.
Control mediante señal de PWM.

🔹 2. Etapa de Almacenamiento de Energía
Uso de inductores y capacitores para garantizar estabilidad.
Carga y descarga controlada para evitar oscilaciones.

🔹 3. Etapa de Generación de PWM
Implementación de un oscilador con OpAmp LM741.
Ajuste de duty cycle para regular la tensión de salida.

🔹 4. Etapa de Retroalimentación
Uso del LM2576 para regular la salida y evitar oscilaciones indeseadas.

## Resultados y Simulación
- Se realizaron simulaciones en Proteus para validar el diseño.
- Se compararon resultados antes y después de la implementación de la retroalimentación, logrando una salida de voltaje estable.

## Archivos del Proyecto
- Informe Técnico
- Archivo de Simulación Proteus

## Mejoras y Futuro Trabajo
- Implementación en hardware real.
- Optimización de componentes para mayor eficiencia.
- Comparación con otros métodos de regulación de voltaje.
