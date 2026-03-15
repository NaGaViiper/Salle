# Système Thomas – Programme d'entraînement

Application web de suivi d'entraînement, installable sur iPhone/Android comme une app native.

---

## 🚀 Mise en ligne sur GitHub Pages (5 minutes)

### 1. Créer le dépôt GitHub
1. Va sur [github.com](https://github.com) et connecte-toi
2. Clique sur **New repository**
3. Nomme-le `thomas-training` (ou ce que tu veux)
4. Laisse-le **Public**
5. Clique **Create repository**

### 2. Uploader les fichiers
1. Dans le dépôt créé, clique **uploading an existing file**
2. Glisse-dépose **tous les fichiers** du dossier `thomas-training` :
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - Le dossier `icons/` avec ses 2 fichiers PNG
3. Clique **Commit changes**

### 3. Activer GitHub Pages
1. Va dans **Settings** → **Pages** (dans le menu de gauche)
2. Sous *Source*, sélectionne **Deploy from a branch**
3. Choisis la branche **main** et le dossier **/ (root)**
4. Clique **Save**
5. Attends ~1 minute, puis l'URL apparaît : `https://TON-USERNAME.github.io/thomas-training/`

---

## 📱 Installer sur iPhone (Safari)

1. Ouvre l'URL GitHub Pages dans **Safari**
2. Appuie sur l'icône **Partager** (carré avec flèche vers le haut)
3. Fais défiler et appuie sur **Sur l'écran d'accueil**
4. Confirme avec **Ajouter**

L'app s'ouvre désormais en plein écran comme une vraie application, **fonctionne hors-ligne**, et toutes tes données sont sauvegardées localement sur ton téléphone.

---

## 💻 Modifier sur ordinateur

Pour modifier l'app, édite simplement le fichier `index.html` avec n'importe quel éditeur de texte (VS Code recommandé).  
Pour voir les changements en direct : ouvre le fichier directement dans ton navigateur.  
Pour mettre à jour l'app en ligne : remplace le fichier sur GitHub (glisser-déposer dans le dépôt → Commit changes).

---

## 📦 Structure des fichiers

```
thomas-training/
├── index.html       ← Toute l'application (HTML + CSS + JS)
├── manifest.json    ← Configuration PWA (nom, icône, couleurs)
├── sw.js            ← Service worker (mode hors-ligne)
└── icons/
    ├── icon-192.png ← Icône app (écran d'accueil)
    └── icon-512.png ← Icône app (haute résolution)
```
