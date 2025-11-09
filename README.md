# Service de Médiation 

## Lancer le site en local

1. Depuis la racine du projet, démarrez un serveur statique :
   ```bash
   python3 -m http.server 8000
   ```
2. Visitez `http://localhost:8000/`. Le fichier `index.html` vous redirige automatiquement vers la nouvelle page d'accueil (`html/index.html`).
3. Les autres pages sont disponibles à `http://localhost:8000/html/services.html` et `http://localhost:8000/html/discutons.html`.

> Alternative : vous pouvez aussi servir uniquement le dossier `html` via `python3 -m http.server 8000 -d html`. Dans ce cas, la page `html/index.html` sera chargée automatiquement et les feuilles de style sont disponibles dans `html/css`.
