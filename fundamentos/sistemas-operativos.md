# Sistemas operativos

## Introducción

En está sección revisaremos los diferentes sistemas operativos así como sus principales características.

Tambien repasaremos un poco de historia.

Un sistema operativo (SO) es el conjunto de programas de un sistema informático que gestiona los recursos del hardware y provee servicios a los programas de aplicación de software. Estos programas se ejecutan en modo privilegiado respecto de los restantes.

## Funciones principales

Algunas de las funciones principales de un sistema operativo son las siguientes:

* **Gestionar la memoria de acceso aleatorio y ejecutar las aplicaciones, designando los recursos necesarios**: El sistema operativo es responsable de administrar eficientemente la memoria RAM y asignar los recursos necesarios a las aplicaciones en ejecución. Además de asignar memoria, también gestiona la liberación de memoria cuando una aplicación ya no la necesita.
* **Administrar la CPU gracias a un algoritmo de programación**: El sistema operativo coordina el uso de la CPU entre las diferentes tareas y procesos que se ejecutan en el sistema. Utiliza algoritmos de programación para determinar el orden y la prioridad de ejecución de los procesos, asegurando un uso equitativo de los recursos de la CPU.
* **Gestionar las entradas y salidas de datos a través de los periféricos**: Además de direccionar las entradas y salidas de datos, el sistema operativo proporciona controladores (drivers) para interactuar con los periféricos de entrada y salida, como teclados, mouse, impresoras, discos duros externos, entre otros. Estos controladores permiten que los dispositivos se comuniquen correctamente con el sistema operativo y las aplicaciones.
* **Administrar la información para el buen funcionamiento del sistema**: El sistema operativo gestiona información esencial para el funcionamiento del sistema, como la tabla de procesos, la tabla de archivos abiertos y otros datos relevantes. Además, realiza tareas de monitoreo y gestión del rendimiento para asegurar un funcionamiento óptimo del sistema.
* **Dirigir las autorizaciones de uso para los usuarios**: El sistema operativo proporciona un mecanismo de autenticación y autorización para garantizar que los usuarios accedan solo a los recursos y funciones para los cuales tienen permisos. Esto incluye la gestión de cuentas de usuario, contraseñas y asignación de privilegios.
* **Administrar los archivos**: El sistema operativo maneja las operaciones relacionadas con la gestión de archivos, como la creación, modificación, eliminación y acceso a los archivos en el sistema de almacenamiento. Esto implica la organización de los archivos en directorios o carpetas, el control de acceso a los archivos y la implementación de mecanismos de seguridad para proteger la integridad y confidencialidad de la información.

## Clasificación

### Administración de tareas
* **Monotarea**: Solamente permite ejecutar un proceso (aparte de los procesos del propio SO) en un momento dado. Una vez que empieza a ejecutar un proceso, continuará haciéndolo hasta su finalización y/o interrupción.
* **Multitarea**: Es capaz de ejecutar varios procesos al mismo tiempo. Este tipo de SO normalmente asigna los recursos disponibles (CPU, memoria, periféricos) de forma alternada a los procesos que los solicitan, de manera que el usuario percibe que todos funcionan a la vez, de forma concurrente. La multitarea puede estar relacionada con el multiprocesamiento, ya que en sistemas con múltiples núcleos de CPU o procesadores, se pueden asignar diferentes procesos a cada núcleo para ejecutarse simultáneamente, lo que mejora el rendimiento y la capacidad de respuesta del sistema. El multiprocesamiento permite una mayor eficiencia en la ejecución de tareas al aprovechar los recursos de la CPU de manera paralela y simultánea.
### Administración de usuarios
* **Monousuario**: Solo permite ejecutar los programas de un usuario al mismo tiempo.
* **Multiusuario**: Permite que varios usuarios ejecuten simultáneamente sus programas, accediendo a la vez a los recursos de la computadora. Normalmente estos sistemas operativos utilizan métodos de protección de datos, de manera que un programa no pueda usar o cambiar los datos de otro usuario.

### Administración de sesiones

* **Monosesión**: Sistemas operativos que son capaces de ejecutar una sola sesión de usuario. Los sistemas operativos de hace tiempo como Windows 98 o Windows 95.
* **Multisesión**: Sistemas operativos que son capaces de ejecutar varias sesiones de usuario a la vez. La funcionalidad de multisesión se puede instalar mediante aplicaciones, pero es el sistema operativo el que permite dicho funcionamiento. Los servidores de la familia Windows Server, la mayoría de las versiones de Linux.12​

### Manejo de recursos
* **Centralizado**: Permite usar los recursos de una sola computadora.
* **Distribuido**: Permite utilizar los recursos (memoria, CPU, disco, periféricos...) de más de una computadora al mismo tiempo.

## Sistemas operativos mas comunes

### Microsoft Windows

Windows es el nombre de una familia de distribuciones de software para PC, servidores, sistemas empotrados y antiguamente teléfonos inteligentes desarrollados y vendidos por Microsoft y disponibles para múltiples arquitecturas, tales como x86, x86-64 (x64) y ARM.

Desde un punto de vista técnico, no son sistemas operativos, sino que contienen uno (tradicionalmente MS-DOS o el más actual cuyo núcleo es Windows NT) junto con una amplia variedad de software; no obstante, es usual (aunque no necesariamente correcto) denominar al conjunto como sistema operativo en lugar de distribución. Microsoft introdujo un entorno operativo denominado Windows el 20 de noviembre de 1985 como un complemento para MS-DOS en respuesta al creciente interés en las interfaces gráficas de usuario (GUI).2​ Microsoft Windows llegó a dominar el mercado mundial de computadoras personales, con más del 70 % de la cuota de mercado, superando a Mac OS, que había sido introducido en 1984.

La versión más reciente de Windows es Windows 11 para equipos de escritorio, Windows Server 2022 para servidores y Windows 10 Mobile para dispositivos móviles. La primera versión en español fue Windows 2.1.

La primera versión se lanzó en 1985 y comenzó a utilizarse de forma generalizada gracias a su interfaz gráfica de usuario (GUI, Graphical User Interface) basada en ventanas. Hasta ese momento (y hasta mucho después como corazón de Windows), el sistema operativo más extendido era MS-DOS (Microsoft Disk Operating System), que por aquel entonces contaba con una interfaz basada en línea de comandos.

Windows 10 llegó de forma oficial y gratuita a usuarios con licencia genuina de Windows 7, Windows 8 y Windows 8.1 el 29 de julio de 2015. Fue la primera versión que buscó la unificación de dispositivos (escritorio, portátiles, teléfonos inteligentes, tabletas y videoconsolas) bajo una experiencia común. Su sucesor, Windows 11, se lanzó oficialmente el 5 de octubre de 2021 como una actualización gratuita a través de Windows Update de Windows 10, para aquellos equipos que cumpla con ciertas especificaciones técnicas compatibles del nuevo sistema. Microsoft promovió que Windows 11 habría mejorado el rendimiento y la facilidad de uso sobre Windows 10, contando con cambios importantes en el Shell de Windows influenciados por el cancelado Windows 10X, incluido un menú Inicio rediseñado, así como la incompatibilidad con la arquitectura x86 de 32 bits o los sistemas que usan firmware del BIOS.

### Unix

Unix es un sistema operativo portable, multitarea y multiusuario desarrollado en 1969 por un grupo de empleados de los laboratorios Bell de AT&T.1

El sistema, junto con todos los derechos fueron vendidos por AT&T a Novell, Inc. Esta vendió posteriormente el software a Santa Cruz Operation en 1995, y esta, a su vez, lo revendió a Caldera Software en 2001, empresa que después se convirtió en el grupo SCO. Sin embargo, Novell siempre argumentó que solo vendió los derechos de uso del software, pero que retuvo el copyright sobre "UNIX®". En 2010, y tras una larga batalla legal, esta ha pasado nuevamente a ser propiedad de Novell.

Solo los sistemas operativos totalmente compatibles y que se encuentran certificados por la especificación Single UNIX Specification pueden ser denominados "UNIX®" (otros reciben la denominación «similar a un sistema Unix» o «similar a Unix»). En ocasiones, suele usarse el término "Unix tradicional" para referirse a Unix o a un sistema operativo que cuenta con las características de UNIX Versión 7 o UNIX System V o unix versión 6.

### Linux

Linux es un software libre y de código abierto,1​ monolítico, modular, multitarea, núcleo de sistema operativo tipo Unix. Fue originalmente escrito en 1991 por Linus Torvalds para su PC basada en i386, y pronto fue adoptado como el núcleo para el sistema operativo GNU, que fue creado como un reemplazo libre para Unix.

Linux se proporciona bajo la Licencia Pública General de GNU versión 2, pero contiene archivos bajo otras licencias compatibles.2​ Desde finales de la década de 1990, ha sido incluido como parte de un gran número de distribuciones de sistemas operativos, muchas de las cuales también se denominan comúnmente Linux.

Linux se despliega en una amplia variedad de sistemas informáticos, como sistemas embebidos, dispositivos móviles (incluido su uso en el sistema operativo Android), computadoras personales, servidores, mainframes y supercomputadoras.3

Puede ser adaptado para arquitecturas específicas y para varios escenarios de uso utilizando una familia de comandos simples (es decir, sin necesidad de editar manualmente su código fuente antes de la compilación).5​6​7​ Usuarios con privilegios también pueden ajustar los parámetros del núcleo en tiempo de ejecución.8​ La mayor parte del código del núcleo de Linux está escrito utilizando las extensiones de GNU del GCC9​10​ al estándar lenguaje de programación C y con el uso de instrucciones específicas de la arquitectura (ISA) en partes limitadas del núcleo. Esto produce un ejecutable altamente optimizado (vmlinux) con respecto a la utilización del espacio de memoria y los tiempos de ejecución de tareas.

#### Distribuciones Linux

Una distribución Linux (GNU/Linux) (coloquial y abreviadamente llamada distro) es una distribución de software basada en el núcleo Linux, y a menudo, un Sistema de gestión de paquetes que incluye determinados paquetes de software, para satisfacer las necesidades de un grupo específico de usuarios, dando así origen a ediciones domésticas, empresariales y para servidores. Por lo general están compuestas, total o mayoritariamente, de software libre, aunque a menudo incorporan aplicaciones o controladores propietarios.
Además del núcleo Linux, las distribuciones incluyen habitualmente las bibliotecas y herramientas del proyecto GNU y el sistema de ventanas X Window System. Dependiendo del tipo de usuarios a los que la distribución esté dirigida se incluye también otro tipo de software como procesadores de texto, hoja de cálculo, reproductores multimedia, herramientas administrativas, etc.

En el caso de incluir paquetes de código del proyecto GNU, se denomina distribución GNU/Linux.

Existen distribuciones que están soportadas comercialmente, como Fedora (Red Hat), openSUSE (SUSE) y Ubuntu (Canonical Ltd.); distribuciones mantenidas por la comunidad, como Debian, Arch Linux y Gentoo; y distribuciones que no están relacionadas con ninguna empresa o comunidad, como es el caso de Slackware.