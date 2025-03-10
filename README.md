# Auth-app

## Rôle du service

L'application Auth-app est un service qui permet de gérer l'authentification des utilisateurs. Elle permet aux utilisateurs de se connecter en utilisant un nom d'utilisateur et un mot de passe, et génère un jeton JWT pour les utilisateurs authentifiés.

## Configuration locale

1. Clonez le dépôt:
    ```sh
    git clone <URL_DU_DEPOT>
    cd auth-app
    ```

2. Installez les dépendances:
    ```sh
    npm install
    ```

3. Créez un fichier `.env` à la racine du projet et ajoutez-y la clé secrète:
    ```dotenv
    SECRET_KEY=mysecret
    ```

4. Démarrez l'application:
    ```sh
    node index.js
    ```

L'application sera accessible sur `http://localhost:4000`.