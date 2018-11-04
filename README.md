# MBR


## Que contiene MBR en la pista cero ?

En el primer sector , MBR esta dividida en 3 partes :

Codigo de máquina : ( Peso = 446 Bytes ) : Es el sistema de codigos directamente interpretable por un circuito microprogramable

Tabla de particiones ( Peso = 64 Bytes ) : Se define a partir de las particiones primarias en ellas se almacena información basica sobre la partición ; si es arrancable ; si no lo es , el formato , el tamaño y el sector de inicio.

Firma de unidad arrancable ; 55 AAh en hexadecimal ( Peso = 2 bytes )

Total de bytes en pista cero : 512 bytes

## Que es MBR ?

Es el primer sector de un dispositivo de almacenamiento de datos como el disco duro.



<img src="https://elendill.files.wordpress.com/2009/04/master-boot-record.jpg?w=570" />
