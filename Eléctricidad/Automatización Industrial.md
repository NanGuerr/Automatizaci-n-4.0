# Resumen de Conceptos de Automatización Industrial

## 1. 🔟 10 Tipos de Sensores Digitales
* **Inductivos:** 🧲 Detectan objetos metálicos sin contacto.
* **Capacitivos:** ⚪ Detectan cualquier objeto (metálicos y no metálicos).
* **Fotoeléctricos (Barrera):** 🔦 Luz entre emisor y receptor interrumpida por el objeto.
* **Fotoeléctricos (Reflexivos):** 🪞 Detectan la luz reflejada por el objeto.
* **Finales de carrera:** 🔘 Interruptores mecánicos activados por contacto físico.
* **Efecto Hall:** 🧲 Detectan campos magnéticos.
* **Ultrasónicos (ON/OFF):** 🔊 Detectan presencia mediante ondas sonoras.
* **Pulsadores y selectores:** 👆 Dispositivos de accionamiento manual por el operador.
* **Termostatos:** 🌡️ Interruptores que cambian de estado por temperatura.
* **Presostatos:** ⚙️ Interruptores que cambian de estado por presión de fluido.

---

## 2. 📖 Explicación de Conceptos

### 🏗️ ¿Cómo está conformado un motor de CC?
Un motor de corriente continua consta de un **estator**, que actúa como la carcasa fija que genera un campo magnético mediante imanes o bobinas, y un **rotor** que gira al convertirse en un imán temporal cuando la corriente lo atraviesa; este sistema se completa con el conjunto de **colector y escobillas**, las cuales permiten el paso de la electricidad hacia el rotor mediante contacto físico durante su rotación, transmitiendo la fuerza mecánica hacia el eje.

### 🔄 Diferencia entre lazo abierto y cerrado
La diferencia radica en la presencia de **realimentación**: en un sistema de **lazo abierto**, el controlador envía una orden y no supervisa el resultado, operando de manera ciega como una tostadora que calienta por tiempo fijo sin saber si el pan se ha quemado. Por otro lado, en un sistema de **lazo cerrado**, el proceso cuenta con sensores que miden constantemente la salida para compararla con el objetivo deseado, permitiendo que el sistema se autoajuste automáticamente.

### 📟 Diferencia entre sensor analógico y digital
La diferencia fundamental radica en su capacidad de proporcionar información: el **sensor analógico** funciona como un "cuentista" que entrega valores continuos y detallados (por ejemplo, midiendo exactamente 25.4 °C), mientras que el **sensor digital** es binario, permitiendo solo dos estados posibles, "Sí" o "No" (encendido/apagado o 1/0), lo cual resulta ideal para tareas específicas como la detección de presencia.

### 🤖 Tipos de PLC y marcas más reconocidas
Los PLC se clasifican en **compactos**, donde la CPU y los módulos de entradas y salidas están integrados en una sola pieza, y **modulares**, que permiten expandir la capacidad añadiendo módulos independientes en un rack. Las marcas más reconocidas a nivel mundial son:
* 🇩🇪 **Siemens** (Alemania)
* 🇺🇸 **Rockwell Automation / Allen-Bradley** (EE. UU.)
* 🇫🇷 **Schneider Electric** (Francia)
* 🇯🇵 **Mitsubishi Electric** y **Omron** (Japón)
