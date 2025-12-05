14h00 – 14h15 : Rappel & montée de niveau

Rappel ultra-rapide du script du précédent BitDevs.

Limites du modèle “Si Alice… sinon Bob”.

Pourquoi les scripts complexes nécessitent une réflexion de sécurité (malicious branches, fail-paths, SIGCOUNT, etc).

14h15 – 14h40 : Théorie – Branches imbriquées & multi-conditions

Objectif : maîtriser les contracts complexes proches des “smart contracts” Bitcoin.

Construction d’un script à 2 ou 3 niveaux :

IF (condition1) { … } ELSE { IF (condition2) … }

Combiner :

OP_CHECKSIG

OP_CHECKMULTISIG

OP_CHECKLOCKTIMEVERIFY (CLTV)

OP_CHECKSEQUENCEVERIFY (CSV)

Comprendre les conditions multiples :

“Alice avant bloc X, sinon Bob si 2 signatures, sinon Carol après délai Y”.

14h40 – 15h15 : Atelier 1 – Script imbriqué 3-niveaux

Script à construire :
“Si Alice signe → paiement immédiat ;
sinon si Bob + Carol signent → paiement avant bloc X ;
sinon après bloc X+5 → Carol seule récupère les fonds.”

Création pas à pas du script.

Analyse des chemins d’exécution.

Prévention des erreurs (branches non atteignables, stack errors).

15h15 – 15h45 : Atelier 2 – CLTV + CSV combinés (verrou dur + verrou relatif)

Objectif : utiliser simultanément un verrou absolu et un verrou relatif.

Cas pratique :
“Si Alice signe → dépense immédiate ;
sinon Bob peut dépenser après bloc X
mais uniquement s’il attend 5 blocs après sa transaction (CSV).”

Création et test dans Bitcoin Core.

Validation par simulation de blocs.

Analyse des compromis de sécurité.

15h45 – 16h10 : Atelier 3 – Analyse et traduction du script en Miniscript

Passer de Script brut → Miniscript → Taproot script-path

Introduction rapide : pourquoi Miniscript ?

Traduction du script imbriqué dans le langage Miniscript.

Vérification automatique des propriétés :

complétude

non-malleabilité

sécurité des branches

Construction d’un Taproot script-path avec ce Miniscript.

16h10 – 16h25 : Atelier 4 – Contrat complet Taproot (Tapscript)

Mini smart contract version Taproot :

“Chemin 1 : signature Schnorr d’Alice → instantané.
Chemin 2 : Bob + Carol via multisig → avec CSV 3 blocs.
Chemin 3 : Carol seule après CLTV bloc X.”

Construction de l’arbre Taptree.

Création et test du contrôle de chemin.

Dépense pratique via Bitcoin Core.

16h25 – 16h30 : Q&A – Perspectives & prochaines étapes

Introduction aux vaults Bitcoin (modeling).

Futur : Covenants, OP_CAT, BIP-119, BitVM.

Mini-débat : “Jusqu’où peut-on aller sans casser la simplicité Bitcoin ?”