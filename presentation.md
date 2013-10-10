# "Il y avait vraiment du gâteau":

<br/>
## pair-programming un retour d'expérience

Note: En fait on n'a pas amené de gateau.
Explications de David

--

## avec Andreas Kundig et David Hodgetts

![muppetspairprogramming.jpg](/images/muppetspairprogramming.jpg)
Note: youpi 
--

## gongfu.io - pratiquer ensemble pour apprendre

<br/>
<iframe src="http://gongfu.io/" width="1000" height="600"></iframe>

Note: L'idée de gongfu.io est de se voir régulièrement pour travailler en binôme sur un projet avec des technologies qu'on ne maitrise pas encore pour les apprendre. Au départ plusieurs binomes se réunissaient tous les jeudis à 17h30 à uni mail. Nous sommes la seule équipe qui a survécu aux vacances d'été de 2012. Gongfu n'existe plus vraiment, nous nous voyons toujours une fois par semaine, mais ou et quand ça nous arrange.



-- 

## Exquis

- espèce de cadavre exquis pour des animations javascript
- vanilla js + canvas.
- functions and datastructures over OOP


Note: L'idée du projet est de faire une espèce de cadavre exquis pour des animations javascript. (montrer exquis) 

La technologie que nous voulions explorer était javascript avec canvas. Nous avons utilisé aussi peu de librairies que possible (require.js pour organiser le code, async pour quelques tests). L'idée était aussi de programmer dans un style plutot fonctionnel en évitant les différentes variantes du javascript orienté objet et la chaine des prototypes.

-- 

## Cadre de l'expérience

<p class="fragment">grow</p>
<p class="fragment">shrink</p>

- projet personnel: pas de délai, pas d'obligation de résultat.
- deux heures par semaine.
- A la fin de chaque session, on fixe les buts de la session suivante, qu'on choisit parfois d'ignorer.


--

## Bilan (aspects positifs)

cerveau + cerveau = ?

Note: 
A priori les cerveaux ne s'additionent pas, on ne fait pas quelqu'un d'intelligent avec plusieurs imbéciles. On n'accélère pas un projet en ajoutant des développeurs et neuf femmes ne font pas un enfant en un mois.
En travaillant à deux sur le même projet, nous avons quand même eu l'impression de disposer de davantage de ressources mentales comme la discipline, la concentration, l'imagination.

-- 
- plus de patience, discipline, concentration 

Note:
Travailler à deux sur le meme écran met à l'abri des distractions qui generaient l'autre, on ne va pas interrompre son travail pour consulter ses emails ou les dernieres nouvelles. Un minimum de politesse fait qu'on ne le fait pas non plus avec son téléphone.

L'attention aux détails est multipliée par deux. Seul on ne relirait pas deux fois son code.

La tentation des raccourcis un peu honteux est moins forte quand on se sait observé. Seul on peut se contenter de noms de variables trompeurs, mais on n'essaierait pas de convaincre un autre de les laisser. Et puis on aimerait pas donner une mauvaise impression.

On est moins être tenté par le genre de virtuosité qui crée de la complexité qui sert juste à se prouver qu'on la maitrise, ou à explorer les aspects les plus ésotériques de ses outils.

--
- bugs plus faciles à trouver

Note:
Chacun s'oriente avec un modèle mental du systeme, une représentation simplifiée qui permet de réfléchir à l'ensemble sans devoir garder tous les détails dans la tête. Un modèle est nécessairement incomplet, voire faux. Les bugs difficiles à expliquer se produisent justement là ou le modèle mental est le plus approximatif. Un programmeur à la recherche d'un bug apporte avec lui un deuxieme modèle mental, qui peut être assez différent. La confrontation de deux modèles permet de mieux circonscrire les parties du système ou bug pourrait se trouver.

expliquer sa pensée à un autre met en évidence les suppositions sur lesquelles on se base, ce qui permet de les examiner et les remettre en cause. C'est le principe qui guide la fameuse technique du rubber ducking, qui consiste à expliquer le problème à un canard en plastique. Le rubber ducking fonctionne évidemment mieux quand le canard écoute vraiment, qu'il pose des questions et apporte ses propres suggestions.

--
- conception (algorithmes, architecture)

Note: meilleure compréhension de questions compliquées. deux points de vue différents sur le meme probleme. meilleure définition du probleme, meilleur eclairages des problèmes potentiels, plus d'idées et d'intuition pour l'aborder, plus d'expérience avec d'autres problèmes à disposition, plus de connaissances.

--
- **transmission de savoir et exercice de communication**
- vim/emacs
- outils, raccourcis claviers
- pratiques (plus de petit pas).
- notion d'élégance et questions de gout
- manière d'approcher les problèmes
- manière de structurer le code
- verbaliser davantage sa réflexion
- négocier sans s'énerver
- parfois plus simple de coder un truc que d'essayer de l'expliquer. Ambiguité du language naturel.
- bon moyen pour expliquer son code à quelqu'un qui va le reprendre.

--
apprendre

Note:
comprendre le code d'une librairie
par contre lire un mode d'emploi ou evaluer différentes librairies nous a semblé plus pénible à deux 

--
- **live code review**
- correction rapide de fautes betes (noms de variables, syntaxe)
- meilleure vision des problemes immédiats qu'on va rencontrer
- critiques plus facile, moins d'ego ecorné parce que le code appartient aux deux
- "the average defect detection rate is only 25 percent for unit testing, 35 percent for function testing, and 45 percent for integration testing. In contrast, the average effectiveness of design and code inspections are 55 and 60 percent." (Code Complete)
- code plus propre
- cure impostor syndrome
- augmente la confiance en soi
--
- motivation

Note: 
Nous continuons à travailler sur ce projet après plus d'un an, alors que nous avons chacun plein de projets personnels à l'abandon.

Au dela d'un projet c'est une occasion de se voir, et aussi en quelque sorte un engagement auprès de l'autre, qu'on ne voudrait pas laisser tomber.
--

## Bilan (aspects négatifs)

![badpair](/images/spy_vs_spy.jpg)
--

- **les bonnes pratiques ne sont pas automatiquement au rendez-vous**
- pas de test unitaires
- modules avec responsabilités mal définies 
- continuité pas évidente avec des sessions hebdomadaires.
- problèmes répétés au niveau de la gestion des test fonctionnels et d'intégration (résolu grâce à Selenium).
--
- toutes les tâches ne se prêtent pas au pair programming

Note:
C'est plus confortable de lire un texte tout seul. Evaluer des produits, lire des modes d'emploi est moins bien à deux.

--
- danger le lâcher son partenaire en allant trop vite

Note:
Coder peut aussi etre une manière de réfléchir pour trouver une solution. Il arrive qu'en étant absorbé dans une réflexion, on néglige d'expliquer à son partenaire ce qu'on fait pour ne pas perdre le fil, et qu'il reste à regarder sans rien comprendre.

Le pair programming est un bon moyen de transmettre ses connaissances à quelqu'un qui va reprendre son code. Il vaut mieux laisser celui qui connait le moins le code au clavier. S'il n'est pas pilote, il risque d'être submergé par trop d'informations. (expérience à Berne et Olten)
--
- un seul committeur
![commit distribution](/images/commit_distribution.jpg)

--
- triple programming?

Note:
Nous avons fait une ou deux sessions à trois. Le risque de malentendu nous a semblé plus élevé. Deux peuvent se parler sans se préocupper de la participation du troisieme

--
- demande une concentration peut-être difficile à tenir sur une longue période

Note:
Nous faisons des sessions de deux heures. Est-ce que nous aurions la force de faire ça huit heures par jour?


--

## 9 mois en remote pair programming

- techno -> facile à mettre en place: (teamviewer + skype)

- souci technique, net absent, 

- pas faire dans un bar

- we each have our keyboard (link to "making software" passage)

- aussi efficace que le physical pair programming.

- chacun à son écran, on est confortable, plus facile de passer de l'un à l'autre.

- refléxion sur l'organisation spatial pour faciliter le process (genre pas de téléphone)

- chacun peut chercher de son côté.

- le bilan est positif.

--

## zoom out Microsoft 

...

--

## définition

## origines

## origines XP -> projet c3 Chrysler Comprehensive Compensation System
Note:
1994 remplacer un systeme de gestion de salaire cobol par quelque chose d'orienté objet: un programme en smalltalk 
1996 Kent Beck reprend le projet
Martin Fowler a travaillé dessus à temps partiel
1997 une premiere étape est livrée presque à temps.
Le projet a été développé selon une méthodologie que Kent Beck décrit plus tard dans son livre "Extreme Programming Explained". La méthodologie comprend des bonnes pratiques comme les itérations courtes, les tests unitaires, et aussi le pair programming. C'est le début des méthodes agiles qui sont aujourd'hui devenues tellement populaires qu'on a du mal à se souvenir d'autres méthodologies qui auraient pu exister.

Peu après la première livraison du projet, le "customer representative" démissionne pour cause de burnout et n'est jamais remplacé, le projet s'enlise pendant deux ans, Chrysler décide de revenir à Cobol et de bannir l'extreme programming, avant de changer d'avis un peu plus tard.

burnout of customer representative


