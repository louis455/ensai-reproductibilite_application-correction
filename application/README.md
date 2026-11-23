# Prix de l'immobilier en petite couronne parisienne

Prédiction du prix au m² des logements vendus en 2022 à Paris et dans
les départements de la petite couronne (92, 93, 94), à partir des
données DVF enrichies par des données socio-économiques (Filosofi).

Exercice fil rouge du cours de "Mise en production de projets de data science" (ENSAE), guidé sur https://ensae-reproductibilite.github.io/website/chapters/application.html

## Utilisation

Pour installer les dépendances du projet :

    pip install -r requirements.txt

Pour pouvoir utiliser ce projet, il
est recommandé de créer un fichier `.env`
ayant la structure suivante:

```yaml
JETON_API="####" #renseigner la valeur pertinente
