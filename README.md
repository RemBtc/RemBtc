# ₿ RemBTC — Bitcoin Knowledge Hub

> **Bitcoin only · apprendre & diffuser**

[![Licence MIT](https://img.shields.io/badge/licence-MIT-green)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-orange)](https://rembtc.github.io/RemBtc/)
[![Langues](https://img.shields.io/badge/langues-FR%20%7C%20EN%20%7C%20ES-blue)]()
[![Bitcoin Only](https://img.shields.io/badge/Bitcoin-Only-F7931A)]()

---

## À propos

**RemBTC** est un dépôt open source de ressources éducatives sur Bitcoin.

L'objectif est simple : fournir des ressources pédagogiques claires, rigoureuses et accessibles sur Bitcoin — pas sur les cryptos, pas sur la spéculation. **Bitcoin uniquement.**

Ce dépôt est **mis à jour en continu** : nouvelles ressources, nouveaux modules, nouvelles versions des outils au fil de l'évolution de l'écosystème Bitcoin.

Les outils proposés ici ne sont pas des conseils financiers. Ce sont des ressources pour comprendre ce qu'est Bitcoin : un protocole monétaire pair-à-pair à offre fixe de 21 millions d'unités, conçu pour fonctionner sans autorité centrale.

---

## Outils déployés

### 📚 Bitcoin Knowledge Hub v12

Référentiel de ressources éducatives organisé en **10 catégories** :

| Catégorie | Contenu |
|---|---|
| 🌱 Débutant | Parcours pas-à-pas · 10 étapes |
| 🧠 Monnaie & Économie | Étalon-or, hyperinflations, école autrichienne |
| 📚 Bibliothèque | Livres fondamentaux · Bastiat, Rothbard, Ammous |
| 📍 Sécurité | Self-custody, hardware wallets, 7 niveaux de sécurité |
| 🔬 Cryptographie | SHA256, ECDSA, BIP32/44/84 |
| ⛏️ Minage | Home mining, DATUM Protocol, énergie |
| 📜 Histoire | Cypherpunks, Satoshi, forks |
| ⚡ Lightning | Layer 2, Phoenix, Blink, Nostr |
| 💰 Stratégie | DCA, Buy-Borrow-Die, LTV, BBD Calculator |
| 🎓 Éducation | YouTube, podcasts, outils temps réel |

**→ Fonctionnalités :**
- Interface trilingue **FR / EN / ES** avec persistance localStorage
- Toggle **light / dark** natif
- Sidebar navigation + recherche full-text + filtres par niveau
- Glossaire Bitcoin (~80 termes × 3 langues) avec liens Perplexity
- Suivi de progression par ressource (vu / non vu)
- Hash routing (`#fr-security`, `#en-glossary`, etc.)

🔗 [hub_light_v12.html](https://rembtc.github.io/RemBtc/hub_light_v12.html) · [hub_dark_v12.html](https://rembtc.github.io/RemBtc/hub_dark_v12.html)

---

### 🗺️ Bitcoin Strategy Guide v12

Guide pratique structuré en **9 phases progressives** :

| Phase | Titre |
|---|---|
| 00 🌱 | Débutant — 10 étapes pour démarrer |
| 01 🛡️ | Sécurité informatique — SECU101 |
| 02 ⛏ | Fondations conceptuelles |
| 03 🔐 | Self-custody avancée |
| 04 ⛏️ | Minage Bitcoin — comprendre le PoW |
| 05 ⚡ | Lightning & Layers |
| 06 💰 | Stratégie financière — Buy, Borrow, Die |
| 07 📜 | Économie, philosophie & histoire |
| 08 📡 | Diffusion & onboarding |

**→ Fonctionnalités :**
- Checklist interactive par étape avec persistance localStorage
- Calculateur **LTV / BBD** intégré (avec barre visuelle)
- Iframe spreadsheet BBD (Rajat Soni)
- Badges "Nouveau" sur les modules ajoutés en v12
- Navigation desktop (onglets phases) + mobile (bottom sheet)
- Trilingue **FR / EN / ES**

🔗 [guide_light_v12.html](https://rembtc.github.io/RemBtc/guide_light_v12.html) · [guide_dark_v12.html](https://rembtc.github.io/RemBtc/guide_dark_v12.html)

---

---

## Stack technique

```
React 18 CDN + Babel standalone (JSX in-browser)
Tailwind CSS CDN
localStorage — persistance lang / phase / progression
Hash routing — URLs partageables par catégorie et langue
0 dépendance serveur — fichiers HTML self-contained
```

**Déploiement :** GitHub Pages (push = live en 30 secondes) ou Netlify Drop.

---

## Structure du dépôt

```
RemBtc/
├── index.html                  # Page d'accueil / portail
├── hub_light_v12.html          # Bitcoin Hub (thème clair)
├── hub_dark_v12.html           # Bitcoin Hub (thème sombre)
├── guide_light_v12.html        # Strategy Guide (thème clair)
├── guide_dark_v12.html         # Strategy Guide (thème sombre)
├── hub_guide_v13.html          # Hub + Guide unifié (en cours)
└── README.md
```

---

## Philosophie

Ce projet est bâti sur une conviction simple, empruntée à l'école autrichienne et aux Cypherpunks :

> *La monnaie saine est un droit, pas un privilège. Bitcoin est le seul actif monétaire à offre fixe, sans émetteur contraignable, sans CEO, sans point de contrôle central.*

Les ressources ici ne cherchent pas à "équilibrer" Bitcoin avec d'autres cryptos. Il n'y a pas d'autre côté à présenter. La distinction est simple : Bitcoin est un protocole. Le reste, c'est de la finance.

**Not your keys, not your coins.**

---

## Contribuer

Les contributions sont les bienvenues — en particulier :
- Traductions ou corrections (FR / EN / ES)
- Nouvelles ressources pédagogiques à ajouter
- Bugs ou améliorations UI

Ouvre une issue ou une pull request.

---

## Avertissement

Ce dépôt est fourni **à des fins éducatives uniquement**.
Il ne constitue pas un conseil financier, juridique ou d'investissement.
Fais tes propres recherches. Vérifie par toi-même. *Don't trust, verify.*

---

## Licence

[MIT](LICENSE) — libre de copier, modifier, redistribuer.
