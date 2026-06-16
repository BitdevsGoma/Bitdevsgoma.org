---
layout: post
type: socratic
title: "Séminaire Socratique #13"
---

### **Agenda**

**14h00 – 14h20 : Théorie — Comprendre le Lightning Network et son rôle dans Bitcoin**

**Introduction au Lightning Network :**

- Qu'est-ce que le Lightning Network et pourquoi il a été créé
- Différence entre transactions en chaîne et paiements hors chaîne
- Notion de canaux de paiement et réseau de routage
- Avantages : rapidité, faible coût, évolutivité

**Architecture du système :**

- Interaction entre Bitcoin L1 et Lightning L2
- Rôle des Nœuds Foudre
- Canaux, liquidité et routage des paiements
- Notions de base : HTLC (Hash Time-Locked Contracts)

**Cas d'usage modernes :**

- Paiements instantanés en e-commerce
- Applications mobiles de micro-paiements
- Jeux, API payantes, systèmes IoT
- 14h20 – 14h45 : Wallets Lightning, paiements et logique interne

**Gestion des portefeuilles Lightning :**

- Création et gestion de portefeuilles compatibles Lightning
- Ouverture et fermeture de canaux
- Gestion de la liquidité entrante/sortante
- Observation des ventes on-chain vs off-chain

**Construction des paiements :**

- Création de factures Lightning
- Envoi et réception de paiements instantanés
- Routage des paiements dans le réseau
- estion des frais Lightning

**Simulation et tests :**

- utilisation d'un environnement regtest / testnet Lightning
- création de nœuds locaux
- simulation de paiements multi-nœuds
- observation des états de canaux

**14h45 – 15h15 : Atelier 1 — Mise en place d'une application mobile Lightning**

**Technique d'empilement :**

- Interface mobile : React Native
- Côté serveur : Node.js / TypeScript
- Interface API : Next.js (routes API ou actions serveur)

**Installation de l'environnement :**

- configuration du projet mobile React Native
- mise en place du backend TypeScript
- intégration d'un nœud Lightning (local ou testnet)
- backend API de connexion ↔ portefeuille Lightning

**Premier prototype :**

- génération d'une facture depuis le backend
- affichage dans l'app mobile
- Scannez le code QR pour payer
- suivi du statut de transaction

**15h15 – 15h50 : Atelier 2 — Paiements temps réel et système complet**

**Flux complet d'un paiement Lightning :**

- création d'une facture côté backend
- affichage et scan côté mobile
- exécution du paiement via nœud Lightning
- confirmation instantanée côté application

**Automatisation avec TypeScript :**

- API de gestion des paiements
- confirmation du webhook
- synchronisation temps réel avec l'application mobile
- gestion des erreurs réseau et logique de nouvelle tentative

**Analyse du système :**

- compréhension du cycle complet : app → backend → Lightning node → réseau
- surveillance des transactions
- gestion de la fiabilité et de la latence
- bonnes pratiques pour les applications financières mobiles

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


