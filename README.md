# AurionJS
A web scrapper for aurion by an isen's student.

## Configuration

Dans le dossier `config`, ajouter :

secrets.json
```json
{
    "username": "<EMAIL_JUNIA>",
    "password": "<PASSWORD_JUNIA>"
}
```

## Docker

Pour créer le fichier `.ics`, lancer grâce à *docker-compose* :

```bash
docker-compose up --abort-on-container-exit --exit-code-from app app
```

**Attention :** Il faut être connecté à un WiFi qui accepte l'utilisation de proxy *tor* (pas le WiFi Junia quoi).
