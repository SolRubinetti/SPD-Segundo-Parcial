# SPD-Segundo-Parcial

## Imagen del proyecto
![Segundo_Parcial_Proyecto_Rubinetti_Maria_Sol_1D](https://github.com/SolRubinetti/SPD-Segundo-Parcial/assets/123521694/d021be74-2126-4e7a-aeb7-fb90a7662f30)


## Alumna
- Rubinetti Maria Sol

## Consigna
El objetivo de este proyecto es diseñar un sistema de incendio utilizando Arduino que pueda
detectar cambios de temperatura y activar un servo motor en caso de detectar un incendio.
Además, se mostrará la temperatura actual y la estación del año en un display LCD.

## Descripción/Explicacion
Implementa un algoritmo que dispara una alarma de incendios junto a un servo y unas luces led que por medio de codigo morse indican "S.O.S."
A su vez, muestra la temperatura actual y la estacion en base a esa temperatura. 

## Funcion principal
La funcion principal se encarga de alarmar al usuario en caso de incendios. 

## Diagrama esquemático
![Segundo_Parcial_Rubinetti_Maria_Sol_1D-1](https://github.com/SolRubinetti/SPD-Segundo-Parcial/assets/123521694/d79b7ac3-a6dc-4adb-ac54-ca402284f031)
 ### Explicación del diagrama:
- SERVO1: Hace refencia al servo utilizado, que se encunetra conectado al pin pwm 3, a 5vlts y a GND. 
- D1_ORANGE: Es una de las dos luces led, conetada al arduino. 
- D2_ORANGE: Es la segunda led conectada al arduino. 
- R1: Resistencia de 220 Ohms, de la primer led.
- R2: Resistencia de 220 Ohms, conectada a la segunda led. 
- U3: Es el sensor de temperatura, conectado al pin A0 del arduino. 
- U4: Display LCD 16X2, conectado a los pines 4,5,6,7,8,9 del arduino para recibir las señales requeridas. 
- U5: Sensor IR conectado al pin 11 del arduino, mandando señal al control remoto. 
- R3: Resistencia de 220 Ohms utilizada por el display LCD 16X2.


## Link al proyecto
[Tinkercard-Sol Rubinetti][(https://www.tinkercad.com/things/j6jtBhN2RIB-parcial-1-spd-rubinetti-maria-sol-/editel?sharecode=VJRVLUPUBYbCXBWKbibcZGOPOiHXRNId3063z9i5KYo)](https://www.tinkercad.com/things/a81E9ZwEfxq-segundo-parcial-rubinetti-maria-sol-1d/editel?sharecode=LFFTw3TXhWQg2QsCxGVOjbr8fHNvMNHjLGMrNyQTfJQ)
