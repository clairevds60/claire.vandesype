# PMO Laboratory — Claire Van De Sype

[Consulter le site](https://clairevandesype.com/) · [Version anglaise](https://clairevandesype.com/en/) · [LinkedIn](https://www.linkedin.com/in/claire-vandesype)

Direction de projet, PMO et formation : ce dépôt contient les fichiers publics du site clairevandesype.com, ses outils et ses analyses du marché du pilotage.

## Se repérer

| Emplacement | Contenu |
| --- | --- |
| `index.html` | Accueil en français |
| `en/` | Pages en anglais |
| `missions.html` | Présentation des missions |
| `bibliotheque.html` | Bibliothèque de ressources |
| `kit/`, `dt/`, `releve/` | Ressources téléchargeables et illustrations |
| `polices/`, `marques/` | Polices et images |
| `sitemap.xml`, `robots.txt` | Informations destinées aux moteurs de recherche |
| `CNAME` | Domaine personnalisé du site |

## Publication

GitHub Pages publie les fichiers de la branche `main`, depuis la racine du dépôt. Le domaine configuré est `clairevandesype.com` et HTTPS est imposé.

Toute modification enregistrée dans `main` peut déclencher une publication. Son état est visible dans l’onglet **Actions**, sous **pages build and deployment**. Une branche de travail ne dispose pas automatiquement d’un site de prévisualisation.

## Modifier le site avec une IA ou à deux

1. Récupérer la version la plus récente avant de commencer. Si une IA ou un autre outil génère les pages, modifier aussi sa source afin qu’une prochaine génération conserve la correction.
2. Créer une branche de travail au nom explicite, par exemple `amelioration-accueil`.
3. Effectuer une modification ciblée et vérifier l’affichage sur ordinateur et téléphone, les liens, les téléchargements et la version anglaise concernée.
4. Ouvrir une **Pull request** : une proposition de modification dont les différences peuvent être relues avant publication.
5. Après relecture, fusionner la proposition dans `main`, vérifier la réussite de la publication dans **Actions**, puis ouvrir la page en ligne.

Ce parcours est recommandé ; les mises à jour directes restent possibles. La branche principale est protégée contre la suppression et les envois forcés qui réécrivent l’historique.

Chaque personne doit utiliser son propre compte GitHub. La propriétaire peut ajouter un collaborateur dans **Settings → Collaborators** ; la personne doit accepter l’invitation avant de pouvoir modifier le dépôt.

## Contrôles avant publication

- Les documents PDF sont proposés sous licence : **ne pas ajouter de PDF en clair**,
  de copie ZIP ni d'archive privée. Les liens de demande de licence remplacent les
  anciens téléchargements. La bibliothèque chiffrée reste en service.
- Les créations originales sont couvertes par [la notice de droits](LICENSE.md).
  Les polices conservent [leurs licences propres](licences/README.md).
- Le générateur local contrôle les documents avant publication. Les changements
  effectués directement sur GitHub doivent respecter cette même règle.

- Conserver le domaine et les fichiers de vérification, sauf changement volontaire de configuration.
- Vérifier les titres, descriptions, adresses canoniques et liens entre les langues lorsqu’une page évolue.
- Mettre à jour le plan du site lorsqu’une page destinée à être indexée est ajoutée ou retirée.
- Compresser les nouvelles images et conserver des dimensions adaptées à leur affichage.
- Vérifier les modifications proposées par une IA avant de les publier.

## Sécurité et assistance

Ce dépôt est public : ne pas y ajouter de mots de passe, de clés d’API, de données clients ni de documents confidentiels. Les problèmes de sécurité peuvent être signalés en privé depuis **Security → Report a vulnerability**.

Pour une anomalie non confidentielle, ouvrir une **Issue** avec l’adresse de la page, le résultat attendu et le problème rencontré.

En cas de mauvaise publication, créer une modification qui annule la correction concernée ; ne pas forcer le remplacement de l’historique de `main`.
