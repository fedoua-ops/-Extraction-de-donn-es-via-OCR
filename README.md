# -Extraction-de-donn-es-via-OCR

## Contexte
Ce projet consiste à extraire les textes de l'image `Genova.png`, incluant  les noms des villes, la localisation de ces champs de textes sur l’image et le taux de confiance associés au processus d’extraction/reconnaissance de texte. Le résultat se trouve dans le fichier output.json.
En outre, l'extraction des données de tableau de l'image `2.png` en gardant la même structuration .

##  Description
- `Genova.png` : Image.
- `2.png` : Image d'un tableau.
- `output.json` : les résultats d'extraction de texte  de l'image Genova.png au format JSON.
- `extracted_table.csv` : Fichier CSV contenant les données extraites du tableau de l'image 2.png.
- `requirements.txt` : Liste des dépendances Python nécessaires pour exécuter le projet.

## Prérequis
Pour exécuter ce projet, assurez-vous d'avoir :
- Compte sur google colab ou bien jupyter notebook


## Installation
1. Clonez ce repository :

    git clone https://github.com/-Extraction-de-donn-es-via-OCR.git
    cd -Extraction-de-donn-es-via-OCR

    
2. Installez les dépendances :

    pip install -r requirements.txt
   

##   Exécution 

Exécuter le notebook OCR.ipynb

## Exemple de Résultat JSON
```json
[
    {
        "text": "Camaldoli",
        "confidence": 0.9999,
        "position": {
            "x": 593,
            "y": 157,
            "width": 60,
            "height": 16
        }
    },
    {
        "text": "Gênes",
        "confidence": 0.9999,
        "position": {
            "x": 284,
            "y": 218,
            "width": 76,
            "height": 30
        }
    }
]
