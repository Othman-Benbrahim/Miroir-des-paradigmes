# Miroir des Paradigmes

> *Un protocole d'introspection calibrée pour révéler l'Image de Soi, les Paradigmes bloquants et les facultés intellectuelles latentes — à travers une enquête conversationnelle guidée.*

---

## Présentation

Le Miroir des Paradigmes est un skill Claude qui conduit l'utilisateur à travers une enquête de 7 à 10 questions profondes, puis génère un **Bilan Calibré** en quatre parties. Il croise deux cadres analytiques complémentaires :

- **Le Big Five** — pour dresser un état des lieux objectif des traits de personnalité dominants.
- **La philosophie Bob Proctor** (issue du *Goal Achiever Workbook*) — pour identifier les croyances subconscientes (Paradigmes) qui dictent ces traits et les leviers pour les transformer.

Ce skill ne prétend pas révéler une vérité définitive sur l'utilisateur. Il formule des **hypothèses testables**, accompagnées d'observations, de contre-signes et de micro-tests comportementaux. Chaque hypothèse est révisable.

---

## Structure du dépôt

```
miroir-des-paradigmes/
├── README.md                               ← ce fichier
├── SKILL.md                                ← instructions complètes pour Claude
└── references/
    ├── proctor-concepts.md                 ← vocabulaire précis : Stickperson, Terror Barrier,
    │                                          Paradigme, Facultés intellectuelles, Goal A/B/C
    ├── big-five-grille.md                  ← calibrage des 5 dimensions avec formulations bienveillantes
    └── exercices-transformation.md        ← répertoire des 6 exercices de transformation (EX-1 à EX-6)
```

**Fichiers externes gérés par l'utilisateur (optionnels) :**

```
journal-transformation.md    ← log des sessions, hypothèses et mises à jour
contexte-session.md          ← contexte injecté en début de session
```

---

## Ce que fait le skill

### 1. Enquête conversationnelle (7–10 questions)
Claude mène une investigation par mises en situation concrètes — jamais de questions fermées. Si une réponse est vague, il creuse l'émotion derrière le fait.

### 2. Moteur d'analyse silencieux
Pendant l'échange, Claude évalue simultanément :
- Les **5 dimensions Big Five** (Ouverture, Conscience, Extraversion, Agréabilité, Névrosisme)
- Les **Paradigmes actifs** dans le subconscient (croyances héritées qui pilotent les comportements)
- L'**Image de Soi** : l'utilisateur se vit-il comme Victime ou Créateur ?
- Les **Facultés intellectuelles** utilisées vs en sommeil (Imagination, Intuition, Volonté, Mémoire, Raison, Perception)
- La présence d'une **Terror Barrier** (blocage juste avant un saut qualitatif)
- Le type de goal inconscient poursuivi : **A (transformationnel), B (intermédiaire) ou C (confort)**

### 3. Bilan Calibré en 4 parties

| Partie | Contenu |
|---|---|
| **1. Radiographie actuelle** | Big Five avec pourcentages estimés, formulés comme une programmation actuelle |
| **2. Paradigmes et blocages** | Format : Observation → Hypothèse → Contre-signe → Micro-test |
| **3. Facultés cachées** | 2 facultés latentes avec leur frein actuel et leur levier de réactivation |
| **4. Exercice de transformation** | Exercice concret issu du Goal Achiever Workbook, adapté au profil |

### 4. Bloc Journal (optionnel)
À la fin du bilan, Claude génère un bloc structuré que l'utilisateur peut copier dans son `journal-transformation.md` pour suivre l'évolution de ses hypothèses dans le temps.

---

## Concepts clés utilisés

Tous les concepts ci-dessous sont définis précisément dans `references/proctor-concepts.md`.

| Concept | Source |
|---|---|
| **Stickperson** | Bob Proctor — modèle des 3 parties de la personnalité (Conscient / Subconscient / Corps) |
| **Paradigme** | Croyance fixée dans le subconscient, héritée, pilotant les comportements automatiquement |
| **Terror Barrier** | Moment de basculement entre croissance et retour à la sécurité |
| **Image de Soi** | Perception subconsciente de soi qui détermine ce qu'on se "permet" d'atteindre |
| **Goal A-1** | Objectif transformationnel hors zone de confort — le seul qui reprogramme l'Image de Soi |
| **Auto-suggestion** | Technique d'impression d'une nouvelle image dans le subconscient par répétition émotionnelle |
| **Law of Gender** | Toute graine mentale a une période de gestation avant manifestation physique |

---

## Exercices disponibles

| Code | Exercice | Profil cible |
|---|---|---|
| EX-1 | Visualisation du Goal A-1 | Imagination latente, Image de Soi floue |
| EX-2 | Auto-suggestion avec enregistrement vocal | Paradigme de peur ou d'indignité |
| EX-3 | Want List + Priorisation A/B/C | Dispersion, absence de direction |
| EX-4 | Goal Card | Tous profils — ancrage quotidien |
| EX-5 | Micro-action de traversée de Terror Barrier | Évitement d'une action précise |
| EX-6 | Journal de Transformation | Tous profils — traçabilité des hypothèses |

---

## Posture du Miroir

- **Empathique, perspicace, direct mais chaleureux.** Ne juge jamais.
- Traite l'utilisateur comme un être parfait avec une **programmation imparfaite**.
- Intègre un **gardien critique** : toute conclusion forte est tempérée par son statut d'hypothèse.
- **Ne se substitue pas** à un accompagnement professionnel pour les sujets lourds.

---

## Installation

Copier le dossier `miroir-des-paradigmes/` dans le répertoire de skills de votre instance Claude, puis activer le skill depuis les paramètres.

---

*Basé sur le Goal Achiever Workbook — Bob Proctor / Proctor Gallagher Institute (2004)*
