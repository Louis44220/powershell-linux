# Powershell-Linux 


## Gérer les fichiers/dossiers


Commandes : 

- Afficher le contenu d'un dossier courant : 
    - Get-Location 
    - pwd 
    
    ![](ressources/2.jpg) 

- Afficher le contenu d'un dossier :
    - Get-ChildItem (+ détaillé)
    - ls
    
    ![](ressources/1.jpg)

- Créer un dossier :
    - New-Item ***nom du fichier*** -ItemType Directory 
  ![](ressources/3.jpg)
  ![](ressources/4.jpg)
  
  **On voit bien que le dossier à été créer** 

- Se déplacer dans les dossiers : 
    - Set-Location ***dossier*** 
    - cd ***dossier*** 
    - chdir ***dossier*** 

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

- Tester l’existence d’un fichier ou dossier : 
    - Test-Path ***chemin/nomFichier.txt***
