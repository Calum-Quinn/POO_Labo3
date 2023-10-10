# Labo 3 POO

## Contraintes d'intégration pour notre model:

- Une fédération a au moins 2 personnes (un gymnaste et un juge) 
- Les gymnastes participant à la discipline doivent avoir le même genre que le genre de la discipline
- Si une discipline est inscrite à un évènement, toutes les catégories le composant aussi
- Une inscription à un évènement a au moins une personne (un gymnaste ou un juge)


## Remarques:

- Nous ne passons pas de paramêtre à la fonction podium parce que les notes des gymnastes ainsi que l'isncription (contenant l'évènement) sont atteignables depuis la classe catégorie
- Pour la fonction victoires() nous passons comme paramêtre une catégorie pour en déduire le podium pour savoir si un gymnaste à gagné
- Expliquer pourquoi compositions
