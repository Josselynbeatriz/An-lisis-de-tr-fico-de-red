<h1>Analisis de tráfico de red</h1>

 

<h2>Description</h2>
Soy un analista de ciberseguridad que trabaja en una empresa que se especializa en brindar servicios de TI a clientes. Varios clientes informaron que no pudieron acceder al sitio web de la empresa cliente www.yummyrecipesforme.com y vieron el error “puerto de destino inalcanzable” después de esperar a que se cargara la página. 
Mi tarea es analizar la situación y determinar qué protocolo de red se vio afectado durante este incidente. Para comenzar, intenta visitar el sitio web y también recibe el error “puerto de destino inalcanzable” Para solucionar el problema, carga su herramienta de análisis de red, tcpdump, e intenta cargar la página web nuevamente. Para cargar la página web, su navegador envía una consulta a un servidor DNS a través del protocolo UDP para recuperar la dirección IP del nombre de dominio del sitio web; esto es parte del protocolo DNS. Luego, su navegador utiliza esta dirección IP como IP de destino para enviar una solicitud HTTPS al servidor web para mostrar la página web. El analizador muestra que cuando envía paquetes UDP al servidor DNS, recibe paquetes ICMP que contienen el mensaje de error: “puerto UDP 53 inalcanzable” 
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
