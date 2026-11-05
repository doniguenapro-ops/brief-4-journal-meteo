# Journal météorologique de la ferme

> Projet individuel du SAS DFS, brief 4 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte

Notre outil est utilisé par les personnes qui travaillent dans le domaine agricole .En mesurant la température, l'humidité de l'air et les précipitations, elle résout le problème du manque de donnée météo en fournissant des données  exactes pour une agriculture precise . il ne permet pas de conclure le climat.

## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-4-journal-meteo.git
cd brief-4-journal-meteo
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

✏️ *Cochez seulement ce qui marche : `- [x]`.*

- [x] Données lues et enregistrées dans `donnees/releves.json`
- [x] Ajouter un relevé, saisies invalides refusées sans arrêter le programme
- [x] Lister les relevés, message si le journal est vide
- [x] Rechercher par identifiant ou par date ; journées pluvieuses (au moins 10 mm)
- [x] Trier par température ou par pluie
- [x] Synthèse : température moyenne, minimale et maximale de la série, cumul de pluie, journées pluvieuses
- [] Bonus : supprimer et modifier un relevé (choix 6 et 7)
- [] Bonus : tri par température décroissante, journée la plus chaude

## Données

✏️ *Le fichier, le nombre de relevés, les champs (voir [docs/dictionnaire-donnees.md](docs/dictionnaire-donnees.md)), les unités. Rappelez qu'ils sont fictifs.*

## Limites

✏️ *Au moins trois. 
 dix jours de relevés forment une courte série, ils ne décrivent pas le climat de la région.
 L'humidité relative de l'air n'est pas l'humidité du sol
 Le seuil de 10 mm est une catégorie d'exercice : il ne prévoit ni inondation ni stress hydrique.

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

✏️ *Doniguena Salif COULIBALY, doniguenapro-ops !. Entraide : avec qui, sur quoi.*
