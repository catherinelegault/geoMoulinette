# geoMoulinette
Script qui vous trouve des coordonnées géographiques à partir d'adresses dans un fichier CSV en vous posant quelques questions.<br>
Conçu pour les étudiants du cours [EDM5240](https://jhroy.gitbooks.io/edm5240-h2017/content/) ([UQAM](https://edm.uqam.ca/)).

:globe_with_meridians: :globe_with_meridians: :globe_with_meridians:

### Instructions

1. Copiez le script **coordonnees.py** dans un de vos espaces de travail sur Cloud9.

2. Copiez dans le même espace de travail le fichier CSV dans lequel se trouvent des adresses dont vous souhaitez trouver les coordonnées (latitude et longitude).

3. Faites fonctionner le script en lançant la commande python3 coordonnees.py dans le terminal.

Répondez à toutes les questions que vous pose le script.<br>
Il vous demandra notamment dans quelles colonnes se trouvent des éléments pouvant permettre de construire une adresse la plus complète possible (rue, ville, province, pays, code postal, etc.)<br>
Avec ces informations, le script consulte l'[API de Google Maps](https://maps.googleapis.com/maps/api/geocode/json?address=1391,%20rue%20Bellevue%20Nord,%20Saint-F%C3%A9licien,%20QC) pour géocoder l'adresse de chacun de vos points et vous pond un deuxième fichier CSV contenant deux colonnes supplémentaires, une pour la latitude, l'autre pour la longitude.
