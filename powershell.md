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
    
    ![](ressources/E.jpg)

    **Avec cette commande on se retrouve dans le dossier que l'on veut** 

- Créer un fichier :
    - New-Item ***nom du fichier*** 
    - ni ***nom du fichier***
    
    ![](ressources/F.jpg)
    ![](ressources/F2.jpg)

    **Le fichier ***test2*** à bien été créer**

- Supprimer un fichier/dossier : 
    - Remove-Item ***nom du fichier*** 
    - del ***nom du fichier*** 
    - erase ***nom du fichier*** 
    - ri ***nom du fichier***
    
    ![](ressources/G.jpg)

    **Le fichier ***test2*** à bien été supprimé**


- Renommer un fichier : 
    - Rename-Item ***nom du fichier*** -NewName ***nom du fichier2*** 
    - rni ***nom du fichier***
   
    ![](ressources/H.jpg)
    ![](ressources/H2.jpg)

    **Le fichier 'test2' à bien été renommé en 'testrename'**


- Copier un fichier : 
    - Copy-Item ***nom du fichier*** -Destination ***nom du fichier2***
    
    ![](ressources/I.jpg)
    ![](ressources/I2.jpg)

    **Le fichier 'test' à bien été copié en 'testcopy'**


  - Déplacer un fichier : 
    - Move-Item ***nom du fichier*** -Destination ***chemin\nom du fichier*** 
    - move ***nom du fichier***
    
    ![](ressources/J.jpg)
    ![](ressources/K.jpg)

  

- Tester l’existence d’un fichier ou dossier : 
    - Test-Path ***chemin/nomFichier.txt***
    ![](ressources/L.jpg)
