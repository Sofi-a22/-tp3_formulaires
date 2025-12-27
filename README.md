
# TP3 - Formulaires Symfony 2025/2026

## Étudiante
Safae DAHI - Groupe A 

## Objectif
Implémenter un formulaire Symfony pour un site e-commerce de vente de casques audio, en respectant les principes SOLID et les bonnes pratiques de développement Symfony.

##Ce que j'ai fait :

1. Création du projet

    composer create-project pour Symfony

    Installation des bundles nécessaires

2. Contrôleur

    ProductController.php créé

    Méthode show() pour afficher la page

3. Template HTML

    show.html.twig avec Bootstrap 5.3

    Structure produit : image, prix, description

4. Route

    /product configuré dans routes.yaml

5. Formulaire

    ProductType.php avec 2 champs :

        quantité (1 à 10)

        couleur (3 options)

    Intégré au contrôleur

6. Validation

    Le formulaire a été testé avec dd($form->getData()), confirmant que les données sont correctement capturées et structurées avant de passer à l'implémentation finale avec messages flash et redirection.
  
