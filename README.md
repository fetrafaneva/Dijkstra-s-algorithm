Algorithme de Dijkstra - Visualisation Interactive

Ce projet est une visualisation interactive de l’algorithme de Dijkstra réalisée en HTML, CSS et JavaScript. Il permet de calculer et d’afficher le chemin le plus court entre deux nœuds d’un graphe pondéré, avec une interface graphique conviviale.

📌 Fonctionnalités

Saisie dynamique des poids des arêtes.

Graphe représenté visuellement avec des nœuds et des liens.

Calcul automatique du chemin le plus court entre deux nœuds choisis par l’utilisateur.

Affichage de tous les chemins les plus courts possibles si plusieurs existent.

Tableau détaillé des étapes de calcul avec :

Nœuds traités

Distances mises à jour

Prédécesseurs

Mise en évidence des changements à chaque étape

🖥️ Aperçu

Graphe interactif avec nœuds (A à G) et lignes représentant les arêtes.

Possibilité de modifier les poids directement sur l’interface.

Résultat affiché avec chemin le plus court et distances.

Tableau étape par étape montrant l’évolution de l’algorithme.

⚡ Comment utiliser

Ouvrir le fichier index.html dans un navigateur web moderne.

Cliquer sur "Calculer le chemin le plus court".

Entrer le nœud de départ et le nœud d’arrivée (ex: A et G).

Visualiser le chemin le plus court et les étapes dans le tableau généré.

Modifier les poids des arêtes si nécessaire et recalculer.

🔧 Technologies utilisées

HTML5 : Structure de la page

CSS3 : Styles et mise en page

JavaScript : Algorithme de Dijkstra et interactions

SVG : Dessin des lignes/arêtes entre les nœuds

🧠 Algorithme implémenté

L’algorithme suit la logique classique de Dijkstra :

Initialiser les distances de tous les nœuds à l’infini, sauf le nœud de départ.

Marquer les nœuds non visités et choisir le plus proche.

Mettre à jour les distances des voisins si un chemin plus court est trouvé.

Répéter jusqu’à ce que tous les nœuds soient visités.

Reconstruire le ou les chemins les plus courts depuis le nœud d’arrivée.
