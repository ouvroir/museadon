---
layout: post
title: Quire, un outil ouvert pour la publication numérique
---

La publication de livres est un moyen de diffusion fréquemment utilisé par les musées. Les livres publiés à l’occasion d’une exposition permettent d’approfondir son sujet et de pérenniser l’accès à son contenu. “La publication subsiste à l'exposition et elle est gardienne de la mémoire de tout ce travail de recherche et de cette réflexion théorique qui sont développés lors de l'élaboration de l'exposition.”1  Ces publications donnent également accès au contenu pour un public plus large, n’ayant pas eu l’occasion de visiter l’exposition.

La production de livres imprimés est toutefois dispendieuse. Les frais d’impression peuvent rapidement devenir un frein à la publication, particulièrement pour des institutions de taille modeste, qui jonglent souvent avec des budgets limités. Au cours des dernières années, les publications numériques deviennent une alternative de plus intéressante à l’édition papier. Les frais de production et de distribution dans le monde de l’édition numérique sont nettement moins prohibitifs. Le numérique permet également d’introduire une navigation interactive ainsi que du contenu vidéo et sonore. 

## Quire
Actuellement en phase beta, Quire est un outil ouvert de publications numériques multiformat développé par le J. Paul Getty Museum. En plus de la publication en ligne, Quire permet de créer des livres numériques sous format EPUB et MOBI prêts à être distribués sur les différentes plateformes de ventes, telles qu’Apple et Amazon.  La version en ligne peut également être exportée en PDF dans un format prêt pour l’impression. Le design des publications Quire est responsive et permet d’inclure des citations, des notes de bas de pages, des images qui peuvent être agrandies, des fichiers audio et vidéos, une bibliographie, une table des matières dynamique et un outil de recherche.

Quire utilise [Hugo](https://gohugo.io/), une plateforme ouverte servant à créer des sites statiques, pour créer des publications numériques à partir de fichiers textes. L’utilisation de sites statiques, en plus de faciliter la mise en ligne, assure une certaine durabilité à la publication. Les publications créées à l’aide de Quire peuvent être hébergées sur n’importe quel serveur ou sur GitHub, sans être liées à une base de données ou un système de gestion de contenu (CMS) pour les mettre à jour.  

Les sites web dépendent généralement d’un CMS lié à une base de données. Le CMS est utilisé pour créer le site web. Une fois le site en ligne, le CMS reconstruit les pages du site à chaque fois qu'elles sont chargées par un utilisateur (à moins d’utiliser des systèmes de cache, possiblement complexes à mettre en place). Ainsi, le CMS doit être fonctionnel pendant toute la durée de vie du site web. Ce n’est pas le cas pour les sites statiques, qui ne sont pas dépendant d’un service externe pour la gestion de contenu. Dans le cas d’un site statique, les pages web sont livrées au navigateur de l'utilisateur exactement tel qu'elles sont stockées. Malgré leur appellation, la navigation des sites statiques est tout aussi dynamique, grâce à la prise en charge de la plateforme web complète (HTML5, CSS3 et JavaScript).  Dans [*Ancient Terracottas in the J. Paul Getty Museum*](https://www.getty.edu/publications/terracottas/), la première publication numérique du Getty, on retrouve une carte interactive, sur laquelle sont apposés les 60 objets de terres cuites listés dans le catalogue.  La recherche par filtre permet également différentes façons de consulter le catalogue, il en résulte une lecture beaucoup moins linéaire que celle d’un livre imprimé.

[ancient-terracottas] Fig. 1 : Navigation par filtres de [*Ancient Terracottas in the J. Paul Getty Museum*](https://www.getty.edu/publications/terracottas/)

Quire supporte [markdown](https://guides.github.com/features/mastering-markdown/), un format de texte brut facile à utiliser. Le formatage dans markdown consiste simplement à utiliser les bons caractères : astérisques pour marque l'italique et le gras, le carré (#) pour les en-têtes et les parenthèses et les crochets pour les liens. Les fichiers texte utilisés pour les publications Quire peuvent à n’importe quel moment être édités, les corrections peuvent être visualisées sur l’application pour ensuite être sauvegardées et actualisées en ligne. 

Les styles prédéfinis de Quire permettent un processus de publication allégé. Le design est sobre et fonctionnel, mais difficilement modifiable. Les développeurs de Quire précisent qu’il est possible de personnaliser les thèmes, toutefois, de tels changements nécessitent des connaissances approfondies en programmation.  Comparativement au design des publications d’expositions imprimées, qui sont souvent très distinctives, le design des publications issues de l’outil Quire paraît plutôt générique.

Pour utiliser la version beta de Quire, il suffit de [s’enregistrer](https://docs.google.com/forms/d/e/1FAIpQLScKOJEq9ivhwizmdazjuhxBII-s-5SUsnerWmyF8VteeeRBhA/viewform) pour obtenir une licence gratuite . Une documentation extensive et une série de [tutoriels](https://quire.getty.edu/tutorial/) sont disponibles pour faciliter la production de publications.

1.Foisy, M.-H. (2008). Quelle place pour les publications d’exposition dans les musées ? Muséologies, 2 (2), 44–63. https://doi.org/10.7202/1033588ar![image](https://user-images.githubusercontent.com/77697613/112734810-72a2e100-8f1e-11eb-94c2-191607853af7.png)


## Bibliographie

[Foisy, M.-H. (2008). Quelle place pour les publications d’exposition dans les musées ? Muséologies, 2 (2), 44–63.](https://doi.org/10.7202/1033588ar)

Getty publications, consulté le 16 mars, à l'adresse : https://www.getty.edu/publications/digital/platforms-tools.html

Documentation sur Quire, consulté le 17 mars, à l'adresse :https://quire.getty.edu/
