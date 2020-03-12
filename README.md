# Generateur-de-couleur
 
Bonjour à tous ! :)
Dans ce TUTO, nous allons manipuler le DOM et créer un générateur de couleurs aléatoires RGB.

- RGB signifie "Red, Blue, Green". Ce sont les trois couleurs qui composent un pixel de l'écran que vous êtes en train de regarder !
- Avec ces trois couleurs primaires mélangées selon différentes intensités (de 0 à 255 pour chacune), un pixel peut générer plus de 16 millions de couleurs. Oui, 16 MILLIONS ! 
- Le code rgb indique l'intensité de chacune de ces trois couleurs pour un pixel. Voici quelques exemples : 

rgb(0, 0, 0) : tous les pixels sont éteints -> couleur noire.
rgb(255, 255, 255) : tous les pixels sont allumés -> couleur blanche.
rgb(255, 0, 0) : Maximum d'intensité pour le rouge et rien pour le reste -> couleur rouge.
rgb(0, 255, 0) : Maximum d'intensité pour le vert et rien pour le reste -> couleur verte.
rgb(0, 0, 255) : Maximum d'intensité pour le bleu et rien pour le reste -> couleur bleue.
rgb(44, 44, 44) : Chaque couleur possède une légère intensité -> couleur d'une certaine tonalité grise.

Etc ...

- Grâce à Javascript, on manipule le DOM pour changer dynamiquement la couleur à l'écran dès que l'on appuie sur une touche.
- On utilise un addEventListener pour lancer une action dès l'appui sur la touche Espace.
- On utilise des fonctions mathématiques de l'objet Math de Javascript pour générer des nombres aléatoires que l'on inclus dans un code rgb.
- On modifie les éléments HTML dynamiquement en modifiant leur style avec Javascript.
