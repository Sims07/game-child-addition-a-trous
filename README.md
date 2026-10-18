# 🎃 Maths d'Halloween - Additions à Trous (CE2)

Une application web ludique, interactive et festive conçue pour aider les enfants de **CE2** à s'entraîner aux **additions à trous à 2 chiffres**.

Le projet est entièrement contenu dans un seul fichier HTML, sans base de données ni serveur, ce qui le rend idéal pour un déploiement gratuit sur **GitHub Pages**.

---

## 🌟 Fonctionnalités

- 🎃 **Thématique Halloween** : Design attrayant (couleurs orange/violet, animations de fantômes, sons ludiques, confettis).
- 🧮 **Additions à trous (CE2)** : Génération dynamique de calculs à deux chiffres (ex: `.. + 24 = 68` ou `35 + .. = 72`).
- ✍️ **Ardoise Magique Tactile** :
  - Modal plein écran optimisé pour iPhone/iPad et écran tactile.
  - Préremplissage automatique de la soustraction sous forme posée avec colonnes des **Dizaines ($d$)** et **Unités ($u$)** bien espacées.
  - Palette de couleurs de craies et fonction effacer.
- 📱 **Clavier Numérique Adapté** : Ouverture automatique du pavé numérique sur smartphone/tablette (évite les lettres).
- 🏆 **Motivation & Progression** :
  - Compteur de score, combo de bonbons 🍬 et suivi du chaudron magique (10 calculs par partie).
  - Écran de récompense finale avec confettis 🎉.
- ⚙️ **Réglages Personnalisables** :
  - Choix de la position du trou (aléatoire, premier ou deuxième terme).
  - Ajustement de la difficulté (Somme < 50, < 100, ou jusqu'à 150).
  - Activation/Désactivation des effets sonores.

---

## 🚀 Déploiement rapide sur GitHub Pages

1. Créez un nouveau dépôt public sur GitHub (ex: `maths-halloween`).
2. À la racine du dépôt, ajoutez le fichier **`index.html`** fourni.
3. Allez dans **Settings** > **Pages** de votre dépôt GitHub.
4. Dans la section **Source**, sélectionnez la branche `main` (ou `master`) et laissez `/ (root)`.
5. Cliquez sur **Save**.
6. En quelques secondes, votre jeu est accessible en ligne à l'adresse : `https://<votre-pseudo>.github.io/maths-halloween/`

---

## 🛠️ Technologies Utilisées

- **HTML5 / CSS3 / JavaScript (ES6)**
- [Tailwind CSS CDN](https://tailwindcss.com/) — Design moderne et responsive
- [FontAwesome 6](https://fontawesome.com/) — Icônes d'Halloween
- [Canvas Confetti](https://github.com/catdad/canvas-confetti) — Effets visuels de célébration
- **Web Audio API** — Génération de sons d'ambiance intégrés