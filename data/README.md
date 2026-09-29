# Données du dictionnaire — Aide Mots Fléchés

Fichiers embarqués dans l'application, publiés ici sous les licences de leurs sources.
Construits le 29/09/2026 par `scripts/build-pack-fr.js` (dépôt de l'application).

## `fr-words.txt` — Mozilla Public License 2.0

> This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0.
> If a copy of the MPL was not distributed with this file, You can obtain one at
> https://mozilla.org/MPL/2.0/.

Dérivé du **Lexique des formes fléchies du français — Grammalecte v7.7** (Olivier R., Dicollecte),
https://grammalecte.net/dic/lexique-grammalecte-fr-v7.7.zip, licence MPL 2.0, consulté le 29/09/2026.

Modifications : mots ramenés à leur écriture de grille (capitales sans accents, sans trait d'union ni
apostrophe), regroupés par longueur et triés par nombre d'occurrences du lexique ; ajout d'un masque de
catégories (nom propre, sigle, abréviation, pluriel, verbe conjugué, rare) tiré des étiquettes du lexique.

Format : section `@longueur <tab> nombre`, puis `MOT <tab> fréquence 0-99 <tab> catégories <tab> graphies <tab> lemmes (index base 36)`.

## `fr-clues.txt` — Creative Commons Attribution-ShareAlike 4.0

Dérivé du **Wiktionnaire** (https://fr.wiktionary.org), contributeurs du Wiktionnaire, via l'extraction
Wiktextract publiée par kaikki.org (https://kaikki.org/frwiktionary/, extraction du 01/09/2026 ;
T. Ylonen, « Wiktextract: Wiktionary as Machine-Readable Structured Data », LREC 2022).
Licence : CC BY-SA 4.0, https://creativecommons.org/licenses/by-sa/4.0/ — ce fichier est publié sous
la même licence.

Modifications : seuls des mots isolés des définitions et des synonymes ont été retenus, sans accents,
comme index inversé « mot → mots du dictionnaire » ; aucune définition n'est reproduite.
