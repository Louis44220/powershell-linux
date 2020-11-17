# Powershell-Linux 


## Gérer les fichiers/dossiers


Commandes : 

- Se déplacer dans les dossiers : 
    - Set-Location ***dossier*** 
- Afficher le contenu d'un dossier :
    - Get-ChildItem
- Afficher le contenu d'un dossier courant : 
    - Get-Location
- Créer un dossier :
    - New-Item ***'nom du fichier'*** -ItemType Directory 
- Créer un fichier :
    - New-Item ***'nom du fichier'***
- Supprimer un dossier : 
    - Remove-Item ***'nom du fichier'***
- Supprimer un fichier/dossier : 
    - Remove-Item ***'nom du fichier'***
- Renommer un fichier : 
    - Rename-Item ***'nom du fichier'*** -NewName ***'nom du fichier2'*** 
- Copier un fichier : 
    - Copy-Item ***'nom du fichier'*** -Destination ***'nom du fichier2'***
- Déplacer un fichier : 
    - Move-Item ***'nom du fichier'*** -Destination ***'chemin\nom du fichier'***


## Alias

- Créer ses propres raccourci : 
    - Set-Alias -Name **'c'** -Value **'clear'** 