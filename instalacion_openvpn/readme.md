Primero instalamos easy-rsa

![](./media/media/image1.png)

Creamos un directorio para los certificados.

![](./media/media/image2.png)

Copiamor los archivos de la carpeta de certificados a la carpeta de
certificados de OpenVPN.

![](./media/media/image3.png)

Inicializamos los certificados CA.

![A picture containing text, orange Description automatically
generated](./media/media/image4.png)

Y lo construimos.

![](./media/media/image5.png)

Generamos la llave Diffie-Hellman.

![](./media/media/image6.png)

Generamos la llave y los certificados.

![](./media/media/image7.png)

Y generamos un certificado para el cliente.

![](./media/media/image8.png)

Despues generaremos el certificado TLS/SSL.

![](./media/media/image9.png)

Definimos los parametros de OpenVPN.

![](./media/media/image10.png)

![Graphical user interface, text, application Description automatically
generated](./media/media/image11.png)

![Text Description automatically
generated](./media/media/image12.png)

Una vez terminado de configurar los parametros crearemos los clientes,
en nuestro caso creamos 4 clientes de VPN.

./easyrsa build-client-full client nopass

./easyrsa build-client-full client2 nopass

./easyrsa build-client-full client3 nopass

./easyrsa build-client-full client4 nopass

![A screenshot of a computer Description automatically generated with
medium confidence](./media/media/image13.png)
