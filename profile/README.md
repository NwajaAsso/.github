# NWAJA

**NWAJA** est un mouvement culturel, communautaire et digital qui rassemble une nouvelle génération autour de l’identité, de la créativité, de l’entraide et de l’ambition.

Nous construisons un écosystème complet composé d’une plateforme web, d’une application mobile, d’un espace communautaire, d’événements, d’une boutique et de services pensés pour connecter les membres entre eux.

Notre objectif est simple : créer un espace moderne où chaque membre peut découvrir, échanger, participer, acheter, proposer des idées et contribuer à faire grandir le mouvement.

---

## Notre vision

NWAJA n’est pas seulement une marque ou une application.

C’est un projet qui mélange :

* communauté
* culture
* événements
* boutique
* réseau social privé
* mise en avant des membres
* outils digitaux
* expérience mobile et web

Nous voulons créer une plateforme élégante, fiable et évolutive, capable d’accompagner le développement du mouvement sur le long terme.

---

## Ce que nous développons

L’organisation GitHub NWAJA regroupe les différents services techniques du projet.

### Site web vitrine

Le site web présente le mouvement, son identité, ses événements, sa boutique et les moyens de rejoindre la communauté.

Il sert de point d’entrée public pour les visiteurs, futurs membres, partenaires et clients.

### Application mobile

L’application mobile est pensée comme l’espace principal des membres.

Elle permet notamment de gérer :

* l’inscription et la connexion
* le fil d’actualité
* les publications
* les commentaires
* les messages privés
* les demandes de contact
* l’annuaire des membres
* les profils
* les idées proposées par la communauté
* les notifications

### Backend / API

Le backend centralise la logique métier du projet.

Il permet aux différentes plateformes de communiquer avec la même base de données et les mêmes règles métier.

Il gère notamment :

* les utilisateurs
* l’authentification
* les rôles et permissions
* les publications
* la messagerie
* les événements
* la boutique
* les commandes
* les paiements
* les notifications
* les contenus administrables

### Boutique et paiements

NWAJA intègre une partie e-commerce pour vendre des produits, vêtements ou autres articles liés au mouvement.

Le système doit pouvoir gérer :

* les produits
* les variantes
* les tailles
* les prix
* le panier
* les adresses de livraison
* les commandes
* les paiements
* les statuts de livraison

Les paiements peuvent être connectés à Stripe pour la partie web, avec une architecture compatible avec les contraintes mobile lorsque l’application est distribuée sur l’App Store ou Google Play.

---

## Architecture du projet

Nous séparons les services dans plusieurs repositories afin de garder une organisation propre, maintenable et évolutive.

Exemple d’organisation possible :

```txt
nwaja-web/          # Site web vitrine et boutique web
nwaja-mobile/       # Application mobile
nwaja-api/          # Backend / API principale
nwaja-admin/        # Dashboard administrateur
nwaja-docs/         # Documentation produit et technique
nwaja-design/       # Ressources design, maquettes, assets
```

Chaque repository doit contenir sa propre documentation, ses conventions de développement et ses instructions de contribution.

---

## Principes techniques

Nos projets doivent être construits avec une logique professionnelle :

* code propre et lisible
* architecture scalable
* séparation claire des responsabilités
* API documentée
* base de données structurée
* sécurité dès la conception
* gestion correcte des erreurs
* expérience utilisateur fluide
* design cohérent entre web et mobile
* intégration progressive des services externes

Nous privilégions une approche modulaire pour permettre au projet de grandir sans devoir tout reconstruire.

---

## Valeurs du projet

NWAJA repose sur plusieurs valeurs fortes :

### Communauté

Créer du lien entre les membres et faciliter les échanges.

### Élégance

Proposer une expérience visuelle forte, cohérente et haut de gamme.

### Fiabilité

Construire des outils stables, sécurisés et maintenables.

### Ambition

Développer un écosystème capable d’évoluer vers une vraie plateforme communautaire et commerciale.

### Transmission

Permettre aux membres de partager des idées, des opportunités, des événements et des projets.

---

## Repositories principaux

Les repositories de cette organisation sont destinés à accueillir les différentes briques de l’écosystème NWAJA.

Chaque repository doit idéalement contenir :

```txt
README.md
AGENTS.md
docs/
src/
.env.example
```

Les documents dans `docs/` peuvent inclure :

```txt
PROJECT_OVERVIEW.md
ARCHITECTURE.md
API_CONTRACT.md
DATABASE_SCHEMA.md
AUTH_AND_ROLES.md
PAYMENT_FLOW.md
ROADMAP.md
CONTRIBUTING.md
```

---

## Pour les contributeurs

Toute personne qui rejoint le développement du projet doit respecter les principes suivants :

1. Lire la documentation du repository concerné.
2. Comprendre le rôle du service avant de coder.
3. Respecter l’architecture existante.
4. Ne pas mélanger les responsabilités entre web, mobile, backend et admin.
5. Documenter les décisions importantes.
6. Proposer des améliorations propres et maintenables.
7. Garder une cohérence avec l’identité NWAJA.

---

## Objectif long terme

Notre ambition est de faire de NWAJA une plateforme complète :

* un mouvement culturel identifiable
* une communauté active
* une application mobile utile
* une boutique connectée
* un espace membre vivant
* un système d’événements
* un réseau privé autour de l’entraide et de la création

Nous construisons progressivement chaque brique pour faire grandir le projet de manière solide.

---

## Contact

Pour toute question concernant le projet, les partenariats ou la contribution technique, merci de contacter l’équipe NWAJA.

**NWAJA — Le mouvement commence ici.**
