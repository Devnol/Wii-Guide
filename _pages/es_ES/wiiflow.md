---
title: "WiiFlow"
---

{% include toc title="Tabla de contenido" %}

Si necesitas ayuda con cualquier cosa en este tutorial, por favor entras [el servidor Discord de RiiConnect24](https://discord.gg/rc24) (recomendado) o [envias un correo electronico a support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![WiiFlow](/images/wiiflowlogo.png)

Esta es una guía de inicio rápido sobre cómo usar USB Loader GX, un popular cargador USB para Wii que se usa para jugar juegos desde una unidad USB.

#### Requisitos

* Una consola Wii
* Una unidad USB y/o tarjeta SD
* [WiiFlow Lite](https://hbb1.oscwii.org/hbb/wiiflow/wiiflow.zip)

¡Asegúrate de haber instalado [cIOS](/cios) antes de continuar!
{: .notice--info}

Te recomendamos que copies los juegos con [Wii Backup Manager](/wiibackupmanager) si utiliza Windows, [Witgui](https://desairem.com/wordpress/category/witgui-download/) si usas macOS, o [Wii Backup Fusion](https://github.com/larsenv/Wii-Backup-Fusion) para Windows, macOS, y Linux.
{: .notice--info}

Si quieres jugar a juegos que están en formato NKit, utiliza [este programa](https://gbatemp.net/download/nkit.36157/) para convertirlos en ISO primero. También puede utilizar una versión de desarrollo de Dolphin, haz clic con el botón derecho del ratón en un juego, y utilice "Convertir archivo" para convertirlo.
{: .notice--info}

Si no vas a copiar los juegos con Wii Backup Manager, Witgui o Wii Backup Fusion, crea una carpeta en la raíz de la unidad USB o tarjeta SD llamada "wbfs" y pon los juegos ahí.
{: .notice--info}

Para jugar a juegos, te recomendamos usar un disco duro externo para tu Wii. Las unidades Flash también funcionan, pero se recomienda el uso de Discos duros externos, debido a que son mucho mas seguros, y pueden almacenar una mayor cantidad de juegos.
{: .notice--info}

Unlike USB Loader GX, WiiFlow can load games of an SD card.
{: .notice--info}

Make sure your USB drive and/or SD card is formatted as FAT32 or NTFS. Do not format it as other types such as exFAT, extFS, or WBFS, the latter is an old format of storing Wii games.
{: .notice--info}

#### Instrucciones

##### Descargando

1. Extrae Wiiflow, y coloca los archivos `apps` y `WiiFlow` en tu Unidad USB o tarjeta SD.
2. Inserta tu unidad USB, y tarjeta SD (si estas usando una) en tu Wii y abre la aplicación Wiiflow desde el Homebrew Channel.

##### Comenzar

This is not a full comprehensive guide on using WiiFlow. This is intended to help you learn how to use it, by giving you a quick start. You should be able to figure out all the great features of WiiFlow by using it.
{: .notice--info}

* Wiiflow esta configurado de forma predeterminada para encontrar juegos solo en la tarjeta SD. Esto puede ser cambiado entrando a "Settings", "Startup settings" y luego deshabilitar la opción "Mount SD Only".
* Puede alternar entre ver los juegos de Wii, juegos de GameCube, canales de Wii, Plugins y Aplicaciones de Homebrew pulsando el segundo botón hasta el ultimo en la derecha.
* Puede descargar el arte de las cajas de los juegos dirigiendose a "Settings" y luego "Download Covers y Banners"

##### Interfaz de usuario

When WiiFlow detects games, they are displayed in flow view. When you click on a game you are given these options:

* Estrella - Añade tus juegos a favoritos.
* Librería - Añade el juego a 1 de 6 categorías de las que elijas.
* Ajustes - Abre un menú de ajustes para específicamente el juego que seleccionaste. Cambiar estos ajustes solamente afectan al juego que seleccionaste previamente.
* X - Borra un juego de la unidad USB o tarjeta SD

When you bring the cursor to the bottom of the screen while in flow view, there are 6 icons:

* Librería - Mira los juegos que están ordenados en las categorías que elegiste para ellos.
* Estrella - Mira los juegos que pusiste de favorito.
* Ajustes - abre los ajustes de WiiFlow.
* Tipo de juego - Cambia entre distintos tipos de aplicaciones/juegos. El logo cambia dependiendo en que tipo de juego seleccionaste.
* Disco - Carga el juego que esta en la ranura para discos de la Wii.
* Casa - Abrirá este menú. Este menú también puede abrirse oprimiendo el botón HOME.

![WF_menu](images/WFmenu.png)

* Ayuda - Muestra todos los controles que puedes usar en WiiFlow.
* Recargar cache - Presiona esto cuando WiiFlow no esta detectando un juego nuevo en el dispositivo USB o tarjeta SD.
* Explorador de archivos - Te permite iniciar juegos/aplicaciones desde cualquier lugar en tu dispositivo USB o tarjeta SD.
* Seleccionar complementos - Te permite seleccionar complementos.
* Créditos - Te muestra la gente que se esforzó y sudo trabajando en WiiFlow.
* Apagar - Te permite ya sea apagar la Wii completamente, o en modo suspensión.
* Salida - Te permite salir al Menú de Wii, HBC, neek2o, Priiloader y Bootmii.
* Configuración - Abre el menú de configuración de WiiFlow

##### Opciones una vez terminado

[WiiFlowiki](https://sites.google.com/site/WiiFlowiki4/)<br> WiiFlowiki is a great resource with information about WiiFlow.
{: .notice--info}

[Continue to RiiTag](riitag)<br> RiiTag is a customizable gamertag for your Wii that WiiFlow Lite can integrate with. This is optional to set up.
{: .notice--info}

[Echa un vistazo a nuestras otras guías](site-navigation)<br> Tenemos muchos otros tutoriales que podrían interesarte.
{: .notice--info}
