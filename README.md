# TPFenetre-MereFille

Présentation du projet: le but est de gérer deux fenêtre dans une même application et de découvrire la gestion de deux fenêtre qui communiquent entre elles au moyen de méthodes,d'accesseurs et d'évènements.

Les outils mes en oeuvre :

* git.
* Visual studio.

le développement  tourne autour de 2 grandes étapes

1.La fenêtre principale(mère) qui est crée par défaut.
2.création de la fenêtre fille.

|**développement**|**langages**|**technique de programmation**|
|-----------------|------------|------------------------------|
|fenêtre principal|c#|Windows Form|
|fenêtre fille|c#|Windows Form|



## Fenêtre princiaple (Mère) ##

fenêtre permettant la gestion de la fenêtre fille.
Elle possèdera les composants graphiques suivants:
- Bouton
1. -Bouton New() : Création d'une nouvelle fenêtre.
2. -Bouton Close() : Ferme la fenêtre.
3. -Bouton show() : Affichage de la fenêtre.
4. -Bouton Hide() : Cacher la fenêtre.
- ListBox :  Recupère le nom des fenêtres crée.



![CaptureMere.png](http://image.noelshack.com/fichiers/2018/47/7/1543155640-capturemere.png)

## Fenêtre secondaire (Fille) ##

Elle possèdera les composants graphiques suivants:
- Label : je change de nom.
- TextBox : Entrer le nom de la fenêtre.
- Bouton
1. -Bouton Changer() : Changer le nom de la fenêtre.
2. -Bouton MaMere() : Affiche la mère de la fenêtre.



![CaptureFille.png](http://image.noelshack.com/fichiers/2018/47/7/1543155954-capturefille.png)

## Rendu Final ##
![Final.png](http://image.noelshack.com/fichiers/2018/47/7/1543155963-capturefinal.png)
