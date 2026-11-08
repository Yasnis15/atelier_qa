# cas-01 - Connexion réussie avec identifiants valides

## Titre
Connexion au compte utilisateur avec un email et un mot de passe valides.

## Préconditions
- Le compte utilisateur existe en base de données (`test.qa@example.com`).
- L'utilisateur est sur la page de connexion.

## Étapes d'exécution
1. Saisir l'adresse email `test.qa@example.com` dans le champ "Email".
2. Saisir le mot de passe `Password123!` dans le champ "Mot de passe".
3. Cliquer sur le bouton "Se connecter".

## Résultat attendu
- L'utilisateur est authentifié avec succès.
- Redirection vers le tableau de bord (Dashboard).
