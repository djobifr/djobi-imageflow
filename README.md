# DJOBI ImageFlow

**Préparez, renommez et convertissez vos images et photographies sous Windows.**

DJOBI ImageFlow est un logiciel édité par **DJOBI**, destiné à la préparation de visuels e-commerce et au classement de photographies. Interface en français, onglets **Images** et **Photographies**.

## Télécharger et installer

**[Télécharger la dernière version officielle](https://github.com/djobifr/djobi-imageflow/releases/latest)**

1. Téléchargez `DJOBI-ImageFlow-vX.Y.Z.zip` dans les Releases.
2. Extrayez le ZIP dans un dossier.
3. Exécutez `Installer-DJOBI.cmd`.
4. Ouvrez **DJOBI ImageFlow** depuis Windows.

**Compatibilité :** Windows, principalement testé sous Windows 11 ; PowerShell 5.1 / Windows Forms. **ImageMagick** est requis pour certaines conversions et peut être proposé à l'installation.

## Fonctionnalités

### Onglet Images
- Import de plusieurs fichiers depuis **Choisir des images…**, par glisser-déposer ou via **Envoyer vers** dans l'Explorateur Windows.
- Bouton **Actualiser** pour récupérer des images ou une archive ZIP récente depuis **Téléchargements** et utiliser, lorsque possible, le code EAN du presse-papiers.
- Renommage optionnel par nom ou code-barres, avec numérotation automatique et tri naturel.
- Préremplissage des codes EAN-8, UPC-A et EAN-13 valides depuis le presse-papiers.
- Formats de sortie **Conserver les formats**, **WEBP**, **PNG** et **JPG**.
- Aperçu des noms, contrôle des conflits, information sur les tailles des fichiers.
- Option de suppression des métadonnées **désactivée par défaut lors d'une première installation** ; les préférences enregistrées peuvent être conservées.

### Onglet Photographies
- Import de photographies et de dossiers, glisser-déposer, aperçu avant traitement.
- Modes de renommage, notamment à partir des dates photographiques (EXIF), avec date manuelle ou de secours et numéro de départ.
- Détection des doublons strictement identiques par **SHA-256**, avec choix des fichiers à conserver.
- Conversion vers les formats proposés dans l'interface ; prise en charge de plusieurs formats photographiques selon les composants disponibles.
- Les vidéos importées sont conservées dans leur format d'origine.
- Choix du dossier de destination ; **originaux conservés par défaut**. Leur suppression nécessite une confirmation et intervient seulement après création et vérification des sorties.

## Utilisation rapide

**Images :** choisissez vos fichiers, activez ou désactivez **Renommer mes images**, saisissez le nom ou l'EAN si nécessaire, choisissez le format, vérifiez l'aperçu et lancez **Renommer / Convertir**.

**Photographies :** ajoutez des fichiers ou un dossier, choisissez le mode de renommage et la date de secours éventuelle, contrôlez les doublons, sélectionnez le format et lancez **Traiter les photographies**. Confirmez le dossier de sortie et le sort des originaux.

Pour les deux onglets, effectuez un premier essai sur des copies de fichiers importants.

## Mises à jour

Depuis la **v4.7.99**, le logiciel vérifie au démarrage si une version plus récente existe. Si oui, une fenêtre permet **d'accepter ou de refuser** l'installation. En cas de refus, la proposition revient au **prochain lancement**. Une mise à jour publiée pendant que le logiciel reste ouvert n'interrompt pas le travail.

La vérification manuelle reste disponible dans le menu **Mises à jour**. Les packages officiels sont distribués dans les [Releases](https://github.com/djobifr/djobi-imageflow/releases). La procédure prévoit des vérifications et une restauration de la version précédente en cas d'échec.

## Guide complet

Consultez le **[guide d'utilisation](GUIDE-UTILISATION.md)** pour les étapes détaillées et le dépannage. Un centre d'aide est également accessible dans le logiciel.

## Sécurité et distribution

- Utilisez uniquement les archives officielles de ce dépôt.
- Vérifiez l'intégrité des téléchargements lorsque des empreintes SHA-256 sont disponibles.
- Ce dépôt public sert à la **distribution et à la documentation** ; le code source de développement est conservé séparément.
- Le logiciel n'est pas présenté comme open source.

## Éditeur

**DJOBI** — https://www.djobi.fr

© 2026 DJOBI. Tous droits réservés.
