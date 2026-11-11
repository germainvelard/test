# Crèches autour de la Villa Gaudelet (Paris 11e)

App web autonome qui recense les crèches situées à moins de 500 m de la Villa Gaudelet (75011), avec adresse, contacts et carte interactive.

**Utilisation :** ouvrir `index.html` dans un navigateur (aucune installation requise).
- Curseur de rayon (200 à 800 m), filtres par type, filtre « avec contact »
- Clic sur une crèche → zoom et fiche sur la carte
- Export CSV de la sélection

Fichiers : `index.html` (l'app), `creches.json` et `creches.csv` (les données, 31 établissements jusqu'à 800 m).

## Les 16 établissements à 500 m ou moins

| Dist. | Nom | Type | Adresse | Téléphone | E-mail | Fiabilité |
|---|---|---|---|---|---|---|
| 6 m | Micro-crèche (12 villa Gaudelet) – non confirmée | Privée / micro-crèche | 12 Villa Gaudelet 75011 Paris | – | – | ⚠ Une seule source (code NAF micro-crèche, 2010). Le 12 villa Gaudelet héberge aussi le SESSAD Le Passage : existence à vérifier |
| 191 m | Micro-crèche Les Explorateurs de Ménilmontant (Les Bébés Explorateurs) | Privée / micro-crèche | 147 Rue Oberkampf 75011 Paris | 07 67 82 17 51 | – | ⚠ Téléphone : conseiller petite enfance People&Baby (pré-inscription), pas la crèche directement |
| 227 m | Crèche associative pour la diversité culturelle et sociale "l'enfance en couleurs" | Associative | 10 Rue Guillaume Bertrand 75011 Paris | 01 47 00 87 46 / 06 26 43 19 91 | enfanceencouleurs@gmail.com | ✔ paris.fr |
| 254 m | Crèche municipale Saint-Maur (108-110 rue Saint-Maur) | Municipale | 108 Rue Saint-Maur 75011 Paris | 01 48 07 24 80 | – | ✔ paris.fr |
| 286 m | Crèche municipale Saint-Maur (56 rue Saint-Maur) | Municipale | 56 Rue Saint-Maur 75011 Paris | 01 48 07 50 95 | – | ✔ paris.fr |
| 315 m | Les Nouvelles Crèches – Jean-Pierre Timbaud | Privée / micro-crèche | 77 Rue Jean-Pierre Timbaud 75011 Paris | – | – | ⚠ Adresse confirmée ; aucun contact public trouvé (siège : 13 rue du Chemin Vert) |
| 319 m | Crèche municipale Jean-Pierre Timbaud (81 bis rue Jean-Pierre Timbaud) | Municipale | 81B Rue Jean-Pierre Timbaud 75011 Paris | 01 47 00 38 93 | – | ✔ paris.fr |
| 331 m | Halte-garderie municipale Jean-Pierre Timbaud | Halte-garderie | 114 Rue Jean-Pierre Timbaud 75011 Paris | 01 55 28 30 45 | – | ✔ paris.fr |
| 340 m | Crèche municipale Ménilmontant (130 boulevard Ménilmontant) | Municipale | 130 Boulevard de Ménilmontant 75020 Paris | 01 58 53 50 55 | – | ✔ paris.fr |
| 379 m | Crèche associative Heikhal Menahem | Associative | 110 Boulevard de Ménilmontant 75020 Paris | – | – | ⚠ Adresse 110-114 bd de Ménilmontant ; aucun contact trouvé |
| 403 m | Mini-crèche coccinelle | Associative | 4 Square du Nouveau Belleville 75020 Paris | 01 43 58 71 26 | nafissatou.sodjinou@groupe-sos.org | ✔ paris.fr |
| 419 m | Crèche associative ganone yad | Associative | 145 Rue Saint-Maur 75011 Paris | 01 48 05 44 15 | ganone145@hotmail.fr | ✔ paris.fr |
| 427 m | Crèche associative saint ambroise | Associative | 19 Rue Pasteur 75011 Paris | 01 56 98 06 25 | saintambroise@fondationbellan.org | ✔ paris.fr |
| 450 m | Halte-garderie associative Suzanne et David Lévy | Halte-garderie | 64 Boulevard de Belleville 75020 Paris | 01 44 62 13 12 | halte-garderie@casip-cojasor.fr | ✔ paris.fr |
| 456 m | Crèche municipale Monplaisir | Municipale | 7 Passage Monplaisir 75020 Paris | 01 43 66 92 24 | – | ✔ paris.fr |
| 465 m | Crèche municipale Couronnes | Municipale | 8 Rue des Couronnes 75020 Paris | 01 43 66 92 56 | – | ✔ paris.fr |

## Sources et méthode

1. **paris.fr** : lecture des 825 fiches « lieux » petite enfance listées dans le plan du site (crèches municipales, associatives, parentales, familiales, haltes-garderies, jardins d'enfants). Adresse, téléphone et e-mail viennent de chaque fiche.
2. **Géocodage** : Base Adresse Nationale (api-adresse.data.gouv.fr). Distances à vol d'oiseau depuis le centre de la Villa Gaudelet (48.86543, 2.37973).
3. **Crèches privées / micro-crèches** : recherches web (annuaires Babilou et People&Baby, registre SIRENE).
4. **Fiches paris.fr retirées** (Saint-Maur 108-110, Saint-Maur 56, halte-garderie J.-P. Timbaud, Heikhal Menahem) : contacts issus d'annuaires tiers, à vérifier.

## Limites

- **Disponibilité des places** : elle n'est publiée nulle part. Pour les crèches municipales et associatives conventionnées, la demande passe par le Relais Informations Familles de la mairie du 11e (01 53 27 11 11) ou du 20e. Les crèches privées s'inscrivent directement.
- Les crèches municipales n'ont pas toutes d'e-mail public : passer par le téléphone ou la mairie.
- Les sites des réseaux privés n'ont pas pu être consultés directement. D'autres micro-crèches privées peuvent exister dans le périmètre : l'annuaire CAF [monenfant.fr](https://monenfant.fr) permet de le vérifier.

Données collectées le 11/11/2026.
