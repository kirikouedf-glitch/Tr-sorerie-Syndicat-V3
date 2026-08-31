# Trésorerie Syndicat V3 TEST

Prototype séparé de la V2.

## Objectif du test
- prendre une photo d'une facture ou d'un ticket ;
- lire automatiquement le texte avec OCR ;
- proposer date, fournisseur, montant, référence et ventilation ;
- créer automatiquement une pièce de type `AA D NNN` ;
- importer un relevé bancaire CSV ;
- calculer une correspondance selon montant, date et libellé ;
- valider manuellement le rapprochement ;
- verrouiller l'écriture rapprochée.

## Important
- L'OCR utilise Tesseract.js dans le navigateur. Une connexion Internet est nécessaire au premier chargement de la bibliothèque.
- Les données du test sont stockées localement dans le navigateur sous une clé séparée de la V2.
- Le rapprochement reste volontairement validé par l'utilisateur.
- Le prototype n'est pas encore la V3 comptable complète.

## Mise en ligne
Créer de préférence un dépôt séparé, par exemple `tresorerie-syndicat-v3-test`, puis déposer :
- index.html
- manifest.webmanifest
- sw.js
- icon.svg
- README.md

Activer ensuite GitHub Pages sur la branche `main` et `/(root)`.
