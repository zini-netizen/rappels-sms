# Rappels SMS

Petite page affichée sur le téléphone du centre pour envoyer les rappels de rendez-vous.

Ce dépôt ne contient **que du code**, jamais de données. La liste du soir arrive dans la fin de l'adresse (après « # »),
lue depuis un QR code affiché à l'écran : cette partie n'est jamais envoyée à un serveur. La page l'efface de l'adresse,
n'autorise aucune connexion (règle `Content-Security-Policy`) et ne garde la liste que le temps de l'onglet.

Les SMS partent du téléphone, un par un, après un appui sur « Envoyer ».
