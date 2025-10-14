---
layout: post
type: socratic
title: "Séminaire Socratique #5"
---

### Agenda

14h00 – 14h25 : **Théorie : Les conditions de dépense dans Bitcoin**



- Rappel rapide : locking script (scriptPubKey) et unlocking script (scriptSig).
- Introduction aux scripts conditionnels : multisig et timelock.
- Principe de OP_CHECKMULTISIG, OP_CHECKLOCKTIMEVERIFY et OP_IF / OP_ELSE / OP_ENDIF.
- Pourquoi ces scripts sont fondamentaux pour la sécurité et les contrats Bitcoin.



14h25 – 14h45 : **Préparation de l’environnement regtest**



- Démarrage du nœud Bitcoin Core en mode regtest.
- Création de trois portefeuilles distincts simulant trois participants (Alice, Bob, Carol).
- Génération de blocs et attribution de fonds de départ.
- Vérification des adresses et soldes initiaux.



14h45 – 15h20 : Atelier 1 : **Créer et utiliser une adresse Multisig 2-of-3**



- Génération des trois clés publiques.
- Construction d’un script multisig et création d’une adresse P2SH correspondante.
- Envoi de fonds vers cette adresse multisig.
- Création et signature d’une transaction nécessitant 2 signatures sur 3.
- Vérification et exécution du script dans regtest.

15h20 – 15h50 : Atelier 2 : **Timelock — Verrouiller une transaction dans le temps**



- Utilisation de nLockTime ou de OP_CHECKLOCKTIMEVERIFY pour bloquer une dépense avant un certain bloc.
- Création d’un UTXO verrouillé jusqu’à un bloc futur.
- Test de dépense avant et après le bloc défini.
- Vérification du comportement avec getblockcount et sendrawtransaction.


15h50 – 16h15 : **Atelier 3 : Mini “contrat intelligent” Bitcoin Script**



- Écriture d’un script conditionnel : “Si Alice signe, paiement direct ; sinon, après 10 blocs, Bob récupère les fonds.”
- Construction manuelle du script (avec OP_IF, OP_ELSE, OP_ENDIF, OP_CHECKSIG, OP_CHECKLOCKTIMEVERIFY).
- Exécution et validation du flux logique dans regtest.


16h15 – 16h30 : **Débat, Q&A et Perspectives**



- Discussion sur l’évolution vers Taproot et Miniscript.
- Avantages des signatures Schnorr et des scripts simplifiés.

---

### Location

L'événement se déroule au **GenesisBar** :

150, Av. Mayi Moto, Kyeshero, Goma, DRCongo,  
Kyeshero  

[Map](https://goo.gl/maps/6S79eh2rn5RK3BhEA)  

---

### Annonces

Nous poursuivons la série de Séminaires Socratiques pour la communauté de développeurs de Goma.  
Prochain rendez-vous : **dernier vendredi du mois prochain au Genesis Bar**.  

---

### Rappels importants

- Pas de photos, vidéos ni enregistrements audio.  
- [Règle de la Maison de Chatham](https://www.chathamhouse.org/about-us/chatham-house-rule) 
- Proposez des idées de sujets pour notre prochain séminaire !  
- Suggest topics for the next Socratic seminar ! [Où trouver des sujets ?](/topics)  
