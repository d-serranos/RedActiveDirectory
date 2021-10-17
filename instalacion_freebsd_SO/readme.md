Una vez tengamos nuestro servidor configurado y con la imagen montada
iniciamos la maquina.

![bsdinstall boot options menu](./media/media/image1.png)

Y procedemos a instalar el sistema.

![bsdinstall choose mode](./media/media/image2.png)

Seleccionamos la distribucion del teclado que usaremos.

![bsdinstall keymap 10](./media/media/image3.png)

Despues agregaremos el hostname de la maquina.

![bsdinstall config hostname](./media/media/image4.png)

Y seleccionaremos los components a instalar.

En nuestro caso utilizamos los componentes:

\*Base-dbg

\*Kernel-dbg

\*Lib32-dbg

\*ports

![bsdinstall config components](./media/media/image5.png)

Despues seleccionaremos como deseamos que se distribuya el espacio del
disco.

![bsdinstall zfs partmenu](./media/media/image6.png)

Seleccionamos el disco duro en el cual haremos la
instalacion![bsdinstall part guided
disk](./media/media/image7.png)

Y le decimos que utilizaremos toda la unidad.

![bsdinstall part entire part](./media/media/image8.png)

Confirmamos la accion.

![bsdinstall ufs warning](./media/media/image9.png)

Finalizamos la configuracion de Freebsd.

![bsdinstall part review](./media/media/image10.png)

Empieza la instalacion del sistema base y los components que escogimos.

![bsdinstall distfile fetching](./media/media/image11.png)

Colocamos una contraseña para el usuario root.

![bsdinstall post root passwd](./media/media/image12.png)

Y habilitamos los servicios que queremos en nuestro caso habilitamos el
SSH para conectarnos a esta maquina y el log de errores del kernel.

![bsdinstall config services](./media/media/image13.png)

Una vez finalizado aplicamos la configuracion y salimos del instalador.

![bsdinstall
finalconfiguration](./media/media/image14.png)

![bsdinstall mainexit](./media/media/image15.png)
