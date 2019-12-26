# SEU.Proyecto-final

Sistema dómotico distribuido de control de iluminación automática con mecanismo de actuación sobre persianas y encendido de iluminación artificial. 

El sistema incluye detección de incedios integrado y coordinado entre todos los elementos del mismo domicilio, con mecanismo manual y remoto vía internet para anular la alarma.

El sistema incorpora un envío de eventos por canal twitter.

## Características técnicas generales:

Por cada habitación que se desee controlar hay que instalar una de las unidades, que se complementará con las demás.

## Características técnicas de cada unidad:

* Sensores:
> * Sensor de iluminación: Se desactiva si las luces de la habitación están encedidas. 
>>* Si detecta luz por encima de un umbral levanta las persianas, si estas están bajadas.
>>* Si detecta falta de luz por debajo de un umbral, baja las persianas.
>* Sensor de temperatura: Activa alarma acústica por encima de un umbral de temperatura. Se activa esta alarma para todas las habitaciones.
* Actuadores directos:
>* Mecanismos de actuación servoeléctrico para apertura y cierre de persianas.
>* Buzzer acústico de alarma de incendios.
>* Botón de anulación de alarma: Cancela la alarma en todas las habitaciones.
>* Botón de encendida/apagado de las luces de la habitación.
>* Botón de apertura/cierre de persianas manual.
* Actuadores remotos:
>* Desactivación de alarma por internet.
* Monitorización y medición del sistema:
>* Información de sensores mediante canal ThingSpeak.
>* Publicación de eventos vía twitter.
