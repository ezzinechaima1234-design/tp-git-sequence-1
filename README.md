# Bienvenue

Programme C++ qui affiche "Bienvenue le monde !" en utilisant la fonction `afficherBienvenue()`.

## Fichiers du projet

- `bienvenue.cpp` : programme principal  
- `fonction-bienvenue.cpp` et `fonction-bienvenue.h` : fonction qui affiche le message de bienvenue  
- `Makefile` : compilation et construction automatique  
- `.gitignore` : fichiers à ignorer  
- `README.md` : ce fichier

## Exécution du programme sous Linux

```sh
$ make rebuild
Fabrication du programme : bienvenue
rm -f *.o
g++ -c -Wall -std=c++11 bienvenue.cpp
g++ -c -Wall -std=c++11 fonction-bienvenue.cpp
g++ -o bienvenue bienvenue.o fonction-bienvenue.o
$ ./bienvenue
Bienvenue le monde !
