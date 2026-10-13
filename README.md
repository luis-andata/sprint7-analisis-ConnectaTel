**Análisis ConnectaTel**

El objetivo de este ejercicio de análisis es realizar una exploración de los datos recopilados de la empresa de telecomunicaciones *ConnecteTel* para identificar los comportmientos de uso de sus clientes con el fin de optimizar la oferta de sus productos y con ello mejorar la experiencia de sus usuarios.

- Los datasets que se utilizaron para este análiis fueron 3:
  - **plans.csv** en el que podemos encontrar las características de qué incluye cada uno de sus productos o planes.
  - **users.csv** en el que podemos encontrar la información de los clientes, como su numero de identificación de cliente, nombre, edad, fecha de contratación, de que ciudad son, el plan que tienen contratado y fecha de fin de contrato si es que ya dejaron el servicio.
  - **usage.csv** en el que podemos encontrar el número de identificación del cliente, los registros del servicio que utilizan (llamada o mensaje) y la duración de las llamadas o longitud de mensajes.

Para comenzar se hizo una revisón de cada dataset para conocer su estructura, qué columnas contiene cada uno y que los tipos datos sean correctos.

Después se hizo una revisión un poco mas detallada para identificar nulos y valores inválidos, para comenzar con la limpieza de los datos, asegurando que los nulos que hubieran fueran nulos reales, remplazar valores inválidos (-999, ?) por una métrica conveniente o por nulos y en columnas donde fuera necesario estandarizar el tipo de dato.

Por último se realizó un resumen estadístico en el que obtuvimos un dataset con la información que nos ayudaría a comprender los patrones de uso de los clientes. Este dataset contiene la información segmentada por sectores de *edad* y *uso* de los clientes además de la creación de algunos histográmas y diagramas de cajas que nos ayudaron a tener una visión más clara del comportamiento de los clientes.
