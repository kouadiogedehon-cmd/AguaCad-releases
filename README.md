# AguaCad

**Modélisation et simulation des réseaux d'eau sous pression** (distribution, adduction d'eau potable).

AguaCad est un logiciel Windows édité par **Okavia SARL**. Ce dépôt ne contient que les **installeurs** et les mises à jour du logiciel.

## Télécharger

➡️ **[Dernière version : AguaCad pour Windows](https://github.com/kouadiogedehon-cmd/AguaCad-releases/releases/latest)**

Sur la page, télécharge le fichier **`AguaCad-Setup-X.Y.Z.exe`**. Les fichiers `latest.yml` et `.blockmap` servent aux mises à jour automatiques : tu n'en as pas besoin.

| | |
|---|---|
| Système | Windows 10 ou 11, 64 bits |
| Espace disque | environ 450 Mo |
| Connexion | requise pour l'activation, puis ponctuellement (voir « Licence ») |

## Ce que fait AguaCad

- **Dessin et saisie du réseau** : nœuds, réservoirs, bâches, conduites, pompes et vannes, avec saisie sous forme de tableau.
- **Fond de plan AutoCAD (DXF)** : import et calage des calques.
- **Modèle numérique de terrain** : triangulation de Delaunay et interpolation des altitudes.
- **Simulation hydraulique** : moteur EPANET, calcul des pressions, vitesses et pertes de charge, avec courbes de pompes et modulations horaires de consommation.
- **Catalogue de conduites** PEHD et PVC et **optimisation économique des diamètres**.
- **Profil en long** et ligne piézométrique.
- **Rapports PDF** et exports (modèle EPANET `.inp`, plans DXF).
- **Interface en 4 langues** : français, anglais, espagnol et arabe.

## Installation

1. Télécharge `AguaCad-Setup-X.Y.Z.exe` depuis la [page des versions](https://github.com/kouadiogedehon-cmd/AguaCad-releases/releases/latest).
2. Lance-le et suis l'assistant (tu peux choisir le dossier d'installation).
3. Au premier démarrage, accepte le contrat de licence, puis active ta licence.

### Avertissement « Windows a protégé votre ordinateur »

L'installeur n'est **pas encore signé numériquement**. Windows SmartScreen peut donc afficher « éditeur inconnu » :

1. Clique sur **Informations complémentaires**.
2. Clique sur **Exécuter quand même**.

Tu peux vérifier l'intégrité du fichier téléchargé : son empreinte SHA-512 (en base64) figure dans le `latest.yml` de la même version.

## Licence

AguaCad nécessite une **clé de licence** (format `AGUA-XXXX-XXXX-XXXX-XXXX`) et l'**adresse e-mail** associée, fournies par Okavia SARL.

- La clé est liée à ton poste. Le nombre de postes autorisés dépend de ta licence.
- Après l'activation, le logiciel fonctionne **hors connexion pendant 15 jours**. Au-delà, il demande de se connecter à Internet : tu disposes alors de **3 jours** pour le faire.
- Pour utiliser ta licence sur un autre poste, contacte-nous afin de libérer l'ancien.

## Mises à jour

Les mises à jour sont **automatiques** : à chaque démarrage, AguaCad vérifie s'il existe une version plus récente, la télécharge et propose de redémarrer. Tu peux aussi installer manuellement la dernière version depuis cette page, par-dessus l'ancienne : tes projets et réglages sont conservés.

## Tes données

- Tes projets sont des fichiers **`.hnet`** que tu enregistres où tu veux. Les anciens fichiers `.hydronet` restent lisibles.
- Les réglages et la licence sont stockés dans `%APPDATA%\AguaCad`.
- La désinstallation ne supprime pas tes projets.

## Support

📧 **contact@okavia.net**

Indique la version d'AguaCad (menu **Aide**, puis **À propos**) et, si possible, le message d'erreur affiché.

---

© 2026 Okavia SARL. Tous droits réservés. Logiciel propriétaire soumis au contrat de licence utilisateur final (CLUF), affiché au premier démarrage. Le contrat est régi par le droit ivoirien.
