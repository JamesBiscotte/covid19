# Covid19

## Est ce que les mouvements des population ont eu un effet sur la dynamique de l'épidémie?

Hello à tous,

j'ai créé ce notebook jupyter dans le but d'analyser l'accélération de l'épidémie covid19 après le début du confinement, par département. En relation avec l'augmentation ou la diminution de la population de ces départements. Le but est de comprendre si les mouvements de population à l'annonce du confinement ont un impact local (lieu de départ et d'arrivée) sur la dynamique de l'épidémie. 

Pour le moment je ne trouve pas de corrélation entre le mouvement des populations et un changement de rythme dans l'épidémie localement. 

Mais je ne suis pas spécialiste en statistiques, et je sais que les données sont incomplètes. Donc je pense que je manque certaines choses. J'ai une attaque gros grain, où j'ai séparé en 3 catégories, grosse augmentation (x>1%), pas d'augmention significative (-1%<x<1%) ou grosse perte de population (x<-1%). Je compare les résulats de chaque groupe avec la moyenne nationale.
 
J'observe la vitesse de progression de l'épidémie à la date t0 (18 mars 2020) et la compare avec la vitesse à d'autres dates (tous les 4 jours, 22 mars, 26 mars, etc). J'évalue cette vitesse avec les entrées à l'hopital et en reanimation, moyenne lissée sur 3 jours.

J'ai aussi vérifié que la vitesse de progression est liée ou non à la population du département. Là non plus pas de tendance.

Je voudrais avoir confirmation/infirmation/correction de ma méthode et/ou mesures. Est ce que je manque de faire certaines normalisations, par rapport aux populations etc? Et il me manque sûrement des tests statistiques de significativité, mais je ne vois pas quoi vérifier.

Le git est:
https://github.com/JamesBiscotte/covid19 

Merci par avance à tous ceux qui se pencheront sur le sujet! Vous pouvez m'envoyer vos suggestions à james.biscotte chez l'herbergeur gmail.

Les données viennent de:
https://www.data.gouv.fr/fr/datasets/donnees-hospitalieres-relatives-a-lepidemie-de-covid-19/
et
https://www.insee.fr/fr/information/4477356

Vous pouvez bien sûr récupérer le tout pour faire d'autres analyses.
