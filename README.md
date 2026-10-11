<p align="center"><img src="icones/mascotte.svg" width="150" alt="Proto, la mascotte de Proto"></p>
<h1 align="center">Proto</h1>
<p align="center"><b>Apprendre l'expérience utilisateur et le Design Thinking en jouant : leçons courtes, exercices, défi du jour et révisions espacées.</b></p>
<p align="center">Expérience utilisateur 1 (ExUt1), Marie Kuter, HEIG-VD, BSc Ingénierie des médias</p>
<p align="center"><a href="https://williamdonze.github.io/exput1/"><b>Ouvrir l'appli →</b></a></p>

Une appli façon Duolingo pour réviser le cours : leçons de cinq minutes, exercices interactifs, XP, séries de jours, badges, défi du jour et révisions espacées (les notions ratées reviennent vite, les autres de plus en plus rarement). Elle s'installe sur le téléphone et marche hors connexion ; la progression reste dans le navigateur.

**9 unités · 40 leçons · 567 questions · 45 fiches de théorie · 10 boss** (les exercices du cours).

## Les unités

| | Unité | Ce que tu sauras faire | Boss |
|---|---|---|---|
| 1 | **Qu'est-ce que l'UX ?**<br><sub>Cours 1.1 et 1.2</sub> | Définir l'ergonomie, l'utilisabilité et l'UX (et les distinguer), situer UX et UI, démonter les idées reçues et retracer l'histoire des interfaces. | Étude de cas d'après les cours 1.1 (Introduction) et 1.2 (Historique) |
| 2 | **Concepts-clés et acteurs de l'UX**<br><sub>Cours 1.3 et 1.4</sub> | Expliquer les concepts-clés de l'UX (user-centric, empathie, personas, omnichannel, accessibilité) et situer l'UX dans les équipes et les métiers. | Étude de cas d'après les Cours 1.3 et 1.4 |
| 3 | **Design Thinking et Empathize**<br><sub>Cours 2.1 et 2.2</sub> | Citer et ordonner les 5 phases du Design Thinking, connaître le Design Sprint, et préparer, mener et exploiter une interview, une observation, un journal de bord. | Étude de cas d'après le cours 2.2 (Empathize) |
| 4 | **Define : HMW et empathy map**<br><sub>Cours 3.1, Focus empathy map</sub> | Formuler et juger un HMW (« Comment pourrait-on… de manière à… »), organiser la recherche utilisateurs et construire une empathy map. | Étude de cas d'après le Cours 3.1 et le Focus empathy map |
| 5 | **Personas et design inclusif**<br><sub>Focus personas, UX Conf</sub> | Construire des personas utiles (processus, contenu, conseils), repérer les stéréotypes, et leur préférer des archétypes inclusifs. | Étude de cas d'après le Focus personas et la UX Conf « Design inclusif » (Cours 3.1) |
| 6 | **Ideate**<br><sub>Cours 4.1, Petit manuel anti page blanche</sub> | Distinguer art et design, définir la créativité, animer un brainstorming (règles, techniques : crazy 8, cadavre exquis, dot-voting) et choisir une bonne idée avec les 5 critères. | Étude de cas d'après le cours 4.1 (Ideate) et le Petit manuel anti page blanche |
| 7 | **Prototype**<br><sub>Cours 5.1</sub> | Expliquer les niveaux de conception d'une interface, du paper prototype à la maquette et au prototype, et choisir le bon livrable et le bon outil selon le besoin. | Étude de cas d'après le cours 5.1 (Prototype) |
| 8 | **Tests utilisateurs**<br><sub>Cours 6.1, template de scénario</sub> | Préparer, mener et exploiter un test utilisateur : à quoi il sert, avec combien d'utilisateurs, le scénario de test, le déroulé en 13 étapes (et ce que dit le facilitateur à chacune), puis la suite à donner. | Étude de cas d'après le cours 6.1 (Tests utilisateurs) et le template de scénario de tests utilisateurs |
| 9 | **Examen blanc**<br><sub>Examen théorique sur table</sub> | T'entraîner à l'examen théorique : des questions sur toutes les unités, définitions et chiffres compris, et deux études de cas du HMW au test, sans indice. | Étude de cas transversale d'après les cours 1 à 6 (examen blanc)<br>Étude de cas transversale d'après les cours 3 à 6 (examen blanc) |

## Sur ton téléphone

Ouvre [l'appli](https://williamdonze.github.io/exput1/) sur ton téléphone : après la première leçon, Proto te montre comment l'ajouter à l'écran d'accueil (iPhone : Partager → « Sur l'écran d'accueil » ; Android : « Installer »). Le mode d'emploi est aussi dans Profil.

## Compléter le cours

- **Nouveaux supports** (slides, énoncés, PDF) : dépose-les dans `supports/` (sur GitHub : *Add file → Upload files*), puis, dans une session Claude Code sur ce dépôt, tape **`/ajouter-supports`**. Claude propose les nouvelles unités, tu valides, il les écrit et les teste.
- **Améliorations du moteur** : **`/mettre-a-jour-moteur`** reprend la dernière version du modèle sans toucher au contenu.

## Pour développer

```bash
python3 -m http.server 8765        # puis http://localhost:8765/
python3 tools/valider-contenu.py && python3 tools/tester-exercices.py && python3 tools/test-parcours.py
```

Le contenu est en JSON dans `content/` (une unité par fichier), le format dans `docs/format-contenu.md`, le programme dans `docs/programme.md`.

---

<p align="center"><sub>Créé à partir du <a href="https://github.com/williamdonze/cours-duolingo-template">modèle de cours façon Duolingo</a> de <a href="https://github.com/williamdonze">William Donzé</a>.</sub></p>
