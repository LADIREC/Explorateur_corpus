# Explorateur_corpus

Script python 3.8.10. La forme ipynb - ou python notebook signifie que le code est organisé selon des blocs qui peuvent être roulés tous ou en partie selon les objectifs d'analyse ou l'utilisation du texte. Un certain nombre de paramètres ont été désignés comme des constantes en tout début du script et sont utilisés comme de variables globales. 
Il contient des fonctions de prétraitement et d'analyse pour explorer à partir de listes de mot-clé, d'une vectorisation, de regroupement et d'entités nommées. Il contient aussi la fonction d'export dans le dernier bloc pour visualiser le traitement pour la validation.
Le script prend une table en format xlsx de texte et des métadonnées et, selon les paramètres désignés en variables globales au début du script, extrait les informations de type exploratoire.
Le dernier bloc contient l'export du corpus enrichi et peut être utilisé dès le premier traitement pour valider le contenu.
Certaines fonctions sont lourdes et devraient être testées avec un corpus réduit puisqu'elles peuvent prendre plusieurs minutes par entrée de texte. Un corpus d'une centaine d'entrées devrait être utilisé pour évaluer le temps d'exécution.
