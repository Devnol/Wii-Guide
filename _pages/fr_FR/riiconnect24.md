---
title: "RiiConnect24"
---

{% include toc title="Table des matières" %}

Si vous avez besoin d'aide pour quoi que ce soit concernant ce tutoriel, veuillez rejoindre [ le serveur RiiConnect24 Discord ](https://discord.gg/rc24) (recommandé) ou [envoyez-nous un e-mail à support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![RiiConnect24 Logo](/images/WiiRC24Logo.jpg)

[RiiConnect24](https://rc24.xyz/) vous permet d'utiliser les services interrompus de WiiConnect24, qui incluent les chaînes infos, météo, votes, Nintendo et concours Mii, ainsi que Wii Mail.

{% capture notice-1 %}
Ce guide concerne uniquement la Wii standard.

- Suivez [ce tutoriel](riiconnect24-vwii) si vous voulez installer Riiconnect24 sur vWii (Mode Wii sur la Wii u).
- Suivez [ce tutoriel](riiconnect24-dolphin) si vous souhaitez installer RiiConnect24 sur Dolphin Emulator.
{% endcapture %}

<div class="notice--warning">{{ notice-1 | markdownify }}</div>

N'INSTALLEZ PAS RIICONNECT24 SUR UNE WII MINI ! Cela ne fonctionnera pas et cela briquera le système.
{: .notice--danger}

#### Ce dont vous avez besoin

* Une carte SD ou un périphérique USB
* Une Wii avec une connexion Internet
* Un ordinateur
* [Patcher Riiconnect24 (Windows, Mac et Linux)](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)

#### Instructions

##### Section 1 - Utiliser le Patcher Riiconnect24

Si vous ne pouvez pas faire marcher le patcher Riiconnect24, Rejoignez le[ Discord Server Riiconnect24](https://discord.gg/rc24) (recommandé) ou [ e-mailez nous chez support@riiconnect24.neta](mailto:support@riiconnect24.net) pour assistance.
{: .notice--info}

1. Cliquez sur le lien ci-dessus pour accéder à la page GitHub où se trouve le patcher.
2. Téléchargez `RiiConnect24Patcher.bat` si vous êtes sous Windows, et `RiiConnect24Patcher.sh` si vous êtes sur un système Unix
3. Sur Windows ouvrez `Riiconnect24Patcher.bat`. Sur les systèmes Unix, ouvrez le terminal et tapez `bash`, puis faites glisser `RiiConnect24Patcher.sh` dans le terminal et appuyez sur Entrée. Cela devrait ressembler à ceci `bash RiiConnect24Patcher.sh`.
4. Appuyez sur 1 pour choisir "`Start`" et confirmez votre sélection en appuyant sur `ENTER`. (NOTE : Ces captures d'écran proviennent de la version Windows du patcher.) ![Écran principal de RiiConnect24 Patcher](/images/RC24_Patcher/1.JPG)
5. Sélectionnez le périphérique pour lequel vous êtes en train de patcher. ![Sélectionnez votre appareil](/images/RC24_Patcher/2.JPG)
6. Pour ce guide, choisissez "`Installer RiiConnect24 sur votre Wii`" ![Install RiiConnect24](/images/RC24_Patcher/3.JPG)
7. Choisissez "`Express (Recommendé)`". Cela vous procurera tout ce dont vous aurez besoin. ![Paramètres Express](/images/RC24_Patcher/4.JPG)
8. Sélectionnez votre région. ![Sélectionnez votre région](/images/RC24_Patcher/5.JPG)
9. Pendant que vous y êtes, RiiConnect24 Patcher peut également télécharger d'autres chaînes optionnelles qui n'utilisent pas RiiConnect24. `[X]` Représente l'option sélectionnée. Appuyez simplement sur 5 et `ENTRÉE` si vous n'êtes pas intéressé. ![Chaînes optionnelles supplémentaires](/images/RC24_Patcher/6.JPG)
10. Connectez votre carte SD ou votre périphérique USB à votre ordinateur et sélectionnez "`1`". ![Activer le copiage vers la carde SD](/images/RC24_Patcher/7.JPG)
11. Si votre périphérique est correctement détecté, sélectionnez "`1`". Sinon, assurez-vous qu'il y a un dossier appelé `apps` sur votre carte SD ou votre clé USB et réessayez. ![Détecté avec succès](/images/RC24_Patcher/8.JPG)
12. Soyez patient... ![Est entrain de patché!](/images/RC24_Patcher/9.JPG)
13. Après que ça se termine, on apprécié so vous prenez une minute pour nous envoyer un commentaire anonyme.  Si vous ne voulez pas, fermez le patcher. Tous les fichiers dois être sur votre carte SD. ![C'est terminé !](/images/RC24_Patcher/10.JPG) ![Les fichiers ont été copiés](/images/RC24_Patcher/11.PNG)
14. Si tout n'a pas été copié automatiquement sur votre carte SD ou votre périphérique USB, copiez les dossiers `WAD` et `apps` à côté de `RiiConnect24Patcher.bat`, et collez-les sur votre carte SD ou votre périphérique USB.

##### Section II - Installer des wads

Vous allez maintenant installer les IOS patchées et chaînes WADs aui sont nécessaires pour utiliser Riiconnect24.

1. Insérer la carte SD ou le périphérique USB dans votre Wii.
2. Lancez la Chaîne Homebrew sur votre Wii.
3. Lancez Wii Mod Lite.
4. À l'aide de la croix directionnelle de votre télécommande Wii, accédez à `WAD Manager`, puis accédez au dossier `wad`.
5. Surlignez tous les WADs du dossier en appuyant sur le bouton + pour les sélectionner. Quand tous les WADs sont sélectionné, appuyez A deux fois pour installer les WADs.
6. Si vous obtenez une erreur indiquant qu'un titre avec une version supérieure est déjà installé (erreur -1035), revenez au menu de sélection WAD et appuyez sur le bouton - sur le WAD en surbrillance pour le désinstaller, puis réessayez de l'installer.
7. Une fois qu'ils sont tous correctement installés, appuyez sur le bouton HOME pour revenir au Homebrew Channel.

##### Section III - Patcher nwc24msg.cfg

Vous allez maintenant patchée votre `nwc24msg.cfg` qui est obligatoire pour utiliser Wii Mail.

1. Lancez RiiConnect24 Mail Patcher.
2. Cela ne devrait prendre que quelques secondes pour patcher votre fichier nwc24msg.cfg. Quand il termine, appuyez sur le bouton HOME pour quitter.

Si vous n'avez pas pus patché votre nwc24msg.cfg correctement, veuillez rejoindre [Le server Discord de Riiconnect24](https://discord.gg/rc24) (recommandé) ou [e-mailez nous vers support@riiconnect24.net](mailto:support@riiconnect24.net) pour assistance.
{: .notice--info}

##### Section IV - Se connecter

{% capture notice-1 %}
À partir du 16 juin 2022, le DNS RiiConnect24 change. En savoir plus: [ici.](riiconnect24-dns-update)
{% endcapture %}

<div class="notice--warning">{{ notice-1 | markdownify }}</div>

Vous allez maintenant configurer votre DNS vers nos serveurs. Cette option est facultative, mais elle est recommandée, car elle améliore l'utilisation de RiiConnect24 et Wiimmfi en rendant certaines autres fonctionnalités disponibles.

1. Allez dans les `Options Wii`.
2. Allez dans `Paramètres Wii`.
3. Allez à la `Page 2`, puis cliquez sur `Internet`.
4. Allez dans `Paramètres de connexion`.
5. Sélectionnez votre connexion actuelle.
6. Cliquez sur `Changer`.
7. Allez dans `Obtention automatique d'un DNS` (pas de l'adresse IP), puis sélectionnez `Non`, puis `Paramètres Avancés`.
8. Tapez `167.86.108.126` comme DNS primaire.
9. Tapez `1.1.1.1` comme DNS secondaire.
10. Sélectionnez `Confirmer`, puis `Sauvegarder`.
11. Appuyez sur `OK` pour effectuer un test de connexion.
12. Si le test de connexion est réussi, sélectionnez `Non` afin d'ignorer la mise à jour système Wii.
13. Allez sur `WiiConnect24`, puis `WiiConnect24` à nouveau, et vérifiez que c'est activé.
14. De retour au menu WiiConnect24, allez sur `Standby Connection` et vérifiez que c'est activé.
15. Dans `Slot Illumination`, nous recommandons de mettre le voyant du disque sur `Dim` ou `Bright`, mais c'est facultatif.
16. Enfin, allez dans la section `Internet`, puis `User Agreements` ou `Agreement/Contact`, puis `Yes`. Veuillez lire le texte affiché.

Il est courant d'obtenir l'erreur FORE000006 sur le canal de prévision après avoir installé RiiConnect24. Si vous l'obtenez, assurez-vous que votre Wii est à la bonne date et heure puis n'attendez pas plus d'une heure et il peut commencer à travailler. [Si vous obtenez toujours une erreur FORE000006 ou si vous recevez NEWS000006, vous devrez supprimer votre SYSCONF avec RC24-Clear-Tool].
{: .notice--warning}

Vous obtiendrez une erreur 268503 lors du chargement de la Chaîne Nintendo. C'est normal. Vous pouvez contourner l'erreur en appuyant sur OK.
{: .notice--warning}

Si vous obtenez l'erreur 107245, vous n'avez pas installé l'IOS corrigé. Assurez-vous d'installer IOS31 et IOS80 avec Wii Mod Lite, avec tous les autres WADs patchés.
{: .notice--warning}

Si vous obtenez l'erreur 107304 ou si vous voyez le contrat d'utilisation de Nintendo sans le logo de RiiConnect24, cela signifie que votre FAI (fournisseur d'accès Internet) ou votre réseau bloque l'utilisation d'un DNS. Vous pouvez définir `optention automatique DNS` sur `On` pour résoudre ce problème. RiiConnect24 fonctionnera toujours sans elle. Ou, vous pouvez utiliser notre programme [DNS-Server](https://github.com/RiiConnect24/DNS-Server/releases/latest).
{: .notice--warning}

[Si vous obtenez d'autres erreurs avec la Chaîne de Prévisions ou la Chaîne Infos, comme un code d'erreur commençant par FORE ou NEWS ou un message interrompu, vous pouvez essayer de supprimer vos VFFs avec RC24-Clear-Tool](deleting-vffs).
{: .notice--warning}

Si vous obtenez des erreurs telles que `WiiConnect24 et la chaîne boutique Wii ne sont actuellement pas disponibles dans votre pays`, allez dans Paramètres Wii - > Dernière page -> Pays et remplacez-le par Royaume-Uni. Vous obtiendrez cette erreur lorsque vous utilisez un pays que nous ne prenons pas en charge. Contactez-nous à [support@riiconnect24.net](mailto:support@riiconnect24.net) si vous avez besoin d'aide supplémentaire.
{: .notice--warning}

[Continuer vers Wiimmfi](wiimmfi)<br> Wiimmfi vous permet de jouer à des jeux en ligne après l'arrêt de la connexion Wi-Fi Nintendo. L'installation est facultative.
{: .notice--info}

[Continué vers wiilink](wiilink)<br> Wiilinl vous permet d'utiliser les chaînes exclusive japonais comme Wii no Ma et la chaîne Digicam Print. L'installation est facultative.
{: .notice--info}

[Continuer vers la navigation du site](site-navigation)<br> Nous avons de nombreux autres tutoriels que vous pourriez aimer.
{: .notice--info}
