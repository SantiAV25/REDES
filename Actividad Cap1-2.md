Preguntas de lectura: Capítulo 2

1. Describir la estructura de una red, incluidos los dispositivos, medios y servicios necesarios para lograr comunicaciones exitosas.

Para lograr una estructura de una red es necesario, diferentes dispositivos los cuales son encargados de lograra transmitir la información, entre ellos encontramos los:

• dispositivos de acceso a la red (hubs, switches y puntos de acceso inalámbricos),
• dispositivos de internetworking (routers),
• servidores de comunicación y módems, y
• dispositivos de seguridad (firewalls).

además de estos dispositivos nos ayudan a conectar a la red, también tenemos los medios, los cuales, son el canal para poder transmitir el mensaje, estos medios pueden ser Alambricos  o  inalambricos, los principales medios hoy en dia son:

• hilos metálicos dentro de los cables,
• fibras de vidrio o plásticas (cable de fibra óptica), y
• transmisión inalámbrica.

Por último también es importante conocer los servicios que va a proveer la red, para lograr asegurar en total su calidad.

2.Comparar y contrastar los siguientes términos: RED, LAN, WAN, INTERNETWORK E INTERNET.

Red:  Una red viene siendo la conexión de dos o más dispositivos, con el fin de poder transmitir datos.

LAN: Red de área local por sus siglas en inglés, como dice es la red encontrada en cierta área determinada, ya sea un edificio o edificios cercanos, las redes LAN son todas aquellas que necesitan de un ISP para lograr su funcionamiento.

WAN: Red de área amplia por sus siglas en inglés, es el término que se usa cuando dos redes LAN o mas separadas por una gran distancia, son conectadas. Las redes WAN necesitan de un ISP que provea la conexión.

Internetwork:  Una internetwork es llamada a los dispositivos y configuraciones hechas en las redes LAN o WAN, es el conjunto de routers y dispositivos que permiten el uso de la red.

Internet: Es llamado la red de redes, es el conjunto de redes a nivel mundial que nos permite entrar a todo tipo de información.

3.¿Cuál es la diferencia entre INTERNETWORK E INTERNET?
Respuesta:
Una Internetwork es el conjunto de dispositivos en su principio routers y sus configuraciones que permiten la conexión y por ende la comunicación en las redes LAN y WAN.
Por su parte Internet es el conjunto de dispositivos a nivel mundial que permiten la comunicación y la conexión en todo el mundo.

4.Describir la diferencia entre Tarjeta de interfaz de red (NIC), puerto físico e interfaz de red.

Una tarjeta de interfaz de red es el puerto físico que permite la conexión a los dispositivo, es al puerto donde se conecta el medio que va a permitir servir de canal a la red, en su lugar el puerto físico es el conector en un dispositivo de red es decir por ejemplo en un switch es donde se inserta el medio,
por último una interfaz de red son puertos especializar en una networking que se conecta con redes individuales ejemplo los routers.

5.¿Por qué se dice que un protocolo es independiente de la tecnología?
Respuesta:
Debido a que los protocolos son estandarizados, es decir son una serie de reglas que se deben seguir si se quiere acceder a cada tipo de servicios de red , estos deben ser independientes a las tecnologías para que cada dispositivo se puede comunicar en una red global, ya que si pasara lo contrario y un protocolo fuera dependiente de una tecnología solo esta tecnología se podría comunicar entre sí

6.Consultar y explicar brevemente qué es una Unidad de Datos del Protocolo(PDU).
Respuesta:
Una PDU  es la unidad básica de información que se transmite una red por en también es la forma la cual adopta un dato en determinada capa en los diferentes protocolos, además en estos protocolos cada capa del protocolo independientemente el cual sea, va encapsula un PDU de la anterior capa.

7.Explicar la función de los protocolos en las comunicaciones de redes y para qué es el proceso de encapsulamiento de los datos (ilustrar el nombre que adopta cada PDU en cada capa del modelo TCP/IP mediante un dibujo)
Respuesta:.
Los protocolos en las comunicaciones se hacen con el fin de tener una serie de reglas internacionalizadas en las cuales se pueden comunicar diferentes dispositivos, sin importar su marca o tecnología. Actualmente hay diferentes protocolos estandarizados,al igual que para lograr una comunicación eficiente existen suite de protocolos, los cuales son el conjunto de protocolos para lograr un fin.
Uno de lo más usados es el protocolo TCP/IP el cual utiliza los UDP  de las siguientes maneras



como podemos ver en la primera capa la cual es de aplicación los datos están como inicialmente son en este caso los datos de un email, en la siguiente capa la cual es de trasporte esta encapsula segmenta esto datos en paquete, y además los encapsula agregando al inicio un encabezado de transporte, En la siguiente capa  la cuales de internet este otra vez vuelve a encapsular para agregar un encabezado de red para finalizar en la última capa la cual es acceso a la red encapsula y agrega dos tramos nuevos al inicio y al final para indicar la longitud del paquete, además de decodificar estos datos en bits.

8.Describir la diferencia entre los modelos de protocolo y modelos de referencia.
Respuesta:
Los modelos de protocolos  son suite de protocolos los cuales definen capa por capa,la manera la cual se van a transportar y tratar los datos como por ejemplo el modelo TCP/IP, por otro lado tenemos los modelos de referencia los cuales es un modelo que como su nombre lo indica agrupa por capa que protocolos se pueden usar en determinada capa, pero este no es funcional, solo es una  referencia para mantener la consistencia dentro de todos los tipos de protocolos y servicios de red.

9.Describir la función de cada capa en los dos modelos de red: TCP/IP y OSI.
Modelo TCP/IP:

Capa de Aplicación: Incluye protocolos como HTTP, FTP, SMTP, Telnet, etc. Se encarga de realizar tareas de aplicación como la transferencia de archivos, la descarga de archivos web, el envío de correo electrónico, el acceso remoto a otro equipo, etc.

Capa de Transporte: Incluye los protocolos TCP y UDP. Se encarga de la transmisión de datos de extremo a extremo.

Capa de Internet: Incluye el protocolo IP. Se encarga de la dirección IP y el enrutamiento de paquetes.

Capa de Acceso a la Red: Se encarga de la interacción con el hardware de red y el medio físico.


Modelo OSI:

Capa Física: Se encarga de la topología de red y las conexiones globales entre la computadora y la red, refiriéndose tanto al medio físico como a la manera en que la información se transmite.

Capa de Enlace de Datos: Proporciona una interfaz de servicio a las redes y maneja errores en la capa física, controla el flujo y el marco de sincronización para redes de punto a punto y multipunto.

Capa de Red: Controla la operación de enrutamiento y conmutación, y puede proporcionar control de congestión.

Capa de Transporte: Proporciona transparencia en la transferencia de datos entre sistemas finales y es responsable del control de calidad y confiabilidad del servicio.

Capa de Sesión: Establece, administra y termina las conexiones entre las aplicaciones locales y remotas.

Capa de Presentación: Proporciona independencia a las aplicaciones de las diferencias en representación de datos (por ejemplo, cifrado) para transferir datos entre sistemas.

Capa de Aplicación: Proporciona servicios de red a las aplicaciones del usuario final, como correo electrónico, transferencia de archivos y acceso a bases de datos.
