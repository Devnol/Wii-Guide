---
title: "cIOS"
---

{% include toc title="Tablof Contents" %}

Aquest tutorial us ensenyarà a instalar cIOS (IOS costumizats). Açò és requerit si vols carregar jocs amb un "USB Loader". Alguns programes "homebrew" poden funcionar millor emprant cIOS.

![instalador d2x cIOS](/images/cios/cIOS.png)

Si tens una Wii U (vWii), segueix [aquesta guia](https://wiiu.hacks.guide/#/vwii-modding)per a instal·lar cIOS. Intentar instal·lar qualsevol altre cIOS a la vWii no funcionarà.
{: .notice--info}

Si tens una Wii, aleshores segueix [aquesta guia](cios-mini). Intentar instal·lar qualsevol altre cIOS a la vWii no funcionarà.
{: .notice--info}

#### Què necessitaràs?

- Una Wii
- Una tarjeta SD o Pendrive USB
- [Instal·lador d2x cIOS](https://hbb1.oscwii.org/hbb/d2x-cios-installer/d2x-cios-installer.zip)

Assegurat que si estàs emprant una targeta SD, l'interruptor de bloqueig es troba a la posició de "desbloqueig", d'altra forma no podràs seleccionar les opcions correctes a l'instal·lador.
{: .notice--warning}

#### Instruccions

<button class="tablinks btn btn--large btn--primary" id="defaultOpen" onclick="openTab(event, 'with-connection')">Amb internet a la Wii</button>
<button class="tablinks btn btn--large btn--info" onclick="openTab(event, 'without-connection')">Sense internet a la Wii</button>

<div id="with-connection" class="blanktabcontent" markdown="1">

##### Secció I - Descarregar

1. Descarrega l'instal·lador del cIOS d2x i extrau-lo al "root" de la tarjeta SD o Pendrive USB.
1. Inserta la tarjeta SD o Penrive USB a la teva Wii, i inicia l'instal·lador del cIOS d2x des-del "Homebrew Channel".
</div>
<div id="without-connection" class="blanktabcontent" markdown="1">

##### Secció I - Descarregar

1. Descarrega, extrau i inicia l'aplicació [NUS Downloader](https://github.com/WiiDatabase/nusdownloader/releases/latest/download/NUSD-Mod-NUS-Fix.zip).
1. Selecciona "Database", "IOS", després "IOS57", i selecciona "v5918".
   - Assegura't que "Pack WAD" està seleccionat però "Patch IOS" no ho està.
1. Repeteix el pas anterior per a IOS56 v5661 i IOS38 v4123.
1. Una vegada hagis descarregat els tres IOS, hi haurà una carpeta anomenada `titles` a la mateixa carpeta del "NUS Downloader". Obri la carpeta i navega a aquesta fins a trobar els tres arxius WAD que vas descarregar. Posa'ls al "root" de la targeta SD o Pendrive USB.
1. Descarrega l'instal·lador del cIOS d2x i extrau-lo al "root" de la tarjeta SD o Pendrive USB.
1. Inserta la tarjeta SD o Penrive USB a la teva Wii, i inicia l'instal·lador del cIOS d2x des-del "Homebrew Channel".
</div>

##### Secció II - Instalant

1. Premeu continuar, després fixeu les opcions a les següents:

```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 57
Select cIOS slot: 249
Select cIOS version: 65535
```

![Install cIOS 249](/images/cios/Install249.png)

1. Una volta preparat, prem A dues vegades per a instal·lar.
1. Quan hagueu acabat d'instalar, premeu A per a tornar, i poseu les opcions a les següents:

```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 56
Select cIOS slot: 250
Select cIOS version: 65535
```

![Install cIOS 250](/images/cios/Install250.png)

1. Una volta preparat, prem A dues vegades per a instal·lar.
1. Quan hagueu acabat d'instalar, premeu A per a tornar, i poseu les opcions a les següents:

```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 38
Select cIOS slot: 251
Select cIOS version: 65535
```

![Install cIOS 251](/images/cios/Install251.png)

1. Una volta preparat, prem A dues vegades per a instal·lar, i ix una vegada acabat.

#### Resolució de problemes

{% capture bruh %}
Although the majority of games should work straight away with the defaults, some may require using a specific cIOS to function, or to utilize certain features within the game.<br> Examples include:

- Using a keyboard in Animal Crossing: City Folk.
- Running SpongeBob's Boating Bash.

A more comprehensive (although still incomplete) list can be found [**here**](https://wiki.gbatemp.net/wiki/Wii_cIOS_base_Compatibility_List)<br> To change the cIOS used for a specific game, follow these instructions:
{% endcapture %}

<div class="notice--warning">{{ bruh | markdownify }}</div>

<button class="tablinks btn btn--large btn--primary" id="defaultOpen" onclick="openTab(event, 'usbloadergx')">USB Loader GX</button>
<button class="tablinks btn btn--large btn--info" onclick="openTab(event, 'wiiflow')">WiiFlow</button>

<div id="usbloadergx" class="blanktabcontent" markdown="1">
1. Select the game that isn't working.
1. Click Settings.
1. Select `Game Load`.
1. Scroll down to `Game IOS`.
1. Enter the IOS slot to use.
    - Try using 250 or 251, if 249 doesn't work.
1. Press ok and try to load the game.
</div>
<div id="wiiflow" class="blanktabcontent" markdown="1">
1. Select the game that isn't working.
1. Click the gear icon.
1. Go to cIOS and use the arrows to select the IOS slot to use.
    - Try using 250 or 251, if 249 doesn't work.
1. Press Save and try to load the game.
</div>
##### Options once complete

[Continue to the Homebrew Browser](hbb)<br> The Homebrew Browser is a good place to get homebrew on your Wii. This is optional to install.
{: .notice--info}

[Continue to site navigation](site-navigation)<br> We have many other tutorials that you might like.
{: .notice--info}

Ara pots utilitzar homebrew com [USB Loader GX](usbloadergx) i [WiiFlow](wiiflow).
{: .notice--info}

<script>
    let tabcontent = document.getElementsByClassName("blanktabcontent");
    let tablinks = document.getElementsByClassName("tablinks");

    function openTab(evt, tabName) {
        let element;

        for (element of tabcontent) {
            element.style.display = "none";
        }

        for (element of tablinks) {
            element.className = element.className.replace("btn--primary", "btn--info");
            if (!element.className.includes('btn--info'))
                element.className += " btn--info";
        }

        document.getElementById(tabName).style.display = "block";
        evt.currentTarget.className = evt.currentTarget.className.replace("btn--info", "btn--primary");
    }

    // Get the element with id="defaultOpen" and click on it
    document.getElementById("defaultOpen").click();
</script>
