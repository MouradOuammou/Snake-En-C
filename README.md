# 🐍 Snake-en-C

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Language](https://img.shields.io/badge/language-C-orange.svg)

Un jeu Snake classique développé en C pur, offrant une expérience de jeu nostalgique directement dans votre terminal. Cette implémentation met l'accent sur la performance et la simplicité, tout en offrant une expérience de jeu fluide et agréable.

## 🌟 Caractéristiques

- 🎯 Gameplay fluide et réactif
- 📊 Système de score avancé
- 💾 Sauvegarde des meilleurs scores
- ⚡ Performance optimisée
- 🎨 Interface ASCII artistique
- 🔄 Mode pause
- 🎵 Effets sonores (bips système)

## 🎮 Captures d'écran

```
+----------------------------------+
|              SNAKE               |
|           Score: 139             |
|                                  |
|        ****                      |
|        *  *                      |
|     🍎  *  *                     |
|        *  ********>             |
|        *                        |
|                                  |
+----------------------------------+
```

## 📥 Installation

### Prérequis

- Compilateur GCC
- Terminal compatible ASCII
- Système d'exploitation : Windows/Linux/MacOS

### Compilation

```bash
# Cloner le repository
git clone https://github.com/MouradOuammou/Snake-en-C.git

# Se déplacer dans le dossier
cd Snake-en-C

# Compiler le jeu
gcc snake_game.c -o snake_game.exe
```

## 🎯 Comment Jouer

1. **Lancement du jeu**
   ```bash
   ./snake_game.exe
   ```

2. **Contrôles**
   - `↑` : Déplacer vers le haut
   - `↓` : Déplacer vers le bas
   - `←` : Déplacer vers la gauche
   - `→` : Déplacer vers la droite
   - `P` : Pause
   - `Q` : Quitter
   - `R` : Recommencer (après game over)

3. **Objectifs**
   - Mangez les pommes (🍎) pour grandir
   - Évitez les collisions avec les murs
   - Évitez de vous mordre la queue
   - Battez votre meilleur score !

## 📊 Système de Score

- **Points de base** : 10 points par pomme
- **Bonus de vitesse** : Points bonus basés sur la vitesse de jeu
- **Multiplicateur** : Bonus croissant pour les pommes consécutives
- **High Scores** : Sauvegarde automatique dans `record.txt`

## 📁 Structure du Projet

```
Snake-en-C/
│
├── snake_game.c        # Code source principal
├── snake_game.exe      # Exécutable du jeu
├── introduction.txt    # Message d'introduction et règles
├── record.txt         # Fichier des meilleurs scores
└── README.md          # Documentation
```

## 🔧 Configuration

Le jeu peut être personnalisé en modifiant les constantes dans `snake_game.c` :

```c
#define BOARD_WIDTH 40
#define BOARD_HEIGHT 20
#define INITIAL_SPEED 100
#define MAX_SPEED 50
// ... etc
```

## 💡 Astuces de Jeu

1. Planifiez votre trajectoire à l'avance
2. Utilisez les bords de l'écran stratégiquement
3. Gardez de l'espace pour les manœuvres
4. Attention à votre vitesse croissante

## 🐛 Résolution des Problèmes Courants

- **Le jeu ne se lance pas** : Vérifiez que votre terminal supporte les caractères ASCII
- **Contrôles ne répondent pas** : Assurez-vous que CAPS LOCK est désactivé
- **Affichage déformé** : Ajustez la taille de votre fenêtre de terminal

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez le projet
2. Créez une branche pour votre fonctionnalité
3. Committez vos changements
4. Poussez vers la branche
5. Ouvrez une Pull Request

## 📝 License

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👥 Auteur

- **MouradOuammou** - *Développement initial* - [GitHub](https://github.com/MouradOuammou)

## 🙏 Remerciements

- Inspiration du Snake original de Nokia
- La communauté C pour ses ressources précieuses
- Tous les testeurs qui ont contribué à améliorer le jeu

## 📞 Contact

- GitHub : [@MouradOuammou](https://github.com/MouradOuammou)
- Gmail  : [@MouradOuammou](mouradouammou8@gmail.com)
---
⭐ N'oubliez pas de mettre une étoile si vous aimez ce projet ! ⭐
