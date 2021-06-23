# Expliquer

* SIGNATURE
Ce sont les données utilisées pour déclarer une fonction.

* DECLARATION
Se dit lorsqu'on utilise la syntaxe spécifique à la création d'une fonction.
En JS et PHP :
  function nomFonction (parametres) {
    instructions
  }
En PYTHON, on va « définir » une fonction :
  def nom(parametres) :

* PARAMETRES
Données

* ARGUMENTS
Correspondent aux paramètres donnés lors de l'appel de la fonction, et se présentent entre parenthèses. 
En PYTHON, on peut assigner des valeurs à des arguments dès la déclaration de la fonction
  def name(nomParametre1 = 0, nomParametre2 = 0) : 

* RECURSIVITE
Une fonction peut se référer à elle-même (c'est un moyen de créer une boucle). Il faut alors une condition pour que la fonction ne tourne pas à l'infini.
Ex :
  function loop(x) {
	  if (x>=10)
	  return ;
  }
  loop(0) ;

* PILE D'APPEL



* FONCTIONS ANONYMES
Se dit d'une fonction dont le nom n'est pas déclaré, et qui s'écrit ainsi :
  function() {
  } 
ou
  var name = function() {
	  var quelqueChose = « truc » ;
	  return quelqueChose ;
  }

* FONCTIONS FLECHEES
La fonction est alors écrite ainsi :
  (parametre) => {
    instructions
  } 
