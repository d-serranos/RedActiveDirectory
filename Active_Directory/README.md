Directorio de Activos

1.  Descargar el Software de Windows server 2012, como es una versión
    gratuita o de prueba tendremos alrededor de 180 días para poder
    realizar dichas configuraciones y hacer uso de estas.

2.  Lo descargamos del siguiente link
    <https://www.microsoft.com/es-es/evalcenter/evaluate-windows-server-2012-r2>

![Imagen que contiene Rectángulo Descripción generada
automáticamente](.//media/image1.png){width="5.552083333333333in"
height="1.7237970253718284in"}

3.  Llenamos los datos del formulario

![Tabla Descripción generada
automáticamente](.//media/image2.png){width="6.1375in"
height="2.6326388888888888in"}

4.  Una vez lleno se empieza descargar automáticamente el servidor.
    Luego de la descarga abrimos nuestro software para virtualizar en
    este caso vamos a utilizar Virtual Box.

    a.  Si no tenemos instalado VirtualBox lo podemos descargar del
        siguiente enlace.

> <https://download.virtualbox.org/virtualbox/6.1.26/VirtualBox-6.1.26-145957-Win.exe>
>
> o Bien si usan otra arquitectura de software lo pueden hacer desde acá
> y seleccionar la suya.
>
> <https://www.virtualbox.org/wiki/Downloads>

b.  Una vez descargado el software para virtualizar lo instalamos.

> ![How to install Windows 10 on Oracle VM VirtualBox? \| Gear up
> Windows 11/10](.//media/image3.png){width="4.364583333333333in"
> height="2.792681539807524in"}

5.  Agregamos una nueva máquina en el botón verde de agregar (**Add**)

    a.  Indicamos el nombre, pero en su versión escogemos Windows 2012
        haciendo referencia al que descargamos.

> ![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
> automáticamente](.//media/image4.png){width="3.3333333333333335in"
> height="2.8089884076990375in"}

b.  Seleccionamos la memoria correspondiente

> ![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
> automáticamente](.//media/image5.png){width="3.633944663167104in"
> height="3.1041666666666665in"}

c.  Creamos un disco duro virtual.

> ![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
> automáticamente](.//media/image6.png){width="3.875in"
> height="3.284192913385827in"}

d.  Creamos un ***Virtual Box Disk Imagen,*** Lo creamos de tamaño
    dinámico para no tener ningún inconveniente, y verificamos el lugar
    en donde queremos almacenar esta información yo Normal mente lo hago
    dentro de ***Mis Documentos,*** y creo una carpeta de ***Virtual,***
    y dentro creo otra carpeta con el sistema operativo que este
    virtualizando con la finalidad de mantener el control.

```{=html}
<!-- -->
```
6.  Al momento de correr el servidor nos pedirá que seleccionemos donde
    esta la imagen que descargamos.

![Interfaz de usuario gráfica, Aplicación, Word Descripción generada
automáticamente](.//media/image7.png){width="4.427083333333333in"
height="3.8117475940507437in"}

7.  Seleccionamos el lugar y pinchamos en ***Iniciar,*** Configuramos el
    país de donde somos y le damos instalar, cuando nos pregunte por el
    tipo de instalación que vamos a realizar, le indicamos ***sistema
    operativo que quiere instalar,*** Seleccionamos lo que esta en la
    imagen.

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image8.png){width="4.28125in"
height="3.1773742344706912in"}

8.  Aceptamos los términos de referencia y seleccionamos la instalación
    ***Personalizada,*** Luego formateamos el disco para que Windows
    server le de el formato adecuado. Y esperamos que realice la
    instalación.

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image9.png){width="3.8645833333333335in"
height="2.866842738407699in"}

9.  Luego nos pedirá una contraseña que será la del administrador del
    servidor.

![Interfaz de usuario gráfica, Aplicación Descripción generada
automáticamente](.//media/image10.png){width="3.96875in"
height="2.5681463254593178in"}

10. Una Vez configurado ingresamos e instalamos open VPN CLIENT, para
    pegar nuestro servidor al servidor de VPN.

![Interfaz de usuario gráfica, Aplicación Descripción generada
automáticamente](.//media/image11.png){width="2.71875in"
height="3.688720472440945in"}

11. Ya estando en esto subimos el archivo que creamos desde la VPN para
    que el servidor pueda verlos sin problema alguno.

![Interfaz de usuario gráfica, Aplicación Descripción generada
automáticamente](.//media/image12.png){width="4.041666666666667in"
height="2.0208333333333335in"}![Icono Descripción generada
automáticamente](.//media/image13.png){width="4.125in" height="0.625in"}

12. Una vez teniendo la conexión a la VPN procedemos a configurar el
    ***ACTIVE DIRECTORY,*** para lo cual vamos a abrir el administrador
    del servidor en las opciones de arriba ***Administrar -\> Agregar
    roles y características***

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image14.png){width="4.510416666666667in"
height="3.201895231846019in"}

13. Pinchamos siguiente en la pestaña de ***Asistente para agregar roles
    y características,*** al dar siguiente nos aparecerá la siguiente
    ventana.

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image15.png){width="4.416666666666667in"
height="3.1046347331583553in"}

14. Escogemos ***Instalación basa en características o en roles,***
    pinchamos en siguiente, en la siguiente ventana escogemos
    ***Seleccionamos un servidor del grupo de servidores,*** pinchamos
    en siguiente, en la posterior ventana donde nos aparece la siguiente
    imagen.

![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
automáticamente](.//media/image16.png){width="5.645833333333333in"
height="3.4166666666666665in"}

15. Una vez seleccionamos el servicio de dominio de ***ACTIVE
    DIRECTORY,*** Nos saldrá la siguiente ventana en donde debemos de
    agregar las características al pinchar allí le damos en siguiente.

![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
automáticamente](.//media/image17.png){width="3.65625in"
height="3.943345363079615in"}

16. En la ventana siguiente estamos confirmando las características que
    aceptamos. Pinchamos en siguiente

![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
automáticamente](.//media/image18.png){width="5.541666666666667in"
height="3.0416666666666665in"}

17. Pincharemos siguiente hasta que el botón de instalar se active y
    luego también realizaremos la instalación de lo que hemos escogido.

![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
automáticamente](.//media/image19.png){width="4.864583333333333in"
height="3.4192486876640418in"}

18. Nos link que indica ***Promover este servidor a controlador de
    dominio,*** para activar este servidor a un servidor de dominio,
    ahora lo que haremos es cerra la ventana actual. Nos iremos
    nuevamente a nuestro ***administrador del servidor***

![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
automáticamente](.//media/image20.png){width="4.7497812773403325in"
height="2.9895833333333335in"}

19. En esta ventana nos damos cuenta que hemos agregado el ***AD DS,***
    en el cual vamos a configurar ahora.

![Interfaz de usuario gráfica Descripción generada
automáticamente](.//media/image21.png){width="4.666666666666667in"
height="3.0429965004374453in"}

20. Al momento de pinchar nos damos cuenta que falta la configuración
    del dominio el cual puede ya existir o no, en nuestro caso el
    servicio ya existe, en la venta que mostramos pinchamos en mas.

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image22.png){width="4.53125in"
height="2.8716371391076114in"}

21. No aparece una ventana de detalle en donde vuelve aparecer la
    promoción de este servidor a un dominio, pinchamos en ello.

![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
automáticamente](.//media/image23.png){width="4.989583333333333in"
height="2.7680391513560805in"}

22. Nos Sale las siguientes opciones. Como nosotros ya contratamos un
    dominio, creamos el nuevo dominio y lo agregamos con el nombre del
    mismo sitio. agregamos el dominio correspondiente, y pinchamos en
    siguiente.

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image24.png){width="4.020833333333333in"
height="2.949430227471566in"}

23. En la siguiente ventana nos aparecen datos de configuración lo
    recomendable es dejarlo en su nivel de función como Windows server
    2012 R2, y llenar las contraseñas para una posible restauración en
    dado caso sea necesario. Al finalizar le damos las opciones de DNS,
    como hasta este punto aun no tenemos la instalación del servidor de
    dns no realizamos mayor cosa que siguiente,

    a.  En dado caso si existirá en las propiedades de red en el
        protocolo IPV4, configuramos el DNS correspondiente.

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image25.png){width="4.322916666666667in"
height="3.1405807086614175in"}

24. En las opciones adicionales verificamos que el nombre sea igual al
    del dominio, o podemos cambiarlo en mi caso lo dejaremos igual.

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image26.png){width="3.8927668416447943in"
height="2.8541666666666665in"}

25. A continuación nos dará las rutas donde escribirá los datos para el
    directorio de archivos en lo persona lo podemos mover a un lugar mas
    especifico, pero por motivos de ejemplo lo dejaremos donde están,
    pinchamos siguiente, esta pantalla solo nos mostrara el script

![Texto, Carta Descripción generada
automáticamente](.//media/image27.png){width="4.395833333333333in"
height="2.74411854768154in"}

26. Nos aparecen varias advertencias, como la falta del DNS, como la
    falta de una ip estática normalmente los servidores tiene esto. Pero
    instalaremos y luego lo iremos configurando.

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image28.png){width="4.072916666666667in"
height="2.9700371828521437in"}

27. Posterior a su instalación el equipo se reiniciará. Entramos ya con
    el dominio que instalamos con el administrador, y su contraseña, con
    esto estaremos iniciando y viendo en nuestro ***Administrador del
    Servidor,*** que este servidor ya se hizo con un servidor ***DNS***
    y el ***ACTIVE DIRECTORY,*** con esto solo nos falta poner la IP
    fija para el servidor.

![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
Descripción generada
automáticamente](.//media/image29.png){width="4.364583333333333in"
height="2.2182786526684164in"}

28. Ahora vamos a crear los usuarios dentro del ***ACTIVE DIRECTORY,***
    para eso vamos a ir a ***Herramientas -\> Centro de administración
    del active directory ,*** Una vez acá ya vamos a poder crear un
    grupo de trabajo o un usuario nuevo como vemos en pantalla.

![Interfaz de usuario gráfica, Sitio web Descripción generada
automáticamente](.//media/image30.png){width="4.792878390201225in"
height="3.0520833333333335in"}

a.  Para crear un usuario pinchamos en usuario, Llenamos los datos
    requeridos, le asignamos un grupo al usuario para que tenga las
    políticas implementadas en el.

> ![Interfaz de usuario gráfica, Texto, Aplicación Descripción generada
> automáticamente](.//media/image31.png){width="4.379328521434821in"
> height="2.8333333333333335in"}

b.  Creamos el grupo igual llenando los datos solicitados.

> ![Interfaz de usuario gráfica, Texto, Aplicación, Correo electrónico
> Descripción generada
> automáticamente](.//media/image32.png){width="4.283333333333333in"
> height="2.762503280839895in"}
