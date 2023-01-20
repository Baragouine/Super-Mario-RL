# Super-Mario-RL
Ce projet est une adaptation du projet de Jiseong Hang: https://github.com/jiseongHAN/Super-Mario-RL

Il consiste en la création et l'entrainement d'un agent capable de jouer à Super Mario Bros en utilisant de l'apprentissage par renforcement.

L'agent de ce projet utilise un duel DQN, après TODO épisodes il arrive à atteindre le niveau 3 du jeu.

## Clonage du projet
### Git clone
```bash
git clone https://github.com/Baragouine/Super-Mario-RL.git
```
### Entrer dans le projet
```bash
cd Super-Mario-RL
```

## Créer un nouvel environnement (anaconda):  
```bash
conda create --name rl-mario python==3.8  
```

## Activer l'environnement:  
```bash
conda activate rl-mario  
```

## Installer les dépendances:
```bash
pip install -r requirements.txt  
```

## Installer ipykernel:  
```bash
conda install -c anaconda ipykernel  
python -m ipykernel install --user --name=rl-mario  
```

## Ouvrir le notebook
```bash
jupyter notebook --NotebookApp.max_buffer_size=99999999999999
```

## Instructions
Après avoir ouvert le notebook vous pouvez entrainer le modèle ou bien le tester en exécutant les bonnes cellules.  
Il y a des indications sur les cellules à exécuter au début de chaque bloc, il suffit de les lire pour savoir quelles cellules exécuter pour l'entrainement et quelles cellules exécuter pour le test.

## Pour désactiver l'environnement:  
```bash
conda deactivate  
```

