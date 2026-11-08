# [ESX] LSPD App – Application Police pour LB Phone & LB Tablet

## 📱 Présentation

**LSPD App** est une application complète et prête à l'emploi, conçue pour les serveurs FiveM utilisant **ESX Legacy**, compatible avec **LB Phone** et **LB Tablet**.

Cette application permet à votre service de police de communiquer efficacement avec les citoyens, de gérer les recrutements et de centraliser toutes les informations importantes du département directement depuis le téléphone ou la tablette en jeu.

L'ensemble des fonctionnalités est accessible directement depuis l'application. Les permissions sont vérifiées côté serveur afin de garantir une meilleure sécurité et d'éviter toute utilisation non autorisée.

La base de données est également installée automatiquement au premier démarrage de la ressource.

## ✨ Fonctionnalités

### 📢 Annonces publiques
- Publication d'annonces destinées à tous les citoyens.
- Gestion de plusieurs catégories d'annonces.
- Possibilité d'ajouter des images.
- Notifications push envoyées aux joueurs lors de la publication.

### 🚨 Système DEFCON
- Système d'alerte comprenant 5 niveaux DEFCON personnalisables.
- Configuration du titre, de la couleur et du message de chaque niveau.
- Modification des niveaux directement depuis l'application.
- Actualisation et notifications en temps réel.

### 👮 Gestion des recrutements
- Ouverture et fermeture des recrutements.
- Définition des conditions de candidature.
- Formulaire de candidature personnalisé.
- Suivi du statut des candidatures par les postulants.
- Interface de gestion réservée au personnel autorisé.
- Acceptation ou refus des candidatures avec possibilité d'ajouter une réponse.

### 📋 Informations du département
Toutes les informations du LSPD sont modifiables directement depuis l'application :

- Présentation du département.
- Missions et objectifs.
- Organisation interne.
- Unités disponibles.
- Grades et hiérarchie.
- Services proposés.
- Adresse et horaires.
- Contacts utiles.
- FAQ (questions fréquentes).
- Règlement intérieur.

### 🔐 Gestion des permissions
- Permissions configurables selon les grades.
- Gestion des accès aux annonces.
- Gestion des recrutements.
- Modification des informations.
- Gestion du système DEFCON.
- Consultation de l'historique.
- Grade de responsable configurable.
- Groupes administrateurs personnalisables.

### 📜 Historique et journalisation
- Enregistrement des actions effectuées dans l'application.
- Consultation des différentes opérations.
- Historique des modifications et des actions administratives.
- Possibilité de supprimer les anciens journaux.

### 🔔 Synchronisation en temps réel
- Actualisation automatique des informations.
- Notifications sur LB Phone et LB Tablet.
- Synchronisation des données entre les deux supports.

### ⚙️ Configuration avancée
- Compatible avec LB Phone uniquement.
- Compatible avec LB Tablet uniquement.
- Compatible avec LB Phone et LB Tablet simultanément.
- Activation ou désactivation de chaque support depuis la configuration.
- Installation automatique des tables SQL.
- Protection contre le spam grâce au système de limitation des requêtes.
- Délai configurable entre les candidatures.
- Vérifications de sécurité côté serveur.
- Configuration centralisée dans `config.lua`.

## 🖼️ Aperçu

Des captures d'écran et une vidéo de présentation seront prochainement disponibles afin de vous présenter l'interface et les différentes fonctionnalités de l'application.

## 📦 Dépendances requises

Pour utiliser correctement cette ressource, vous devez disposer de :

- `es_extended` – ESX Legacy.
- `oxmysql` – Gestion de la base de données.
- `lb-phone` – Compatibilité téléphone.
- `lb-tablet` – Compatibilité tablette.

Vous pouvez utiliser LB Phone, LB Tablet ou les deux simultanément.

## 📥 Installation

**Étape 1 – Installation de la ressource**

Téléchargez la ressource et placez le dossier `lspd_app` dans votre dossier `resources`.

**Étape 2 – Configuration du server.cfg**

Ajoutez la ligne suivante dans votre `server.cfg`, après le démarrage de LB Phone et LB Tablet :

```cfg
ensure lspd_app
```

**Étape 3 – Installation de la base de données**

Démarrez votre serveur. Les tables SQL seront créées automatiquement au premier lancement.

Un fichier `sql/install.sql` est également fourni pour permettre une installation manuelle si nécessaire.

**Étape 4 – Configuration**

Ouvrez le fichier `config.lua` afin de personnaliser :

- Les jobs de police autorisés.
- Les grades et leurs permissions.
- Les niveaux DEFCON.
- Les catégories d'annonces.
- Les différents paramètres de l'application.

**Étape 5 – Installation de l'application**

Les joueurs peuvent installer l'application depuis l'App Store de leur téléphone ou tablette.

Vous pouvez également activer l'installation automatique en configurant :

```lua
Config.DefaultApp = true
```

**Conseil :** si l'application affiche une page blanche sur LB Tablet, essayez d'activer le paramètre suivant :

```lua
Config.TabletUiWithResourceName = true
```

## ⬇️ Téléchargement

**Google Drive :** GOOGLE_DRIVE_LINK

## 🛠️ Support et assistance

Une question, un problème d'installation ou une suggestion d'amélioration ?

Rejoignez notre serveur Discord **BENDEV** pour obtenir de l'aide et échanger avec la communauté.

**Discord :** DISCORD_LINK

Pensez à fournir les informations suivantes en cas de problème :
- Le message d'erreur présent dans la console serveur.
- La version de LB Phone utilisée.
- La version de LB Tablet utilisée.
- Une description détaillée du problème rencontré.

D'autres ressources et scripts FiveM arriveront prochainement sur **BENDEV SHOP** !

## 📄 Licence et crédits

- Utilisation gratuite sur votre propre serveur.
- Modification du code autorisée.
- Revente interdite.
- Redistribution interdite sous votre propre nom.
- Les crédits originaux de **Bendev** doivent impérativement être conservés.

Merci de respecter le travail fourni !

---

## 📌 Informations sur la ressource

| Information | Détail |
|---|---|
| Nom | LSPD App |
| Framework | ESX Legacy |
| Téléphone | LB Phone |
| Tablette | LB Tablet |
| Base de données | oxmysql |
| Code source | Accessible |
| Abonnement | Aucun |
| Nombre de lignes | Environ 1 100 |
| Code Lua | Environ 540 lignes |
| Interface HTML/CSS/JS | Environ 520 lignes |
| Support | Disponible |
| Prix | Gratuit |

**Développé par Bendev – BENDEV SHOP**
