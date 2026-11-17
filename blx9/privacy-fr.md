# Politique de confidentialité

Localiser+ · Dernière mise à jour : 17 novembre 2026

## 1. À propos de cette politique

Localiser+ (l'« App ») est une app iOS permettant de partager manuellement une position à la fois avec les personnes que vous autorisez. Cette politique décrit les données traitées, leur lieu de stockage et vos choix. L'App est fournie par le développeur de Localiser+ (« nous »). Contact : https://github.com/xxlcmb9/doc/issues.

## 2. Données traitées

- Numéro de partage : un nombre aléatoire à 9 chiffres généré sur votre appareil. Aucun e-mail, numéro de téléphone, mot de passe ni compte social n'est requis, et nous ne demandons ni nom, ni contacts, ni photos.
- Position que vous confirmez : latitude, longitude, altitude et horodatages, envoyés uniquement après appui sur partager et confirmation.
- Liste d'autorisation et liste de blocage : les numéros autorisés ou bloqués, enregistrés dans votre profil.
- Messages que vous nous envoyez : en cas de contact via la page d'assistance.

## 3. Fonctionnement du partage

- Rien n'est publié automatiquement, en arrière-plan ou selon un minuteur. Chaque publication exige votre confirmation et peut être annulée.
- Chaque publication envoie un seul enregistrement qui remplace le précédent. L'App ne conserve aucun historique.
- L'enregistrement expire dans l'App une heure après publication et n'est plus affiché aux autres utilisateurs. L'expiration n'est qu'une règle d'affichage : elle ne supprime pas le fichier du stockage cloud. Le fichier est supprimé lorsque vous retirez le partage ou supprimez votre identité.
- Afficher votre propre position sur la carte locale est un réglage facultatif distinct et ne partage rien.

## 4. Où sont stockées les données

Les enregistrements partagés, les listes et l'index des numéros sont stockés dans Tencent Cloud Object Storage (COS), région ap-nanjing (Chine continentale), avec des identifiants temporaires émis par le point d'authentification de l'App. Votre numéro et vos listes restent aussi sur l'appareil. Nous n'exploitons pas de base analytique distincte pour les positions. Après suppression, les sauvegardes du prestataire peuvent subsister pendant une durée limitée.

## 5. Services tiers

- Tencent Cloud COS : hébergement des enregistrements et des listes.
- Google AdMob et Google User Messaging Platform : publicités et écrans de consentement ; Google peut recevoir des identifiants d'appareil, l'adresse IP et les interactions publicitaires.
- Apple : App Store, achats intégrés et paiements. Nous ne recevons jamais vos données de carte bancaire.
- open-elevation.com : uniquement lorsque vous sélectionnez un point sur la carte pour en connaître l'altitude, la coordonnée choisie est transmise ; vous pouvez annuler avant.

Nous ne vendons pas de données personnelles.

## 6. Publicités et suivi

Les publicités financent la version gratuite. À partir d'iOS 14.5, l'App demande l'autorisation de suivi (ATT) lorsque nécessaire ; en cas de refus, vous voyez des publicités non personnalisées. Modifiable dans Réglages → Confidentialité et sécurité → Suivi et dans les options de consentement de l'App.

## 7. Sécurité et limites

Le trafic utilise HTTPS/TLS et des identifiants temporaires à expiration. Avant toute consultation, l'App vérifie la liste de blocage et la liste d'autorisation des deux côtés ; le blocage prévaut. Ce contrôle est appliqué par l'App et non isolé côté serveur : il n'empêche pas une personne disposant d'identifiants valides de lire des objets du bucket, ni un destinataire de faire des captures d'écran ou des copies. Ne partagez que ce que vous pouvez divulguer.

## 8. Vos choix

- Retirer le partage à tout moment (supprime l'enregistrement partagé).
- Bloquer ou débloquer ; le déblocage ne rétablit pas l'autorisation.
- Masquer votre position sur la carte locale.
- Supprimer votre identité dans l'App : position, profil et entrée d'index sont supprimés, puis les données locales. L'achat à vie n'est pas affecté.
- Révoquer l'accès à la position dans Réglages iOS ; la carte, la boussole et l'altitude cessent de fonctionner, le reste de l'App reste utilisable.
- Nous contacter via le lien d'assistance pour demander l'accès, la rectification ou la suppression des données liées à votre numéro.

## 9. Enfants

L'App ne s'adresse pas aux enfants de moins de 13 ans, ou de l'âge minimum requis dans votre pays. Nous ne collectons pas sciemment leurs données. Si vous pensez qu'un enfant a partagé des données, contactez-nous et nous les supprimerons.

## 10. Modifications et contact

Nous pouvons mettre à jour cette politique ; la date ci-dessus changera et la nouvelle version sera publiée sur cette page. Questions : https://github.com/xxlcmb9/doc/issues.

Assistance : https://github.com/xxlcmb9/doc/issues
