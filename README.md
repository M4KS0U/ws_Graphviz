```# ws_Graphviz
Apprenez à coder un graphique en dot avec Graphviz.
Pour télécharger Graphviz :
- https://graphviz.org/download/
- sur vsCode ajoutez l'extension GraphViz de Joao Pinto.
- Pour lancer la preview, créer un fichier "graph.dot", CTRL+SHIFT+P, entrez "graphviz dans la barre de recherche et choisir "Open Preview to the Side"

Sinon, ouvre votre moteur de recherche https://dreampuf.github.io/GraphvizOnline/ ou alors http://magjac.com/.

Le but à la fin de ce Workshop serait de vous rendre capable de faire un graphique similaire : ![alt text] (https://github.com/M4KS0U/ws_Graphviz/blob/main/graph.png)

1. les Nodes
    Pour vous aider voici la doc : https://graphviz.org/doc/info/shapes.html
    Commencez par créer une node en forme de losange avec comme nom "start".
    Créez ensuite 2 nodes supplémentaire : - un cercle rempli de couleur rouge et appelez le "a0"
                                           - un trapèze inversé rempli de jaune ainsi que des bords bleu avec une ecriture rouge, appelez le "a1"

2. les Liens
    Maintenant que vous savez manipuler les nodes, passons aux liens.
    Pour vous aider voici la doc : https://graphviz.org/doc/info/arrows.html
    Tracez une flèche allant de "start" à "a0" et une autre allant de "a0" à "a1".
    Modifiez le lien entre "a0" et "a1" pour qu'elle n'ai pas de direction (ligne sans flèche).
    Changez la couleur de la flèche allant de "start" à "a0" en vert, modifiez l'épaisseur de ce lien à la valeur 3 et rendre la forme de la tête de ce dernier en "tee".

3. les sous-graph
    Passons maintenant aux sous-graph:
    Pour vous aider voici la doc : https://graphviz.org/doc/info/lang.html#subgraphs-and-clusters
    Créez un sous-graph contenant "a0 et "a1" et appelez-le "bograph".

4. Maintenant vous en savez assez pour reproduire le graph en exemple.

5. Pour terminer, vous allez devoir modéliser l'arbre généalogique de la famille suivante:
    - un enfant unique, nommé Ethan et agé de 18 ans.
    - les parents d'Ethan, nommés Caroline et Patrice et agés de 45 et 48 ans.
    - les parents de Caroline, nommés Mireille et Maurice et agés de 78 et 79 ans.
    - les parents de Patrice, nommés Patricia et Claude et agés de 80 et 76 ans.
Afin de différencier les femmes des hommes, vous devrez colorer les bordures dans les couleurs de votre choix (différentes pour chaque sexe).
De plus Caroline et ses parents vivent actuellement en Angleterre. Représentez leurs nodes en pointillets.
Enfin Mireille et Maurice sont mariés, symboliser ce lien par une double flèche rouge.
```