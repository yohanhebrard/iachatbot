# 🕰️ TimeTravel Agency — Webapp Interactive

Webapp pour une agence de voyage temporel fictive, développée dans le cadre du projet supervisé IA M1/M2 — Session 2 : WEBAPP & IA AGENTS.

---

## 👥 Membres du groupe

- Yohan Hebrard
- Tom Candela
- Nils Jaudon
- Mathéo Laurens

---

## 🌐 Liens

- **Webapp déployée** : [https://yohanhebrard.github.io/iachatbot/](https://votre-url.netlify.app)
- **Repository GitHub** : [https://github.com/yohanhebrard/iachatbot.git](https://github.com/votre-repo)

---

## 🛠️ Stack Technique

| Technologie | Usage |
|---|---|
| HTML5 / CSS3 / JavaScript | Structure, style, logique — fichier unique |
| Google Fonts (Cormorant Garamond + Montserrat) | Typographie premium |
| Intersection Observer API | Animations reveal au scroll |
| CSS Animations | Étoiles, horloge rotative, fade-in, typing indicator |
| Netlify / GitHub Pages | Hébergement gratuit |

---

## ✨ Features Implémentées

### Page d'accueil
- Hero section avec animation de fond (étoiles scintillantes + horloge décorative rotative)
- Titre animé avec apparition progressive au chargement
- CTA vers les destinations et le quiz

### Galerie des destinations
- 3 cards interactives avec hover reveal (description + prix + bouton réserver)
- **Paris 1889** — Belle Époque, Exposition Universelle, Tour Eiffel
- **Crétacé −65 Ma** — Dinosaures, nature préhistorique vierge
- **Florence 1504** — Renaissance italienne, Michel-Ange, Léonard de Vinci

### Agent conversationnel (Chatbot Chronos)
- Widget flottant en bas à droite
- Moteur de règles intelligent (fonctionne offline, sans API)
- Répond aux questions sur les destinations, prix, réservation, sécurité, durées
- Indicateur de frappe animé
- Historique de conversation dans la session

### Quiz de recommandation personnalisée (Exercice 3.2)
- 4 questions avec système de scoring pondéré
- Recommande automatiquement la destination idéale selon les réponses
- Description personnalisée du résultat

### UX / Animations
- Fade-in progressif des sections au scroll (Intersection Observer)
- Hover effects sur les cards de destinations
- Navigation sticky avec changement au scroll
- Design responsive mobile-first

---

## 🤖 IA Utilisées

| Usage | Outil / Modèle |
|---|---|
| Génération du code | Claude Sonnet (Anthropic) via claude.ai |
| Chatbot conversationnel | Moteur de règles JS (offline) |
| Visuels des destinations | Génération IA — Session 1 |
| Maquette initiale | Conception assistée IA |

---

## 📁 Structure du Projet

```
timetravel-agency/
│
├── index.html          # Fichier unique (HTML + CSS + JS)
└── README.md           # Documentation technique
```

---

## 🚀 Installation & Déploiement

### Ouvrir en local
Aucune installation requise. Double-cliquer sur `index.html` dans votre navigateur.

### Déployer sur Netlify
1. Aller sur [netlify.com](https://netlify.com)
2. Glisser-déposer le fichier `index.html`
3. L'URL publique est générée instantanément

### Déployer sur GitHub Pages
```bash
git init
git add .
git commit -m "Initial commit"
git push origin main
# Activer GitHub Pages dans les Settings du repo
```

---

## 💬 Prompts Utilisés (Transparence IA)

**Prompt génération initial :**
> "Crée une webapp complète en HTML/CSS/JS pour TimeTravel Agency, une agence de voyage temporel de luxe. Design dark premium avec accents dorés, typographie Cormorant Garamond. Sections : hero animé avec étoiles, about, 3 destinations (Paris 1889, Crétacé, Florence 1504), quiz de recommandation, chatbot flottant, footer."

**Prompt chatbot :**
> "Tu es Chronos, l'assistant virtuel de TimeTravel Agency. Professionnel mais chaleureux, passionné d'histoire. Tu conseilles sur Paris 1889, Crétacé −65 Ma et Florence 1504."

**Prompt quiz :**
> "Quiz de 4 questions avec scoring pondéré pour recommander la destination idéale parmi 3 choix."

---

## 🎨 Choix de Design

- **Palette** : Dark (#080808) avec accents or (#C9A84C) — évoque le luxe et le mystère temporel
- **Typographie** : Cormorant Garamond (titres élégants) + Montserrat (corps lisible)
- **Animations** : Fluides, durée 0.6–0.8s, easing naturel — subtiles et non intrusives
- **Responsive** : Mobile-first, breakpoint à 900px

---

## 📄 Licence

Projet pédagogique — M1/M2 Digital & IA  
Usage non commercial uniquement.

---

*Réalisé avec des outils d'IA générative dans le cadre du cours IA Créatives — Session 2, 2025*
