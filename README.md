# Script Extractor 🚀

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

### ✅ Validation avancée
- **Vérification de l'indentation** : détecte les problèmes d'alignement
- **Vérification de syntaxe** : identifie les erreurs de code basiques
- **Rapport d'erreurs détaillé** : vous indique exactement où se trouvent les problèmes
- **Suggestions de correction** : propose des solutions pour corriger les erreurs

### 💾 Export facile
- Téléchargement direct du script nettoyé
- Génération du fichier avec l'extension appropriée
- Code prêt à être utilisé immédiatement

## 🚀 Comment utiliser

### Étape 1 : Préparer votre texte
Copiez votre conversation contenant le script. Exemple :

```
Utilisateur: Écris-moi un script Python qui affiche "Hello World"

IA: Bien sûr! Voici un script simple:

```python
print("Hello World")
```
```

### Étape 2 : Charger le texte
1. Ouvrez l'application dans votre navigateur
2. Collez votre conversation dans la zone de texte
3. Cliquez sur "Extraire"

### Étape 3 : Vérifier les résultats
L'outil va :
- Extraire tous les scripts trouvés
- Afficher un rapport de validation
- Mettre en évidence les erreurs détectées (s'il y en a)

### Étape 4 : Télécharger
- Cliquez sur "Télécharger" pour récupérer votre script
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
- 📥 Fichier `script.js` prêt à télécharger

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
- Et bien d'autres...

## 🎯 Cas d'usage

- 📚 **Étudiants** : Extraire et valider du code depuis les tutoriels en ligne
- 👨‍💻 **Développeurs** : Récupérer rapidement du code des discussions IA sans erreurs
- 📝 **Documentation** : Valider les snippets avant de les documenter
- 🔧 **Prototypage** : Tester et corriger du code généré par IA
- 🎓 **Formation** : Vérifier les exercices de code des apprenants

## ⚙️ Fonctionnement technique

### Validation d'indentation
L'outil détecte :
- Les espaces/tabs incohérents
- L'indentation non alignée
- Les blocs de code mal structurés

### Vérification de syntaxe
- Parenthèses/crochets/accolades mal fermés
- Guillemets non appairés
- Mots-clés manquants
- Erreurs d'indentation Python

### Rapport d'erreurs
```
⚠️ Erreur ligne 3: Indentation incohérente
ℹ️ Erreur ligne 5: Parenthèse non fermée
✓ Syntaxe globale: OK pour JavaScript
```

## 🎨 Interface utilisateur

- Design épuré et intuitif
- Éditeur de texte avec surlignage
- Aperçu en temps réel
- Messages d'erreur clairs et actionnables
- Boutons de téléchargement visibles

## 📥 Installation

Simplement clonez le repository et ouvrez le fichier HTML dans votre navigateur :

```bash
git clone https://github.com/Richerrail/script_extractor.git
cd script_extractor
```

Ouvrez le fichier `index.html` dans votre navigateur préféré et commencez à extraire des scripts !

## 🌐 Compatibilité

- ✅ Chrome / Edge / Brave
- ✅ Firefox
- ✅ Safari
- ✅ Tous les navigateurs modernes supportant HTML5

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Signaler des bugs
- Proposer de nouvelles fonctionnalités
- Améliorer la validation
- Soumettre des pull requests

## 📄 License

Ce projet est sous license MIT - consultez le fichier [LICENSE](LICENSE) pour plus de détails.

## 👨‍💻 Auteur

**Richerrail**

---

### 💡 Conseils d'utilisation

- Pour de meilleurs résultats, collez le texte entier de la conversation
- Les blocs de code bien formatés (avec ``` ) sont reconnus automatiquement
- Vous pouvez corriger les erreurs avant de télécharger
- Utilisez les rapports d'erreurs pour améliorer votre code

**Fait avec ❤️ pour faciliter votre workflow de développement**
