---
layout: post
title: Le modèle d’audioguide statique pour musée de l’ACMI LABS
---

L’audioguide est aujourd’hui l’un des outils incontournables de médiation muséale mis à disposition des publics ayant pour vocation l’aide à la visite et l’interprétation des contenus.

> À l’usage, l’audioguide est ainsi porteur de liberté et d’autonomie pour les visiteurs qui interprètent la proposition dans ce sens et non pas comme une contrainte. La logique d’accompagnement l’emporte sur le sentiment d’être assisté, ou « enfermé » dans une logique de parcours dirigiste. L’activité de sélection et d’interprétation des œuvres devient un modèle pour « apprendre des choses » au musée : apprendre à voir et accéder aux savoirs, aux « façons de faire » qui fondent le regard éclairé, à fortiori quand « les objets ne parlent pas d’eux-mêmes. – Sophie Deshayes [1]

Cependant, habituellement les visiteurs·euses doivent débourser un montant supplémentaire pour emprunter un audioguide au musée et la mise sur pied d’une telle logistique mobilise un nombre certain de ressources. Dans le cadre de l’exposition _Scorsese_ présentée à l'Australian Centre for the Moving Image (ACMI) en 2016, les développeurs Joel Glovier, Andrew Serong et Seb Chan de l’[ACMI LABS](https://labs.acmi.net.au/) se sont ainsi donné pour mission de créer un audioguide statique entièrement gratuit et accessible sur tous les types d’appareils.

![ScorseseAudioguide](http://www.museadon.ca/images/ScorseseAudioguide.jpg)

[Scorsese Audio Guide](https://guides.acmi.net.au/scorsese/welcome/)

> […] the audio tour is really an add-on experience, so rather than treat this as an up-sell, we liked the idea of keeping it free, and treat it kind of like bonus features on a DVD. Something that’s fun, offers interesting insights, but isn’t critical to the enjoyment of the exhibition. And rather than just limit it to the in-museum experience, build it as something that could be interesting to listen to after a museum visit, so it should also work on a desktop, tablet or laptop layout. – Andrew Serong [2] 

Conçu sur le populaire générateur de site statique [Jekyll](https://jekyllrb.com/), et suivant les principes _open source_ ou code source ouvert[3], Glovier, Serong et Chan ont publié leur audioguide selon les termes de la [licence du MIT](https://www.mit.edu/~amini/LICENSE.md) – la réutilisation du code est donc très permissive. À noter que le modèle emploie des bibliothèques [JavaScript](https://www.javascript.com/) couvertes par leurs propres licences ([jQuery](https://jquery.com/), [Slick JS](http://kenwheeler.github.io/slick/) et [jPlayer](http://jplayer.org/)). Quoi qu’il en soit, ce dernier est facilement utilisable dans sa forme actuelle, seulement quelques compétences de base en HTML et en développement sont nécessaires, des fichiers audio MP3, et des connaissances en édition d'images, sur Photoshop par exemple, peuvent également être utiles.

Le modèle d’audioguide statique pour musée de l’ACMI LABS comprend : 
- Une **page d’accueil** usant d’un carrousel Slick JS pour présenter l’audioguide aux utilisateurs·trices.
- Un **menu principal** composé d’icônes numérotées.
- Des **pages d’arrêt individuelles** possédant un menu déroulant, un carrousel d’images et un lecteur audio fixe en pied de page.
- Il est aussi possible d’ajouter une **page simple** renvoyant aux pages du **réseau WiFi captif** de votre institution. 

![DemoStaticAudioguide](http://www.museadon.ca/images/DemoStaticAudioguide.jpg)

[Demo – Static Museum Audio Guide](http://acmilabs.github.io/static-museum-audio-guide/welcome/)

D’un point de vue critique, il est à mentionner que l’usage de cet outil requiert une connexion internet, il nécessite que les publics utilisent leurs propres appareils mobiles, il exclut possiblement celles et ceux qui n’ont pas d’appareil ou qui sont peu confortables avec cette technologie, et une option multilingue est malheureusement manquante.

Les avantages de ce modèle d’audioguide statique sont tout de même nombreux – un _backend_[4] agréable permettant de créer du contenu original ; il est rapide et facile d’utilisation ; il est léger et multiplateforme ; l’hébergement est possible sur [Github](https://github.com/) ou sur un serveur dédié ; il permet la récupération de projets existants ; il est peu coûteux à réaliser et son caractère statique demande un maintien minimal et le rend pérenne.[5]

À ce jour, près de trente institutions ont d’ailleurs utilisé ce code source pour leur propre projet, dont l’Immigration Museum à Melbourne en Australie pour l’exposition [Lustre](https://lustre.guide/) et les National Galleries of Scotland pour l’exposition [A Perfect Chemistry: Photographs by Hill & Adamson](https://audio.nationalgalleries.org/).

N’attendez plus, déployez votre propre audioguide statique dès maintenant en suivant le modèle [ACMI LABS static museum audio guide](https://github.com/ACMILabs/static-museum-audio-guide#getting-started).

–––

[1] Sophie Deshayes, « Interprétation du statut d’un audioguide », Études de communication, no 24, 2001, pp. 71-90. En ligne. < [https://journals.openedition.org/edc/995](https://journals.openedition.org/edc/995) >.

[2] Andrew Serong, « Making the free audio guide for Scorsese », ACMI LABS, 30 mai 2016. En ligne. < [https://labs.acmi.net.au/making-the-free-audio-guide-for-scorsese-3cf5398e5658#](https://labs.acmi.net.au/making-the-free-audio-guide-for-scorsese-3cf5398e5658#) >.  

[3] Gill Hamilton et Fred Saunderson, Open Licensing for Cultural Heritage, London, Facet Publishing, 2017.

[4] « Dans le monde de l'informatique, le « backend » désigne toute partie d'un site web ou d'un logiciel que les utilisateurs ne voient pas. Il contraste avec le « frontend », qui fait référence à l'interface utilisateur d'un programme ou d'un site web. Dans la terminologie de la programmation, le backend est la « couche d'accès aux données », tandis que le frontend est la « couche de présentation ». [Traduction libre]. Tiré de Per Christensson, « Backend Definition. » TechTerms, 11 avril 2020. En ligne. < [https://techterms.com/definition/backend](https://techterms.com/definition/backend) >.

[5] Andrew Serong, « An open source museum audio guide », ACMI LABS, 31 mai 2016. En ligne. < [https://labs.acmi.net.au/an-open-source-static-museum-audio-guide-4c5cd83dbdcb#](https://labs.acmi.net.au/an-open-source-static-museum-audio-guide-4c5cd83dbdcb#) >.
