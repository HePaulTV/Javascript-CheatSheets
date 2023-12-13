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










