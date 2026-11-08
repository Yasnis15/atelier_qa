# cas-02 - Échec de connexion avec mot de passe incorrect

## Titre
Tentative de connexion avec un mot de passe erroné.

## Préconditions
- Le compte utilisateur existe en base de données (`test.qa@example.com`).
- L'utilisateur est sur la page de connexion.

## Étapes d'exécution
1. Saisir l'adresse email `test.qa@example.com`.
2. Saisir un mot de passe incorrect `WrongPass123!`.
3. Cliquer sur le bouton "Se connecter".

## Résultat attendu
- Affichage du message d'erreur : "Identifiants incorrects".
- L'utilisateur reste sur la page de connexion sans être authentifié.
