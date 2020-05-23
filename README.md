# GestionDeProjet4A

Dans le dossier Version Multi Fichier, vous trouverez :
- Fonctions_Test où la plupart des fonctions sont définies
- Polynomes_2p1 qui permet de résoudre le problème d'interpolation par un polynôme positif
- Polynomes_2p1_avecArguments identique à Polynomes_2p1 et qui permet de prendre des fonctions ayant en arguments x,h, et autres
- Test_Fonctionnement qui permet de vérifier l'implémentation de la méthode
	- tests sur des fonctions classiques 
	- tests sur des fonctions moins classiques
	- evolution des résidus de Newton-Raphson
	- tests pour une fonction partiellement négative
- EtudeParametres
	- etude de p
	- etude de h (ordre)
	- tests sur des fonctions auxquels on ajoute une droite ou une constante (ordre)
	- etude de epsilon
	- effets gibbs (fonction creneau)
- Etude_S_init
	- etude de S, séparateur de noeud
	- etude de l'influence de l'initialisation
- Test_Diffusion_Onde
	- etude de l'effet mémoire (pour initialisation) dans le cas de l'advection d'une onde et de la diffusion d'une gaussienne
- Advection
	- exemple d'application de la méthode, méthode utilisée pour approcher l'initialisation au cours de la résolution d'un schéma numérique
 