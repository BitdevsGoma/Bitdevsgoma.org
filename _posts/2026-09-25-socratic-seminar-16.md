---
layout: post
type: socratic
title: "Séminaire Socratique #16"
---

### **Agenda**



### ** BITCOIN SANS MAGIE : CONSTRUIS ET SIGNE TA PREMIÈRE TRANSACTION **


Derrière chaque transaction Bitcoin se cachent des UTXOs que vous pouvez comprendre, contrôler et construire. Après avoir mis en place notre environnement Regtest en août, l’objectif de cette session est de construire manuellement une transaction, sélectionner les UTXOs, définir les outputs, calculer les frais, la signer puis la diffuser sur le réseau local.


### **14h00 – 14h20 : Les fondations d'une transaction Bitcoin**


* Qu'est-ce qu'un UTXO (Unspent Transaction Output) ?
* Structure anatomique d'une transaction : Inputs, Outputs et Witness
* Fonctionnement de la sélection des UTXOs et gestion du monnaie rendue (Change)
* Comprendre la notion de frais de transaction (Sat/vByte)


### **14h20 – 14h45 : Préparation des composants sur Regtest**


* Inspection des UTXOs disponibles avec les commandes RPC
* Définition de l'adresse de destination et du montant
* Calcul précis de la taille de la transaction et estimation des frais
* Définition de l'adresse de rendu pour le reliquat


### **14h45 – 15h15 : Atelier — Construction et signature de la transaction**


* Création d'une transaction brute non signée (`createrawtransaction`)
* Décodage et vérification de la structure JSON (`decoderawtransaction`)
* Signature cryptographique de la transaction avec les clés privées (`signrawtransactionwithwallet`)
* Inspection des données witness et du script de déverrouillage


### **15h15 – 15h50 : Atelier — Diffusion, minage et vérification**


* Broadcast de la transaction brute sur le réseau local (`sendrawtransaction`)
* Observation de la transaction dans le Mempool avant confirmation
* Minage d'un bloc pour valider la transaction
* Analyse finale de la transaction confirmée via les commandes RPC


Le résultat recherché à la fin est très simple : **chaque participant doit être capable de comprendre ce qui se passe derrière un simple bouton « Envoyer »[cite: 1], de maîtriser le modèle UTXO et d'assembler manuellement une transaction Bitcoin de A à Z.**


---

### Location

L'événement se déroule au **Genesis Bar**

Sis 150, Av. Mayimoto, Q. Kyeshero  
Goma / Nord-Kivu DRC
Réf: Hôpital DOCS Kyeshero 

[Map](https://goo.gl/maps/6S79eh2rn5RK3BhEA)  

---

### Annonces

Nous poursuivons la série de Séminaires Socratiques pour la communauté de développeurs de Goma.  
Prochain rendez-vous : **Vendredi 25 Septembre 2026 de 14h00 à 16h00 au Genesis Bar**  

Sponsorisé par **Btrust**.

---

### Rappels importants

- Pas de photos, vidéos ni enregistrements audio.  
- [Règle de la Maison de Chatham](https://www.chathamhouse.org/about-us/chatham-house-rule) 
- Proposez des idées de sujets pour notre prochain séminaire !  
- Suggest topics for the next Socratic seminar ! [Où trouver des sujets ?](/topics)