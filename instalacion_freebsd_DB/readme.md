Por medio del instalador de paquetes verificamos las versions que
podemos instalar de mysql

![Text Description automatically generated with medium
confidence](./media/media/image1.png){width="6.5in"
height="1.0340277777777778in"}

Instalaremos la version mas reciente disponible de mysql

![](./media/media/image2.png){width="4.31196084864392in"
height="0.2395538057742782in"}

Activamos el servicio para que se inicie cada vez que el sistema inicie

![](./media/media/image3.png){width="4.103653762029746in"
height="0.49993766404199474in"}

Y iniciamos el servidor de base de datos

![](./media/media/image4.png){width="3.9682534995625547in"
height="0.5103532370953631in"}\
y verificamos si el servicio esta arriba

![](./media/media/image5.png){width="4.114069335083115in"
height="0.4686909448818898in"}

Accedemos a mysql por la consola

![](./media/media/image6.png){width="2.0934886264216974in"
height="0.22913823272090988in"}

![Text Description automatically
generated](./media/media/image7.png){width="6.5in"
height="1.7229166666666667in"}

Y modificamos la contraseña del usuario root por motivos de seguridad

![](./media/media/image8.png){width="6.020080927384077in"
height="0.21872265966754156in"}

Y creamos un usuario para la conexion

![Text Description automatically
generated](./media/media/image9.png){width="6.5in"
height="1.7083333333333333in"}

Para permitir la conexion desde cualquier IP nos vamos a archivo de
configuracion de mysql

![](./media/media/image10.png){width="4.811898512685914in"
height="0.2812150043744532in"}

Y modificamos la linea de la Ip para que quede de la siguiente manera

![](./media/media/image11.png){width="5.322251749781278in"
height="0.27079943132108486in"}

Y reiniciamos el servicio de mysql

![](./media/media/image12.png){width="4.166146106736658in"
height="0.22913823272090988in"}

Probamos la conexion desde otra maquina en mi ccaso usare MYSQL
Workbench

![Graphical user interface, text, application, email Description
automatically generated](./media/media/image13.png){width="6.5in"
height="4.077083333333333in"}

![Graphical user interface, text, application Description automatically
generated](./media/media/image14.png){width="6.5in"
height="4.077083333333333in"}

Instalamos OpenVPN para conectarlo a nuestro servidor VPN y poder
consumirlo desde alli

![](./media/media/image15.png){width="2.083073053368329in"
height="0.36453740157480313in"}

Agregamos nuestro archivo de configuracion a la carpeta predeterminada
de open vpn con el nombre "openvpn.conf"

![](./media/media/image16.png){width="2.8017333770778654in"
height="0.37495297462817145in"}

Activamos openvpn para que se active junto con el booteo de la maquina

![](./media/media/image17.png){width="4.5410990813648295in"
height="0.36453740157480313in"}

Y lo iniciamos

![](./media/media/image18.png){width="4.395284339457568in"
height="0.2812150043744532in"}

Ahora utilizando el commando ifconfig, comprobamos que el servidor este
conectado a la VPN

![Text Description automatically
generated](./media/media/image19.png){width="6.5in"
height="2.5416666666666665in"}

Una vez agregado a la VPN nos conectamos atravez de esta a la base de
datos utilizando las mismas credenciales.

![Graphical user interface, text, application Description automatically
generated](./media/media/image20.png){width="6.5in"
height="4.077083333333333in"}
