# "Il y avait vraiment du gâteau":

<br/>
## pair-programming un retour d'expérience

Note: En fait on n'a pas amené de gateau.
Explications de David
un résumé de la structure du talks

1. notre expérience
2. un sondage ms (qui confirme un peu notre expérience)
3. les études académiques.
4. Que Faire.

--

## Andreas Kundig (@andreaskundig) et David Hodgetts (@David_Hodgetts)

![muppetspairprogramming](/images/muppetspairprogramming.jpg)
Note: bio respectives
--

## gongfu.io - pratiquer ensemble pour apprendre

![gung-fu](/images/gung_fu.jpg)

Note: L'idée de gongfu.io est de se voir régulièrement pour travailler en binôme sur un projet avec des technologies qu'on ne maitrise pas encore pour les apprendre. Au départ plusieurs binomes se réunissaient tous les jeudis à 17h30 à uni mail. Nous sommes la seule équipe qui a survécu aux vacances d'été de 2012. Gongfu n'existe plus vraiment, nous nous voyons toujours une fois par semaine, mais ou et quand ça nous arrange.

-- 

## Exquis

- "cadavre exquis" pour des animations javascript
- vanilla js + canvas.
- functions and datastructures over OOP


Note: L'idée du projet est de faire une espèce de cadavre exquis pour des animations javascript. (montrer exquis) 

La technologie que nous voulions explorer était javascript avec canvas. Nous avons utilisé aussi peu de librairies que possible (require.js pour organiser le code, async pour quelques tests). L'idée était aussi de programmer dans un style plutot fonctionnel en évitant les différentes variantes du javascript orienté objet et la chaine des prototypes.

-- 

## Cadre de l'expérience

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
plus de patience, discipline, concentration 

Note:
Travailler à deux sur le meme écran met à l'abri des distractions qui generaient l'autre, on ne va pas interrompre son travail pour consulter ses emails ou les dernieres nouvelles. Un minimum de politesse fait qu'on ne le fait pas non plus avec son téléphone.

L'attention aux détails est multipliée par deux. Seul on ne relirait pas deux fois son code.

La tentation des raccourcis un peu honteux est moins forte quand on se sait observé. Seul on peut se contenter de noms de variables trompeurs, mais on n'essaierait pas de convaincre un autre de les laisser. Et puis on aimerait pas donner une mauvaise impression.

On est moins être tenté par le genre de virtuosité qui crée de la complexité qui sert juste à se prouver qu'on la maitrise, ou à explorer les aspects les plus ésotériques de ses outils.

--
bugs plus faciles à trouver

Note:
Chacun s'oriente avec un modèle mental du systeme, une représentation simplifiée qui permet de réfléchir à l'ensemble sans devoir garder tous les détails dans la tête. Un modèle est nécessairement incomplet, voire faux. Les bugs difficiles à expliquer se produisent justement là ou le modèle mental est le plus approximatif. Un programmeur à la recherche d'un bug apporte avec lui un deuxieme modèle mental, qui peut être assez différent. La confrontation de deux modèles permet de mieux circonscrire les parties du système ou bug pourrait se trouver.

expliquer sa pensée à un autre met en évidence les suppositions sur lesquelles on se base, ce qui permet de les examiner et les remettre en cause. C'est le principe qui guide la fameuse technique du rubber ducking, qui consiste à expliquer le problème à un canard en plastique. Le rubber ducking fonctionne évidemment mieux quand le canard écoute vraiment, qu'il pose des questions et apporte ses propres suggestions.

--
conception (algorithmes, architecture)

Note: meilleure compréhension de questions compliquées. deux points de vue différents sur le meme probleme. meilleure définition du probleme, meilleur eclairages des problèmes potentiels, plus d'idées et d'intuition pour l'aborder, plus d'expérience avec d'autres problèmes à disposition, plus de connaissances.

--
transmission de savoir et exercice de communication

Note: 
vim/emacs
outils, raccourcis claviers
pratiques (plus de petit pas).
notion d'élégance et questions de gout
manière d'approcher les problèmes
manière de structurer le code
verbaliser davantage sa réflexion
négocier sans s'énerver
parfois plus simple de coder un truc que d'essayer de l'expliquer. Ambiguité du language naturel.
bon moyen pour expliquer son code à quelqu'un qui va le reprendre.
comprendre le code d'une librairie
par contre lire un mode d'emploi ou evaluer différentes librairies nous a semblé plus pénible à deux 

--
live code review (better than rubber ducking)

Note:
correction rapide de fautes betes (noms de variables, syntaxe)
meilleure vision des problemes immédiats qu'on va rencontrer
critiques plus facile, moins d'ego ecorné parce que le code appartient aux deux
"the average defect detection rate is only 25 percent for unit testing, 35 percent for function testing, and 45 percent for tegration testing. In contrast, the average effectiveness of design and code inspections are 55 and 60 percent." (Code mplete)
code plus propre
cure impostor syndrome
augmente la confiance en soi
--
motivation++

Note: 
Nous continuons à travailler sur ce projet après plus d'un an, alors que nous avons chacun plein de projets personnels à l'abandon.

Au dela d'un projet c'est une occasion de se voir, et aussi en quelque sorte un engagement auprès de l'autre, qu'on ne voudrait pas laisser tomber.
--

## Bilan (aspects négatifs)

![badpair](/images/spy_vs_spy.jpg)
--

**les bonnes pratiques ne sont pas automatiquement au rendez-vous**

Note:
pas de test unitaires
modules avec responsabilités mal définies 
continuité pas évidente avec des sessions hebdomadaires.
problèmes répétés au niveau de la gestion des test fonctionnels et d'intégration (résolu).

--
toutes les tâches ne se prêtent pas au pair programming

Note:
C'est plus confortable de lire un texte tout seul. Evaluer des produits, lire des modes d'emploi est moins bien à deux.

--
lâcher son partenaire en allant trop vite (in the zone alone)

Note:
Coder peut aussi etre une manière de réfléchir pour trouver une solution. Il arrive qu'en étant absorbé dans une réflexion, on néglige d'expliquer à son partenaire ce qu'on fait pour ne pas perdre le fil, et qu'il reste à regarder sans rien comprendre.

Le pair programming est un bon moyen de transmettre ses connaissances à quelqu'un qui va reprendre son code. Il vaut mieux laisser celui qui connait le moins le code au clavier. S'il n'est pas pilote, il risque d'être submergé par trop d'informations. (expérience à Berne et Olten)
--
un seul committeur
![commit distribution](/images/commit_distribution.jpg)

--
triple programming?

Note:
Nous avons fait une ou deux sessions à trois. Le risque de malentendu nous a semblé plus élevé. Deux peuvent se parler sans se préocupper de la participation du troisieme

--
demande beaucoup d'énérgie, difficile à maintenir sur une longue période

Note:
Nous faisons des sessions de deux heures. Est-ce que nous aurions la force de faire ça huit heures par jour?


--

## 9 mois en remote pair programming
![remote](/images/remote.jpg)

--

**expérience étonement réussie**

![win](/images/epic_win.jpg)

Note:

we each have our keyboard (link to "making software" passage)
aussi efficace que le physical pair programming.
chacun à son écran, on est confortable, plus facile de passer de l'un à l'autre.
pas faire dans un bar
chacun peut chercher de son côté.

--

*notre recette technique*

- teamviewer + skype


--

## Mais qu'en pense-t'-on chez Microsoft?

Pair Programming: What’s in it for Me? (microsoft research 2008)

--
une étude sur les bénéfices et problèmes perçus (sondage).


Note:
took form of a survey sent to a randomly selected 10% of engineers at Microsoft that 22% pair program or have pair programmed in the past.

tried to sort the perceived benefits and problems

--

- 487 sondés
- 106 ont déja pratiqué le PP (21.7%)

--

- 64.4% pense que la pratique fonctionne pour eux
- 62.8% pense que la pratique fonctionne pour leur partenaire
- 48.2% estime que la pratique est bénéfique pour l'équipe 
- 39.2% estime que la pratique est bénéfique pour l'organisation.

Note:
This reflects the grassroots nature of pair programming adoption at Microsoft. Individual teams are trying out pair programming, but are finding it difficult to get management buy-in to spread the practice.


--
## le top ten des bénéfices
<p class="fragment">1. Fewer Bugs</p>
<p class="fragment">2. Spreads Code Understanding</p>
<p class="fragment">3. Higher Quality Code</p>
<p class="fragment">4.Can Learn from Partner</p>
<p class="fragment">5.Better Design</p>
<p class="fragment">6. Constant Code Reviews</p>
<p class="fragment">7. Two Heads are Better than One</p>
<p class="fragment">8.Creativity and Brainstorming</p>
<p class="fragment">9.Better Testing and Debugging</p>
<p class="fragment">10.Improved Morale</p>

Note:
ça ressemble pas mal à notre expérience.

--
“greater un-derstanding of a larger codebase across the team.”
--
“higher quality code in terms of consisten-cy with guidelines.”
--
“quickly ramp-up new members,”
--
enables “users to learn new techniques faster.”
--
“every-one learns constantly from each other.”
--
## le top ten des problèmes

<p class="fragment">1. Cost efficiency</p>
<p class="fragment">2. Scheduling</p>
<p class="fragment">3. Personality clash</p>
<p class="fragment">4. Disagreements</p>
<p class="fragment">5. Skill differences</p>
<p class="fragment">6. Programming style differences</p>
<p class="fragment">7. Hard to find a partner</p>
<p class="fragment">8. Personal style differences</p>
<p class="fragment">9. Distractions</p>
<p class="fragment">10. Misanthropy</p>
<p class="fragment">10. Bad Communication</p>
<p class="fragment">10. Metrics/Hard to Reward Talent</p>


--
“if I have a choice, I can employ one star programmer instead of two programmers who need to code in a pair.”
--
Pairing “reduces the freedom of work hours of individual contributors.” (scheduling)
--
“Many partnerships fail due to personality conflicts,” (personality clash) - “pairs get sick of each other.
--
“Sometimes we waste time on discussion,”
--
“tends to drag the faster/smarter/better person down.”
--
“if the partners‟ abilities are imba-
lanced, it could be that one partner become obsolete in the process.”
--
## le top ten des qualités du bon partenaire

<p class="fragment">1. Complementary Skills</p>
<p class="fragment">2. Flexibility</p>
<p class="fragment">3. Good Communications</p>
<p class="fragment">4. Smart</p>
<p class="fragment">4. Personable</p>
<p class="fragment">6. At Least the Same Skills as Me</p>
<p class="fragment">7. Strong programmer</p>
<p class="fragment">7. Better Skills than Me</p>
<p class="fragment">7. Able to Focus</p>
<p class="fragment">10. Knowledgeable</p>
--
“usually looks at things from a different angle.”
--
“able to think … even [from] a different role (e.g. test and dev together).”
--
“blocks on different things than I do,”
--
“some-one who complements my thinking and skills in terms of technical and design skills.”
--
“willing to cooperate and step away from the PC with me to work on design or other details.”
--
“able to adapt to different working styles.”
--
“good listener,”
--
“articulate,”
--
“enjoy debating and discussing code,”
--
“sense of humor,”
--
“comfortable with people around them.”
--
## le top ten des qualités d'un team qui pratique le PP

<p class="fragment">1. Good Communications</p>
<p class="fragment">2. Complementary Skills</p>
<p class="fragment">3. Compatible Personalities</p>
<p class="fragment">4. Team Works Effectively</p>
<p class="fragment">5. No Ego</p>
<p class="fragment">6. Fast and Efficient</p>
<p class="fragment">7. Flexibility</p>
<p class="fragment">8. Common Goals</p>
<p class="fragment">8. Good Quality</p>
<p class="fragment">10. Same programming skills</p>
<p class="fragment">10. Collaborative</p>
<p class="fragment">10. Work Well Together</p>
--
“Communication, communication, communication.” (this is MS after all ; ))
--
An ideal team “consists of easy-going people who want to listen and share ideas with each other.
--
“A little diversity here is good.”
--
“cooperative personalities, they work well together, rather than trying to compete with one another.”
--
“permissive to mistakes.”
--
## oui mais ça reste de la science molle tous ça!
<br>
**"Making Software: What Really Works, and Why We Believe It"**,  Andy Oram, Greg Wilson, 2010

Note:
"Pair Programming", Laurie Williams

--
### 1. Pair Programmation définition ?
<br>
"one driver, one navigator"


![](/images/pair_chair.jpg)

Note:
driver types at computer or writes a design
navigator observes the work of the driver. Navigator should get typos but also see the long range strategic options.
Both are in constant brainstorm and chatting partners.

--
### 2. L'histoire?

<p class="fragment">**Fred Brooks**, l'auteur de "Mythical man month" évoque un projet qu'il a réalisé en pair à l'époque de ses études: "we produced 1500 lines of defect free code; it ran correctly the first time"</p>

<p class="fragment">**années 80:** on parle de "dynamic duos". Larry Constantine note que: "the code benefited from the thinking of two bright minds and the steady dialog between two trusted programmers"</p>

<p class="fragment">**années 90:** un papier de recherche de Bell Labs "Developing in pairs": "Some problems are bigger than any one individual"</p>

--
### 2. L'histoire?

- **Kent Beck** rend la pratique visible avec XP.

--

### origines XP -> projet c3 Chrysler Comprehensive Compensation System
Note:
1994 remplacer un systeme de gestion de salaire cobol par quelque chose d'orienté objet: un programme en smalltalk 
1996 Kent Beck reprend le projet
Martin Fowler a travaillé dessus à temps partiel
1997 une premiere étape est livrée presque à temps.
Le projet a été développé selon une méthodologie que Kent Beck décrit plus tard dans son livre "Extreme Programming Explained". La méthodologie comprend des bonnes pratiques comme les itérations courtes, les tests unitaires, et aussi le pair programming. C'est le début des méthodes agiles qui sont aujourd'hui devenues tellement populaires qu'on a du mal à se souvenir d'autres méthodologies qui auraient pu exister.

Peu après la première livraison du projet, le "customer representative" démissionne pour cause de burnout et n'est jamais remplacé, le projet s'enlise pendant deux ans, Chrysler décide de revenir à Cobol et de bannir l'extreme programming, avant de changer d'avis un peu plus tard.

burnout of customer representative
--
## pratique rencontrée dans l'industrie

"suitable length for pairing session 1.5h to 4h (pairing can be mentally exhausting)"

--
"frequent pair rotation is beneficial for knowledge spread"
--
"rotating roles (driver, navigator) is important to keep both partners engaged."
--
"possession of keyboard as a subtle effect on decision making, with the driver often being the final decision maker"
--
"frequent switching of the keyboard helps keep both partners engaged."
--
"PP must be structured and organised (proclaimed hours for PP) (space layout, large desk, large screen, wireless mouse and kb, whiteboards, and isolation, pairs make noise)"
--
"teams find code written in PP to be more understandable"
--
"some engineers feel that the benefit is real for more complex tasks. One paper noticed a quality improvement with pairs on complex tasks but no quality on simpler tasks."
--
## oui mais les gains du PP, ça se mesure ?

<p class="fragment">**Laurie Williams:** une pair 15 % plus lent que deux dévs seul, le code sans erreur monte de 70 à 85%. Vu que le testing et le debugging sont lourd et couteux. Le gain est évident.</p>

<p class="fragment">D'autres études montrent des gains certains dans les phases de Design, et le travail sur les parties complexes.</p>

Note:
restons méfiant sur ces études. Difficile de mesurer le code.

--

## en résumé

<p class="fragment">pas de gain de temps</p>
<p class="fragment">mais gain de qualité du code</p>
<p class="fragment">et réduction des risques</p>
<p class="fragment">et cycle plus rapide</p>
<p class="fragment">et esprit d'équipe</p>
<p class="fragment">"you cannot expect faster and better and cheaper."</p>
--

## malgré ces avantage, l'adoption reste basse

<p class="fragment">habitudes du solo programming</p>
<p class="fragment">raisons écononomiques (ça coûte le double)</p>
<p class="fragment">coordination</p>
--
habitudes du solo programming
<p class="fragment">solution:</p>
<p class="fragment">coding dojo, code retreat, petit projet pilote</p>
--
raisons écononomiques
<p class="fragment">solution:</p>
<p class="fragment">commencer petit, gagner une meilleure compréhension de la pratique, projet pilote</p>
--
coordination
<p class="fragment">solution:</p>
<p class="fragment">utiliser les scrum meeting pour dynamiquement créer les pairs en fonction des tâches du jour</p>
--
# conclusion
![dilbert](/images/dilbert-xp.gif)
--
## Références:

- **"Making Software: What Really Works, and Why We Believe It"**,  Andy Oram, Greg Wilson, 2010
- "Pair Programming: What’s in it for Me?", Andrew Begel, Nachiappan Nagappan, 2008
- http://www.pairprogramwith.me/ 












