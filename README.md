# Ma Première Page Web

Ce projet contient un exemple simple de page HTML qui affiche un message lorsque l'utilisateur clique sur un bouton. C'est un projet de démarrage pour se familiariser avec les bases du développement web.

## Fonctionnalités

- **Titre** : Affiche "Bienvenue sur ma première page web !" comme titre principal.
- **Paragraphe** : Un paragraphe de texte simple introduit la page.
- **Bouton interactif** : Un bouton déclenche une alerte avec un message personnalisé lorsque l'utilisateur clique dessus.

## Code

Le fichier `index.html` contient le code suivant :

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma première page HTML</title>
</head>
<body>
    <h1>Bienvenue sur ma première page web !</h1>
    <p>Ceci est un paragraphe de texte simple.</p>

    <!-- Un bouton avec un message qui s'affiche au clic -->
    <button onclick="afficherMessage()">Clique ici pour afficher un message</button>

    <script>
        function afficherMessage() {
            alert('Bonjour, bienvenue sur ma première page web !');
        }
    </script>
</body>
</html>
