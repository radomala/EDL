# Ligne decommande

## Navigation / Répertoires  
`cd` Change Directory  
`mkdir` Make Directory  
`rm -rf monrep` : ReMove Recursive Force  
`ls` liste le contenu du répertoires


## Les fichiers

-`head -10 monfic` affiche les 10 premières lignes d'un fichiers

-`tail -10 monfic` pour les dernières lignes
- `tail -f monlog` pour voir le fichier s'écrire en temps réél (`ctrl-c` pour arreter)
- `cat monfic` pour le lire dans la console

# Le |
Permet de rediriger la sortie d'une commande vers l'entrée d'une autre
ex :  
`alias | less` permet de paginer la sortie de la commande alias
