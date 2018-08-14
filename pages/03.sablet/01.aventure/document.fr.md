---
title: 'L''aventure Sablet'
abstract: 'Lancer un ballon sonde pour observer Terre et atmosphère fut une aventure enrichissante… Récit.'
media_order: envol.jpg
header_image:
    image: envol.jpg
    color: '#2b6ead'
    title: 'L''envol du ballon, juste après son décollage'
    author: 'A. Carrade'
    vertical_centering: 74
date: '11:42 27-06-2018'
license: by-sa
authors:
    1: 'Timothée Bailly'
    0: 'Amaury Carrade'
---

_Cette page est en cours de rédaction. Revenez plus tard ! Le site n'est pas encore officiellement lancé._

Lancer un ballon-sonde ne s'improvise pas la veille pour le lendemain. En l'occurrence, le projet SABLET a débuté au début de l'année 2017 (pour un lancement en août de la même année). Initialement, Timothée Bailly était seul sur le projet, rejoint au milieu de la préparation par Amaury Carrade.

Oh, six mois n'étaient pas vraiment nécessaires pour mener le projet à bien — mais nous n'avions pas 100 % de notre temps à consacrer, et (mais ce sera évoqué plus tard) certains soucis administratifs ont décalé le lancement.

# Préparation

[tweet=https://twitter.com/Yoku_Sama/status/870725624268193793]

Les premiers mois furent consacrés à la mise au point de ce que l'on voulait faire, et aux renseignements et contacts concernant les possibilités que l'on avait. L'objectif initial était clair : réussir l'envol (le premier de cette envergure pour Timothée), et obtenir de belles photographies et films de la Terre vue de la stratosphère, incluant idéalement la courbure de notre planète. Après discussions, s'ajouta celui de prendre des mesures de température, pression, et proportion d'ozone régulièrement dans l'atmosphère grâce à des capteurs intégrés au ballon.

En juin, nous commençâment à [recevoir les pièces](/sablet/materiel), commandées sur Internet. Il s'agissait de tester le matériel, s'assurant par exemple que la caméra pouvait tenir suffisamment longtemps, mais aussi réfléchir à comment tout assembler proprement. Nous avions trois principales contraintes : 

- le **poids** de la charge utile[^charge-utile], qui était très limité, car il fallait que le ballon puisse décoller et aller haut[^limite-poids] ;
- les **limites du matériel** : la température descend très bas en haute altitude, et tout ce que nous voulions embarquer ne supportait pas de telles conditions ; aussi, il fallait que les appareils devant communiquer avec le sol… puissent le faire[^blocage-gps] ;
- la **loi**, eh oui, qui [impose d'embarquer certains éléments et de respecter certaines normes](/sablet/loi), notamment de vitesse d'ascension.

[^charge-utile]: La charge utile, c'est simplement ce que le ballon transporte… _d'utile_, en plus de lui-même (la nacelle, la caméra, le GPS, les capteurs…).
[^blocage-gps]: Plus de détails sur ça un peu plus bas…
[^limite-poids]: Quand on monte ce genre de projets, on se retrouve très vite à chercher à économiser le moindre gramme. Ce fut d'ailleurs un des critères du choix des capteurs embarqués, et de tout le reste du matériel d'ailleurs (vous trouverez [plus de détails sur la page dédiée au matériel](/sablet/materiel)). _In fine_, nous sommes arrivés à une masse tout juste au delà du kilogramme (pour la nacelle uniquement).

## Jouer avec les limites du matériel

Il fut plus simple de tester certains éléments que d'autres. Les composants électroniques embarqués furent assez simple à tester, dans les limites que nous le faisions sur Terre et non aux températures réelles auxquelles ils allaient être exposés. Cela nous a d'ailleurs donné l'occasion de publier certains de ces tests lorsqu'ils se révélèrent jolis — par exemple, cet innocent _timelaps_ publié sur Instagram a initialement été tourné pour s'assurer que la batterie de la caméra tournerait longtemps.

[instagram=https://www.instagram.com/p/BVAgNxeFij0/]

Pour d'autres éléments, il n'était pas vraiment possible de tester, ou de manière très limitée. Difficile, par exemple, de tester le bon déploiement du parachute… sans envoyer un autre ballon (et ce bien que nous annoncions avant le lancement que nous comptions faire ce test !). Aussi, nous n'avions pas de chambre froide pour tester l'isolation de notre nacelle en polystyrène face à une température extérieure de -50 °C, ni pour nous assurer que nos capteurs exposés résisteraient à de telles températures. Cela dit, ce ne fut pas un réel problème étant donné que les limites étaient généralement précisées sur les notices ou _datasheets_ des éléments utilisés.

[tweet=https://twitter.com/Yoku_Sama/status/871437949853982723]

On pourrait penser que ce qui limite la résistance de l'électronique embarquée, ce sont les parties actives (caméras, capteurs…). En réalité le facteur bloquant est tout autre, ces parties actives fonctionnant généralement sans problème à des températures très basses. Non, ce à quoi il faut faire attention quand on envoie de l'électronique à très basse température, ce sont les **batteries**.

Les batteries fonctionnent grâce à des réactions chimiques qui sont beaucoup moins efficaces lorsqu'il fait froid. Dans notre cas et d'après nos relevés, l'intérieur isolé de la nacelle est tombé à -20 °C, une température que nous avions approximativemnt anticipé. Nous n'avions pas jugé nécessaire de chauffer au delà de l'isolation pour éviter que les batteries ne meurent (même si nous l'avions envisagé sérieusement), et tout s'est finalement bien passé, mais avec des batteries plus sensibles au froid ou par simple prudence, il peut être un bonne idée d'y songer (par exemple grâce à des lingettes chauffantes, ou une seconde couche d'isolant autour des batteries).

## Se conformer à la loi

En plus des contraintes de matériel embarqué et de vitesse sus-mentionnées, la loi nous contraint également à une déclaration de lancement auprès de la DSAC.

[tweet=https://twitter.com/Yoku_Sama/status/871302979479105536]

Nous nous sommes un peu fait avoir à ce niveau car nous attendions une réponse, alors que la demande est sous-entendue acceptée en cas de silence de l'administration de plus de trois semaines. Ils ne répondent généralement que s'ils ont quelque chose à redire — ou si ça leur chante, comme ce fut le cas pour notre seconde demande.

[tweet=https://twitter.com/Yoku_Sama/status/898245818364329988]

[DSAC]: Direction de la sécurité de l'Aviation civile

# Veille du lancement