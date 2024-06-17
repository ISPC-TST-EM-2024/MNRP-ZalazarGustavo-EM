## Componentes Necesarios
    Microcontrolador PIC16F648A
    Display de 7 segmentos (ánodo o cátodo común)
    Dip switch de 8 bits
    Pulsador
    Resistencias pull-up (4.7kΩ o similar)
    Protoboard (opcional)
    Cables de conexión
    Código Fuente
    El código fuente está escrito en lenguaje ensamblador para el PIC16F648A. Se incluye un archivo Contador_Display_7_Segmentos.asm que    contiene el programa completo.

### Instrucciones de Uso

    Cargar el Programa: Compilar el código fuente en MPLAB X IDE y cargar el archivo HEX resultante en el PIC16F648A utilizando un programador.
    Conectar el Circuito: Conectar el display de 7 segmentos, el dip switch y el pulsador al PIC16F648A según el esquema del circuito.
    Ajustar el Retardo: Modificar el valor del retardo en la subrutina Delay si es necesario para evitar problemas de rebote del pulsador.
    Operar el Contador:
    Utilizar el dip switch para establecer el valor inicial del contador.
    Presionar el pulsador para incrementar el valor mostrado en el display.