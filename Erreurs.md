Voici tous les erreur corrigés:

###########################"1er erreur########################
Sur le site les bouton qui ramenait dans chaque paties de html,java,python,ect... ne fonctionnait pas donc j'ai corrigé ça en modifiant ce code :

Version avec l'erreur
<button><a href="python.html">En savoir plus</a></button>

Version corrigés
<button><a href="pages/python.html">En savoir plus</a></button>

j'ai rajouté pages pour que le code cherche le fichier dans le dossier pages

###########################2e erreur#######################
Dans CSS le fond est bleu, j'ai réglé le problème en repérant que le changement de couleurs venais de ce code
<link rel="stylesheet" href="../css/Global.css" />
je suis aller dans le fichier css puis Global.css et après j'ai modifier ce code 
Version avec l'érreur:

body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background-color: rgb(bleu);
}
Version sans l'érreur:
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background-color: rgb(white);
}

#############################3e erreur############################
dans la partie CSS il manquait un espaces sur le coté gauche pour les Titres et les sous titres donc j'ai corrigé en rajoutant un main dans le code 

Partie avec erreur:
  <!--Le contenue principale-->
     
     <h1>Introduction à CSS</h1>
     <p>

      CSS (Cascading Style Sheets) est un langage de style utilisé pour décrire
      la présentation d'un document HTML. Il permet de contrôler l'apparence
      visuelle des éléments d'une page web, tels que les couleurs, les polices,
      les marges et les dispositions.
     </p>
    
     <p>
      CSS a été développé par le W3C (World Wide Web Consortium) et a été publié
      pour la première fois en 1996. Depuis lors, il a évolué pour inclure de
      nombreuses fonctionnalités avancées, telles que les animations, les
      transitions et les grilles.
     </p>
     <p>
      L'utilisation de CSS permet de séparer le contenu d'une page web de sa
      présentation, ce qui facilite la maintenance et la mise à jour des styles.
      De plus, CSS permet d'appliquer des styles de manière cohérente sur
      l'ensemble d'un site web.
     </p>
    
Partie sans erreur:
<!--Le contenue principale-->
     <main>
     <h1>Introduction à CSS</h1>
     <p>

      CSS (Cascading Style Sheets) est un langage de style utilisé pour décrire
      la présentation d'un document HTML. Il permet de contrôler l'apparence
      visuelle des éléments d'une page web, tels que les couleurs, les polices,
      les marges et les dispositions.
     </p>
    
     <p>
      CSS a été développé par le W3C (World Wide Web Consortium) et a été publié
      pour la première fois en 1996. Depuis lors, il a évolué pour inclure de
      nombreuses fonctionnalités avancées, telles que les animations, les
      transitions et les grilles.
     </p>
     <p>
      L'utilisation de CSS permet de séparer le contenu d'une page web de sa
      présentation, ce qui facilite la maintenance et la mise à jour des styles.
      De plus, CSS permet d'appliquer des styles de manière cohérente sur
      l'ensemble d'un site web.
     </p>
    </main>
####################################################################################""

