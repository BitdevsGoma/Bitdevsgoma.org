---
layout: post
type: socratic
title: "Séminaire Socratique #6"
---

### Agenda

14h00 – 14h20 : **Théorie avancée Multisig & scripts conditionnels**


- Rappel rapide : multisig 2-of-3 et timelock.
- Introduction aux scripts conditionnels combinant multisig et timelock.
- Cas pratique : “2 signatures avant bloc X, sinon 1 signature alternative après bloc X”.



14h20 – 14h40 : **Préparation de l’environnement de test**


- Démarrage d’un nœud Bitcoin Core sur ordinateur.
- Création de trois portefeuilles simulant trois participants (Alice, Bob, Carol).
- Génération de blocs et attribution de fonds initiaux.
- Vérification des soldes et adresses.


14h40 – 15h25 : **Atelier 1 – Multisig 2-of-3 approfondi**


- Création et combinaison de clés publiques pour un multisig 2-of-3.
- Construction d’une adresse P2SH multisig et envoi de fonds.
- Création et signature d’une transaction multisig.
- Vérification et exécution complète.


15h25 – 15h55 : **Atelier 2 – Multisig + timelock (Mini contrat)**


- Construction d’un script combinant multisig et verrou temporel : “2 signatures avant bloc X, sinon 1 signature d’un autre participant après bloc X”.
- Simulation et test des dépenses avant et après le bloc défini.
- Validation du comportement avec les commandes Bitcoin Core.



15h55 – 16h20 : **Atelier 3 – Script conditionnel avancé (Mini contrat intelligent)**


- Script : “Si Alice signe, paiement immédiat ; sinon après 5 blocs, Bob ou Carol récupère les fonds.”
- Construction manuelle du script avec OP_IF, OP_ELSE, OP_ENDIF, OP_CHECKSIG, OP_CHECKLOCKTIMEVERIFY.
- Test complet du flux logique et validation.



16h20 – 16h30 : **Débat, Q&A et perspectives**


- Discussion sur Taproot et Miniscript.
- Avantages des signatures Schnorr pour les multisig et les contrats complexes.
- Applications réelles : garde-fous, escrow, DAO simplifiés.


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


