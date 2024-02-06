# TP-python-POO
# Python-POO
Programmation orienter objet basics

# Création d'une classe Player

On va créer une classe
```python

```

On crée ensuite des attributs. Il faut se poser la question : qu'est-ce qu'un attribut ?

De quoi a besoin un joueur ?
- Pseudo
- Santé
- Attaque

```python

```

Ensuite, une fois créée, on peut les utiliser.

On instancie le joueur (on crée le joueur de notre choix).
Création d'une instance player1
```python

```
On crée un deuxième joueur. 
```python

```

Mais il aura le même prénom, ce qui n'est pas intéressant. Ce qui nous intéresse est de créer quelque chose de générique.

Donc, plus besoin de les mettre en dur. On va déplacer les valeurs écrites en dur directement lors de la création du joueur.

```python

```

C'est ici une notion très importante que l'on retrouve dans tous les langages : le constructeur.
```python

```
PETITE EXPLICATION CONSTRUCTEUR: La méthode __init__ sert à attribuer à chaque objet de la classe une valeur d'attribut qui lui est propre.

Maintenant, on veut créer une fonction qui nous retourne notre vie, santé, etc.

On a besoin d'informations ou de valeurs.

On va créer différentes méthodes.
```python

```
DRY EXPLICATION
```python

```

Cette fonction va vous permettre de subir une attaque et afficher votre santé qui est propre à chaque joueur.

Maintenant, on veut infliger une attaque.
```python

```
On crée une fonction qui va prendre en paramètre un joueur à attaquer. Ensuite, on indique le joueur que l'on veut attaquer et on y ajoute la fonction damage créée juste avant.

Sauf qu'on ne veut pas mettre un chiffre au hasard, on veut mettre notre attaque. Alors on appelle l'attaque des joueurs qui est self.attack.

Pour la faire fonctionner, c'est simple. Si je dis joueur 1 attaque joueur 2 :
```python

```
Maintenant, on va afficher les informations du joueur 1 et joueur 2.

```python

```
On voit bien que la santé du joueur 2 a diminué.

------------------------------------------------
# Exercices

On veut donner des armes à notre joueur.

Créez une classe Weapon qui prend en attributs un nom et des dégâts.

Ensuite, créez deux méthodes qui retournent le nom et les dégâts de cette arme.

Attribuez cette arme à un joueur.

Instanciez l'arme à un joueur.

Puis modifiez la fonction attack_player qui devra ajouter les dégâts de l'arme en plus des dégâts du joueur.
