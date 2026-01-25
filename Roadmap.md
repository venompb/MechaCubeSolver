# 🗺️ Roadmap — MechaCubeSolver

Cette roadmap décrit les grandes étapes du projet **MechaCubeSolver**.  
Elle est volontairement **indicative** et pourra évoluer au fil de la conception, des tests et des choix techniques.

L’objectif est de garder une vision claire de l’avancement sans se brider.

---

## 🔹 v0.1 — Conception & fondations
*(phase actuelle)*

- [ ] Définition de l’architecture mécanique globale
- [ ] Choix de la forme du socle (MDF, double fond)
- [ ] Définition des angles et positions des 6 colonnes
- [ ] Validation de la position du cube en “diamant”
- [ ] Premiers modèles 3D (supports moteurs, bras, colonnes)
- [ ] Mise en place de la structure du dépôt Git

**Objectif :** poser des bases mécaniques et conceptuelles solides.

---

## 🔹 v0.2 — Prototype mécanique

- [ ] Fabrication du socle en MDF
- [ ] Impression 3D des colonnes et supports moteurs
- [ ] Assemblage mécanique complet (sans électronique)
- [ ] Tests de rigidité et d’alignement
- [ ] Ajustements mécaniques si nécessaire

**Objectif :** obtenir une structure physique stable et fonctionnelle.

---

## 🔹 v0.3 — Électronique & contrôle moteur

- [ ] Conception de la carte d’isolation (optocoupleurs)
- [ ] Intégration du Raspberry Pi
- [ ] Câblage des drivers moteurs (TB6560)
- [ ] Tests de rotation manuelle des axes
- [ ] Mise en place de la ventilation et de l’alimentation

**Objectif :** faire tourner les 6 axes de manière fiable et sécurisée.

---

## 🔹 v0.4 — Logiciel & interface

- [ ] Développement de l’interface graphique en PureBasic
- [ ] Commande manuelle des moteurs
- [ ] Gestion des séquences de mouvements
- [ ] Mode test / debug
- [ ] Communication stable avec le Raspberry Pi

**Objectif :** contrôler proprement la machine via une interface dédiée.

---

## 🔹 v0.5 — Résolution automatique

- [ ] Intégration de l’algorithme de résolution (type Kociemba)
- [ ] Traduction des mouvements en rotations moteurs
- [ ] Calibration fine des angles
- [ ] Premières résolutions complètes
- [ ] Optimisation des mouvements et du temps de résolution

**Objectif :** résoudre un Rubik’s Cube automatiquement.

---

## 🔹 v1.0 — Finalisation & documentation

- [ ] Optimisations mécaniques finales
- [ ] Nettoyage et stabilisation du code
- [ ] Documentation complète du projet
- [ ] Photos, schémas et explications détaillées
- [ ] Publication d’un tutoriel de construction

**Objectif :** proposer un projet abouti, reproductible et partageable.

---

🧩 *MechaCubeSolver est avant tout un projet de passion, évolutif et documenté, mêlant mécanique, électronique et logiciel.*