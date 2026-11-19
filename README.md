# DJOBI ImageFlow

**Renommez, convertissez et préparez vos images plus simplement sous Windows.**

DJOBI ImageFlow est un utilitaire Windows édité par **DJOBI**, conçu pour préparer des lots d'images, notamment pour les fiches produits et les catalogues e-commerce.

## Fonctionnalités

- **Renommage par lot** avec numérotation automatique (`01`, `02`, etc.).
- **Conversion** entre PNG, JPG et WEBP à l'aide d'ImageMagick.
- **Préservation de la transparence** pour les formats compatibles ; fond blanc pour les images converties en JPG.
- **Nettoyage des anciens titres et métadonnées** lors du traitement.
- **Préremplissage du code-barres** depuis le presse-papiers lorsqu'un EAN-8, UPC-A ou EAN-13 valide est détecté.
- **Aperçu des noms** et indication du poids des fichiers.
- **Intégration à l'Explorateur Windows** via le menu *Envoyer vers* pour la sélection multiple.
- **Vérification des mises à jour** et outils de maintenance depuis les paramètres.

## Télécharger

➡️ **[Accéder aux versions officielles](https://github.com/djobifr/djobi-imageflow/releases/latest)**

Téléchargez l'archive `DJOBI-ImageFlow-vX.Y.Z.zip` de la dernière version, extrayez-la, puis lancez `Installer-DJOBI.cmd`.

> **Compatibilité :** application destinée à Windows, principalement testée sous Windows 11. ImageMagick est nécessaire au traitement des images ; l'application peut proposer son installation lorsqu'il est absent.

## Utilisation

1. Sélectionnez les images dans l'Explorateur de fichiers.
2. Ouvrez **Afficher d'autres options → Envoyer vers → DJOBI ImageFlow**.
3. Indiquez un nom de base ou un code EAN.
4. Choisissez le format de sortie.
5. Vérifiez l'aperçu, puis lancez **Renommer / Convertir**.

**Exemple de résultat :**

```text
4719072842918 - 01.webp
4719072842918 - 02.webp
4719072842918 - 03.webp
```

**Conseil :** effectuez un premier essai sur des copies de vos images. Selon le traitement, les fichiers originaux peuvent être remplacés ou supprimés après réussite.

## Mises à jour

Ouvrez **Paramètres → Vérifier les mises à jour** dans DJOBI ImageFlow. Les versions officielles sont distribuées via les [Releases](https://github.com/djobifr/djobi-imageflow/releases).

Le comportement d'installation dépend de la version déjà installée. La v4.7.3 introduit un mécanisme d'installation automatique qui doit encore être validé de bout en bout sur Windows.

## Sécurité et distribution

- Téléchargez uniquement depuis les Releases officielles de ce dépôt.
- Les archives peuvent être accompagnées d'une empreinte **SHA-256** permettant d'en vérifier l'intégrité.
- Ce dépôt est dédié à la **distribution** ; il ne contient pas le code source de développement.
- La disponibilité publique d'un installateur ne signifie pas que le logiciel est open source.

## Éditeur

**DJOBI** — [djobi.fr](https://www.djobi.fr)

© 2026 DJOBI. Tous droits réservés.
