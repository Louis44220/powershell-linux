# Les variables 

- Déclarer une variable : 
  - $NomVariable = 'Hello'
  
![](ressources/Variables.jpg)

![](ressources/testvariables.jpg)


Remarque : pour savoir le type de la variable on peut taper la commande $NomVariable.GetType() pour savoir si c'est un string, un int, etc .. 

![](ressources/typevariables.jpg)

- Forcer le type d'une variable : 
  - [type]$NomVariable = 'Hello' 

![](ressources/Capture.jpg)

- Stocker le résultat d'une commande dans une variable : 
  - $NomVariable = Get-Service 

![](ressources/cmddansunevariables.jpg)

![](ressources/cmd.jpg)

***
## Pipeline 

Dans PowerShell, le Pipeline permet de connecter deux commandes. La sortie d'une commandes sera la sortie de la suivante. Il permet par exemple d'afficher tout les programmes en cours d'execution. 

  - Get- Service | Where-Object { $_.Status -eq "Running" }

![](ressources/pipe.jpg)

![](ressources/pipe2.jpg)