# covid19

# est ce que les mouvements des population ont eu un effet sur la dynamique de l'épidémie?

Hello à tous,

j'ai créé un notebook jupyter dans le but d'analyser l'accélération de l'épidémie covid19 après le début du confinement, par département. En relation avec l'augmentation ou la diminution de la population de ces départements. Le but est de comprendre si les mouvements de population à l'annonce du confinement ont un impact local (lieu de départ et d'arrivée) sur la dynamique de l'épidémie. 

Je ne suis pas spécialiste en statistiques, je sais que les données sont incomplètes. 

Pour le moment je ne trouve pas de corrélation entre le mouvement des populations et un changement de rythme dans l'épidémie localement. 

Mais je suis sûr que je manque plein de choses. J'ai une attaque gros grain, où j'ai séparé en 3 catégories, grosse augmentation (x>1%), pas d'augmention significative (-1%<x<1%) ou grosse perte de population (x<-1%). 
Je voudrais avoir confirmation/infirmation/correction de ma méthode et/ou mesures. 
Il me manque sûrement des tests statistiques de significativité, mais je ne vois pas quoi vérifier.

Le git est:
https://github.com/JamesBiscotte/covid19 

Merci par avance à tous ceux qui se pencheront sur le sujet!

Les données viennent de:
https://www.data.gouv.fr/fr/datasets/donnees-hospitalieres-relatives-a-lepidemie-de-covid-19/
et
https://www.insee.fr/fr/information/4477356
