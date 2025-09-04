---
title: 💡 Aide-mémoire
description: Résumé de toutes les notions abordées dans ce cours
---

# 💡 Aide-mémoire

### Opérateurs arithmétiques

<table>
    <tr>
        <th>Opérateur</th>
        <th>Exemple</th>
        <th>Résultat</th>
    </tr>
    <tr>
        <td><center>`+`</center></td>
        <td>`5 + 5`</td>
        <td>`10`</td>
    </tr>
    <tr>
        <td><center>`-`</center></td>
        <td>`20 - 7.5`</td>
        <td>`12.5`</td>
    </tr>
    <tr>
        <td><center>`*`</center></td>
        <td>`-2 * 1.5`</td>
        <td>`-3`</td>
    </tr>
    <tr>
        <td><center>`/`</center></td>
        <td>`5 / 2`</td>
        <td>`2.5`</td>
    </tr>
</table>

### Déclaration de variables

```js
let animal;
let nom = "Jean-Jérémie";
let prixTotal = 1.99 * 3;
```

### Opérateurs d'affectation

<table>
    <tr>
        <th>Opérateur</th>
        <th>Exemple</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><center>`=`</center></td>
        <td>`maVariable = 25;`</td>
        <td>La valeur de `maVariable` est **remplacée** par 25</td>
    </tr>
    <tr>
        <td><center>`+=`</center></td>
        <td>`maVariable += 3`</td>
        <td>La valeur de `maVariable` est **augmentée** de 3</td>
    </tr>
    <tr>
        <td><center>`-=`</center></td>
        <td>`maVariable -= 2`</td>
        <td>La valeur de `maVariable` est **réduite** de 2</td>
    </tr>
</table>

### Littéraux de gabarit (template strings)

```js
let nom = "Judith";
let objet = "chaises";
let phrase1 = `Je suis ${nom} et j'aime les ${objet}`;
// phrase1 contient "Je suis Judith et j'aime les chaises"

let article = "rhododendron";
let qte = 3;
let prix = 3.99;
let phrase2 = `${qte} ${article} coûtent ${qte * prix} dollars.`;
// phrase2 contient "3 rhododendron coûtent 11.97 dollars."
```

### Fonctions

```js showLineNumbers
function nomDeLaFonction(){

    // Code de la fonction

}
```

### Fonctions préexistantes

```js
// Crée une alerte (un pop-up) dans la page
alert("Skbidi");

// Affiche un message dans la console du navigateur
console.log("Natacha n'attache pas ses chats");
```

### DOM

Accéder au contenu textuel d’un élément (et le ranger dans une variable, par exemple)
```js
let texte = document.querySelector(".classe").textContent;
```

Modifier le contenu textuel d’un élément (Avec `=` on remplace, avec `+=` on ajoute)
```js
document.querySelector(".classe").textContent = "Nouveau texte";
```
