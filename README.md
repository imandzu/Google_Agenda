# Google_Agenda
Récupérer les événements de votre agenda

Dans un premier temps, vous devez :
 créer une authentification Google
 récupérer le client_secret.json
 mettre le répertoire 'google-api-php-client-2.2.0' à la racine de serveur Web
 vérifier que l'appel du google-api-php-client est bien : '../../../google-api-php-client-2.2.0/vendor/autoload.php';

Ce petit projet permet
+ l'affichage du dashboard en utilisant la bibliothèque graphique JavaScript D3.js qui permet 
  l'affichage de données numériques sous une forme graphique et dynamique 
+ création un d'un trombinoscope à partir des photos prise par un mobile
+ intégrer W2ui pour afficher les événements d'un agenda :
- W2UI est une petite bibliothèque d'interface utilisateur JavaScript avec un ensemble complet de widgets: 
  layout, grid, sidebar, toolbar, tabs, fields, popup, utilities.
- afficher les agendas 
- afficher les événements d'un agenda dans un grid sur le clic de la ligne du grid des agendas

Description :
- créer en SVG avec Inkscape une palette d'évènement.
- utiliser les popup w2ui pour avertir l'utiliser du chargement : http://w2ui.com/web/demos/#!popup/popup-9
- créer des évènements avec le toolbar du  grid http://w2ui.com/web/demos/#!grid/grid-17
- choisir le type d'événement à partir de la palette
- choisir la date avec les champs W2ui http://w2ui.com/web/demos/#!fields/fields-2
- afficher les évènements

