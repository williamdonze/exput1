# Programme — Proto (Expérience utilisateur 1, HEIG-VD)

Cours **ExUt1 — Expérience utilisateur 1** de Marie Kuter (HEIG-VD, BSc Ingénierie des médias). Supports : export Moodle reçu le 2026-10-11 (registre : `docs/cours/index.md`). Profil : **méthodes et études de cas**, avec une bonne part de **par cœur** (définitions, vocabulaire, étapes). Aucun module (pas de code). Pas de projet dans l'appli (le Hackathon Para-Fake est laissé de côté, consignes non reçues). Une unité **examen blanc** à la fin, pour l'« Examen théorique sur table ».

Avec `docs/format-memo.md`, ce fichier suffit pour écrire chaque unité : lire seulement les fichiers de `docs/cours/` cités dans la section de l'unité.

## Exercices et travaux du cours

Les supports reçus ne contiennent **aucun énoncé d'exercice** : seulement les slides, deux templates (empathy map, scénario de test utilisateur), un template de paper prototype (image) et le « Petit manuel anti page blanche ». Les quizz d'apprentissage Moodle (BUX1, BUX22, BUX23, Ideate), le glossaire, l'examen et le hackathon n'ont pas été reçus.

Les boss sont donc des **études de cas** construites sur les exemples et templates des slides (cas cités tels quels : Connectivity as Aid, agence IT, VTS, HMW « aller au travail », empathy map de David, étude Diverse Personas, 13 étapes du test…), avec en plus **d'autres situations** que celles du cours. Leur `source` dit « Étude de cas d'après le cours X.Y » : jamais présentées comme une consigne de l'enseignante.

## Règles d'écriture propres à ce cours

- Vocabulaire du cours conservé tel quel, y compris en anglais : Empathize, Define, Ideate, Prototype, Test ; HMW (How might we), empathy map, persona, pain-points, user-centric, wireframe, zoning, guerilla testing, crazy 8, dot-voting.
- Définitions **mot pour mot** des slides quand elles existent (ISO 9241, SELF, AIE, Lubart, IxDF) ; ne rien ajouter que les slides ne disent pas.
- Ce que les slides ne couvrent pas n'est **pas** enseigné : en particulier le SUS (System Usability Scale) et le Net Promoter Score, cités dans les objectifs mais absents des slides reçues.
- Les chiffres des slides (5 utilisateurs = 80 % des problèmes, 211 personas / 43 projets, max. 5 personas principaux, interview max. 1 heure, 1,4 million de personnes en situation de handicap en Suisse…) sont de bonnes questions de jeu : la répétition espacée les fera revenir.
- Pas de rédaction libre : les savoir-faire (rédiger un HMW, remplir une empathy map, préparer un test) deviennent des choix (« quel est le meilleur HMW ? »), des tris (« dans quelle zone de l'empathy map ? »), des remises en ordre (étapes) et des repérages d'erreurs (« qu'est-ce qui cloche dans ce persona / cette question d'interview ? »).

## Analogies (toujours les mêmes, d'une unité à l'autre)

1. **Le reporter** (empathie, interviews, observations) : le cours lui-même le dit : « imaginez que vous êtes journaliste, reporter ou que vous souhaitez écrire un livre sur l'histoire de cette personne ». Proto, le renard, part en reportage : il écoute, observe, prend des notes structurées, ne coupe pas la parole.
2. **Le zoom de l'appareil photo** (HMW) : trop large, on ne voit rien de précis (« sauver la planète ») ; trop serré, on ne voit qu'un détail et la solution est déjà dans le cadre (« la voiture, par l'autoroute, à 9 h ») ; le bon HMW cadre juste.
3. **La boussole** (personas, user-centric) : le persona est la boussole de l'équipe tout au long du projet ; on la consulte à chaque décision (plutôt que d'écouter le HIPPO ou le dernier qui a parlé).
4. **Le plan de la maison** (niveaux de conception) : zoning = le plan des pièces en blocs ; wireframe = le plan meublé ; maquette = la maison décorée ; prototype = la visite où l'on passe d'une pièce à l'autre.
5. **Le chef qui fait goûter** (tests et itérations) : on fait goûter le plat tôt et souvent, à quelques personnes ; on teste le plat, pas le goûteur ; un plat corrigé en cuisine coûte moins qu'un plat renvoyé de la salle (coût du changement).

## Difficultés de l'élève (toutes signalées comme importantes) et où elles se travaillent

| difficulté | où |
|---|---|
| Définitions et vocabulaire (UX, utilisabilité, ergonomie, UX vs UI, concepts-clés, acteurs, métiers) | u01, u02 (fiches, jeux d'association), reprises dans tous les quiz et l'examen blanc |
| Les 5 phases et leurs livrables (quelle méthode à quelle étape) | u03 (les 5 phases), puis chaque unité u04 à u08 commence par situer son étape ; jeu de tri « quelle étape ? » en u06, u07, u08 ; examen blanc |
| Interviews et tests utilisateurs (déroulé, DOs / DON'Ts, bonnes questions) | u03 (interviews), u08 (tests) ; boss u03 et u08 |
| Personas et design inclusif (bons / mauvais personas, stéréotypes, archétypes) | u02 (notion), u05 (processus, conseils, Diverse Personas, archétypes) ; boss u05 |

## Fiches : tous les ids du cours (définis une seule fois, ici)

| unité | ids de fiches |
|---|---|
| u01 | `ux`, `ergonomie`, `utilisabilite`, `ux-vs-ui`, `idees-recues-ux`, `historique-interfaces`, `references-ux` |
| u02 | `user-centric`, `empathie`, `persona`, `omnichannel`, `accessibilite`, `acteurs-ux`, `competences-ux` |
| u03 | `design-thinking`, `design-sprint`, `donnees-publiques`, `interview`, `interview-dos-donts`, `observation-ethnographique`, `journal-de-bord` |
| u04 | `hmw`, `recherche-utilisateurs`, `empathy-map`, `empathy-map-processus` |
| u05 | `persona-processus`, `persona-conseils`, `diverse-personas`, `archetypes` |
| u06 | `art-vs-design`, `creativite`, `brainstorming`, `techniques-ideation`, `bonne-idee` |
| u07 | `wireframe`, `paper-prototyping`, `zoning`, `maquette`, `prototype`, `outils-prototypage` |
| u08 | `test-utilisateur`, `guerilla-testing`, `scenario-de-test`, `deroule-test`, `apres-test` |

---

## u01 — Qu'est-ce que l'UX ?
- Objectif : définir l'ergonomie, l'utilisabilité et l'UX (et les distinguer), situer UX et UI, démonter les idées reçues, et retracer l'histoire des interfaces.
- Supports : docs/cours/01-introduction.md (Cours 1.1 Introduction, Cours 1.2 Historique), docs/cours/00-generalites.md (objectifs)
- Fiches : ux (définition du cours + ISO 9241 : avant, pendant, après l'usage), ergonomie (SELF et AIE ; le résultat et le processus), utilisabilite (ISO 9241 : efficacité, efficience, satisfaction, contexte spécifié), ux-vs-ui (l'UX est une démarche, la UI la partie visible ; schéma ergonomie ⊂ utilisabilité ⊂ UX, rationnel / émotionnel), idees-recues-ux (les 3 idées reçues et leurs réponses : « les wireframes, je peux les faire », « le design ça sert à rien », « l'UX c'est très cher »), historique-interfaces (cartes perforées, souris 1963, Altair 1975, Apple I 1976, iPhone 2007, interfaces vocales 2014-2018, AR/VR 2016-2017 ; « pas uniquement une page Web »), references-ux (Nielsen & Norman, Nogier / Usabilis, Bastien & Scapin)
- Notions des unités précédentes à revoir : aucune
- Leçons : 1. Ergonomie, utilisabilité, UX : trois définitions emboîtées 2. UX ou UI ? Les idées reçues 3. Une histoire des interfaces (frise : `ordre`) 4. Mélange
- Jeu : « Vocabulaire de pro » (assoc, vf, qcm sur les définitions et dates), avec `"badge": "memoire"` et `"seuilBadge": 0.8`
- Boss : étude de cas « Convaincre ton équipe » : des collègues répètent les idées reçues (« l'UX, c'est des wireframes », « c'est trop cher », « le design ça sert à rien ») ; choisir les bons arguments du cours (Cours 1.1), et situer des produits non-Web (enceinte vocale, appli AR) dans l'UX (Cours 1.2)
- État : écrite, testée

## u02 — Concepts-clés et acteurs de l'UX
- Objectif : expliquer les concepts-clés (user-centric, empathie, personas, omnichannel, accessibilité) et situer l'UX dans les équipes et les métiers.
- Supports : docs/cours/01-introduction.md (Cours 1.3 Concepts-clés, Cours 1.4 Acteurs de l'UX)
- Fiches : user-centric (analyse des besoins et attentes ; utilisateurs réels en contexte réel ; observation vs déclaratif ; user-centric vs HIPPO vs last-one talking), empathie (définition IxDF ; What/How/Why, 5 Whys, bodystorming, journal de bord / photo), persona (définition 1.3 : archétypes fictifs basés sur des utilisateurs réels ; objectifs, quand, qui ; utilisateurs extrêmes), omnichannel (multichannel vs omnichannel, cross-device, miroir vs complément, « Customers don't see channels: they see brands », 84 %), accessibilite (WCAG, A à AAA, handicap permanent ou temporaire, 1,4 million en Suisse), acteurs-ux (qui sont les UX : chiffres ; où on les trouve ; acteurs de la démarche ; l'UX dans l'équipe d'un projet de communication vs d'application), competences-ux (skills vs soft skills ; revenus en Suisse)
- Notions des unités précédentes à revoir : ux, utilisabilite, ux-vs-ui
- Leçons : 1. User-centric et empathie 2. Personas : la boussole 3. Omnichannel et accessibilité 4. Les acteurs et les métiers de l'UX 5. Mélange
- Boss : étude de cas « Le projet d'appli » : une équipe projet d'application (rôles de la slide 1.4) doit trancher une décision (HIPPO ou user-centric ?), choisir des utilisateurs à rencontrer (dont extrêmes), un parcours cross-device, un niveau WCAG ; trier skills et soft skills d'une offre d'emploi fictive
- État : écrite, testée

## u03 — Design Thinking et étape 1 : Empathize
- Objectif : citer et ordonner les 5 phases du Design Thinking, connaître le Design Sprint, et préparer, mener et exploiter une interview, une observation, un journal de bord.
- Supports : docs/cours/02-design-thinking-empathize.md (Cours 2.1, Cours 2.2)
- Fiches : design-thinking (définition ; 5 phases avec leur verbe : comprendre, reformuler, brainstormer, rendre concret et testable, recueillir les feedbacks ; Exploration, Définition, Idéation, Prototypage, Test), design-sprint (5 étapes en 5 jours ; Knapp, Zeratsky, Kowitz, Google Ventures), donnees-publiques (stores, groupes, forums, personnalités ; recherche sur le long terme), interview (questions ouvertes ou précises ; scriptée mais guide ; avant : contenu, logistique, autres ; exemples de questions par catégorie : contexte, motivations, pain-points, ouverture ; après : notes, codes couleur, remerciement), interview-dos-donts (les deux listes, mot pour mot), observation-ethnographique (shadowing ; recul par rapport au déclaratif ; peut contredire les interviews), journal-de-bord (déclaratif mais proche du moment ; photos ; plusieurs jours)
- Notions des unités précédentes à revoir : empathie, user-centric, persona
- Leçons : 1. Les 5 phases du Design Thinking (et le Design Sprint) 2. Empathize : données publiques 3. Préparer une interview 4. Pendant l'interview : DOs et DON'Ts 5. Observer, faire écrire, et après l'interview
- Boss : étude de cas « Le reporter en mission » : les 3 exemples du cours (Connectivity as Aid, agence de services IT, VTS) : quelle méthode, quelle information inattendue, quelle conséquence ; puis une interview à préparer et à mener dans un autre domaine (repérer les DON'Ts dans un compte rendu, classer des questions par catégorie, remettre l'avant / pendant / après dans l'ordre)
- État : écrite, testée

## u04 — Étape 2 : Define (HMW et empathy map)
- Objectif : formuler et juger un HMW (« Comment pourrait-on… de manière à… »), organiser la recherche utilisateurs, et construire une empathy map.
- Supports : docs/cours/03-define.md (Cours 3.1 Define : HMW et empathy map ; Focus empathy map ; Template Empathy Map)
- Fiches : hmw (forme How might we… so that ; ni trop vague ni trop précis ni solution déjà exprimée ; focus sur le problème vs sur sa résolution ; schéma « aller au travail »), recherche-utilisateurs (Temps 1 : recherche « anonyme » de masse vs personnalisée, les listes ; conseils : notes au même endroit, contenus visuels et audio, proxies, demander d'autres contacts, posture de journaliste), empathy-map (définition ; Quoi : intro qui / objectifs, ce qu'elle perçoit : dit, fait, entend, voit, ce qu'elle ressent : ressent, pense ; template Dave Gray : 7 zones, pains et gains ; exemple de David), empathy-map-processus (les 5 étapes : sujet central, mind-map, parties prenantes, écouter, synthétiser ; Temps 1 / Temps 2 ; pas forcément une par personne)
- Notions des unités précédentes à revoir : design-thinking, interview, observation-ethnographique, journal-de-bord, empathie
- Leçons : 1. Le HMW : cadrer le problème 2. Trop vague, trop précis, déjà la solution 3. Récolter : la recherche utilisateurs 4. L'empathy map 5. Mélange
- Boss : étude de cas « De la recherche au problème » : l'empathy map de David (exemple du cours) : ranger les indices dans les zones ; puis un autre sujet : trier des notes d'interview dans l'empathy map, choisir le meilleur HMW parmi des candidats trop vagues / trop précis / déjà orientés solution
- État : écrite, testée

## u05 — Personas et design inclusif
- Objectif : construire des personas utiles (processus, contenu, conseils), repérer les stéréotypes, et leur préférer des archétypes inclusifs.
- Supports : docs/cours/03-define.md (Cours 3.1 Define : partie Persona ; Focus personas ; UX Conf : Design inclusif)
- Fiches : persona-processus (les 5 étapes : identifier, lister pain-points / motivations / attitudes / contextes, clusters, personnage fictif, prioriser max. 5 principaux ; Temps 1 à 6 ; proto-personas), persona-conseils (contenu du persona : empathie, visuel, citation, à propos, contexte, écosystème, attitude, besoins, pain-points, motivations, expérience souhaitée ; les 6 conseils), diverse-personas (étude Marie Kuter 2023, 211 personas, 43 projets, UX Conf Paris ; représentativité et représentation ; chiffres clés ; conclusions et causes probables ; les deux stéréotypes), archetypes (isoler les données individuelles ; garder pain-points, motivations, contexte, attitudes ; illustrer le contexte ; icônes de handicap ; tranches de vie ; NN/g)
- Notions des unités précédentes à revoir : persona, empathy-map, recherche-utilisateurs, accessibilite
- Leçons : 1. Fabriquer un persona en 5 étapes 2. Ce qu'on met (et ce qu'on enlève) 3. Diverse Personas : ce que révèlent 211 personas 4. Les archétypes 5. Mélange
- Boss : étude de cas « Audit de personas » : une série de personas d'un projet (autre domaine que le cours) : repérer ce qui contredit les conseils et les biais de l'étude (visuel « beau », données socio-démographiques préjugées, stéréotypes, plus de 5 principaux…), puis choisir comment les transformer en archétypes
- État : écrite, testée

## u06 — Étape 3 : Ideate
- Objectif : distinguer art et design, définir la créativité, animer un brainstorming (règles, techniques) et choisir une bonne idée.
- Supports : docs/cours/04-ideate.md (Cours 4.1 Ideate, Petit manuel anti page blanche)
- Fiches : art-vs-design (le message d'abord vs la fonction avant tout ; « la forme suit la fonction » ; Tinguely vs Starck), creativite (définition de Lubart : nouvelle et adaptée au contexte ; « vous êtes tous créatifs »), brainstorming (3 buts avec leurs citations ; les règles de base ; de la quantité à la qualité), techniques-ideation (crazy 8, 3-2-1 « cadavre exquis », dot-voting ; Petit manuel anti page blanche : HMW, associations d'idées, « que diraient les autres ? », inspiration chez les autres ; tout le monde peut sketcher), bonne-idee (les 5 critères ; de l'idée au concept au produit)
- Notions des unités précédentes à revoir : hmw, persona, design-thinking
- Leçons : 1. Art ou design ? La créativité 2. Les règles du brainstorming 3. Diverger puis converger : crazy 8, cadavre exquis, dot-voting 4. Qu'est-ce qu'une bonne idée ? 5. Mélange (et « quelle étape du Design Thinking ? »)
- Boss : étude de cas « L'atelier d'idéation » : animer un brainstorming à partir d'un HMW (autre domaine) : repérer les comportements contraires aux règles, remettre les étapes dans l'ordre (manuel anti page blanche, crazy 8, dot-voting), juger des idées avec les 5 critères
- État : écrite, testée

## u07 — Étape 4 : Prototype
- Objectif : expliquer les niveaux de conception d'une interface, du zoning au prototype, et choisir le bon livrable et le bon outil selon le besoin.
- Supports : docs/cours/05-prototype.md (Cours 5.1 Prototype)
- Fiches : wireframe (définition générale « fil de fer » ; l'étape wireframe : blocs détaillés, contenus, widgets ; la plus adaptée aux feedbacks et tests), paper-prototyping (papier et stylos ; explorer, quantité plutôt que finalité ; workshops, co-conception ; templates), zoning (blocs en nuances de gris, une couleur pour cliquables et call-to-action ; document de travail interne ; difficile pour les parties prenantes), maquette (identité graphique, couleurs, alignements, contrastes ; livrable final, brief pour le développement ; passage côté UI), prototype (écrans interreliés, parcours utilisateurs ; wireframes cliquables ; « l'objectif d'un prototype, c'est de tester et faire tester ; ce n'est pas le produit final »), outils-prototypage (Figma : prototypes interactifs, lien partageable, desktop / tablette / mobile ; avancé : Axure et Google Analytics, eye-tracking ; Lovable, Figma Make ; alternatives : storyboard, jeu de rôle, slides, low-code / no-code comme Glide, constructions / installations)
- Notions des unités précédentes à revoir : bonne-idee, design-thinking, ux-vs-ui
- Leçons : 1. Du papier d'abord 2. Zoning puis wireframe 3. Maquette et prototype 4. Les outils et les alternatives 5. Mélange (et « quel livrable pour quel besoin ? »)
- Boss : étude de cas « Le bon livrable au bon moment » : pour une appli (autre domaine), choisir à chaque situation le livrable (paper prototype, zoning, wireframe, maquette, prototype cliquable) et l'outil ; remettre les niveaux dans l'ordre ; repérer les erreurs (montrer un zoning à des utilisateurs, maquette avant les tests…)
- État : à écrire

## u08 — Étape 5 : Tests utilisateurs
- Objectif : préparer, mener et exploiter un test utilisateur : objectifs, scénario de test, déroulé en 13 étapes, et suite à donner.
- Supports : docs/cours/06-test.md (Cours 6.1 Tests utilisateurs, Template scénario de tests utilisateurs)
- Fiches : test-utilisateur (définition ; 5 utilisateurs = 80 % des problèmes (NN/g) ; learning launch, tâches à accomplir ; scenario-based vs récolte d'avis ; commenter ses actions ; efficacité, efficience, satisfaction ; à quoi ça sert : les 5 exemples ; coût d'un changement au fil du cycle projet ; le bouton à 300 millions de dollars), guerilla-testing (objectifs, quand, qui, concepts-clés : basé sur un scénario, empathie, timeboxé ; 1 h max structuré vs quelques minutes en guerilla), scenario-de-test (format A4 ; sections : introduction, contexte, tâches, questions spécifiques, subjectives, avec leurs exemples ; les 3 questions d'Avinash Kaushik ; template du cours), deroule-test (les 13 étapes de l'agenda, avec ce qu'on dit à chacune ; avant : recrutement, invitations, rappels, prototype, salle, guide), apres-test (mettre les notes au propre, rassembler, mettre en valeur les points-clés, réunion de débrief, prioriser, plan d'action, décisions, implémentation, nouveau round)
- Notions des unités précédentes à revoir : prototype, persona, interview-dos-donts, utilisabilite
- Leçons : 1. Pourquoi tester (et avec combien d'utilisateurs) 2. Le scénario de test 3. Les 13 étapes du test (1 à 6) 4. Les 13 étapes du test (7 à 13) et après 5. Mélange
- Boss : étude de cas « Le jour du test » : avec le template du cours, préparer le test d'une appli (autre domaine) : remettre l'agenda dans l'ordre, associer chaque phrase du facilitateur à son étape, repérer les erreurs (orienter, tester la personne, avis subjectifs), choisir les bonnes questions par section, puis prioriser les suites
- État : à écrire

## u09 — Examen blanc
- Objectif : s'entraîner à l'« Examen théorique sur table » : des questions de toutes les unités, sans indice.
- Supports : tous les fichiers de docs/cours/ (seulement à travers les fiches déjà écrites). Le format de l'examen n'est **pas connu** (à demander à l'élève ou à l'enseignante) : qcm, vf, assoc, ordre, tri en attendant.
- Fiches : aucune nouvelle (seulement des renvois aux fiches de u01 à u08)
- Notions des unités précédentes à revoir : toutes
- Leçons : aucune ou une seule de méthode (« comment réviser l'examen ») ; l'essentiel est le **quiz** (25 à 30 questions, 3 ou 4 par unité, dont les chiffres et définitions mot pour mot) et deux **boss études de cas transversaux** sans indice (une démarche Design Thinking complète du HMW au test, sur un nouveau sujet)
- État : à écrire
