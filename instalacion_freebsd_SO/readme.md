Una vez tengamos nuestro servidor configurado y con la imagen montada
iniciamos la maquina

![bsdinstall boot options menu](./media/media/image1.png){width="6.5in"
height="3.615972222222222in"}

Y procedemos a instalar el sistema

![bsdinstall choose mode](./media/media/image2.png){width="6.5in"
height="3.609722222222222in"}

Seleccionamos la distribucion del teclado que usaremos

![bsdinstall keymap 10](./media/media/image3.png){width="6.5in"
height="3.609722222222222in"}

Despues agregaremos el hostname de la maquina

![bsdinstall config hostname](./media/media/image4.png){width="6.5in"
height="3.609722222222222in"}

Y seleccionaremos los components a instalar

En nuestro caso utilizamos los components:

\*Base-dbg

\*Kernel-dbg

\*Lib32-dbg

\*ports

![bsdinstall config components](./media/media/image5.png){width="6.5in"
height="3.6041666666666665in"}

Despues seleccionaremos como deseamos que se distribuya el espacio del
disco

![bsdinstall zfs partmenu](./media/media/image6.png){width="6.5in"
height="3.609722222222222in"}

Seleccionamos el disco duro en el cual haremos la
instalacion![bsdinstall part guided
disk](./media/media/image7.png){width="6.5in"
height="3.609722222222222in"}

Y le decimos que utilizaremos toda la unidad

![bsdinstall part entire part](./media/media/image8.png){width="6.5in"
height="3.609722222222222in"}

Confirmamos la accion

![bsdinstall ufs warning](./media/media/image9.png){width="6.5in"
height="3.609722222222222in"}

Finalizamos la configuracion de Freebsd

![bsdinstall part review](./media/media/image10.png){width="6.5in"
height="3.609722222222222in"}

Empieza la instalacion del sistema base y los components que escogimos

![bsdinstall distfile fetching](./media/media/image11.png){width="6.5in"
height="3.609722222222222in"}

Colocamos una contraseña para el usuario root

![bsdinstall post root passwd](./media/media/image12.png){width="6.5in"
height="3.609722222222222in"}

Y habilitamos los servicios que queremos en nuestro caso habilitamos el
SSH para conectarnos a esta maquina y el log de errores del kernel

![bsdinstall config services](./media/media/image13.png){width="6.5in"
height="3.609722222222222in"}

Una vez finalizado aplicamos la configuracion y salimos del instalador

![bsdinstall
finalconfiguration](./media/media/image14.png){width="6.5in"
height="3.609722222222222in"}

![bsdinstall mainexit](./media/media/image15.png){width="6.5in"
height="3.609722222222222in"}
