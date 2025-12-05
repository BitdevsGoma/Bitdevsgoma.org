---
layout: post
type: socratic
title: "Séminaire Socratique #7"
---

### Agenda

14h00 – 14h15 : **Rappel & montée de niveau**


- Rappel ultra-rapide du script du précédent BitDevs.
- Limites du modèle “Si Alice… sinon Bob”.
- Pourquoi les scripts complexes nécessitent une réflexion de sécurité (malicious branches, fail-paths, SIGCOUNT, etc).



14h15 – 14h40 : **Théorie – Branches imbriquées & multi-conditions**

**Construction d’un script à 2 ou 3 niveaux :**

- IF (condition1) { … } ELSE { IF (condition2) … }
- Combiner :
- OP_CHECKSIG
- OP_CHECKMULTISIG
- OP_CHECKLOCKTIMEVERIFY (CLTV)
- OP_CHECKSEQUENCEVERIFY (CSV)
- Comprendre les conditions multiples :
- “Alice avant bloc X, sinon Bob si 2 signatures, sinon Carol après délai Y”.



14h40 – 15h15 : **Atelier 1 – Script imbriqué 3-niveaux**



- Script à construire :
- “Si Alice signe → paiement immédiat ;
- sinon si Bob + Carol signent → paiement avant bloc X ;
- sinon après bloc X+5 → Carol seule récupère les fonds.”

**Création pas à pas du script.**

- Analyse des chemins d’exécution.
- Prévention des erreurs (branches non atteignables, stack errors).


15h15 – 15h45 : **Atelier 2 – CLTV + CSV combinés (verrou dur + verrou relatif)**


**Cas pratique :**

- “Si Alice signe → dépense immédiate ;
- sinon Bob peut dépenser après bloc X mais uniquement s’il attend 5 blocs après sa transaction (CSV).”
- Création et test dans Bitcoin Core.
- Validation par simulation de blocs.
- Analyse des compromis de sécurité.



15h45 – 16h10 : **Atelier 3 – Analyse et traduction du script en Miniscript**



- Passer de Script brut → Miniscript → Taproot script-path
- Introduction rapide : pourquoi Miniscript ?
- Traduction du script imbriqué dans le langage Miniscript.
- Vérification automatique des propriétés :
- complétude
- non-malleabilité
- sécurité des branches
- Construction d’un Taproot script-path avec ce Miniscript.




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


