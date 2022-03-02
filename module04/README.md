# ANI2012H22

## Module 4 : Dessin

### Exemple 4.1 (DrawPoint)

Un programme peut dessiner des points dans l'espace de la fenêtre d'affichage avec une primitive vectorielle qui a pour attributs une position sur l'axe X et Y. Le diamètre du point sera en fonction de la taille du trait.

Dans cet exemple, le programme dessine une séquence de points de taille croissante.

### Exemple 4.2 (DrawLine)

Un programme peut dessiner des lignes dans l'espace de la fenêtre d'affichage avec une primitive vectorielle qui a pour attributs les positions sur l'axe X et Y de deux sommets. La largeur de la ligne sera en fonction de la taille du trait.

Dans cet exemple, le programme dessine une séquence de lignes de taille croissante.

### Exemple 4.3 (DrawRect)

Un programme peut dessiner des rectangles dans l'espace de la fenêtre d'affichage avec des primitives vectorielles qui ont pour attributs les positions sur l'axe X et Y de quatre sommets.

Le rectangle peut donc être représenté sous forme d'une position au coin supérieur gauche ou au centre de la primitive, ainsi que d'une largeur et d'une hauteur qui permet de calculer la position de ses quatre sommets.

Dans cet exemple, le programme dessine une séquence de rectangles de taille décroissante.

### Exemple 4.4 (DrawQuad)

Un programme peut dessiner des quadrilatères dans l'espace de la fenêtre d'affichage avec des primitives vectorielles qui ont pour attributs les positions sur l'axe X et Y de quatre sommets.

Un quadrilatère peut utiliser n'importe quelle position de l'espace de la fenêtre d'affichage pour ses quatre sommets alors qu'un rectangle est un quadrilatère dont les arêtes opposées sont alignées parallèlement sur les axes de l'espace de la fenêtre d'affichage.

Dans cet exemple, le programme dessine une séquence de quadrilatères dont les quatre sommets ont des positions aléatoires.

### Exemple 4.5 (DrawEllipse)

Un programme peut dessiner une ellipse dans l'espace de la fenêtre d'affichage avec une primitive vectorielle qui a pour attributs les positions sur l'axe X et Y du centre de la primitive, d'une largeur et d'une hauteur.

Dans cet exemple, le programme dessine une séquence d'ellipses de taille décroissante.

### Exemple 4.6 (DrawArc)

Un arc d'ellipse peut aussi être dessiné en tenant compte d'un angle de début et de fin de l'arc.

Dans cet exemple, le programme dessine une séquence d'arcs d'ellipse avec un angle croissant.

### Exemple 4.7 (DrawTriangleRandom)

Un programme peut dessiner des triangles dans l'espace de la fenêtre d'affichage avec une primitive vectorielle qui a pour attributs les positions sur l'axe X et Y de trois sommets.

Dans cet exemple, le programme dessine une séquence de triangles dont les trois sommets ont des positions aléatoires.

### Exemple 4.8 (DrawTriangleAtPosition)

Dans cet exemple, le programme dessine un triangle équilatérale à une position précise.

Le premier triangle est au centre de la fenêtre d'affichage.

D'autres triangles peuvent être dessinés à la position d'un clic de souris.

### Exemple 4.9 (DrawPolygon)

Un programme peut dessiner un polygone dans l'espace de la fenêtre d'affichage avec une primitive vectorielle ayant pour attributs les positions sur l'axe X et Y de chacun des ses sommets.

Dans cet exemple, le programme dessine une séquence de polygones réguliers avec un nombre de côtés croissant.

### Exemple 4.10 (DrawStar)

Dans cet exemple, le programme dessine des polygones en forme d'étoile.

### Exemple 4.11 (DrawCurve)

Un programme peut dessiner une courbe de Bézier dans l'espace de la fenêtre d'affichage avec une primitive vectorielle qui a pour attributs les positions sur l'axe X et Y de trois points de contrôle pour une courbe de Bézier quadratique ou de quatre points de contrôle pour une courbe de Bézier cubique.

Dans cet exemple, le programme dessine une courbe de Bézier cubique avec ses quatre points de contrôle et différents repères visuels.

### Exemple 4.12 (ShapesAnimation)

Dans cet exemple, une animation générative est créée à partir de structures logiques, des structures itératives et des primitives vectorielles. 

À un intervalle régulier, des instances de primitives vectorielles sont dessinées avec des attributs aléatoires.

L'effet d'estompement progressif présenté dans l'exemple 3.4 est utilisé pour faire disparaitre les formes après un certain temps.

Les touches de 1 à 9 du clavier permettent d'activer ou de désactiver chaque type de primitives vectorielles et la touche 0 permet de toutes les désactiver.

### Exemple 4.13

#### Exemple 4.13.1 (UserInterface1)

Dans cet exemple, nous présentons différents types de contrôles d'interface utilisateur : 1 bouton standard, 3 cases à chocher, 3 boutons radio et 1 slider animé par oscillation.

#### Exemple 4.13.1 (UserInterface2)

Exemple d'une interface utilisateur avec 3 sections.
Chaque section à sa propre fonction d'affichage.
