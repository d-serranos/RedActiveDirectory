Por medio del instalador de paquetes verificamos las versions que
podemos instalar de mysql.

![Text Description automatically generated with medium
confidence](./media/media/image1.png)

Instalaremos la version mas reciente disponible de mysql.

![](./media/media/image2.png)

Activamos el servicio para que se inicie cada vez que el sistema inicie.

![](./media/media/image3.png)

Y iniciamos el servidor de base de datos.

![](./media/media/image4.png)

Y verificamos si el servicio esta arriba.

![](./media/media/image5.png)

Accedemos a mysql por la consola.

![](./media/media/image6.png)

![Text Description automatically
generated](./media/media/image7.png)

Y modificamos la contraseña del usuario root por motivos de seguridad.

![](./media/media/image8.png)

Y creamos un usuario para la conexion.

![Text Description automatically
generated](./media/media/image9.png)

Para permitir la conexion desde cualquier IP nos vamos a archivo de
configuracion de mysql.

![](./media/media/image10.png)

Y modificamos la linea de la Ip para que quede de la siguiente manera.

![](./media/media/image11.png)

Y reiniciamos el servicio de mysql.

![](./media/media/image12.png)

Probamos la conexion desde otra maquina en mi ccaso usare MYSQL
Workbench.

![Graphical user interface, text, application, email Description
automatically generated](./media/media/image13.png)

![Graphical user interface, text, application Description automatically
generated](./media/media/image14.png)

Instalamos OpenVPN para conectarlo a nuestro servidor VPN y poder
consumirlo desde alli.

![](./media/media/image15.png)

Agregamos nuestro archivo de configuracion a la carpeta predeterminada
de open vpn con el nombre "openvpn.conf".

![](./media/media/image16.png)

Activamos openvpn para que se active junto con el booteo de la maquina.

![](./media/media/image17.png)

Y lo iniciamos.

![](./media/media/image18.png)

Ahora utilizando el commando ifconfig, comprobamos que el servidor este
conectado a la VPN.

![Text Description automatically
generated](./media/media/image19.png)

Una vez agregado a la VPN nos conectamos atravez de esta a la base de
datos utilizando las mismas credenciales.

![Graphical user interface, text, application Description automatically
generated](./media/media/image20.png)
