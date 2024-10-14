# Instalación de Linux en VirtualBox

## Elección de distribución
En este apartado se va a instalar Linux en una máquina virtual en Virtual Box. Lo primero sería elegir una distribución para instalar. 

Hablaremos más adelante de las diferentes distribuciones Linux con sus propiedades pero para avanzar elegiremos una en este momento. En base a las diferentes tématicas que seguiremos en esta formación vamos a elegir **Kali Linux**, distribución especializada en ciberseguridad basada en **Debian**, pero queda a elección personal la elección de otra distribución.

En principio seria recomendable que sea una distribución basada en Debian o Ubuntu ya que se usarán algunos comandos nativos de estas distribuciones. Recomendamos instalar una de estas:

* **Kali Linux**: Basada en Debian especializada en seguridad.
* **Parrot OS**: Basada en Ubuntu especializada en seguridad.
* **Ubuntu**: Proposito general.
* **Debian**: Proposito general.
* **Linux Mint**: Proposito general basada en Ubuntu.

## Descarga de Kali Linux

Podemos descargar la última versión de Kali Linux en formato ISO, (para poder instalarla en una VM), desde la página de Kali, (https://www.kali.org/):

![alt text](../images/img-instalacionvbox.png)

En descargas seleccionamos **Installer Images**.

![alt text](../images/img-instalacionvbox-1.png)

Seleccionamos la opción de 64bits y pulsamos la flecha.

![alt text](../images/img-instalacionvbox-2.png)

El enlace directo si no queremos navegar es https://cdimage.kali.org/kali-2024.3/kali-linux-2024.3-installer-amd64.iso

## Creación de máquina virtual en VirtualBox

Abrimos VirtualBox y en el menú **Maquina** seleccionamos **Nueva**, o en la página de bienvenida pulsamos el botón **Nueva**.

![alt text](../images/img-instalacionvbox-3.png)

* Le damos nombre. Recomendamos "kali-nombre", por ejemplo **kali-jamunoff**.
*  Seleccionamos la carpeta de almacenamiento. **IMPORTANTE** asegurar un sitio controlado y con espacio suficiente. Está maquina puede llegar a ocupar 100GB. Para mejorar el rendimiento es conveniente que esté en dosco SSD.
* Imagen ISO. Seleccionar el fichero iso de la distribución de Kali Linux descargada.
* En tipo dejamos Linux.
* En subtipo podemos dejar Ubuntu o Debian.
* En versión Debian 64 bits o Ubuntu 64 bits. Si sabemos de que versión de Debian o de Ubuntu hereda la distribución lo podemos elegir. Lo único que hace esto es ofrecer parámetros de memoria, disco y procesador en la VM. No obstante da un poco igaul porque los revisaremos manualmente.

![alt text](../images/img-instalacionvbox-4.png)

Seleccionamos ahora la opción de **Hardware**:

* Memoria: Mínimo 4GB. Si es posible 6GB, (1024 * 6 = 6144).
* Procesador: Con 2 nucleos vale. Como mucho la mitad de los posibles.

![alt text](../images/img-instalacionvbox-5.png)

Selecionamos ahora disco duro. Ponemos 100GB. El resto como viene por defecto.

Ahora pulsamos **Terminar**.

![alt text](../images/img-instalacionvbox-6.png)

## Instalación de Kali Linux

Arrancamos la máquina virtual pulsando **Iniciar**, con la máquina recien creada seleccionada.

![alt text](../images/img-instalacionvbox-7.png)

Esperamos a que arranque. Se abrirá una ventana nueva con la máquina virtual. Ocultamos las notificaciones de la derecha y elegimos **Graphical Install**.

![alt text](../images/img-instalacionvbox-8.png)

Elegimos idioma español y continuar.

![alt text](../images/img-instalacionvbox-9.png)

Elegimos ubicación **España**.

![alt text](../images/img-instalacionvbox-10.png)

Idioma **Español**.

![alt text](../images/img-instalacionvbox-11.png)

Dejamos que cargen elementos y se configura la red. Introducimos nombre de máquina. Recomendamos el que pusimos a la VM, kali-idusuario.

![alt text](../images/img-instalacionvbox-12.png)

Dejamos nombre de dominio en blanco.

![alt text](../images/img-instalacionvbox-13.png)

Damos como Nombre completo nuestro nombre de usuario.

![alt text](../images/img-instalacionvbox-14.png)

Lo mismo para usuario.

![alt text](../images/img-instalacionvbox-15.png)

Ponemos dos veces la contraseña. En este punto que tampoco sea muy compleja ya que la vamos a insertar muchas veces. Algo comodo y rapido de teclear y **QUE NO SE OS OLVIDE**.

![alt text](../images/img-instalacionvbox-16.png)

Dejamos que se configure la zona horaria. No pedirá ubicación dentro de España. Elegimos peninsula.

![alt text](../images/img-instalacionvbox-17.png)

Ahora comienza la preparación del disco. Le damos la opción de guiado por defecto.

![alt text](../images/img-instalacionvbox-18.png)

Elegimos el único disco duro virtual que existe.

![alt text](../images/img-instalacionvbox-19.png)

Damos la opción recomendada para particionar el disco. Todo en una partición.

![alt text](../images/img-instalacionvbox-20.png)

Pulsamos en Finalizar y confirmamos.

![alt text](../images/img-instalacionvbox-21.png)

![alt text](../images/img-instalacionvbox-22.png)

Dejamos ahora que instale el sistema. 
Nos pedirá elegir el entorno de escritorio y los programas a instalar. Elegimos lo que viene por defecto.

![alt text](../images/img-instalacionvbox-23.png)

Dejamos que acabe de instalar. Esto puede tardar un rato.

Cuando acabe nos preguntará si queremos instalar el cargador de arranque. Le decimos que sí.

![alt text](../images/img-instalacionvbox-24.png)

Elegimos el disco para el cargador de arranque. El único que hay.

![alt text](../images/img-instalacionvbox-25.png)

Le dejamos finalizar la instalación.

![alt text](../images/img-instalacionvbox-26.png)

Pulsamos continuar para reiniciar y dejamos que arranque.

![alt text](../images/img-instalacionvbox-27.png)

Introdcimos el usuario y contraseña que le dimos en la instalación y entramos en la máquina.

![alt text](../images/img-instalacionvbox-28.png)

![alt text](../images/img-instalacionvbox-29.png)


## Actualización de Kali Linux

Una vez arrancado el sistema podemos maximizar la pantalla con la conbinzación de teclas CTLR DER + F.

Lo primero es comprobar que tenemos acceso a Internet desde la máquina virtual para ello abrimos el navegador Firefox e intentamos navegar a google y realizar una búsqueda.

![alt text](../images/img-instalacionvbox-30.png)

![alt text](../images/img-instalacionvbox-31.png)

Procedemos ahora a actualizar el sistema. Para ello abrimos una consola.

![alt text](../images/img-instalacionvbox-32.png)

![alt text](../images/img-instalacionvbox-33.png)

Escribimos el siguiente comando para actualizar los repositorios.

```bash
sudo apt update
```

> [!CAUTION]IMPORTANTE
> La orden **sudo** ejecuta comandos como usuario con privilegios, como root. Os pedirá vuestra contraseña la primera vez y cuando pase determinado tiempo.

![alt text](../images/img-instalacionvbox-34.png)

Ahora actualizamos los paquetes que estén desactualizado. Según la imagen 912.

Ejecutamos el comando: 

```bash
sudo apt upgrade -y
```

![alt text](../images/img-instalacionvbox-35.png)

El **-y** hace que se instalen las actualizaciones sin solicitar confirmación. Este proceso puede tardar un poco.

Puede solicitarnos el reincio de algunos servicios. Si es así le damos a la aopción **Yes**. Para ello nos movemos con el tabulador y pulsamos ENTER para aceptar.

![alt text](../images/img-instalacionvbox-36.png)


Cuando acabe repetimos el proceso con la orden **full-upgrade** y **dist-upgrade**. La primera fuerza actualizaciones del nucleo, (kernel), de Linux si las hubiera. La segunda fuerza actualización de versión del sistema operativo si las hubiera.


```bash
sudo apt full-upgrade -y
```
![alt text](../images/img-instalacionvbox-37.png)

```bash
sudo apt dist-upgrade -y
```
![alt text](../images/img-00-instalacionvbox.png)


Luego ejecutamos la opción autoremove para eliminar paquetes obsoletos.

```bash
sudo apt autoremove -y
```
![alt text](../images/img-00-instalacionvbox-1.png)

Por último comprobamos que está todo al día con otro update.

![alt text](../images/img-00-instalacionvbox-2.png)

Si todo está OK reiniciamos con el comando **reboot**.

![alt text](../images/img-00-instalacionvbox-3.png)

```bash
sudo reboot
```

