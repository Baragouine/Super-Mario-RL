# Super-Mario-RL
Ce projet est une adaptation du projet de Jiseong Hang: https://github.com/jiseongHAN/Super-Mario-RL

Il consiste en la création et l'entrainement d'un agent capable de jouer à Super Mario Bros en utilisant de l'apprentissage par renforcement.

L'agent de ce projet utilise un duel DQN, après 29000 épisodes ou 171 heures d'entrainements (bien avant) il arrive à atteindre le niveau 3 du jeu.

<p float="center">
  <img src="/miniature.gif" width="350" />
</p>

## Auteurs
SAID Raoufdine 11502286  
KORICHI Ilyes 11810510  
ABDULLATIEF Noauffal 11803762  
EL AZZOUZI Mohamed 11804134  

## Rapport et vidéo de démonstration
Le rapport est dans le répertoire `doc` au format pdf.  
Une vidéo de démonstration après les 29000 épisodes est disponible sur YouTube à l'url suivante: https://www.youtube.com/watch?v=idIOWg084KQ .  

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
Après avoir ouvert le notebook (SuperMarioBrosRL.ipynb) vous pouvez entrainer le modèle ou bien le tester en exécutant les bonnes cellules.  
Il y a des indications sur les cellules à exécuter au début de chaque bloc, il suffit de les lire pour savoir quelles cellules exécuter pour l'entrainement et quelles cellules exécuter pour le test.

## Modèle pré-entrainer
Dans le répertoire `checkpoints` il y a le modèle pré-entrainer (épisode 29000) et l'historique de notre entraînement.  
Vous n'avez pas besoin de modifier le notebook pour exécuter ce modèle pré-entrainer, exécuter seulement les bonnes cellules.  

## Pour désactiver l'environnement:  
```bash
conda deactivate  
```

## Reference
[Wang, Ziyu, et al. "Dueling network architectures for deep reinforcement learning." International conference on machine learning. PMLR, 2016.](https://arxiv.org/pdf/1511.06581.pdf)
