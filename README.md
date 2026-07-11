# Script Extractor 🚀

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-Richerrail-blue)](https://github.com/Richerrail/script_extractor)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://richerrail.github.io/script_extractor/)

Un outil puissant pour extraire, valider et télécharger des scripts directement à partir de conversations avec une IA.

## 📋 Description

**Script Extractor** est un extracteur de code intelligent qui vous permet de :

- **Extraire des scripts** depuis des conversations textuelles (discussions avec ChatGPT, Claude, Copilot, etc.)
- **Valider automatiquement** l'indentation et la syntaxe du code
- **Détecter les erreurs** potentielles (indentation incorrecte, balises mal fermées, etc.)
- **Générer des fichiers prêts à télécharger** au format approprié
- **Prendre en charge plusieurs langages** de programmation

## ✨ Fonctionnalités principales

### 🔍 Extraction intelligente
- Reconnaît automatiquement les blocs de code dans vos conversations
- Extrait les scripts JavaScript, Python, HTML, CSS, JSON et bien d'autres
- Préserve le formatage original du code
- Support de multiples blocs de code dans une même conversation

### ✅ Validation avancée
- **Vérification de l'indentation** : détecte les problèmes d'alignement
- **Vérification de syntaxe** : identifie les erreurs de code basiques
- **Rapport d'erreurs détaillé** : vous indique exactement où se trouvent les problèmes
- **Suggestions de correction** : propose des solutions pour corriger les erreurs
- **Analyse en temps réel** : validation instantanée au fur et à mesure de la saisie

### 💾 Export facile
- Téléchargement direct du script nettoyé
- Génération du fichier avec l'extension appropriée
- Code prêt à être utilisé immédiatement
- Support du presse-papiers pour copier rapidement

### 🎯 Nouvelles fonctionnalités
- **Aperçu en temps réel** : visualisez le code extrait avant téléchargement
- **Historique des extractions** : conservation locale des scripts récents
- **Mode sombre** : interface confortable avec thème sombre par défaut
- **Détection automatique du langage** : identification du type de code
- **Correction automatique** : suggestions d'amélioration du code
- **Support du drag-and-drop** : glissez-déposez vos fichiers .txt ou .md
- **Terminal de sortie** : visualisez les logs d'exécution en temps réel

## 📸 Aperçu de l'interface

L'application dispose d'une interface moderne et intuitive :

![Script Extractor Interface](https://github.com/Richerrail/script_extractor/blob/main/assets/screenshot.png?raw=true)

**Caractéristiques de l'UI :**
- Zone de dépôt/chargement avec drag-and-drop
- Éditeur de texte spacieux pour coller vos conversations
- Bouton "Extraire les scripts" bien visible (cyan)
- Terminal de sortie pour voir les rapports en temps réel
- Design épuré avec thème sombre par défaut
- Interface responsive (fonctionne sur tous les appareils)

## 🚀 Comment utiliser

### Étape 1 : Accéder à l'application
Ouvrez directement : 🌐 [https://richerrail.github.io/script_extractor/](https://richerrail.github.io/script_extractor/)

### Étape 2 : Charger votre texte
Vous avez 3 options :
1. **Glissez-déposez** un fichier .txt ou .md sur la zone pointillée en haut
2. **Cliquez sur "parcours"** pour sélectionner un fichier
3. **Collez directement** votre texte dans la zone de saisie

### Étape 3 : Coller votre conversation
Exemple de texte à coller :

```
Utilisateur: Écris-moi un script Python qui affiche "Hello World"

IA: Bien sûr! Voici un script simple:

```python
print("Hello World")
```
```

### Étape 4 : Extraire les scripts
1. Cliquez sur le bouton cyan **"Extraire les scripts"**
2. L'outil analyse automatiquement le contenu
3. Le terminal affiche les résultats en temps réel
4. Les erreurs détectées s'affichent avec leur localisation exacte

### Étape 5 : Vérifier les résultats
L'outil va :
- Extraire tous les scripts trouvés
- Afficher un rapport de validation complet
- Mettre en évidence les erreurs détectées (s'il y en a)
- Proposer les corrections possibles
- Afficher les logs d'exécution dans le terminal

### Étape 6 : Télécharger ou copier
- Cliquez sur **"Télécharger"** pour récupérer votre script en fichier
- Ou utilisez **"Copier"** pour mettre le code dans votre presse-papiers
- Le fichier est généré avec l'extension correcte
- Prêt à être utilisé !

## 📝 Exemple complet

**Entrée :**
```
Je veux un script JavaScript simple.

Réponds avec ceci:

```js
const message = "Hello"
console.log(message)
```

Merci!
```

**Résultat :**
- ✅ Script extrait avec succès
- ✅ Indentation correcte
- ✅ Syntaxe valide
- ✅ Détection du langage : JavaScript
- 📥 Fichier `script.js` prêt à télécharger

**Logs du terminal :**
```
$ En attente d'exécution...
✓ Fichier chargé avec succès
✓ 1 bloc de code détecté
✓ Langage identifié: JavaScript
✓ Validation syntaxique: OK
✓ Fichier "script.js" prêt à télécharger
```

## 🛠️ Langages supportés

- JavaScript / TypeScript
- Python
- HTML / CSS
- JSON
- Java
- C / C++ / C#
- PHP
- Ruby
- Go
- Rust
- SQL
- Markdown
- YAML
- XML
- Et bien d'autres...

## 🎯 Cas d'usage

- 📚 **Étudiants** : Extraire et valider du code depuis les tutoriels en ligne
- 👨‍💻 **Développeurs** : Récupérer rapidement du code des discussions IA sans erreurs
- 📝 **Documentation** : Valider les snippets avant de les documenter
- 🔧 **Prototypage** : Tester et corriger du code généré par IA
- 🎓 **Formation** : Vérifier les exercices de code des apprenants
- 💼 **Code review** : Analyser le code avant incorporation dans le projet

## ⚙️ Fonctionnement technique

### Validation d'indentation
L'outil détecte :
- Les espaces/tabs incohérents
- L'indentation non alignée
- Les blocs de code mal structurés
- Les dédents incorrects en Python

### Vérification de syntaxe
- Parenthèses/crochets/accolades mal fermés
- Guillemets non appairés
- Mots-clés manquants
- Erreurs d'indentation Python
- Balises HTML/XML mal fermées

### Rapport d'erreurs détaillé
```
$ En attente d'exécution...
⚠️ Erreur ligne 3: Indentation incohérente (attendu 4 espaces, trouvé 2)
ℹ️ Erreur ligne 5: Parenthèse non fermée (ouvert ligne 4)
ℹ️ Avertissement ligne 7: Variable inutilisée 'x'
✓ Syntaxe globale: OK pour JavaScript
✓ Fichier prêt à utiliser
```

## 🎨 Interface utilisateur

- **Design épuré et intuitif** : facile à utiliser pour tous les niveaux
- **Thème sombre par défaut** : confortable pour longues sessions
- **Zone de dépôt intéractive** : drag-and-drop ou sélection de fichier
- **Éditeur de texte spacieux** : large zone de saisie avec placeholder utile
- **Boutons d'action évidents** : cyan luminescent, faciles à localiser
- **Terminal de sortie** : logs en temps réel avec couleurs
- **Messages clairs et actionnables** : erreurs faciles à comprendre
- **Interface responsive** : fonctionne parfaitement sur mobile et desktop
- **Adaptation thème système** : respecte vos préférences de contraste

## 📥 Installation

### Option 1 : Utilisation directe (recommandée) ⭐
Accédez simplement au lien suivant dans votre navigateur :
🌐 [https://richerrail.github.io/script_extractor/](https://richerrail.github.io/script_extractor/)

**Aucune installation requise !** L'application fonctionne directement dans votre navigateur.

### Option 2 : Cloner le repository
Si vous souhaitez exécuter l'application localement ou la modifier :

```bash
# Cloner le repository
git clone https://github.com/Richerrail/script_extractor.git
cd script_extractor

# Ouvrir le fichier dans votre navigateur
# Sous Windows
start index.html

# Sous macOS
open index.html

# Sous Linux
xdg-open index.html
```

### Option 3 : Serveur local (optionnel)
Pour une meilleure expérience de développement :

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js/npm (http-server)
npm install -g http-server
http-server

# Avec Ruby
ruby -run -ehttpd . -p8000

# Puis visitez: http://localhost:8000
```

## 🌐 Compatibilité

### Navigateurs supportés
- ✅ Chrome / Chromium 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Brave
- ✅ Opera
- ✅ Tous les navigateurs modernes supportant HTML5/ES6

### Appareils
- ✅ Desktop (Windows, macOS, Linux)
- ✅ Mobile (iOS, Android)
- ✅ Tablette

### Configuration minimale
- Navigateur moderne (2020 ou plus récent)
- JavaScript activé
- Minimum 256 MB de RAM disponible
- Connexion Internet (pour le live demo)

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Signaler des bugs via [Issues](https://github.com/Richerrail/script_extractor/issues)
- Proposer de nouvelles fonctionnalités
- Améliorer la validation et la détection
- Soumettre des pull requests
- Améliorer la documentation

### Processus de contribution
1. **Fork** le projet
2. **Créez une branche** pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. **Commitez** vos changements (`git commit -m 'Add some AmazingFeature'`)
4. **Poussez** vers la branche (`git push origin feature/AmazingFeature`)
5. **Ouvrez une Pull Request**

## 📄 License

Ce projet est sous license **MIT** - consultez le fichier [LICENSE](LICENSE) pour plus de détails.

Vous êtes libre de :
- ✅ Utiliser à titre personnel ou commercial
- ✅ Modifier le code
- ✅ Distribuer le code
- ✅ Utiliser le code en privé

Avec la condition de :
- 📋 Inclure une copie de la license
- 📋 Inclure un notice de copyright

## 👨‍💻 Auteur

**Richerrail**

---

## 💡 Conseils d'utilisation

- Pour de meilleurs résultats, collez le texte **entier** de la conversation
- Les blocs de code bien formatés (avec ``` ) sont reconnus **automatiquement**
- Vous pouvez **corriger les erreurs** avant de télécharger
- Utilisez les **rapports d'erreurs** pour améliorer votre code
- L'outil conserve un **historique local** de vos extractions récentes
- Les fichiers .txt et .md sont supportés pour le **drag-and-drop**
- Utilisez le **terminal** pour comprendre les erreurs en détail

## 🐛 Signaler un bug

Avez-vous trouvé un bug ? Ouvrez une [issue](https://github.com/Richerrail/script_extractor/issues/new) avec :
- **Description détaillée** du problème
- **Étapes pour reproduire** le bug
- **Navigateur et version** utilisés
- **Capture d'écran** (si applicable)
- **Exemple de texte** qui cause le problème

**Template rapide :**
```
### Description
Décrivez le bug ici...

### Étapes pour reproduire
1. ...
2. ...

### Comportement attendu
...

### Comportement actuel
...

### Environnement
- Navigateur: [ex. Chrome 121]
- OS: [ex. Windows 11]
```

## 📮 Feedback et suggestions

Votre feedback est précieux ! Partagez vos idées via :
- [Discussions](https://github.com/Richerrail/script_extractor/discussions)
- [Issues (Feature Request)](https://github.com/Richerrail/script_extractor/issues/new?labels=enhancement)
- Email : feedback@example.com

---

### 🌟 Aimez ce projet ?

N'hésitez pas à :
- ⭐ **Mettre une star** au repository
- 🔗 **Partager** le lien avec vos collègues
- 💬 **Donner votre feedback**
- 🐛 **Signaler des bugs**
- 🚀 **Proposer des améliorations**

---

Forgé dans les flammes des sessions de debug à 3h du mat 🕒🔥 — Pas un outil. Une arme. ⚔️💀

Dernière mise à jour : 2026-07-11
