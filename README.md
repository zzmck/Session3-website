### Projet 3 - OpenClassRoom

## Dynamisez une page web avec des animations CSS.


## Vue des objectifs mobile first

### Version Mobile :

La cible étant les personnes connectées et pressées, le site sera développé en utilisant
l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées.
  - [x] L’ensemble du site devra être responsive sur mobile, tablette et desktop.
  - [x] Les pages devront passer la validation W3C en HTML et CSS sans erreur.
  - [x] Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox

### Version Bureau / Tablette :

Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires,
leur mise en page est libre.

### Spécificités

**Page d’accueil (x1)**

  - [x] Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
  - [x] Une courte présentation de l’entreprise.
  - [x] Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

**Pages de menu (x4)**

  - [x] 4 pages contenant chacune le menu d’un restaurant.

**Footer**

  - [x] Le footer est identique sur toutes les pages.
  - [x] Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

**Header**

  - [x] Le header est présent sur toutes les pages.
  - [x] Sur la page d’accueil, il contient le logo du site.
  - [x] Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil


### Animations CSS

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.

**Boutons**

  - [x] Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
  - [x] À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

**Page d’accueil**

  - [x] Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.
 
**Pages de menu**

  - [x] À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
  - [x] Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.


### Test sur Github en ligne :
https://zzmck.github.io/Session3-website/Accueil.html

### Rendu mobile :

**Page d’accueil**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/mjnj.jpg" target="blank"><img src="https://zupimages.net/up/22/45/mjnj.jpg" align="center" width="20%" alt="accueil"  /></a>
</p>

**Page des menus**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/wi79.jpg" target="blank"><img src="https://zupimages.net/up/22/45/wi79.jpg" align="center" width="20%" alt="menu"  /></a>
</p>

### Rendu desktop :


**Page d’accueil**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/449a.jpg" target="blank"><img src="https://zupimages.net/up/22/45/449a.jpg" align="center" width="50%" alt="accueil"  /></a>
</p>

**Page des menus**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/p9ft.jpg" target="blank"><img src="https://zupimages.net/up/22/45/p9ft.jpg" align="center" width="50%" alt="menu"  /></a>
</p>

### W3C Validator CSS :

**style.css (généré par prépocesseur SASS)**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/3yos.jpg" target="blank"><img src="https://zupimages.net/up/22/45/3yos.jpg" align="center" width="50%" alt="validator w3C css"  /></a>
</p>

### W3C Validator HTML :

**Accueil.html**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/yawb.jpg" target="blank"><img src="https://zupimages.net/up/22/45/yawb.jpg" align="center" width="50%" alt="validator w3C accueil"  /></a>
</p>

**menu_la_palette_du_gout.html**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/e0yn.jpg" target="blank"><img src="https://zupimages.net/up/22/45/e0yn.jpg" align="center" width="50%" alt="validator w3C menu1"  /></a>
</p>

**menu_la_note_enchantee.html**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/y499.jpg" target="blank"><img src="https://zupimages.net/up/22/45/y499.jpg" align="center" width="50%" alt="validator w3C menu2"  /></a>
</p>

**menu_a_la_francaise.html**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/zp7z.jpg" target="blank"><img src="https://zupimages.net/up/22/45/zp7z.jpg" align="center" width="50%" alt="validator w3C menu3"  /></a>
</p>

**menu_le_delice_des_sens.html**

<p align="center">
<a href="https://zupimages.net/viewer.php?id=22/45/lgtr.jpg" target="blank"><img src="https://zupimages.net/up/22/45/lgtr.jpg" align="center" width="50%" alt="validator w3C menu4"  /></a>
</p>


#### **Merci de suivre mon projet**

**Mickael**
