
[Lien README.md](https://github.com/juju2307/exercice-markdown/blob/1996b0b89f52d5cfae1e0929f363b274181d64fe/README.md)

# Exercice MarkDown

## Objectif du MarkDown

"Le Markdown est une syntaxe légère et facile à utiliser pour styliser toutes les formes d'écriture sur la plate-forme GitHub."

## Description MarkDown

"Le language de balisage Markdown est un moyen de styliser du texte sur le Web. 
Vous contrôlez l'affichage du document; styliser des mots en
gras ou italique, ajouter des images et créer des listes ne sont que quelques-unes des choses que nous pouvons faire avec le Markdown. 
La plupart du temps,
Markdown est juste un texte normal avec quelques caractères non alphabétiques ajoutés, comme # ou *."

> Liste non-ordonnée

* Item 1
* Item 2
* Item 3

> Liste ordonnée

1. Item 1
2. Item 2
3. Item 3

> Liste dans une liste

1. Item
    1. Item 1.1 
    1. Item 1.2
    1. Item 1.3
1. Item
    1. Item 2.1
    2. Item 2.2
    3. Item 2.3
* Item x
    * Item xx
    * Item xy
    * Item xz

> Titres et sous-titres

## Hello World
### La vie est belle
#### Le ciel est bleu

> Quelques liens

[Open Classroom](https://openclassrooms.com/fr/)

[Codecademy](https://www.codecademy.com/)

[Grafikart](https://grafikart.fr/)

> Images statique

![Image markdown](https://miro.medium.com/max/3000/1*HB9Cy4zmmggm5QUKAOO71g.png)

> Image animée

![Image animated](https://user-images.githubusercontent.com/57039079/67622173-2b835e80-f807-11e9-821d-bfbb688bc329.gif)

> Code (HTML)

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice Markdown</title>
</head>
<body>
    <a href="https://github.com/juju2307/exercice-markdown/blob/1996b0b89f52d5cfae1e0929f363b274181d64fe/README.md">https://github.com/juju2307/exercice-markdown/blob/1996b0b89f52d5cfae1e0929f363b274181d64fe/README.md</a>
    <img src="https://miro.medium.com/max/3000/1*HB9Cy4zmmggm5QUKAOO71g.png" alt="Image markdown">

    <button onclick="clickMe()">Click Me :)</button>

    <ul>
        <li>Test 1</li>
        <li>Test 2</li>
        <li>Test 3</li>
    </ul>

    <ol>
        <li>Test 1</li>
        <li>Test 2</li>
        <li>Test 3</li>
    </ol>

    <ol>
        <li>Test 1</li>
        <li>Test 2</li>
        <ol>
            <li>Test 1</li>
            <li>Test 2</li>
            <li>Test 3</li>
        </ol>
    </ol>

    <h1>H1</h1>
    <h2>H2</h2>
    <h3>H3</h3>
    <h4>H4</h4>
    <h5>H5</h5>
    <h6>H6</h6>

    <a href="https://google.com">Google</a>
    <a href="http://becode.org/">Becode</a>

    <img src="https://user-images.githubusercontent.com/57039079/67622173-2b835e80-f807-11e9-821d-bfbb688bc329.gif" alt="Image markdown">

    <script>
        function clickMe() {
            alert("Bonjour ! :)")
        }
    </script>
</body>
</html>
html```
