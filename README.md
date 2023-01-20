# Super-Mario-RL
Ce projet est une adaptation du projet de Jiseong Hang: https://github.com/jiseongHAN/Super-Mario-RL

Il consiste en la création et l'entrainement d'un agent capable de jouer à Super Mario Bros en utilisant de l'apprentissage par renforcement.

L'agent de ce projet utilise un duel DQN, après TODO épisodes il arrive à atteindre le niveau 3 du jeu.

Créer un nouvel environnement (anaconda):  
conda create --name rl-mario python==3.8  
  
Activer l'environnement:  
conda activate rl-mario  

Pour installer les dépendances:  
pip install -r requirements.txt  

Installer ipykernel:  
conda install -c anaconda ipykernel  
python -m ipykernel install --user --name=rl-mario  

Pour désactiver l'environnement:  
conda deactivate  
  

