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

