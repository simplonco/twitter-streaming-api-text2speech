Démonstration de l'API streaming Twitter. Synthèse vocale des tweets par Festival.

1. Installer le paquet « festival »  de votre distro. Pour une meilleure qualité, utiliser les voix HTS (sous Arch, `festival-hts-voices-patched` depuis l'AUR installe tout)
2. Créer une [app Twitter](http://dev.twitter.com) et autorisez-là avec votre comp
te
3. Configurer le client Twitter en créant un fichier `.env` à la racine de l'appli, avec les identifiants de l'appli et les identifiants du compte (`ACCESS_TOKEN`).

   ```
   CONSUMER_KEY=<valeur>
   CONSUMER_SECRET=<valeur>
   ACCESS_TOKEN=<valeur>
   ACCESS_TOKEN_SECRET=<valeur>
   ```
