# Evolution-CO2
Cyrielle Clastres - Catherine Yong -  Tahar Amairi - Thanh Liem Ta

Evolution du CO2 dans le monde : la COP21 peut-elle être respectée et à quel prix ?

Modélisation des facteurs (population, énergie, CO2, PIB).

Modélisation mondiale puis dans différentes régions, continents en prenant en compte le CO2 réellement produit et celui "importé".




# 13 mars 2019:

Nous nous sommes séparés le travail, chacun s'occupant d'un paramètre.
Catherine se charge de la population, Cyrielle du PIB, Tahar du CO2 et Thanh de l'énergie consommée.

Concernant la modélisation de la population, nous avons pu obtenir la population du continent à l'année voulue en prenant en compte le taux de natalité et de mortalité, que l'on peut modifier. De plus, s'il un problème survient, la population n'évoluera pas de la même manière. Nous avons utilisé l'évolution exponentielle, évolution la plus réaliste parmi celles qui existent. Les données ont été prises à l'année 2017 pour estimer la suite. 

Concernant le PIB, une première approche a été faite, une approche mondiale. Elle n'est pas précise, donc nous chercons à l'améliorer en étudiant le PIB à l'échelle continentale.

Pour l'évolution du CO2, deux modèles existent. Tahar fera des recherches plus approfondies chez lui.

Pour l'évolution de l'énergie, nous avons trouvé un tableau donnnant toutes les valeurs pour chaque région de l'énergie consommée. Etant donné l'absence de modèle accessible pour modéliser ce paramètre, nous avons convenu qu'il fallait programmer un modèle de régression linéaire sur python, pour approximer le phénomènne étudié.




# 14 mars 2019:

Cyrielle finit le calcul du CF par continent pour la deuxième approche et fait les recherches pour le calcul du FBCF. Il s'agit d'une partie difficile car il faut avoir des données non officielles (argent dépensés dans les travaux des habitants par an) avec des données officielles (nombre d'entreprises dans un continent et investissements faites par celles-ci).

# 18 mars 2019

Pour la population (Catherine), il reste à faire le graphique pour visualiser l'évolution de la population à l'année voulue.

# 19 mars 2019:
La recherche des données pour le FBCF est faite et le programme fait. Les données pour le FBCF sont globales : il n'y a plus de distinctions entre particuliers et entreprises. Pour le calcul de VS les seules données trouvées sont par pays. Il faut donc les classer pour avoir une moyenne par continent et par habitant.

Le code concernant l'évolution vient d'etre ajouté, il ne manque plus que le test qui se fera demain. Si celui-ci est concluant, on pourra passer l'approximation des parametres du programme.  
