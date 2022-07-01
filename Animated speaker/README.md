# Animated speaker
:scroll: - Affiche une icone de haut parleur animée, surligne les contours et joue un effet de tremblement lorsque qu'un utilisateur parle.

:speech_balloon: - **Le code peut être ammené à changer avec le temps ! (Correction de bugs, ajouts visuels etc). Pensez à consulter régulièrement le github pour voir si une nouvelle version a été mise en ligne.** <br />
*Note: Les anciennes versions d'un projet restent archivées. Si une version plus récente implémente des fonctionnalités qui ne vous plaisent pas, vous êtes libre d'utiliser une version antérieur.*

:eyes: - **Aperçus** <br /><br />
![ezgif-2-54f4a57b3e](https://user-images.githubusercontent.com/72102780/176675257-91cbb6d7-dc2b-4cc2-83d7-278062324d61.gif)

:memo: Dans chaque fichier css, vous trouverez différentes options personnalisables présentées sous cette forme :
```css

:root{
    --colorSpeak: #8bbf5e;
    --colorBase: #000000;
    --shake: infinite;
    --shakeSpeed: 3s;
    --shakeDelay: 0.5s;
    --pseudoBgColor: rgba(0,0,0,0.7);
    --borderWidth: 4px;
}

```

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

**pseudoBgColor :** *\<Couleur>*
> Définit la couleur de fond du pseudo

**pseudoColor :** *\<Couleur>*
> Définit la couleur du pseudo

**borderWidth :** *\<Taille en pixel>*
> Définit la largeur de la bordure (exemple: 2px, 6px, 8px).
