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

```
pi.toFixed(0); //Retourne la valeur 3.
```

```
pi.toFixed(2); //Retourne 3.14.
```

```
pi.toPrecision(2); //Retourne 3.1.
```

```
pi.valueOf(); //Retourne number.
```

```
Number(true); //Converti en nombre.
```

```
Number(new Date()) //Retourne le nombre de millisecondes depuis 1970.
```

```
parseInt("3 Mois"); //Retourne 3.
```

```
parseFloat("3.5 Jours"); //Retourne 3.5.
```

```
Number.MAX_VALUE; //Retourne le plus grand nombre JS possible.
```

```
Number.MIN_VALUE; //Retourne le plus petit nombre JS possible.
```

```
Number.NEGATIVE_INFINITY //-Infini
```

```
Number.POSITIVE_INFINITY //Infini
```











