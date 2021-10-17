Para instalar en nuestro servidor los components para tener el DNS

![Text Description automatically
generated](./media/media/image1.png){width="6.249219160104987in"
height="0.5207677165354331in"}

Despues configuramos el archivo named.conf.local que es el utilizdo para
la DNS lcoales

![Text Description automatically
generated](./media/media/image2.png){width="4.030745844269466in"
height="0.5728455818022747in"}

Y agregamos las siguientes lineas

![Graphical user interface, text, application Description automatically
generated](./media/media/image3.png){width="6.5in"
height="3.6708333333333334in"}

Despues copiaremos el modelo para hacer el fordward con el siguiente
command

\# sudo cp /etc/bind/db.local /etc/bind/forward.idbfreebsd.local.db

Y despues le agregamos para que quede con este contenido

![A screenshot of a computer Description automatically generated with
medium confidence](./media/media/image4.png){width="6.5in"
height="3.890277777777778in"}

Hora configuraremos la reversa para el DNS copiaremos el archivo

\# sudo cp /etc/bind/db.192 /etc/bind/reverse.dbfreebsd.local

Y reinicamos el servidor de bind

\# Systemctl restart bind9

Probamos la conexion del dominio

![Graphical user interface, text Description automatically
generated](./media/media/image5.png){width="6.5in"
height="3.890277777777778in"}

Y probamos el proxi reverso

![Graphical user interface, application Description automatically
generated](./media/media/image6.png){width="6.5in"
height="3.890277777777778in"}
