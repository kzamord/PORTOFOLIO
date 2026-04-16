# 🚀 Mon Portfolio Data & BI

Portfolio professionnel Data Analyst / BI Engineer, hébergé sur **GitHub Pages**.

## 🌐 Voir le site en ligne

> `https://kzamord.github.io/PORTOFOLIO`

---

## 📁 Structure du projet

```
portfolio/
├── index.html        ← Page principale (tout-en-un)
└── README.md         ← Ce fichier
```

---

## ⚙️ Déploiement sur GitHub Pages (étape par étape)

### 1. Créer un repo GitHub

1. Aller sur [github.com](https://github.com) → **New repository**
2. Nom du repo : `portfolio` (ou ce que tu veux)
3. Visibilité : **Public** (obligatoire pour GitHub Pages gratuit)
4. Cliquer **Create repository**

### 2. Pousser le code

```bash
# Dans le dossier où tu as téléchargé les fichiers
git init
git add .
git commit -m "🚀 Initial portfolio"
git branch -M main
git remote add origin https://github.com/VOTRE_USERNAME/portfolio.git
git push -u origin main
```

### 3. Activer GitHub Pages

1. Dans ton repo → onglet **Settings**
2. Section **Pages** (menu gauche)
3. Source → **Deploy from a branch**
4. Branch → `main` / `/ (root)`
5. Cliquer **Save**

✅ Ton site sera en ligne en ~2 minutes sur :
`https://VOTRE_USERNAME.github.io/portfolio`

---

## ✏️ Personnaliser le contenu

Ouvre `index.html` et remplace les placeholders :

| Élément | Où chercher |
|---|---|
| Prénom / Nom | Balise `<h1>` dans la section hero |
| Email | `href="mailto:hello@votresite.fr"` |
| LinkedIn | `href="https://linkedin.com/in/votre-profil"` |
| GitHub | `href="https://github.com/votre-profil"` |
| Stats (50+, ×70…) | Section `#about` → `.stat-num` |
| Projets | Section `#projects` → `.project-card` |
| Compétences | Section `#skills` → `.skill-tags` |
| Disponibilité | Hero tag : "Disponible pour missions" |

---

## 🎨 Personnaliser les couleurs

En haut du `<style>` dans `index.html`, modifie les variables CSS :

```css
:root {
  --accent:  #00E5FF;   /* Couleur principale (cyan) */
  --accent2: #7B2FFF;   /* Violet */
  --accent3: #FF3CAC;   /* Rose */
  --bg:      #080B12;   /* Fond principal */
}
```

---

## 🔄 Mettre à jour le site

```bash
git add .
git commit -m "✏️ Mise à jour contenu"
git push
```

Le site se met à jour automatiquement en ~1 minute.
