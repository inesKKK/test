### Chronologie du cours

**2 septembre 2022**:

* présentation rapide de ce qu'est l'informatique;
* introduction à la ligne de commande et au SGF

**5 septembre 2022**:

* commandes liées au SGF : `pwd`, `cd`, `ls`, `mkdir`, `rmdir`, `cp`,
  `mv`, `rm`
* notion d'i-nœud et de numéro d'i-nœud
* droits sur les fichiers : consultation, signification et modification
* contenu d'un répertoire

**8 septembre 2022**:

* liens physiques et symboliques, commande `ls`
* espace d'adressage: description de System V
* exemple de création d'un faux gros fichier; code:
  [bigfile.c](code/bigfile.c)
* caractérisation d'un langage de programmation: paradigmes
  (POO/impératif/fonctionnel)
* graphe de flot de contrôle d'un programme
* compilation vs. interprétation
* types: définition, taille, conversions explicite et implicite, typage fort vs. typage faible

**12 septembre 2022**:
* typage statique vs. typage dynamique
* bases de `C` : compilation, flot d'un programme `C` et rôle de la
  fonction `main`
* types en `C`: `int`, `unsigned int`, `int8_t`, `int32_t`, `int64_t`,
  `uint8_t`, `uint32_t`, `uint64_t`
* bit de poids fort / bit de poids faible
* complément à 2

**15 septembre 2022**:
* norme IEEE 754 pour les nombres à virgule flottante en double
  précision
* opérations sur les doubles, problèmes de précision et erreurs d'arrondi
* opérations entre doubles et entiers
* booléens
* identifiants en C: règles

**16 septembre 2022** (complément en TP):
* variables en `C`: déclaration, affectation, portée; code : [reutilisation_identifiant.c](code/reutilisation_identifiant.c)

**19 septembre 2022**
* constantes en `C` (littérales et symboliques)
* fonctions en `C`: invocation/appel, passage par valeurs, variables
  locales, valeur de retour; code :
  [passage_par_valeurs.c](code/passage_par_valeurs.c)
* structures de contrôle de `C`: conditionnelles, boucles
  (conditionnelles et inconditionnelles)
* introduction à l'algorithmique

**22 septembre 2022**
* conception d'un algorithme: entrée, sortie, problème de décision
* correction: terminaison, correction partielle et totale; code :
  [plus_grande_puissance_de_2.c](code/plus_grande_puissance_de_2.c) /
  [plus_grande_puissance_de_2.ml](code/plus_grande_puissance_de_2.ml)
* efficacité: complexité temporelle, complexité spatiale
* indécidabilité du problème de l'arrêt