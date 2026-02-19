# Câblage d'énergie

Dans notre serveur, l'énergie est centralisée via un système AE2. Voici les règles et bonnes pratiques à suivre :

- Quand un emplacement est éloigné, utilisez des Quantum Rings pour relier l'énergie sur de longues distances.
- Si une zone a besoin d'énergie, nous tirons un `ME Smart Cable` et un `Flux Accessor` afin de limiter le nombre de channels et permettre la connexion d'éléments sans polluer le réseau principal.
- Pour les machines avec entrée/sortie, utilisez des `ME Import Export Bus`. Configurez-les avec des filtres pour n'autoriser que les FE les types d'énergie que vous utilisez.

Placez ici des captures d'écran du câblage et des configurations d'`ME Import/Export Bus` pour référence.

![placeholder-cablage](assets/screenshots/cablage-energie.png)
