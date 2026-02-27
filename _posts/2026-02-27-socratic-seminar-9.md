---
layout: post
type: socratic
title: "Séminaire Socratique #9"
---

### Agenda

14h00 – 14h20 : **Théorie Architecture et modèle LNbits**



**Problématique du Lightning côté applicatif :**

- gestion des canaux
- liquidité entrante et sortante
- gestion multi-wallet
- sécurité et permissions

**Architecture de LNbits :**

- serveur LNbits (wallet server layer)
- connexion à un backend Lightning :

**LND**

**Core Lightning**

- système d’extensions modulaires
- API REST et WebSocket

**Modèle de sécurité :**

- séparation admin key / invoice key
- isolation des wallets
- possibilité de déploiement self-hosted

- Limites du modèle et hypothèses de confiance


14h20 – 14h45: **Théorie Fonctionnalités clés et logique applicative**

- création d’invoices via API
- paiement d’invoices externes
- webhooks et événements temps réel

**LNURL et extensions :**

- LNURL-pay
- LNURL-withdraw
- LNURL-auth

**Extensions natives de LNbits :**

- Point of Sale
- Paywall
- TPoS
- Donation page
- API wallet

**Cas d’usage applicatifs :**

- SaaS Lightning
- Marketplace
- API pay-per-request
- Microservices monétisés

14h45 – 15h15 : **Atelier 1 Déploiement et configuration LNbits**

**Préparation de l’environnement (testnet ou regtest)**

**Déploiement LNbits :**

- via Docker
- connexion à un backend Lightning
- configuration des variables d’environnement

**Création d’un wallet :**

- génération des clés API
- test des endpoints

**Observation :**

- dashboard
- logs
- gestion des permissions


15h15 – 15h50 : **Atelier 2 Construction d’une mini application**

**Script à réaliser :**

- Création d’une invoice via API
- Affichage côté frontend
- Réception d’un paiement

**Implémentation :**

- webhook de confirmation
- mise à jour automatique UI

**Ajout d’un module :**

- activation d’une extension
- simulation d’un paywall

**Analyse :**

- structure des appels API
- sécurité des clés
- scalabilité horizontale

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


