# Jour 1 : Bases de Programmation - Variables et Types de Données

## Description rapide
L’objectif du jour est de comprendre les variables et les types de données en JavaScript. Une variable est un conteneur pour stocker des données,
déclaré avec let (modifiable), const (constante) ou var (ancienne syntaxe). Les types de données principaux sont : 
string (texte), number (nombre), boolean (vrai/faux), array (tableau), et object (objet).

---

## Documentation

### 1. **Objectif du jour : Comprendre les variables et les types de données en JavaScript**

### **Variables**
Une **variable** est un **conteneur** qui permet de **stocker des données**.

#### `let`
- Utilisé pour déclarer une variable **modifiable**.

```javascript
let fruit = "pomme";
console.log(fruit); // Affiche "pomme"
fruit = "orange";
console.log(fruit);  // Affiche "orange"
```

#### `const`
- Utilisé pour déclarer une variable **constante**.

```javascript
const pays = "Maroc";
console.log(pays); // Affiche "Maroc"
// pays = "France";  <-- Cela provoquerait une erreur.
```

#### `var`
- Ancienne façon de déclarer des variables. Préférez utiliser `let` et `const`.

---

### **Les types de données en JavaScript**

1. **String (chaîne de caractères)**
   - Texte entouré de guillemets (simples `' '` ou doubles `" "`).

```javascript
let nom = "Keltoum";
console.log(nom); // Affiche "Keltoum"
```

2. **Number (nombre)**
   - Peut être un nombre entier ou décimal.

```javascript
let age = 18;
console.log(age); // Affiche 18
```

3. **Boolean (booléen)**
   - Peut contenir deux valeurs : `true` (vrai) ou `false` (faux).

```javascript
let estEtudiant = true;
console.log(estEtudiant); // Affiche true
```

4. **Array (tableau)**
   - Liste de plusieurs valeurs (strings, numbers, etc.).

```javascript
let fruits = ["pomme", "orange", "banane"];
console.log(fruits); // Affiche ["pomme", "orange", "banane"]
```

5. **Object (objet)**
   - Structure complexe regroupant plusieurs propriétés.

```javascript
let personne = {
  nom: "Keltoum",
  age: 18,
  ville: "Casablanca"
};
console.log(personne.nom);   // Affiche "Keltoum"
console.log(personne.age);   // Affiche 18
console.log(personne.ville); // Affiche "Casablanca"
```

---

## Exercices

### **Faciles**
1. Déclarez une variable `nom` avec votre nom et affichez-la dans la console avec `console.log(nom)`.
2. Créez une constante `age` avec votre âge et affichez-la.
3. Déclarez une variable `estEtudiant` avec `true` si vous êtes étudiant, sinon `false`, et affichez-la.

### **Moyens**
1. Créez deux variables numériques `a` et `b`, additionnez-les et affichez le résultat.
2. Concaténez deux chaînes de caractères (votre prénom et nom) dans une variable `nomComplet` et affichez-la.
3. Convertissez la chaîne "10" en nombre avec `parseInt()` ou `Number()`, ajoutez-la à un autre nombre, et affichez le résultat.
4. Créez un tableau `fruits` avec trois fruits de votre choix et affichez-le.

### **Difficiles**
1. Créez un objet `personne` avec les propriétés `nom`, `age` et `ville`, puis affichez chaque propriété avec `console.log()`.
2. Déclarez une variable `let compteur = 5`, modifiez sa valeur à 10, et affichez-la avant et après la modification.
3. Essayez de modifier une constante (ex. `const x = 5`) et observez l'erreur dans la console.

---

**Astuce** : Lisez attentivement les messages d'erreur dans la console. Ils vous aident à identifier les problèmes et à mieux comprendre JavaScript.
