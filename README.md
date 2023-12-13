# **Javascript CheatSheets**
![Banner](https://github.com/HePaulTV/Javascript-CheatSheets/assets/113673467/738a4592-584d-4382-949a-f40231f1b707)

## Les scripts de pages :
Vous pouvez déclarer des script directement dans votre page html.
```
<script type="text/javascript">
Le contenu de votre script...
</script>
```

## Inclure un script externe :
Pour ajouter un script externe à la page html il suffis de le faire dans le **head** de la page :
```
<script src="chemin/du/fichier.js"><script>
```

## Faire une fonction :
Strcuture d'une fonction en javascript :

```
function addNumbers(a, b) {
  return a + b;
}
```

## Les commentaires :
Commenter votre code est très **important** pour la compréhension global et pour vous y retrouver :
```
/* Plusieurs lignes
de commentaires */

// Une seul ligne de commentaire
```

## Affichage et débug :
Il est important de faire du **debug** en affichant des valeurs pour trouver la source du probleme :
```
console.log(a);
document.write(a);
alert(a);
confirm("Accepter?");
prompt("Votre âge?", "18");
```

## Les types de données :
Il existe plusieurs type de données, et on utlise **let** pour les déclarer car **var** est déprécié :

### Les nombres :
```
let age = 18;
```

### Les chaîne de charactères :
```
let nom = "Paul Carouge";
```

### Les objets :
```
let personne = {prenom:"Paul", nom:"Carouge"};
```

### Les booléens :
```
let estVrai = true;
```

### Les tableaux :
```
let tableau = ["HTML", "CSS", "JAVASCRIPT"];
```

### Les non-définis :
```
let a;
```

### Les nulls :
```
let nulle = null;
```

## Les conditions if/else :
Les conditions sont une partie importante du développement et elle permettre de rendre le code adapté à la situation :
```
if ((age >= 14) && (age < 19)) {
  status = "Eligible";
} else {
  status = "Non-Eligible";
}
```

## Les nombres en Javascript :
Javascript permet d'utiliser une grande variété de fonctions pour les traiter, les voici :
```
let pi = 3.141; // On déclare une variable pi.
```

### Afficher les x premiers chiffres
```
pi.toFixed(0); //Retourne la valeur 3.
```

### Afficher les x premiers chiffres
```
pi.toFixed(2); //Retourne 3.14.
```

### Afficher les x premier nombre avec virgules
```
pi.toPrecision(2); //Retourne 3.1.
```

### Affiche la valeur d'un nombre
```
pi.valueOf(); //Retourne number.
```

###  Convertir en nombre
```
Number(true); //Converti en nombre.
```

### Affiche une date
```
Number(new Date()) //Retourne le nombre de millisecondes depuis 1970.
```

### Affiche les x chiffres **entier** dans une chaîne de charactère
```
parseInt("3 Mois"); //Retourne 3.
```

### Affiche les x chiffres à **virgules** dans une chaîne de charactère
```
parseFloat("3.5 Jours"); //Retourne 3.5.
```

### Affiche une valeur maximale
```
Number.MAX_VALUE; //Retourne le plus grand nombre JS possible.
```

### Affiche une valeur minimale
```
Number.MIN_VALUE; //Retourne le plus petit nombre JS possible.
```

### Affiche -Infini
```
Number.NEGATIVE_INFINITY //-Infini.
```

### Affiche Infini
```
Number.POSITIVE_INFINITY //Infini.
```

## Les chaînes de charactères en javascript :
Une liste d'outils pour traiter les chaînes de chractères :
```
let abc = "Je suis une chaine de charactère";
```

### Retour à la ligne
```
let ligne = "Je retourne \n à la ligne"; // Le retour à la ligne avec \n.
```

### Affiche la longeur de la chaîne de charactère
```
let long = abc.length; //Retourne la longueur de la chaîne de charatères.
```

### Afficher un morceau de la chaîne
```
abc.indexOf("chaine"); //Trouve un substring.
```

### Afficher une occurence
```
abc.lastIndexOf("chaine"); //Trouve la dernière occurence.
```

### Afficher un bout de la chaîne de charactère avec des index
```
abc.slice(3, 6); //Retourne "sui" de la chaine abc.
```

### Remplace une partie de la chaîne de charatère
```
abc.replace("abc","123"); //Trouve et rémplace dans la chaîne de charactère.
```

### Convertir en Majuscule
```
abc.toUpperCase(); //Converti en majuscules.
```

### Convertir en Minuscule
```
abc.toLowerCase(); //Converti en miniscules.
```

### Faire une concaténation
```
abc.concat(" ", str2); //Retourne abc + " " + str2.
```

### Afficher un charactère avec un indice
```
abc.charAt(2) //Retourne la charactère à l'indice 2.
```

### Afficher la valeur ASCII d'un charactère avec un indice
```
abc.charCodeAt(2); //Retourne la valeur ASCII de charactère à l'indice.
```

### Séparé la chaîne de charactère 
```
abc.split(","); //Retourne la chaîne séparé par des virgules.
```


## Les boucles en javascript :
Les boucles sont une autre partie importante de la programmation, les voici en javascript :

### For :
```
for (let i = 0; i < 10; i++){
  document.write(i + "<br />");
}
```

### While :
```
let i = 1;
while (i < 100) {
  i *= 2;
  document.write(i + ", ");
}
```

### Do-While :
```
let i = 1;
do {
  i*= 2;
  document.write(i + ", ");
} while (i < 100)
```


## Les Math en javascript :
Il existes plusieurs moyen de faire des calculs mathématiques en javascript :

### Retourne Pi
```
let pi = Math.PI; //Retourne 3.141592653589793
```

### Arrondir un nombre
```
Math.round(4.4); //Retourne 4, mais 4.5 donnerai 5.
```

### Faire une puissance
```
Math.pow(2,8); //Retourne 256 qui correspond à 2 puissance 8.
```

### Faire une racine carré
```
Math.sqrt(49); //Retourne 7 qui est la racine carré.
```

### Affiche l'absolu positif
```
Math.abs(-3.14); //Retourne 3.14 qui est l'absolu positif.
```

### Affiche l'arrondi supérieur
```
Math.ceil(3.14); //Retourne 4 qui est l'arrondi supérieur.
```

### Affiche l'arrondi inférieur
```
Math.floor(3.99); //Retourne 3 qui est l'arrondi inférieur.
```

### Afficher le plus petit nombre
```
Math.min(0, 3, -2, 2); //Retourne -2 qui est le plus petit des nombres.
```

### Afficher le plus grand nombre
```
Math.max(0, 3, -2, 2); //Retourne 3 qui est le plus grand des nombres.
```

### Nombre aléatoire
```
Math.random(); //Retourne un nombre aléatoire entre 0 et 1.
```
```
Math.floor(Math.random()  * 5) + 1; //Retourne un entier entre 1 et 5.
```











