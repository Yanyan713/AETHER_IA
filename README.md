# AETHER IA
> # ⚠️ Note : Windows Defender peut afficher une alerte lors du premier lancement.
> Cliquez sur "Plus d'informations" puis "Exécuter quand même" pour continuer.
> Ce programme est sûr et open-source.

# uniquement pour windows
Une intelligence artificielle légère et portable en langage C, conçue pour répondre de manière pertinente à des questions en se basant sur une base de données de phrases (stockée dans `memoire.txt`).

##  Fonctionnalités
- Apprentissage de phrases via commandes simples
- Réponses pertinentes (filtrage de mots vides, score de pertinence)
- Base de données sauvegardée automatiquement dans `memoire.txt`
- Interface console professionnelle et épurée
- Portable (exécutable `.exe` fonctionne sans dépendances sous Windows)

##  Utilisation
### Prérequis
- Windows (l'exécutable est compilé pour Windows ; pour Linux/macOS, recompiler le code source avec `gcc`)
- Aucune installation de logiciel supplémentaire (Dev-C++/compilateur uniquement si tu modifies le code)

### Lancement rapide
1. Télécharge le fichier `AETHER_IA.exe` et `memoire.txt` (même dossier)
2. Double-clique sur `AETHER_IA.exe`
3. Si Windows Defender affiche une alerte :
   - Clique sur « Plus d'informations »
   - Clique sur « Exécuter quand même »

### Commandes disponibles
| Commande       | Description                                      |
|----------------|--------------------------------------------------|
| `\help`        | Affiche l'aide des commandes                     |
| `\texte`       | Enregistre une nouvelle phrase (ex: `\Je suis une IA`) |
| `quit`         | Ferme l'application (sauvegarde automatique)     |

##  Compilation (si vous modifies le code)
### Sous Windows (Dev-C++)
1. Ouvre le fichier `aether_ia.c` dans Dev-C++
2. Compile avec `F9`
3. L'exécutable est généré dans le dossier du projet (`aether_ia.exe`)

### Sous Linux/macOS (GCC)
```bash
gcc aether_ia.c -o aether_ia
./aether_ia

```

### LICENCE
```
MIT License

Copyright (c) 2026 yanyan713

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.```
