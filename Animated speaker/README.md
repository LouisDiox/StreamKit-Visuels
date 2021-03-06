# Animated speaker
:scroll: - Affiche une icone de haut parleur animée, surligne les contours et joue un effet de tremblement lorsque qu'un utilisateur parle.

:speech_balloon: - **Le code peut être ammené à changer avec le temps ! (Correction de bugs, ajouts visuels etc). Pensez à consulter régulièrement le github pour voir si une nouvelle version a été mise en ligne.** <br />
*Note: Les anciennes versions d'un projet restent archivées. Si une version plus récente implémente des fonctionnalités qui ne vous plaisent pas, vous êtes libre d'utiliser une version antérieur.*

:eyes: - **Aperçus :** <br /><br />
Original            |  Variation
:-------------------------:|:-------------------------:
![original](https://user-images.githubusercontent.com/72102780/176884100-65420fb5-4b07-4b91-a594-6b0766a1527d.gif)  |  ![variation](https://user-images.githubusercontent.com/72102780/176884205-30bce592-1d39-422c-8890-04e4cfb07d60.gif)


-----------------------------------

:memo: Dans chaque fichier css, vous trouverez différentes options personnalisables présentées sous cette forme :
```css

:root{
    --colorSpeak: #8bbf5e;
    --colorBase: #000000;
    --shake: infinite;
    --shakeSpeed: 3s;
    --shakeDelay: 0.5s;
    --borderWidth: 4px;
    --pseudoBgColor: rgba(0,0,0,0.7);
    --pseudoColor: rgba(255,255,255,1);
    --pseudoSize: 100%;
    --spaceBetween: 50px;
}

```
*Pour trouver le code couleur que vous souhaitez, rendez vous sur [rgbacolorpicker]*

**colorSpeak :** *\<Couleur>*
> Définit la couleur de la bordure lorsqu'un utilisateur parle.

**colorBase :** *\<Couleur>*
> Définit la couleur de la bordure par défaut.

**shake :** *\<infinite | 0>*
> Définit si l'effet de tremblement est active ou désactivé. <br />
> • infinite → Effet activé <br />
> • 0 → Effet désactivé

**shakeSpeed :** *\<Durée en seconde>*
> Définit la rapidité de l'effet de tremblement. <br />
> • 1s à 2s → Effet rapide <br />
> • 3s à 4s → Effet moyen <br />
> • 5s et + → Effet lent

**shakeDelay :** *\<Durée en seconde>*
> Définit le délai avant l'activation de l'effet de tremblement lorsqu'un utilisateur commence à parler. <br />
> Exemples : <br />
> • 0s → Aucun délai d'activation <br />
> • 0.5s → L'utilisateur doit parler pendant au moins 500 millisecondes avant l'activation de l'effet.

**borderWidth :** *\<Taille en pixel>*
> Définit la largeur de la bordure (exemple: 2px, 6px, 8px).

**pseudoBgColor :** *\<Couleur>*
> Définit la couleur de fond du pseudo

**pseudoColor :** *\<Couleur>*
> Définit la couleur du pseudo

**pseudoSize :** *\<Taille en %>*
> Définit la taille du pseudo

**spaceBetween :** *\<Taille en px>*
> Définit l'espace séparant chaque utilisateur

[rgbacolorpicker]: https://rgbacolorpicker.com/
