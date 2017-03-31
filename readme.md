# [Symfony Live - Paris 2017](http://paris2017.live.symfony.com/) talks

- All talks are in **french**.
- Comment and rate talks on [joind.in](https://joind.in/event/symfonylive-paris-2017)

## Symfony 4

<dl>
  <dt>Description</dt>
  <dd>Symfony 4 sortira en décembre 2017. Aucune surprise d'un point de vue fonctionnel puisque toutes les nouvelles fonctionnalités seront disponibles dans les versions 3 successives (dont la 3.4 qui sortira en même temps). Quoi de neuf du coup ? Grâce à Symfony Flex, la façon de développer des applications va changer.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.sensiolabs.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## A la découverte du composant Serializer

<dl>
  <dt>Description</dt>
  <dd>Le composant Serializer de Symfony existe depuis la première version de Symfony 2, mais a gagné énormément de fonctionnalités ces derniers temps.

Au cours de cet talk, je présenterai les fonctionnalités méconnues et pourtant très puissantes de cette bibliothèque.

Après un rappel des fondamentaux, nous découvrirons comment le composant permet - de manière transparente - de manipuler tous types d'objets PHP, quelques soient leurs styles : getters / setters, propriétés publiques, proxys....

Nous verrons ensuite les différents formats supportés nativement : JSON, XML, YAML et CSV. Puis nous manipulerons des dates, et évoquerons l'upload de fichiers avec le support des "data: URI".

Finalement, nous aborderons quelques cas plus complexes tels que choisir les propriétés à sérialiser / désérialiser grâce aux groupes, gérer les références circulaires, sérialiser des arbres en limitant leur profondeur et mettre à jour des objets déjà existants.</dd>
</dl>

[Slides](https://speakerdeck.com/lyrixx/symfony-live-2017-serializer)  
~~Video~~

By [Grégoire Pineau](https://connect.sensiolabs.com/profile/lyrixx)  
![github](icon/github.png) [@lyrixx](https://github.com/lyrixx)  
![twitter](icon/twitter.png) [@lyrixx](https://twitter.com/lyrixx)

---

## Grâce aux tags Varnish, j'ai switché ma prod sur Raspberry Pi

<dl>
  <dt>Description</dt>
  <dd>Le moyen le plus rapide d'obtenir une réponse d'un Backend est de ne pas l'appeler ;-) Une solution fournie par les "reverse-proxy" me direz-vous, mais pas si simple d'invalider le cache...

Ce talk aborde une fonctionnalité méconnue de Varnish: les tags. Nous verrons comment en tirer partie via les "event listeners" d'une application Symfony standard. Au menu, un cluster de Rasberry Pi, une API, et des données toujours fraîches sous la milliseconde.</dd>
</dl>

[Slides](https://slideshare.net/JrmyDeruss/grce-aux-tags-varnish-jai-switch-ma-prod-sur-raspberry-pi)  
~~Video~~

By [Jérémy Derussé](https://connect.sensiolabs.com/profile/jderusse)  
![github](icon/github.png) [@jderusse](https://github.com/jderusse)  
![twitter](icon/twitter.png) [@jderusse](https://twitter.com/jderusse)

---

## JWT - Sécurisez vos APIs

<dl>
  <dt>Description</dt>
  <dd>Les web-services sont aujourd'hui au centre des SI de nos entreprises. Ils permettent de transmettre l'information entre des systèmes hétérogènes, à la fois au sein de l’entreprise mais également à l'extérieur, notamment et de plus en plus vers des systèmes mobiles. Or exposer cette information, potentiellement critique, pose la question de la sécurisation de ces échanges.

Cette présentation sera l'occasion de présenter JWT, d'expliquer son fonctionnement et son implémentation au sein d'un projet Symfony 3.</dd>
</dl>

[Slides](https://blog.webnet.fr/wp-content/uploads/2017/03/2017-03-30-Pr%C3%A9sentation-SymfonyLive-JWT.pdf)  
~~Video~~

By [André Tapia](https://connect.sensiolabs.com/profile/dedeparisg)  
![twitter](icon/twitter.png) [@dedeparisg](https://twitter.com/dedeparisg)

---

## Micro-Services Symfony chez Meetic : retour d’expérience après 2 ans de refonte ! 

<dl>
  <dt>Description</dt>
  <dd>Eté 2015, nous décidons de changer notre stratégie d’architecture en découpant encore plus finement notre nouvelle API monolithique en micro-services Symfony et faisons le choix fort d’effectuer cette refonte en continu, en parallèle des initiatives métiers. Presque 2 ans plus tard, nous souhaitons aujourd’hui revenir sur nos choix techniques avec du recul, vous partager les inquiétudes que nous avions en début de projet et voir si elles sont avérées justes ainsi que vous faire découvrir les surprises que nous avons eues en cours de route !

Nous profiterons de ce vrai retour d’expérience pour aller plus loin que les succès et échecs, en rentrant dans le détail sur de nombreux aspects : de la stratégie de base de données à l’industrialisation d’une architecture µServices en passant par l’implémentation dans Symfony, le monitoring, la performance ou les impacts sur les équipes. Vous saurez tout ce que nous avons appris après 2 ans de refonte et notre dernier talk au SF Live en 2015 !</dd>
</dl>

~~Slides~~  
~~Video~~

By [Etienne Broutin](https://connect.sensiolabs.com/profile/etienneb)

---

## Utiliser Webpack dans une application Symfony

<dl>
  <dt>Description</dt>
  <dd>Depuis la version 2.8 de Symfony, Assetic le gestionnaire d'assets PHP n'est plus inclus par défaut dans la Standard Edition. Du coup, se pose la question, faut-il encore l'utiliser ? Quels sont les alternatives qui s'offrent à nous ?

Au cours de cette présentation, je vous présenterai l'outil Webpack, qui permet de packager nos assets via une configuration. Étape par étape, nous verrons comment migrer une application Symfony utilisant Assetic vers une application Symfony avec Webpack, du dev à la production.</dd>
</dl>

[Slides](https://slideshare.net/alainhippolyte1/utiliser-webpack-dans-une-application-symfony)  
~~Video~~  
[Code](https://github.com/alOneh/sf-live-2017-symfony-webpack)

By [Alain Hippolyte](https://connect.sensiolabs.com/profile/aloneh)  
![github](icon/github.png) [@alOneh](https://github.com/alOneh)  
![twitter](icon/twitter.png) [@Al0ne_H](https://twitter.com/Al0ne_H)

---

## Introduction to CQRS and Event Sourcing

<dl>
  <dt>Description</dt>
  <dd>Command Query Responsibility Segregation et Event Sourcing sont des principes en vogue mais souvent très peu compris. Après avoir présenté cette architecture qui consiste à ne s'occuper que des événements générés par les actions utilisateur (ou non) en lieu et place de l'état final, je vous donnerai les clefs pour démarrer une application Symfony utilisant ces principes, et vous apporterai des conseils et observations après plus d'un an de production avec ce type d'architecture.</dd>
</dl>

[Slides](https://slideshare.net/samuelroze/introduction-to-cqrs-and-event-sourcing-74061563)  
~~Video~~

By [Samuel Roze](https://connect.sensiolabs.com/profile/sroze)  
![github](icon/github.png) [@sroze](https://github.com/sroze)  
![twitter](icon/twitter.png) [@samuelroze](https://twitter.com/samuelroze)

---

## Quoi de neuf dans Symfony depuis un an ?

<dl>
  <dt>Description</dt>
  <dd>Il y a un peu plus d'un an, en novembre 2015 la version 3.0 est sortie. Beaucoup de choses se sont passées depuis ! 71 blog posts pour vous tenir au courant de toutes les nouveautés, plus de 1300 pull requests, 2 nouvelles versions… Je suis sûre que vous avez dû manquer un petit quelque chose ! Nous allons revoir ensemble ce qui est arrivé ; passer en revue les fonctionnalités que vous auriez râtées ou les redécouvrir.</dd>
</dl>

[Slides](https://speakerdeck.com/saro0h/symfonylive-paris-quoi-de-neuf-depuis-1-an)  
~~Video~~

By [Sarah Khalil](https://connect.sensiolabs.com/profile/saro0h)  
![github](icon/github.png) [@saro0h](https://github.com/saro0h)  
![twitter](icon/twitter.png) [@Saro0h](https://twitter.com/Saro0h)

---

## Qui veut gagner une carrière de développeur ?

<dl>
  <dt>Description</dt>
  <dd>Keynote by CommitStrip. Venez assister à la grande première à Paris de cette émission basée sur un format complètement inédit ! Le but : trouver le meilleur job ! Comment ? Le candidat devra répondre à des questions toutes plus techniques les unes que les autres. La technicité et la logique du candidat seront mises à rude épreuve !</dd>
</dl>

~~Slides~~  
~~Video~~

By [Thomas Guenoux](https://connect.sensiolabs.com/profile/thomasgx)  
![twitter](icon/twitter.png) [@thomasgx](https://twitter.com/thomasgx)

---

## Architecture inutile ?

<dl>
  <dt>Description</dt>
  <dd>Symfony offre au développeur PHP une grande souplesse et une puissance certaine. Malgré cela, comme tout outil, il peut être mal utilisé s'il est mal compris, conduisant parfois des projets dans des situations délicates où l'urgence de la production fait inexorablement gonfler la dette technique. Et cette dette technique, elle se paye à terme beaucoup plus cher que l'investissement de départ !

Dans cette présentation nous mettrons en valeur les vertus d'une architecture logicielle réfléchie et pragmatique, exemples réels à l'appui. Nous verrons les outils que Symfony met à notre disposition pour y arriver, les design patterns mis en œuvre et les pièges à éviter. Les "buzzwords" SOLID, KISS, DRY et autres DDD prendront alors tout leur sens !</dd>
</dl>

~~Slides~~  
~~Video~~

By [Jérôme Vieilledent](https://connect.sensiolabs.com/profile/lolautruche)  
![github](icon/github.png) [@lolautruche](https://github.com/lolautruche)  
![twitter](icon/twitter.png) [@jvieilledent](https://twitter.com/jvieilledent)

---

## Déployer une app Symfony dans un PaaS

<dl>
  <dt>Description</dt>
  <dd>SensioCloud, Heroku, OpenShift... Aujourd'hui les solutions PaaS se démocratisent. Permettant de déployer une application et tous ses services dans des conteneurs, elles promettent de simplifier la vie des développeurs en gérant l'infrastructure avec le code.

Mais, au moment de l'utiliser pour l'une de nos applications, de nombreuses problématiques dont certaines propres à Symfony se sont posées : déploiement continu, 0-downtime, gestion du cache / des mots de passe / de la performance, adaptation journalière aux pics de trafic, etc.

Voici comment nous les avons résolues une à une, ce qui a réussi, ce qui a échoué et ce qu'il reste à faire.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Tristan Darricau](https://connect.sensiolabs.com/profile/nicofuma)  
![github](icon/github.png) [@Nicofuma](https://github.com/Nicofuma)  
![twitter](icon/twitter.png) [@Nicofuma](https://twitter.com/Nicofuma)

---

## Sécurité web : et si on continuait à tout casser ?

<dl>
  <dt>Description</dt>
  <dd>Sur le même principe que mon talk de l'année dernière, je vais vous montrer d'autres moyens de casser des sites, dans le but que vous sachiez comment vous protéger par la suite.

Redirect attacks, URL obfuscation, Man-in-the-Middle, Password reuse, premium phone numbers, captcha cracking, insecure direct object reference... sont sûrement des buzzwords que vous avez entendus, mais savez-vous les exploiter ?</dd>
</dl>

~~Slides~~  
~~Video~~

By [Alain Tiemblo](https://connect.sensiolabs.com/profile/ninsuo)  
![github](icon/github.png) [@ninsuo](https://github.com/ninsuo)  
![twitter](icon/twitter.png) [@ninsuo](https://twitter.com/ninsuo)

---

## Créer des webapps modernes avec Symfony, ReactJS et API Platform 

<dl>
  <dt>Description</dt>
  <dd>Découvrez comment utiliser Symfony et API Platform pour créer extrêmement rapidement des applications riches utilisant ReactJS pour leur couche de présentation.

Nous créerons pas à pas une API web 100% fonctionnelle grâce à API Platform, Symfony et Doctrine. Il ne nous faudra que quelques minutes pour la concevoir, et pourtant elle supportera la validation, la pagination, les filtres, l’imbrication de ressources, sera documentée via Swagger et Hydra et disposera d’une interface graphique orientée développeur.

Nous découvrirons ensuite les tout nouveaux outils frontend du projet API Platform :

- Une système d'administration complet (à la Sonata), construit automatiquement en découvrant l’API et bénéficiant d'une interface moderne (Material Design) basée sur React et Redux
- Un générateur de code permettant de créer des interfaces ReactJS en CRUD, à la manière des outils de génération de code fournis par Symfony (mais côté client).</dd>
</dl>

~~Slides~~  
~~Video~~

By [Kévin Dunglas](https://connect.sensiolabs.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## Tout ce qu'un dev devrait savoir à propos d'Unicode

<dl>
  <dt>Description</dt>
  <dd>UTF-8, charsets, points de code, glyphes, CLDR, etc. Tout le monde connaît quelques mots des vocabulaires Unicode. Cette norme mondiale rassemble presque toutes les langues écrites sur Terre. Je vous propose de plonger dans ce fantastique projet qui organise tout ces éléments linguistiques et culturels importants de notre époque. Voyons comment nous, les développeurs, avons le privilège de jouer avec ces derniers au niveau technique. Comment cela marche-t-il? Comment cela s'applique-t-il aux applications que nous créons? Avez-vous entendu parler de collations ? Translitérations ? Grapheme Clusters ? NFC ? Laissez-vous guider.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Nicolas Grekas](https://connect.sensiolabs.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## Optimisations de performances avec PHP 7

<dl>
  <dt>Description</dt>
  <dd>PHP 7 a vu son moteur retapé en profondeur. Et les performances de cette version du langage sont sensiblement plus élevées que les versions précédentes.

Nous allons voir ce qui a changé dans le moteur de PHP pour obtenir de tels niveaux de performances, et comment l'utilisateur peut en tirer parti dans son code.

Nous parlerons de OPCache, du nouveau compilateur de PHP, du nouveau design des tableaux, de la nouvelle machine virtuelle et de toutes les optimisations que l'on peut utiliser, lorsqu'on les connait, en tant que développeur PHP.

Nous utiliserons à la fois PHP 7.0 et PHP 7.1, et nous lâcherons quelques mots sur le futur de PHP en terme de performances pour savoir à quoi s'attendre dans les années à venir.</dd>
</dl>

[Slides](https://slideshare.net/OriPekelman/construire-des-applications-cloud-natives-symfonylive-paris-2016)  
[Video](https://youtu.be/63wHVLvWYM4)

By [Julien Pauli](https://connect.sensiolabs.com/profile/jpauli)  
![github](icon/github.png) [@jpauli](https://github.com/jpauli)  
![twitter](icon/twitter.png) [@julienPauli](https://twitter.com/julienPauli)

---

---

---

# Lightning Talks

## Go, beyond, composer update, Contribute !

~~Slides~~

By [Nicolas Grekas](https://connect.sensiolabs.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)
