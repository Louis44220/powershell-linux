# Powershell-Linux 


## Gérer les fichiers/dossiers


Commandes : 

- Se déplacer dans les dossiers : 
    - Set-Location ***dossier*** 
    - cd ***dossier*** 
    - chdir ***dossier*** 

- Afficher le contenu d'un dossier :
    - Get-ChildItem 

- Afficher le contenu d'un dossier courant : 
    - Get-Location 
    - pwd 

- Créer un dossier :
    - New-Item ***nom du fichier*** -ItemType Directory 

- Créer un fichier :
    - New-Item ***nom du fichier*** 
    - ni ***nom du fichier***

- Supprimer un fichier/dossier : 
    - Remove-Item ***nom du fichier*** 
    - del ***nom du fichier*** 
    - erase ***nom du fichier*** 
    - ri ***nom du fichier***

- Renommer un fichier : 
    - Rename-Item ***nom du fichier*** -NewName ***nom du fichier2*** 
    - rni ***nom du fichier***

- Copier un fichier : 
    - Copy-Item ***nom du fichier*** -Destination ***nom du fichier2***

- Déplacer un fichier : 
    - Move-Item ***nom du fichier*** -Destination ***chemin\nom du fichier*** 
    - move ***nom du fichier***

## Alias

- Afficher tout les Alias disponible : 
    - Get-Alias

- Créer ses propres raccourci : 
    - Set-Alias -Name **c** -Value **clear** 