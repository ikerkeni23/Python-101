# python101


Bases de la programmation



## Environnement interactif : Jupyter Notebook et Python Tutor

### Jupyter Notebook 
On utilise **Jupyter Notebook**  http://jupyter.org/ pour les supports de cours-TD-TP
Jupyter Notebook est installable notamment avec Anaconda https://www.anaconda.com/download/

### Alternative : Jupyter Notebook Docker image  

# docker pull jupyter/minimal-notebook:latest
$ docker run -p 8888:8888 jupyter/minimal-notebook 

![image](https://user-images.githubusercontent.com/47931933/234310165-63bd76bd-13cc-4d9e-a903-6ebcf175b88e.png)


Commande de lancement : `jupyter-notebook`

### Python Tutor 
 **Python Tutor**  permet permet de visualiser l'exécution d'un code en python, ce qui aide à comprendre son fonctionnement.
 
*Pour l'installer*, il faut utiliser les commandes suivantes 
```
    git clone https://github.com/kandjiabdou/visual_pytutor.git
    
    jupyter nbextension install visual_pytutor
    
    jupyter nbextension enable visual_pytutor/main
```    
Sur les machines de l'IUT seule la dernière commande est nécessaire. Elle doit être exécutée avant le lancement du notebook.

*Pour visualiser le code* : cliquer sur l'oeil qui apparait à gauche de chaque cellule de code, une fenêtre de suivi d'exécution s'ouvre alors. 







