# Introduction

L'objectif du document est la création d'une *cheat sheet* ou "feuille de triche". 

L'ensemble des fonctions que vous devez documenter se trouvent dans ce document, à vous de  remplir les espaces vides 😉

Ce document pourra vous suivre tout au long de vos études, n'hésitez à le compléter au fur et à mesure.

---

Pour compléter le document, vous utiliserez la fonction **fork** de GitHub pour copier ce projet dans votre espace personnel.

[Si besoin, rendez-vous dans ce dépôt pour revoir les bases de Javascript](https://github.com/Maxence-Machu/javascript-basic-memo)

---

## La fonction GetElementByID()

### Que fait la fonction ?
La méthode getElementById() renvoie un objet qui représente l'élément dont la propriété  id correspond à la chaîne de caractères spécifiée.
Étant donné que les ID d'élément doivent être uniques, s'ils sont spécifiés, ils constituent un moyen utile d'accéder rapidement à un élément spécifique.

### Pourquoi l'utiliser ?
La fonction getElementById doit être utilisée si l'on veut utiliser un élément du DOM en HTML grâce à Javascript 

#### Note supplémentaire
La fonction getElementByID est à ne pas confondre avec la fonction *getElementsByClassName*. 
Les ID dans une page web sont uniques, on ne peut donc pas récupérer plusieurs éléments avec cette fonction. 

### Exemple de code:
```javascript
let element = document.getElementByID('mon-element');
console.log(element);
```

## La fonction GetElementsByClassName()

### Que fait la fonction ?

La fonction GetElementsByClassName() fait référence à tous les éléments dans le document étant associé au nom de la classe spécifiée


### Pourquoi l'utiliser ?

La fonction getElementByClassName() doit être utilisée si l’on veut utiliser plusieurs éléments ayant une même classes du DOM en HTML grâce à Javascript

### Exemple de code:
```javascript
let elements = document.getElementsByClassName('mon-elemnt');
console.log(element);
```

## La fonction querySelector() et querySelectorAll()

### Que fait la fonction ?
querySelector () renvoie le premier élément qui correspond à un ou plusieurs _sélecteurs CSS_ spécifiés dans le document.

### Pourquoi l'utiliser ?
On peut utiliser querySelector () pour cibler un élément précis

#### Note supplémentaire
La méthode querySelector () renvoie uniquement le premier élément qui correspond aux sélecteurs spécifiés. Pour renvoyer toutes les correspondances, utilisez plutôt la méthode [querySelectorAll ()]

### Exemple de code:
```javascript
element = document.querySelector(sélecteurs);
```


## La fonction addEventListener()

### Que fait la fonction ?

La fonction addEventListener () permet de lier un gestionnaire d'événements à l'élément spécifié.

### Pourquoi l'utiliser ?
On peut l'utiliser pour créer une animation lorsqu'on effectue une action (ex : cliquer pour activer notre fonction)

### Exemple de code:
```javascript
document.getElementById("monid").addEventListener("click", myFunction);  
  
function myFunction() {  
document.getElementById("demo").innerHTML = "Hello World";  
}
```

## La fonction stopPropagation()

### Que fait la fonction ?
stopPorpagation() évite qu'un évènement se propage à un autre endroit que celui prévu initialement.


### Pourquoi l'utiliser ?
On peut l'utiliser pour fixer une largeur et un hauteur sur une image 

### Exemple de code:
```javascript
_event_.stopPropagation();
```

## La fonction addEventListener('mousemove', maFonction)

### Que fait la fonction ?
La fonction addEventListener('mousemove', maFonction) permet d'associer la fonction "maFonction" au mouvement de la souris.

### Pourquoi l'utiliser ?
Pour créer un pointage suis la image ou un autre élément 

### Exemple de code:
```javascript
maPhoto.addEventListener('mousemove', maFonction)
```

## La fonction parseInt()

### Que fait la fonction ?
...

### Pourquoi l'utiliser ?
...

### Exemple de code:
```javascript
// CODE
```
