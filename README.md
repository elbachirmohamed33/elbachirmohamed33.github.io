# 🕌 Sira du Prophète Muhammad ﷺ - Application Éducative Complète

Application web progressive (PWA) dédiée à la biographie complète du Prophète Muhammad ﷺ et au Saint Coran. Une expérience immersive et authentique basée sur les sources islamiques classiques avec des outils éducatifs modernes.

## ✨ Fonctionnalités Principales

### 📖 **Contenu Éducatif Authentique**
- **15 périodes détaillées** de la vie du Prophète ﷺ
- **Quiz interactifs** pour tester les connaissances
- **Cartes historiques** interactives des lieux saints

### 🌍 **Support Français**
- **Français** : Version complète avec toutes les fonctionnalités

### 💰 **Monétisation Respectueuse**
- **Google AdSense** uniquement
- **Publicités non-intrusives** respectant le contenu religieux
- **Mission éducative prioritaire** sur la rentabilité

## 🗂️ Structure de l'Application

```
sira-optimized/
├── app-sira-quran.html       # Application principale PWA (Sira + Coran)
├── index.html                # Page d'accueil (à créer)
├── manifest.json             # Configuration PWA
├── sw.js                     # Service Worker
├── offline.html              # Page hors ligne
├── 
├── # Pages Éducatives
├── carte_interactive.html    # Cartes historiques interactives
├── quiz.html                 # Quiz éducatifs sur la Sira
├── audio.html                # Lecteur audio avec récitations
├── galerie.html             # Galerie historique éducative
├── 
├── # Pages de Support
├── soutenir.html            # Page de donations PayPal
├── boutique.html            # Boutique éducative
├── 
├── # Ressources
├── css/
│   ├── style_optimized.css  # Styles principaux
│   ├── style_premium.css    # Styles avancés
│   └── adsense.css          # Styles publicités
└── # Versions Francais complète
    ├── fr/                  # Version française complète
    ```

## 🎯 Pages Principales

### **Outils Éducatifs**
- **`carte_interactive.html`** - Exploration géographique de l'époque du Prophète ﷺ
- **`quiz.html`** - Tests de connaissances avec 25 questions authentiques

### **Support et Monétisation**
- **`soutenir.html`** - Page de donations PayPal pour soutenir le projet
- **`boutique.html`** - Boutique éducative avec ressources islamiques

## 🚀 Technologies Utilisées

- **HTML5** avec sémantique moderne
- **CSS3** avec animations fluides et design islamique
- **JavaScript ES6+** pour interactivité avancée
- **Service Workers** pour fonctionnalités hors ligne
- **Web App Manifest** pour installation PWA
- **Google AdSense API** pour monétisation respectueuse
- **LocalStorage** pour sauvegarde des préférences utilisateur

## 📋 Installation et Déploiement sur GitHub

### **Étape 1 : Préparer le Repository**

```bash
# Se placer dans le bon dossier
cd "C:\Users\user\Documents\mon site\sira-optimized"

# Initialiser Git (si pas encore fait)
git init

# Créer le fichier .gitignore
echo "node_modules/
.DS_Store
*.log
.env" > .gitignore
```

### **Étape 2 : Créer la Page d'Accueil**

Nous devons créer `index.html` comme point d'entrée :

```bash
# Copier app-sira-quran.html comme page principale
copy app-sira-quran.html index.html
```

### **Étape 3 : Ajouter et Commiter**

```bash
# Ajouter tous les fichiers
git add .

# Premier commit
git commit -m "🕌 Application Sira & Coran - Version complète PWA


### **Étape 4 : Publier sur GitHub**

```bash
# Créer le repository sur GitHub d'abord, puis:
git remote add origin https://github.com/VOTRE-USERNAME/sira-prophete-muhammad.git
git branch -M main  
git push -u origin main
```

### **Étape 5 : Activer GitHub Pages**

1. Aller sur GitHub.com → votre repository
2. **Settings** → **Pages**
3. **Source** : Deploy from a branch
4. **Branch** : main
5. **Folder** : / (root)
6. **Save**

🌐 **Votre site sera disponible sur :** `https://votre-username.github.io/sira-prophete-muhammad/`

## 🔧 Configuration Finale

### **URLs de l'Application**

Une fois déployé, vos pages seront accessibles via :

- **Application principale** : `https://votre-username.github.io/sira-prophete-muhammad/`
- **Sira + Coran** : `https://votre-username.github.io/sira-prophete-muhammad/app-sira-quran.html`
- **Quiz** : `https://votre-username.github.io/sira-prophete-muhammad/quiz.html`
- **Cartes** : `https://votre-username.github.io/sira-prophete-muhammad/carte_interactive.html`
- **Audio** : `https://votre-username.github.io/sira-prophete-muhammad/audio.html`
- **Galerie** : `https://votre-username.github.io/sira-prophete-muhammad/galerie.html`

### **Configuration Google AdSense**

Dans vos fichiers, remplacez `VOTRE-ID` par votre vraie ID AdSense :

```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-VOTRE-ID"></script>
```

## 📊 Fonctionnalités Uniques

### **🕌 Contenu Islamique Authentique**
- Sources vérifiées : Sahih Bukhari, Muslim, Ibn Hisham, At-Tabari
- Approche respectueuse et éducative
- Validation par des scholars qualifiés

### **🎯 Expérience Utilisateur Optimale**
- Design islamique élégant (couleurs vert et or)
- Navigation intuitive et accessible
- Performance optimisée avec cache intelligent
- Support complet du mode hors ligne

### **📱 PWA Complète**
- Installation sur tous appareils (mobile, tablette, desktop)
- Notifications push pour nouvelles fonctionnalités
- Icônes et splash screens personnalisés
- Fonctionnement natif une fois installée

## 🎉 Mission et Impact

Cette application a été développée avec pour mission de :

- **Éduquer** sur la vie du Prophète Muhammad ﷺ de manière authentique
- **Faciliter** l'accès au Saint Coran avec traductions et audio
- **Respecter** les enseignements islamiques dans la présentation
- **Utiliser** les technologies modernes au service de l'éducation religieuse
- **Servir** la communauté musulmane mondiale et ceux qui découvrent l'Islam

## 🤝 Contribution et Support

- **Issues GitHub** pour rapporter des problèmes
- **Pull Requests** bienvenues pour améliorations
- **Respect** du contenu religieux obligatoire
- **Sources authentiques** seulement

## 📄 Licence

Projet sous licence MIT - Libre d'utilisation pour l'éducation islamique.

---

**Qu'Allah ﷻ bénisse ce travail et en fasse un moyen de guidance pour tous. Ameen.**

*Développé avec ❤️ et dévotion pour la Oumma musulmane*

