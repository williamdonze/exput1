<p align="center"><img src="icones/mascotte.svg" width="150" alt="Proto, la mascotte de Proto"></p>
<h1 align="center">Proto</h1>
<p align="center"><b>Apprendre l'expérience utilisateur et le Design Thinking en jouant : leçons courtes, exercices, défi du jour et révisions espacées.</b></p>
<p align="center">Expérience utilisateur 1 (ExUt1), Marie Kuter, HEIG-VD, BSc Ingénierie des médias</p>
<p align="center"><a href="https://williamdonze.github.io/exput1/"><b>Ouvrir l'appli →</b></a></p>

Une appli façon Duolingo pour réviser le cours : leçons de cinq minutes, exercices interactifs, XP, séries de jours, badges, défi du jour et révisions espacées (les notions ratées reviennent vite, les autres de plus en plus rarement). Elle s'installe sur le téléphone et marche hors connexion ; la progression reste dans le navigateur.

**2 unités · 5 leçons · 59 questions · 6 fiches de théorie · 3 boss** (les exercices du cours).

## Les unités

| | Unité | Ce que tu sauras faire | Boss |
|---|---|---|---|
| 1 | **Bien apprendre**<br><sub>Exemple : une unité sans code</sub> | Comprendre pourquoi l'appli te fait répondre plutôt que relire, revenir sur une notion après quelques jours, et mélanger les sujets. À remplacer par la première unité de ton cours. | Exemple d'étude de cas (boss d'un cours sans code) |
| 2 | **Catalogue des exercices**<br><sub>Exemple : un exercice de chaque type</sub> | Voir chaque type d'exercice du moteur en action, avec un exemple réel tiré de ProgWeb 2 (cours de JavaScript). À supprimer ou remplacer dans un vrai cours. | TP Fonctions · exercice 1<br>TP DOM · exercice 1 |

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
