	# "Il y avait vraiment du gâteau":

<br/>
## pair-programming un retour d'expérience
![dilbert](/images/dilbert-xp.gif)

Note: En fait on n'a pas amené de gateau.
Explications de David
--
## plan

<li class="fragment">qu'est-ce que le pair programming?</li>
<li class="fragment">notre expérience</li>
<li class="fragment">la littérature</li>


Note:

un résumé de la structure du talks

finalement rien sur le remote working.

Pourquoi temps de méfiance (david: expérience scrum beer)

quels bilan tirer de la pratique. Gains mesurables?

0. est-ce que ça vaut la peine
1. définition
2. histoire
1. notre expérience
2.
2. un sondage ms (qui confirme un peu notre expérience)
3. les études académiques.
4. Que Faire.

--
![muppetspairprogramming](/images/muppetspairprogramming.jpg)

**Andreas Kundig** @andreaskundig

**David Hodgetts** @David_Hodgetts

Note: bio respectives

--

# qu'est-ce que le pair programming?

--

## définition (wikipedia)

<p class="fragment">La programmation en binôme (ou pair programming en anglais) est une méthode de travail dans laquelle deux développeurs travaillent ensemble sur la même partie de code, en binôme sur un même poste de travail</p>

<li class="fragment">le premier, appelé pilote (driver), a le clavier. C'est lui qui va travailler sur la portion de code à écrire. 
<li class="fragment">le second, appelé copilote (partner), est là pour l'aider, en suggérant de nouvelles possibilités ou en décelant d'éventuels problèmes.</li>
<p class="fragment">Les rôles s'échangent régulièrement pendant la séance de programmation.</p>

note:

--

### 2. L'histoire

<p class="fragment">**Kent Beck** popularise la pratique avec les méthodologies de l'Extreme Programming...</p>

<p class="fragment">...la pratique est néanmoins plus ancienne:</p>

<p class="fragment">Dans les années 50, **Fred Brooks**, l'auteur de "Mythical man month" évoque un projet qu'il a réalisé en pair à l'époque de ses études: "we produced 1500 lines of defect free code; it ran correctly the first time"</p>

<p class="fragment"> Dans les années 70, **Dick Gabriel**, le concepteur de Common Lisp et "l'inventeur" des patrons de conception évoque des sessions de binomage.</p>

<p class="fragment">Dans les années 80, **Larry Constantine** parle de "dynamic duos".</p>

<p class="fragment">Dans les années 90 **James Coplien**, publie dans un papier de recherche de Bell Labs "Developing in pairs": "Some problems are bigger than any one individual"</p>

Note:
Constantine, human centered computing. structured design. cohesion coupling

Avec l'extreme programming Kent Beck formalise la démarche appliquée dans un projet qui devait remplacer une grosse application cobol par du smalltalk. Après un succès initial et de nombreuses péripéties comme le rachat de l'entreprise, le smalltalk a finalement été remplacé par du cobol.

david. Je viens d'une autre métier. La pratique s'y retrouve sans le nom.

--

# notre expérience

--
## gongfu.io

![gung-fu](/images/gung_fu.jpg)

Note: L'idée de gongfu.io est de se voir régulièrement pour travailler en binôme sur un projet avec des technologies qu'on ne maitrise pas encore pour les apprendre. Au départ plusieurs binomes se réunissaient tous les jeudis à 17h30 à uni mail. Nous sommes la seule équipe qui a survécu aux vacances d'été de 2012. Gongfu n'existe plus vraiment, nous nous voyons toujours une fois par semaine, mais ou et quand ça nous arrange.

-- 

## Exquis
"Cadavre exquis" pour des animations javascript.  
Vanilla js + canvas + un peu de node.js  
Fonctions et structure de donéés favorisé par rapport à l'orienté objet.  


Note: L'idée du projet est de faire une espèce de cadavre exquis pour des animations javascript. (montrer exquis) 

La technologie que nous voulions explorer était javascript avec canvas. Nous avons utilisé aussi peu de librairies que possible (require.js pour organiser le code, async pour quelques tests). L'idée était aussi de programmer dans un style plutot fonctionnel en évitant les différentes variantes du javascript orienté objet et la chaine des prototypes.

-- 

## Cadre de l'expérience

<li class="fragment">Projet personnel: pas de délai, pas d'obligation de résultat.</li>
<li class="fragment">Deux heures par semaine.</li>
<li class="fragment">Dans un bar le plus souvent....</li>
<li class="fragment">...avec un petit laptop.</li>
<li class="fragment">vim, puis sublime, finalement emacs -> aprendre à faire des compromis</li>
<li class="fragment">En remote pour quelques mois.</li>



Note:
A la fin de chaque session, on fixe les buts de la session suivante, qu'on choisit parfois d'ignorer
Les conditions physiques, la gestion de l'espace et du bruit.
être les deux à l'aise avec le même éditeur.
forme d'intimité à gérer.

--

## Bilan 

cerveau + cerveau = ?

![chair](/images/pair_chair.jpg)

Note: 
A priori les cerveaux ne s'additionent pas, on ne fait pas quelqu'un d'intelligent avec plusieurs imbéciles. On n'accélère pas un projet en ajoutant des développeurs et neuf femmes ne font pas un enfant en un mois.
En travaillant à deux sur le même projet, nous avons quand même eu l'impression de disposer de davantage de ressources mentales comme la discipline, la concentration, l'imagination.

-- 
## Aspects positifs
<li class="fragment">Plus de patience, discipline, concentration</li>
<li class="fragment">Bugs plus faciles à trouver</li>
<li class="fragment">Conception (algorithmes, architecture)</li>
<li class="fragment">Transmission de savoir et exercice de communication</li>
<li class="fragment">Live code review (mieux que le rubber ducking)</li>
<li class="fragment">Motivation++</li>

--
## Aspects négatifs
![badpair](/images/spy_vs_spy.jpg)
--
## Aspects négatifs

<li class="fragment">Les bonnes pratiques ne sont pas automatiquement au rendez-vous</li>
<li class="fragment">Toutes les tâches ne se prêtent pas au pair programming</li>
<li class="fragment">Lâcher son partenaire en allant trop vite (in the zone alone)</li>
<li class="fragment">Un seul committeur</li>
<li class="fragment">Triple programming?</li>

--

## L'expérience du remote pair programming

<li class="fragment">Skype (voix uniquement)</li>
<li class="fragment">Teamviewer</li>
<li class="fragment">Et le bilan est très positif</li>


Note:

bilan positif peut-être du à notre setup un peu serré d'habitude (bar + petit laptop)
description de teamviewer (partage de la souris se fait naturellement)
we each have our keyboard (link to "making software" passage)
aussi efficace que le physical pair programming.
chacun à son écran, on est confortable, plus facile de passer de l'un à l'autre.
difficulté du setup en pp physique (gestion de l'espace). perte de contrôle du navigateur.
pas faire dans un bar
chacun peut chercher de son côté.
--

## options techniques (téléprésence)

![tele presence](images/tele_presence.jpg)

Voix ou voix + vidéo

Note: accrocher des ipads avec skype pour simuler la présence
les options et question à se poser pour réussir le remote pp.

--

## options techniques (coding)

<p class="fragment">Screen sharing (team viever, skype, etc.)</p>
<p class="fragment">Terminal sharing (screen, tmux)</p>
<p class="fragment">Funky cloud stuff (floobits, screenhero.com, cloud 9)</p>

--

# littérature
-- 
<br>
### "Pair Programming: What’s in it for Me?" (microsoft research 2008)


Note:
une étude sur les bénéfices et problèmes perçus (sondage).
took form of a survey sent to a randomly selected 10% of engineers at Microsoft that 22% pair program or have pair programmed in the past.

tried to sort the perceived benefits and problems

--

487 Sondés   
106 Ont déja pratiqué le PP (21.7%)  

--

64.4%  pense que la pratique fonctionne pour eux
<p class="fragment">62.8%  pense que la pratique fonctionne pour leur partenaire  </p>
<p class="fragment">48.2%  estime que la pratique est bénéfique pour l'équipe   </p>
<p class="fragment">39.2%  estime que la pratique est bénéfique pour l'organisation.  </p>

Note:
This reflects the grassroots nature of pair programming adoption at Microsoft. Individual teams are trying out pair programming, but are finding it difficult to get management buy-in to spread the practice.
les gens pensent que c'est bien mais qu'il auront de la peine à convaincre l'organisation.

--
## Les bénéfices
<p class="fragment">“greater understanding of a larger codebase across the team.”</p>

<p class="fragment">“higher quality code in terms of consistency with guidelines.”</p>

<p class="fragment">“quickly ramp-up new members,”</p>

<p class="fragment">enables “users to learn new techniques faster.”</p>

<p class="fragment">“every-one learns constantly from each other.”</p>
--
## le top ten 
<p class="fragment">1. Fewer Bugs</p>
<p class="fragment">2. Spreads Code Understanding</p>
<p class="fragment">3. Higher Quality Code</p>
<p class="fragment">4. Can Learn from Partner</p>
<p class="fragment">5. Better Design</p>
<p class="fragment">6. Constant Code Reviews</p>
<p class="fragment">7. Two Heads are Better than One</p>
<p class="fragment">8. Creativity and Brainstorming</p>
<p class="fragment">9. Better Testing and Debugging</p>
<p class="fragment">10. Improved Morale</p>

Note:
ça ressemble pas mal à notre expérience.

--
## Les problèmes

<p class="fragment">“if I have a choice, I can employ one star programmer instead of two programmers who need to code in a pair.”</p>
<p class="fragment">Pairing “reduces the freedom of work hours of individual contributors.” (scheduling)</p>
<p class="fragment">“Many partnerships fail due to personality conflicts,” (personality clash) - “pairs get sick of each other.
</p>
<p class="fragment">“Sometimes we waste time on discussion,”
</p>
<p class="fragment">“tends to drag the faster/smarter/better person down.”</p>
<p class="fragment">“if the partners‟ abilities are imbalanced, it could be that one partner become obsolete in the process.”
</p>
--
## le top ten 

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
## les qualités du bon partenaire
<p class="fragment">“usually looks at things from a different angle.”</p>

<p class="fragment">“able to think … even [from] a different role (e.g. test and dev together).”</p>

<p class="fragment">“blocks on different things than I do,”</p>

<p class="fragment">“some-one who complements my thinking and skills in terms of technical and design skills.”</p>

<p class="fragment">“willing to cooperate and step away from the PC with me to work on design or other details.”</p>

<p class="fragment">“able to adapt to different working styles.”</p>

<p class="fragment">“good listener,”</p>

<p class="fragment">“articulate,”</p>

<p class="fragment">“enjoy debating and discussing code,”</p>

<p class="fragment">“sense of humor,”</p>

<p class="fragment">“comfortable with people around them.”</p>

--
## le top ten

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
## les qualités d'un team qui pratique le PP

<p class="fragment">“Communication, communication, communication.” (this is MS after all ; ))</p>
<p class="fragment">An ideal team “consists of easy-going people who want to listen and share ideas with each other.”</p>
<p class="fragment">“A little diversity here is good.”</p>
<p class="fragment">“cooperative personalities, they work well together, rather than trying to compete with one another.”</p>
<p class="fragment">“permissive to mistakes.”</p>

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
## **"Pair Programming Illuminated"**, Laurie Williams, 2002  
### seven habits of effective pair programmers (Pair Programming Illuminated)
<p class="fragment">take breaks</p>
<p class="fragment">practice humility</p>
<p class="fragment">be confident / be receptive</p>
<p class="fragment">communicate</p>
<p class="fragment">listen</p>
<p class="fragment">be a team player</p>
<p class="fragment">Hone the balance between compromise and standing firm</p>
--

--
### **"Making Software: What Really Works, and Why We Believe It"**,  Andy Oram, Greg Wilson, 2010
--
### A retenir

<p class="fragment">"suitable length for pairing session 1.5h to 4h (pairing can be mentally exhausting)"</p>

<p class="fragment">"frequent pair rotation is beneficial for knowledge spread"</p>

<p class="fragment">"rotating roles (driver, navigator) is important to keep both partners engaged."</p>

<p class="fragment">"possession of keyboard as a subtle effect on decision making, with the driver often being the final decision maker"</p>

<p class="fragment">"frequent switching of the keyboard helps keep both partners engaged."</p>

<p class="fragment">"PP must be structured and organised (proclaimed hours for PP) (space layout, large desk, large screen, wireless mouse and kb, whiteboards, and isolation, pairs make noise)"</p>


--
tête à tête (Pivotal labs)

![tête à tête](/images/tete_a_tete_1.jpg)

--
![tête à tête](/images/tete_a_tete_2.jpg)

Note: les écrans montrent la même chose. c'est une expérience.

--
## oui mais les gains du binômage, ça se mesure?


<p class="fragment">Une même étude, sur un projet nombre de bugs équivalent (entre dev solo et binome), alors que sur un autre projet il y en aurait 6 fois moins</p>

<p class="fragment">39% de bugs en moins pour une autre</p>

<p class="fragment">D'autres études montrent des gains certains dans les phases de Design, et le travail sur les parties complexes.</p>

<p class="fragment">???</p>

--
## Laurie Williams 1999 

<li class="fragment">13 étudiants solo et 28 en binômes (avec une certaine expérience de la programmation).</li>
<li class="fragment">4 travaux pratiques à réaliser.</li>
<li class="fragment">Les pairs passent 15% de tests en plus (90% au lieu de 75%), i.e 0.1/0.25 = 40% de bugs en moins.</li>
<li class="fragment">Les pairs rendent à temps, les solos sont parfois en retard.</li>
<li class="fragment">Les pairs écrivent 20% de code en moins (+ de cohésion  et des classes aux responsabilités mieux définies).</li>
<li class="fragment">Les pairs prennent 15% plus de temps (quand on multiplie par deux). Mais ce n'est pas statistiquement significatif.</li>
--
## Estimation du gain de productivité
Williams combine ses résultats avec des mesures de moyennes tirées d'autres études: 

<li class="fragment">22 lignes de code écrites par heures  </li>
<li class="fragment">6 bugs pour 1000 lignes  </li>
<li class="fragment">1 semaine pour corriger un bug trouvé chez le client  </li>


<p class="fragment">Elle calcule la productivité en lignes de code correctes par heure-personne et obtient:</p>  

<li class="fragment">4.3 en solo </li>
<li class="fragment">7.4 en binome</li>


Note:
restons méfiant sur ces études. Difficile de mesurer le code.
On a lu pour vous certain de ces papers, et c'est pas convainquant.

--

## En résumé

<p class="fragment">Gain de qualité du code</p>
<p class="fragment">Meilleure répartition du savoir</p>
<p class="fragment">Cycle plus rapide</p>
<p class="fragment">Plus de motivation et meilleur esprit d'équipe</p>
--

## malgré ces avantage, l'adoption reste basse

<p class="fragment">Les habitudes du solo programming</p>
<p class="fragment">Les raisons écononomiques ("ça coûte le double")</p>
<p class="fragment">Les difficultés de coordination</p>

--
## Les solutions de Williams
**Les habitudes du solo programming**
<p class="fragment">coding dojo, code retreat, petit projet pilote</p>

Note: pingpong tests.
--
## Les solutions de Williams
**Les raisons écononomiques**

<p class="fragment">Commencer petit, gagner une meilleure compréhension de la pratique, projet pilote</p>
--
## Les solutions de Williams
**Les difficultés de coordination**
<p class="fragment">Meeting quotidien pour dynamiquement créer les paires en fonction des tâches du jour</p>
--
# Conclusion

--
## Références:

- **"Pair Programming Illuminated"**, Laurie Williams, Robert Kessler, 2002
- **"Making Software: What Really Works, and Why We Believe It"**,  Andy Oram, Greg Wilson, 2010
- **"Pair Programming: What’s in it for Me?"**, Andrew Begel, Nachiappan Nagappan, 2008
- http://www.pairprogramwith.me/ 
- http://rubyrogues.com/126-rr-remote-pair-programming-with-sam-livingston-gray/



