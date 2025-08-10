Contexte et objectifs:
Ce projet vise à optimiser la gestion de la flotte de véhicules pour les livraisons last-mile sur la ville de Casablanca en prenant en compte plusieurs contraintes opérationnelles et environnementales. L’objectif principal est de réduire :

Le taux d’émission de CO₂ lié aux trajets de livraison, contribuant ainsi à un impact écologique moindre.

La distance totale parcourue par les véhicules, pour améliorer l’efficacité énergétique et réduire les coûts.

Le respect des plages horaires des clients, garantissant la satisfaction et la fidélisation.

Le respect des capacités de chaque véhicule, en prenant en compte l’hétérogénéité de la flotte (taille, charge maximale).

Approche méthodologique:
Modélisation du problème sous la forme d’un Heterogeneous Capacitated Time Window Vehicle Routing Problem (HCTWVRP), intégrant les contraintes de capacité, fenêtres horaires, et diversité des véhicules.

Application d’un algorithme métaheuristique Ant Colony Optimization (ACO) pour explorer efficacement l’espace des solutions possibles.

Utilisation de Optuna pour optimiser automatiquement les hyperparamètres de l’algorithme ACO et maximiser la qualité des solutions.

Tests réalisés sur plusieurs variantes classiques de benchmark : n32k5, n40k6 et n80k7, chacune présentant des configurations différentes de clients, véhicules et contraintes.

Résultats:
Les résultats obtenus sont présentés sous forme de captures d’écran illustrant les itinéraires optimisés sur des cartes réalistes.

Ces captures mettent en évidence les routes effectivement planifiées, ainsi que les indicateurs clés tels que la distance totale parcourue, les émissions de CO₂ estimées, et le respect des contraintes capacitaires et horaires.
Les chiffres démontrent une optimisation notable de la flotte et une réduction significative des impacts environnementaux.






Les chiffres démontrent une optimisation notable de la flotte et une réduction significative des impacts environnementaux.
