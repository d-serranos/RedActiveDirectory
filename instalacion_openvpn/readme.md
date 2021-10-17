Primero instalamos easy-rsa

![](./media/media/image1.png){width="3.1871019247594052in"
height="0.31246062992125984in"}

Creamos un directorio para los certificados

![](./media/media/image2.png){width="3.0725328083989503in"
height="0.31246062992125984in"}

Copiamor los archivos de la carpeta de certificados a la carpeta de
certificados de OpenVPN

![](./media/media/image3.png){width="5.7701115485564305in"
height="0.3332917760279965in"}

Inicializamos los certificados CA

![A picture containing text, orange Description automatically
generated](./media/media/image4.png){width="2.760071084864392in"
height="0.624922353455818in"}

Y lo construimos

![](./media/media/image5.png){width="2.166395450568679in"
height="0.31246062992125984in"}

Generamos la llave Diffie-Hellman

![](./media/media/image6.png){width="1.895596019247594in"
height="0.31246062992125984in"}

Generamos la llave y los certificados

![](./media/media/image7.png){width="4.863975284339458in"
height="0.45827646544181977in"}

Y generamos un certificado para el cliente

![](./media/media/image8.png){width="4.6556681977252845in"
height="0.36453740157480313in"}

Despues generaremos el certificado TLS/SSL

![](./media/media/image9.png){width="6.38461832895888in"
height="0.31246062992125984in"}

Definimos los parametros de OpenVPN

![](./media/media/image10.png){width="3.499562554680665in"
height="0.3541229221347332in"}

![Graphical user interface, text, application Description automatically
generated](./media/media/image11.png){width="5.863850612423447in"
height="5.353497375328084in"}

![Text Description automatically
generated](./media/media/image12.png){width="5.665958005249344in"
height="5.697204724409449in"}

Una vez terminado de configurar los parametros crearemos los clientes,
en nuestro caso creamos 4 clientes de VPN

./easyrsa build-client-full client nopass

./easyrsa build-client-full client2 nopass

./easyrsa build-client-full client3 nopass

./easyrsa build-client-full client4 nopass

![A screenshot of a computer Description automatically generated with
medium confidence](./media/media/image13.png){width="6.5in"
height="3.8465277777777778in"}
