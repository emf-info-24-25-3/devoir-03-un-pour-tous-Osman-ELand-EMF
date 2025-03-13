## REPONSES :
1. Peut-on modifier l'âge d'un chien une fois qu'il a été créé (essayez de donner 10 ans à chien3 pour vérifier) ? 

Oui, l'âge d'un chien peut être modifié, car l'attribut age est une variable d'instance et non static. Il appartient donc à chaque instance de Chien et peut être modifié individuellement.

2. Que se passe-t-il si on modifie le nom de chien2 ?

Si on modifie le nom de chien2, cela affectera le nom de tous les chiens. En effet, l'attribut nom est déclaré comme static, ce qui signifie qu'il est partagé par toutes les instances de la classe Chien. Ainsi, modifier chien2.nom revient à modifier la valeur de nom pour toutes les instances de la classe.

3. Pourquoi tous les chiens ont tous le même nom ?

Tous les chiens partagent le même nom, car l'attribut nom est déclaré static. Un attribut static appartient à la classe et non aux instances individuelles. Ainsi, chaque fois qu'un nouvel objet Chien est créé, la valeur de nom est écrasée par la nouvelle valeur passée au constructeur.

4. Observez avec attention les lignes N°20 à N°26 du main() et réfléchissez : par quel miracle le chien3 à la ligne N°26 s'affiche correctement ?
   Répondez à cette question en expliquant avec précision ce qui se passe et pourquoi.

Le miracle est qu'il ne s'affiche pas correctement du tout !


