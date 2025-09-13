#**¿Qué es una red**

Es una malla de conexiones entre diferentes puntos, en este caso al ser por medio de computadores su conexión es en internet. Ya sea alámbricamente o inalambricamente. 

*Para poder CONSULTAR esto se debe tener desactivado el Firewall.*

#**Firewall**

Es un sistema de seguridad que protege tu red de accesos no autorizados. Puede bloquear ciertos tipos de tráfico, como el ICMP.

#**Dirección IP**

comando: *ipconfig*

Es como la dirección de una casa en Internet. Permite que los dispositivos se encuentren y se comuniquen entre sí. Hay dos versiones principales: IPv4 e IPv6.

#**ICMP (INTERNET CONTROL MESSAGE PROTOCOL)**

Es un protocolo que se utiliza para enviar mensajes de control y de error entre dispositivos en una red. El comando *ping* utiliza ICMP para verificar la conectividad.

#**PING**

comando: *ping www.amazon.com.mx*

Es un comando que se utiliza para verificar si un dispositivo está accesible en una red. Envía paquetes ICMP a una dirección IP y espera una respuesta.

#**DNS (Domain Name Service)**

Es como una guía telefónica de Internet. Traduce los nombres de dominio (como "mercadolibre.com.mx") a direcciones IP, para que tu computadora pueda encontrar los servidores correctos.

#**TTL (Time To Live)**

Es un valor que indica el tiempo máximo que un paquete puede vivir en una red. Evita que los paquetes se queden dando vueltas indefinidamente en caso de un problema de enrutamiento.

#**Traceroute**

comando: *tracert -d www.amazon.com.mx* 
//la página puede variar.

Este comando te permite rastrear la ruta que toman los paquetes de datos desde tu computadora hasta un servidor de destino en Internet. Es útil para diagnosticar problemas de conexión y entender la estructura de la red.
