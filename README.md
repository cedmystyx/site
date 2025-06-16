# site

## L’injection de prompt, c’est quoi ?
L’injection de prompt c’est le fait de manipuler les modèles d’IA afin de générer des 
réponses potentiellement nuisibles (révélation d’informations sensibles, passer outre les filtres imposés…)

## Comment fonctionnent les attaques ? 

Les attaques de prompts exploitent la manière dont les modèles d’IA traitent les informations, les attaquants parviennent tromper les modèles de langage et donc à effectuer des actions qui conduisent à des conduites manipulées qui entraînent des fuites de données sensibles, le contournement des politiques de sécurité voire à la désinformation générée par l’IA.
Il existe plusieurs mesures de protection afin de contrer ce genre d’attaque. 
Les entreprises telles que OpenAI peuvent utiliser la “validation robuste des entrées” ce système assainit les entrées utilisateurs en filtrant les caractères spéciaux et en appliquant des expressions régulières afin de détecter les entrées potentiellement nuisibles.



## Quels risques pour l’intelligence artificielle ?

##Parmi les menaces les plus critiques pesant sur l’IA, la prompt injection se distingue. Elle représente un risque comparable à l’exécution de code non autorisé ou à l’exposition involontaire de données sensibles. Ce type d’attaque exploite la manière dont les modèles interprètent les instructions, souvent sans distinction claire entre commandes fiables et malveillantes. Les approches de défense actuelles échouent fréquemment, car elles reposent sur l’hypothèse erronée que le modèle est stable et prévisible. Or, la nature même des modèles de langage les rend sensibles aux variations de contexte et aux manipulations subtiles, rendant leur sécurisation complexe.




## Comment contourner les mesures de protection contre ce risque sur l’IA

Pour contourner les protections contre l’infiltration de requête (prompt injection), les attaquants créent des instructions déguisées qui exploitent la confusion du modèle entre les prompts internes et externes. Ils utilisent des formulations ambiguës ou détournées pour désactiver les garde-fous, influencer les réponses ou obtenir des informations sensibles. Parmi les techniques courantes : l’enchaînement de commandes, l’usage de langages alternatifs, les métaphores trompeuses, ou encore l'encapsulation dans des balises ou citations. Certains vont jusqu’à dissimuler des instructions dans des données apparemment inoffensives. Même les modèles entraînés avec des filtres stricts peuvent être contournés si les entrées sont suffisamment subtiles et bien pensées.

