# OBM — Site gratuit (type Devon Rodriguez) + IA

Ce dépôt contient un **site one‑page** propre, gratuit à héberger, avec :
- Galerie
- Commandes (boutons WhatsApp)
- Shop (liens Payhip/Gumroad)
- Assistant IA (embed)
- À propos + Contact

## 🚀 Hébergement 100% gratuit
### Option A — GitHub Pages
1. Crée un compte GitHub.
2. Nouveau dépôt `obm-site` → **Upload** des fichiers.
3. Réglages → Pages → Source: `main` / root → Enregistrer.
4. Ton site sera en `https://toncompte.github.io/obm-site/`.

### Option B — Netlify
1. Va sur `https://app.netlify.com/` (compte gratuit).
2. Glisse-dépose tout le dossier.
3. Netlify te donne une URL gratuite immédiate.

## 🧠 Assistant IA (gratuit)
- **Hugging Face Spaces + Gradio** : crée un Space (public) avec un chatbot simple (ou FAQ). Dans les settings tu récupères l’URL et l’`<iframe>` à coller dans `index.html` (section Assistant IA).
- **Botpress Cloud** (free) : crée un bot, active le **Webchat**, copie le script d’embed et remplace l’iframe par le script.
- **Chatbase** (free tier) : entraîne sur ton texte (FAQ/prix), copie le code d’embed.

## 💵 Paiements & Shop (gratuit)
- **Payhip** (0 €/mois, commission) : produits physiques / prints / digitaux → colle l’URL dans la section Shop.
- **Gumroad** : même logique (commissions). 
- **WhatsApp** : liens pré-remplis déjà présents. Remplace juste le texte et ajoute ton numéro au format international: `https://wa.me/243XXXXXXXXX?text=...`

## ✍️ Modifier les textes
- Ouvre `index.html`, repère les sections (#galerie, #commandes, #shop, #assistant, #apropos, #contact) et remplace les textes.
- Mets tes images dans `/assets` et remplace `placeholder1.jpg` etc.

## 🔍 SEO rapide
- Modifie `<title>` et la meta `<description>` en haut de `index.html`.
- Ajoute tes liens TikTok/Instagram/YouTube dans la section Contact.

## 🛠 Astuce pro
- Ajoute Google Analytics (gratuit) en collant le script dans `<head>`.
- Pour un nom de domaine plus tard, pointe-le vers Netlify (facile).

— OBM • Art & Mémoire
