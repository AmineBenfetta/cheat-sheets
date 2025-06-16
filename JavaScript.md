## 🧠 Les Bases de JavaScript

###  Déclaration de variables

```js
let x = 10;     // variable modifiable
const y = 20;   // constante (non modifiable)
var z = 30;     // ancienne méthode (peu recommandée)
```

###  Types de données

```js
let nom = "Alice";      // Chaîne de caractères
let age = 25;           // Nombre
let actif = true;       // Booléen
let vide = null;        // Null
let pasDefini;          // Undefined
let symbole = Symbol(); // Symbole
```

###  Opérateurs utiles

```js
// Arithmétiques : + - * / % **
// Comparaison : == === != !== < > <= >=
// Logiques : && || !
// Affectation : = += -= *= /=
// Ternaire : condition ? valeurSiVrai : valeurSiFaux
```

###  Conditions

```js
if (age > 18) {
  console.log("Majeur");
} else {
  console.log("Mineur");
}
```

###  Boucles

```js
for (let i = 0; i < 5; i++) {
  console.log(i);
}

while (condition) {
  // ...
}
```

---

## 🎯 Fonctions

###  Fonctions simples

```js
function direBonjour(nom) {
  return "Bonjour " + nom;
}
```

###  Fonctions fléchées

```js
const direBonjour = (nom) => "Bonjour " + nom;
```

###  Paramètres par défaut

```js
function saluer(nom = "inconnu") {
  console.log("Salut " + nom);
}
```

---

## 📆 Tableaux et Objets

###  Tableaux

```js
let fruits = ["pomme", "banane"];
console.log(fruits[0]);
fruits.push("orange");
```

###  Objets

```js
let personne = {
  nom: "Bob",
  age: 40,
  parler() {
    console.log("Salut je suis " + this.nom);
  }
};
personne.parler();
```

---

## 🔄 Manipulation du DOM

###  Accès aux éléments

```js
document.querySelector("h1")
document.getElementById("monId")
```

###  Modifier le contenu

```js
el.textContent = "Nouveau texte";
el.classList.add("visible");
```

###  Écouter un événement

```js
el.addEventListener("click", () => {
  console.log("Clic !");
});
```

---

## 🚀 Asynchrone (async / await)

###  Exemple simple

```js
async function charger() {
  let reponse = await fetch("/data.json");
  let data = await reponse.json();
  console.log(data);
}
```

---

## 🔧 Outils pratiques

```js
console.log("info");
console.error("erreur");
JSON.stringify(objet) // convertir en texte JSON
JSON.parse(jsonTexte) // convertir en objet
```
