# Pourquoi l'utiliser ?

On utilise le pattern Observer quand on doit gérer des évenements.

# Fonctionnement

Dans une classe qui doit déclencher des évenements, on ajoute:
- En attribut : une liste d'Observateurs
- Une méthode permettant d'ajouter un Observateur dans la liste
- Une méthode permettant d'envoyer un signal a tous ses obsevateurs.
  
  
"Observateur" est une classe abstraite avec une méthode signal, dont héritent des observateurs "concrets" qui implémentent cette méthode.  
  
Quand l'état de la classe change elle doit envoyer un signal a tout ses observateurs qui doivent effectuer l'action nécessaire en fonction du nouvel état de la classe.

# Diagramme UML

![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8d/Observer.svg/854px-Observer.svg.png)
