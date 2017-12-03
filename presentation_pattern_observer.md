# Pourquoi l'utiliser ?

On utilise le pattern Observer pour gérer des évenements.

# Fonctionnement

Dans une classe qui doit déclencher des évenements, on ajoute en attribut une liste d'Observateurs.
Observateur est une classe abstraite que l'on créé, dont héritent des observateurs "concrets".
Quand l'état de la classe change elle doit envoyer un signal a tout ses observateurs qui doivent effectuer l'action nécessaire en fonction du nouvel état de la classe

# Diagramme UML

![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/Observer.svg/854px-Observer.svg.png)
