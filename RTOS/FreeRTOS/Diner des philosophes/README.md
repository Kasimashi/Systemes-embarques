# Introduction
La situation est la suivante :

cinq philosophes (initialement mais il peut y en avoir beaucoup plus) se trouvent autour d'une table ;
chacun des philosophes a devant lui un plat de spaghetti ;
à gauche de chaque plat de spaghetti se trouve une fourchette.
Un philosophe n'a que trois états possibles :

penser pendant un temps indéterminé ;
être affamé (pendant un temps déterminé et fini sinon il y a famine) ;
manger pendant un temps déterminé et fini.
Des contraintes extérieures s'imposent à cette situation :

quand un philosophe a faim, il va se mettre dans l'état « affamé » et attendre que les fourchettes soient libres ;
pour manger, un philosophe a besoin de deux fourchettes : celle qui se trouve à gauche de sa propre assiette, et celle qui se trouve à droite (c'est-à-dire les deux fourchettes qui entourent sa propre assiette) ;
si un philosophe n'arrive pas à s'emparer d'une fourchette, il reste affamé pendant un temps déterminé, en attendant de renouveler sa tentative.
Le problème consiste à trouver un ordonnancement des philosophes tel qu'ils puissent tous manger, chacun à leur tour. Cet ordre est imposé par la solution que l'on considère comme celle de Dijkstra avec sémaphores ou Courtois avec des compteurs.

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/An_illustration_of_the_dining_philosophers_problem.png/578px-An_illustration_of_the_dining_philosophers_problem.png)
