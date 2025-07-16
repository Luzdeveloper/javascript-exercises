# Exercise 03 - numberChecker

Modifiez le code pour qu'il retourne `true` lorsque le nombre est supérieur ou égal à 10, et `false` s'il est inférieur à 10.

Actuellement, le code retourne `true` si le nombre est `6`, sinon il retourne `false`.

Vous remarquerez également que dans cet exercice, il y a plusieurs tests (dans le fichier `numberChecker.spec.js`). Seul le premier test est actuellement activé. Après avoir vérifié que le premier test passe, activez le suivant en supprimant la partie `.skip` de la fonction `test.skip()`. Il est généralement plus facile d'activer un seul test à la fois, puis de modifier votre code pour qu'il passe. Continuez à activer un test à la fois jusqu'à ce qu'ils passent tous, petit à petit !

- Si l’exécution de `npm test numberChecker.spec.js` affiche des résultats similaires à ceux ci-dessous, assurez-vous d’avoir activé les autres tests comme indiqué ci-dessus.

```
Test Suites: 1 passed, 1 total
Tests:       3 skipped, 1 passed, 4 total
```

## Conseils

- Vous n'avez besoin de modifier que la ligne 2.

- Consultez la documentation sur les opérateurs de comparaison en JavaScript pour un rappel rapide.
