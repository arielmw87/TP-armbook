# Agitador magnetico - magnetic stirrer

## descripcion:
El sistema consta de un motor DC acoplado a imanes que hace girar un buzo magnético dentro de
un erlenmeyer agitando su contenido. La salida del motor se visualiza mediante un LED.

El usuario debe poder controlar encendido y setear un tiempo de agitacion entre valores
predefinidos y la velocidad mediante un potenciómetro. Como opcion para el usuario se podra
setear y activar desde una terminal serie, además de monitorizar tiempo restante, velocidad seteada
y temperatura.

## perifericos:

botones:
    start:          BUTTON1 (PC13)
    cambiar set_time +: PB5
    cambiar set_time -: PB4

LEDs:
    leds set_time:  PB15   (muestran en binario el tiempo seteado)
                    PB14
                    PB13


    Motor           PB1

Analogico:
    Pote:           A0      (PA0)   (seteo de velocidad)