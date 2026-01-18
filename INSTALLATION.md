# 📱 GUIDE D'INSTALLATION - Snake Game PWA

## 🎯 Qu'est-ce qu'une PWA ?
Une Progressive Web App (PWA) est une application web qui s'installe comme une vraie application sur votre téléphone, SANS passer par le Play Store !

## ✨ Avantages :
- ✅ Icône sur l'écran d'accueil
- ✅ Fonctionne hors ligne
- ✅ Plein écran (pas de barre d'adresse)
- ✅ Contrôles tactiles optimisés
- ✅ Aucune autorisation Android nécessaire
- ✅ Installation en 2 minutes

---

## 📲 INSTALLATION SUR ANDROID (Chrome)

### Méthode 1 : Hébergement en ligne (RECOMMANDÉ)

1. **Hébergez les fichiers gratuitement** :
   - Allez sur **GitHub Pages**, **Netlify** ou **Vercel**
   - Uploadez tous les fichiers (HTML, JS, JSON, PNG)
   - Vous obtiendrez une URL (ex: https://votre-nom.github.io/snake)

2. **Sur votre téléphone Android** :
   - Ouvrez Chrome
   - Allez sur l'URL de votre jeu
   - Cliquez sur le menu (⋮) en haut à droite
   - Sélectionnez **"Installer l'application"** ou **"Ajouter à l'écran d'accueil"**
   - Confirmez l'installation

3. **C'est fait !** 🎉
   - L'icône Snake apparaît sur votre écran d'accueil
   - Lancez-le comme n'importe quelle app
   - Jouez même sans connexion !

### Méthode 2 : Test local (pour développeurs)

1. **Installez un serveur HTTP local** :
   ```bash
   # Avec Python
   python3 -m http.server 8000
   ```

2. **Trouvez l'IP de votre ordinateur** :
   - Windows : `ipconfig`
   - Mac/Linux : `ifconfig` ou `ip addr`

3. **Sur votre téléphone** :
   - Connectez-vous au même WiFi
   - Ouvrez Chrome
   - Allez sur `http://[IP-ORDINATEUR]:8000/snake_game.html`
   - Installez comme ci-dessus

---

## 🍎 INSTALLATION SUR iOS (Safari)

1. Ouvrez Safari (PAS Chrome)
2. Allez sur votre URL
3. Cliquez sur l'icône Partage (carré avec flèche)
4. Sélectionnez **"Sur l'écran d'accueil"**
5. Nommez l'app et confirmez

---

## 🌐 HÉBERGEMENT GRATUIT (étape par étape)

### Option A : GitHub Pages (FACILE)

1. **Créez un compte GitHub** (gratuit)
2. **Créez un nouveau repository** :
   - Nom : `snake-game` (ou ce que vous voulez)
   - Public
3. **Uploadez TOUS ces fichiers** :
   - `snake_game.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
4. **Activez GitHub Pages** :
   - Settings → Pages
   - Source : main branch
   - Save
5. **Votre URL** : `https://votre-nom.github.io/snake-game/snake_game.html`

### Option B : Netlify (TRÈS FACILE)

1. Allez sur **netlify.com**
2. Glissez-déposez le dossier contenant tous les fichiers
3. Netlify vous donne une URL instantanément !
4. Vous pouvez personnaliser l'URL dans les paramètres

### Option C : Vercel (RAPIDE)

1. Allez sur **vercel.com**
2. Importez votre projet
3. Déployez en un clic
4. URL fournie automatiquement

---

## 🔧 FICHIERS NÉCESSAIRES

Assurez-vous d'avoir TOUS ces fichiers ensemble :
- ✅ snake_game.html (le jeu)
- ✅ manifest.json (configuration PWA)
- ✅ service-worker.js (mode hors ligne)
- ✅ icon-192.png (petite icône)
- ✅ icon-512.png (grande icône)

---

## ❓ DÉPANNAGE

### "Installer l'application" ne s'affiche pas ?
- ✅ Vérifiez que vous utilisez HTTPS (ou localhost)
- ✅ Assurez-vous que tous les fichiers sont au même endroit
- ✅ Attendez quelques secondes après le chargement
- ✅ Rafraîchissez la page

### L'icône ne s'affiche pas correctement ?
- ✅ Vérifiez que les fichiers PNG sont bien uploadés
- ✅ Désinstallez et réinstallez l'app

### Le jeu ne fonctionne pas hors ligne ?
- ✅ Lancez le jeu une fois avec internet
- ✅ Vérifiez que service-worker.js est bien présent

---

## 🎮 CONTRÔLES

**Sur ordinateur** :
- Flèches du clavier ↑ ↓ ← →
- Ou touches ZQSD

**Sur téléphone** :
- Boutons tactiles ↑ ↓ ← →
- Apparaissent automatiquement sur petit écran

---

## 🎨 PERSONNALISATION

Une fois installé, vous pouvez :
- Changer les couleurs du serpent et de la nourriture
- Régler la vitesse (1 = lent, 10 = ultra rapide)
- Réinitialiser les paramètres par défaut

---

## 💡 ASTUCES

- Commencez à vitesse lente (2-3) pour vous entraîner
- Essayez différentes combinaisons de couleurs
- Le score s'affiche en haut de l'écran
- Évitez les murs et votre propre queue !

---

Amusez-vous bien ! 🐍🎮
