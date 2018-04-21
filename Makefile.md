# Makefile
Pour plus d'exemples, il faut se rendre sur le projet : Makefile-addon de Twan0u 
## Les bases

Makefile est utile lors de la compilation, il évite de devoir recompiler à chaque fois toutes les librairies.

``` make
cible : prérequis prérequis
  Script
```
On lance le script on peut soit spécifier la cible avec :
``` bash
make cible
```
Mais si aucune cible n'est définie, ce sera la première cible (ou la cible par défaut) qui sera exécutée
``` bash
make
```

Quand les cibles ne sont pas des fichiers à générer on peut ajouter PHONY pour le stipuler

``` make
.SILENT # Masque la sortie de toutes les commandes sur le terminal
.PHONY: cible1 cible2
.DEFAULT_GOAL = cible
# commentaire

VARIABLE = 1234 # définit une variable
$(VARIABLE) # accède à cette variable
```
