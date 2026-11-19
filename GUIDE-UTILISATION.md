# Guide d'utilisation — DJOBI ImageFlow

**Édition 2026 — fonctionnalités jusqu'à v4.7.100**

## 1. Installation et lancement

Téléchargez la dernière archive sur [les Releases officielles](https://github.com/djobifr/djobi-imageflow/releases/latest), extrayez-la, puis exécutez `Installer-DJOBI.cmd`. Lancez DJOBI ImageFlow depuis Windows. Le logiciel s'appuie sur PowerShell 5.1 et Windows Forms. ImageMagick est nécessaire pour certaines opérations de conversion.

## 2. Onglet « Images »

1. Cliquez sur **Choisir des images…** ou glissez-déposez les fichiers dans l'application. Vous pouvez également utiliser l'intégration **Envoyer vers** de l'Explorateur Windows.
2. Utilisez **Actualiser** pour rechercher les derniers fichiers ou ZIP pertinents dans **Téléchargements** et récupérer, lorsque possible, l'EAN présent dans le presse-papiers.
3. Cochez ou décochez **Renommer mes images**. Si le renommage est activé, renseignez le nom de base ou le code-barres. Les codes EAN-8, UPC-A et EAN-13 valides peuvent être préremplis.
4. Sélectionnez **Conserver les formats**, **WEBP**, **PNG** ou **JPG**.
5. Vérifiez l'**aperçu des noms de sortie**, l'ordre naturel et les éventuels conflits.
6. Cliquez sur **Renommer / Convertir** (ou **Convertir** si le renommage est désactivé), puis sélectionnez la destination.

**Métadonnées :** la suppression des métadonnées est désactivée par défaut à la première installation. Vérifiez ce réglage avant traitement ; les préférences enregistrées peuvent être réutilisées.

**Transparence :** les formats compatibles peuvent la conserver ; la conversion en JPG nécessite un fond opaque, généralement blanc.

## 3. Onglet « Photographies »

1. Cliquez sur **Ajouter des photos…**, **Importer un dossier…**, ou glissez-déposez les fichiers.
2. Choisissez le **mode de renommage** : les modes fondés sur les dates utilisent les informations photographiques disponibles, notamment EXIF. Vous pouvez renseigner une **date manuelle ou de secours**.
3. Indiquez le **numéro de départ** si nécessaire.
4. Cliquez sur **Vérifier les doublons**. Le contrôle compare les contenus par empreinte **SHA-256** ; il s'agit de doublons stricts, pas d'une reconnaissance visuelle de photos similaires.
5. Choisissez le **format de sortie**. La disponibilité de certains formats dépend des outils installés.
6. Contrôlez l'aperçu, puis cliquez sur **Traiter les photographies** et choisissez le dossier de destination.

**Protection des originaux :** ils sont conservés par défaut. La suppression est un choix explicite, proposé au moment du traitement, uniquement après vérification de la création des fichiers de sortie. **Les vidéos restent dans leur format d'origine.**

## 4. Mises à jour

Au **lancement**, ImageFlow recherche une nouvelle version officielle. Lorsqu'elle existe, une petite fenêtre propose :

- **Oui** : télécharger, vérifier et installer la mise à jour.
- **Non** : continuer à utiliser le logiciel. La proposition réapparaîtra au **prochain lancement** tant que la mise à jour reste disponible.

Une version publiée pendant que le logiciel est **déjà ouvert** ne provoque pas de nouvelle fenêtre pendant la session. Vous pouvez toujours lancer une recherche manuelle dans **Mises à jour**.

Si l'installation échoue, le mécanisme prévoit un **retour à la version précédente**. Les journaux utiles sont situés dans `%LOCALAPPDATA%\DJOBI\`, notamment `ImageFlow-Update.log` et `ImageFlow-Installer.log`.

## 5. Conseils et dépannage

- Testez d'abord sur des **copies** de vos fichiers importants.
- Vérifiez le dossier de sortie, les droits d'écriture et l'espace disponible.
- En cas de conversion impossible, vérifiez la présence d'**ImageMagick** et la prise en charge du format concerné.
- En cas de conflit de noms, ajustez le nom de base ou le numéro de départ.
- Si aucune notification de mise à jour n'apparaît, vérifiez qu'une version **strictement plus récente** est publiée et que la connexion Internet fonctionne.
- Pour désinstaller le logiciel, utilisez la fonction prévue dans l'application ou `Desinstaller-DJOBI.cmd`. Les fichiers personnels ne doivent pas être supprimés par la désinstallation.

## 6. Historique récent

| Version | Principales évolutions |
| --- | --- |
| v4.7.85 | Correction de la syntaxe bloquant certaines mises à jour |
| v4.7.86–v4.7.91 | Ajout et ajustement du bouton **Actualiser** pour les téléchargements et les EAN |
| v4.7.92–v4.7.96 | Titres et alignements de l'interface Images |
| v4.7.97 | Pieds de page harmonisés et vérification des réglages de métadonnées |
| v4.7.98 | Correction du blocage `InvalidPackage` de l'installateur |
| v4.7.99 | Proposition de mise à jour au démarrage, refus possible et rappel au prochain lancement |
| v4.7.100 | Version de test de la notification de mise à jour |

© 2026 DJOBI. Tous droits réservés.
