---
title: 💡 Aide-mémoire
description: Résumé de toutes les notions abordées dans ce cours
---

# 💡 Aide-mémoire

### 🧮 Opérateurs arithmétiques

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

### 📝 Déclaration de variables

```js
let animal;
let nom = "Jean-Jérémie";
let prixTotal = 1.99 * 3;
```

### 📈📉 Opérateurs d'affectation

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

### ✒️ Littéraux de gabarit (template strings)

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

### ⚙️ Fonctions

```js showLineNumbers
function nomDeLaFonction(){

    // Code de la fonction

}
```

### ⚙️🎨 Fonctions avec paramètres

```js showLineNumbers
function couleurFond(classe, couleur){

    document.querySelector(classe).style.backgroundColor = couleur;

}

// Ex : cet appel rend le fond de l'élément .texte rouge
couleurFond(".texte", "red");
```

### ⚙️📫 Fonctions avec retour

```js showLineNumbers
function valeursEgales(nombre1, nombre2){

    if(nombre1 == nombre2){
        return true;
    }
    else{
        return false;
    }

}

// Ex : la variable x contiendra false
let x = valeursEgales(2, 4);
```

### ⚙️✅ Fonctions préexistantes

```js
// Crée une alerte (un pop-up) dans la page
alert("Skbidi");

// Affiche un message dans la console du navigateur
console.log("Natacha n'attache pas ses chats");
```

### ⚖️ Opérateurs de comparaison

<table>
    <tr>
        <th>Opérateur</th>
        <th>Exemple</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><center>`==`</center></td>
        <td>`5 == 7`</td>
        <td>`5` est-il **égal** (identique) à `7` ?</td>
    </tr>
    <tr>
        <td><center>`!=`</center></td>
        <td>`2 != 3`</td>
        <td>`2` est-il **différent** (pas égal) à `3` ?</td>
    </tr>
    <tr>
        <td><center>`<`</center></td>
        <td>`3 < 2`</td>
        <td>`3` est-il **plus petit** que `2` ?</td>
    </tr>
    <tr>
        <td><center>`>`</center></td>
        <td>`4 > 2`</td>
        <td>`4` est-il **plus grand** que `2` ?</td>
    </tr>
    <tr>
        <td><center>`<=`</center></td>
        <td>`5 <= 5`</td>
        <td>`5` est-il **plus petit ou égal** à `5` ?</td>
    </tr>
    <tr>
        <td><center>`>=`</center></td>
        <td>`9 >= 3`</td>
        <td>`9` est-il **plus grand ou égal** à `3` ?</td>
    </tr>
</table>

### ⚖️⚖️ Opérateurs logiques

<table>
    <tr>
        <th>Opérateur</th>
        <th>Exemple</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><center>`&&`</center></td>
        <td>`a > 3 && b > 4`</td>
        <td>`a` est plus grand que `3` ET `b` est plus grand que `4` ?</td>
    </tr>
    <tr>
        <td><center>`||`</center></td>
        <td>`a != b || a < 10`</td>
        <td>`a` est différent de `b` OU `a` est plus petit que `10` ?</td>
    </tr>
</table>

### ❓ Conditions

```js showLineNumbers
if( ... condition ... ){

    // Code à exécuter si la condition est true

}
```

```js showLineNumbers
if( ... condition ... ){

    // Code à exécuter si la condition est true

}
else{

    // Code à exécuter si la condition est false

}
```

```js showLineNumbers
if( ... condition 1 ... ){

    // Code à exécuter si la condition 1 est true

}
else if( ... condition 2 ...){

    // Code à exécuter si la condition 1 est false, mais la condition 2 est true

}
else{

    // Code à exécuter si toutes les conditions sont false

}
```

### ➰ Boucles

```js showLineNumbers
while( ... condition ... ){

    // Coder à exécuter plusieurs fois

}
```

```js showLineNumbers
do{

    // Coder à exécuter plusieurs fois

}while( ... condition ... );
```

### 💻 DOM

🔍 Accéder au contenu textuel d’un élément (et le ranger dans une variable, par exemple)
```js
let texte = document.querySelector(".classe").textContent;
```

📝 Modifier le contenu textuel d’un élément (Avec `=` on remplace, avec `+=` on ajoute)
```js
document.querySelector(".classe").textContent = "Nouveau texte";
```

👂 Ajouter un écouteur d'événements pour un élément spécifique (Généralement dans `init()`) Les types d'événements utilisés dans ce cours sont `"click"`, `"mouseover"` et `"mouseout"`.
```js
document.querySelector(".classe").addEventListener("type", nomFonction);
```

💄 Manipuler les classes
```js
document.querySelector(".classe").classList.add("maClasse"); // Ajouter
document.querySelector(".classe").classList.remove("maClasse"); // Retirer
document.querySelector(".classe").classList.toggle("maClasse"); // Basculer

// Vérifier si un élément possède une classe (x contiendra true ou false)
let x = document.querySelector(".classe").classList.contains("maClasse");
```

🧪 Manipuler les attributs
```js
document.querySelector(".classe").nomAttribut = "valeur"; // Ajouter ou modifier
document.querySelector(".classe").nomAttribut = ""; // Retirer

// Obtenir la valeur d'un attribut
let x = document.querySelector(".classe").nomAttribut;
```

🎨 Modifier le style d’un élément
```js
document.querySelector(".classe").style.propriété = "valeur";
```

<table>
<tr>
    <td>Propriété</td>
    <td>`color`, `backgroundColor`,<br/> `borderColor`</td>
    <td>`borderWidth`, `height`,<br/>`width`, `left`, `right`</td>
    <td><center>`display`</center></td>
    <td>`opacity`</td>
</tr>
<tr>
    <td>Exemple(s) de valeur</td>
    <td><center>`"red"`, `"#696969"`</center></td>
    <td><center>`"15px"`</center></td>
    <td><center>`"none"`, `"block"`</center></td>
    <td>`0.5`, `1`</td>

</tr>
</table>

### 🦑 currentTarget

```js showLineNumbers
function init(){

    document.querySelector(".bouton1").addEventListener("click", changerCouleur);

}

function changerCouleur(event){

    event.currentTarget.style.color = "red"; // Affectera l'élément .bouton1

}
```

