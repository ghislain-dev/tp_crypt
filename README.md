## Travail réalisé par Ghislain Mundeke Kasereka  
### dans le cadre d’une recherche scientifique

# 🔐 Application de Chiffrement Asymétrique (RSA)

## 📌 Description

Cette application web permet de simuler un échange sécurisé de messages entre deux utilisateurs (**Ghislain** et **Kasereka**) en utilisant le **chiffrement asymétrique (RSA)**.

Elle illustre les concepts fondamentaux de la cryptographie moderne tels que :

* le chiffrement/déchiffrement
* l’utilisation des clés publiques et privées
* le principe de sécurité basé sur les clés

---

## 🎯 Objectifs du projet

* Comprendre le fonctionnement du **chiffrement asymétrique**
* Simuler une communication sécurisée entre deux utilisateurs
* Appliquer les principes fondamentaux de la cryptographie moderne
* Illustrer le **principe de Kerckhoffs**

---

## 🧠 Concepts utilisés

### 🔑 Chiffrement asymétrique (RSA)

Le système repose sur deux clés :

* **Clé publique** : utilisée pour chiffrer
* **Clé privée** : utilisée pour déchiffrer

👉 Un message chiffré avec une clé publique ne peut être déchiffré que par la clé privée correspondante.

---

### 📜 Principe de Kerckhoffs

> La sécurité d’un système ne doit pas dépendre du secret de l’algorithme, mais uniquement de la clé.

✔️ Dans cette application :

* Les algorithmes sont publics
* Seules les clés privées restent secrètes

---

## ⚙️ Fonctionnalités

* 🔐 Génération de paires de clés (publique / privée)
* ✉️ Chiffrement de message
* 📥 Déchiffrement de message
* 👥 Simulation de communication entre deux utilisateurs :

  * Ghislain
  * Kasereka
* 📊 Interface simple et intuitive

---

## 🔄 Fonctionnement

### 1. Génération des clés

Chaque utilisateur génère :

* une clé publique
* une clé privée

### 2. Chiffrement

* Ghislain écrit un message
* Il chiffre le message avec **la clé publique de Kasereka**

### 3. Envoi

* Le message chiffré est transmis à Kasereka

### 4. Déchiffrement

* Kasereka utilise **sa clé privée**
* Il retrouve le message original

---

## 📌 Règles importantes

* ❌ Ghislain ne peut pas déchiffrer le message qu’il a chiffré
* ✅ Seul Kasereka peut déchiffrer avec sa clé privée
* 🔒 Les clés privées ne doivent jamais être partagées

---

## 🛠️ Technologies utilisées

* HTML5
* CSS3 / Bootstrap
* JavaScript
* Node.js selon

---


## 🔒 Sécurité

* Respect du principe de Kerckhoffs
* Aucune clé privée stockée en base de données
* Validation des entrées utilisateur
* Protection contre les injections

---

## 🚀 Améliorations possibles

* Ajout de la signature numérique
* Intégration de certificats (X.509)
* Communication en temps réel (WebSocket)
* Interface utilisateur avancée
* Export des clés en fichier

---

## 👨‍💻 Auteurs

* Ghislain Mundeke
* (Projet académique en cryptographie)

---

## 📚 Références

* Rivest, Shamir, Adleman (RSA, 1978)
* Kerckhoffs (1883)
* NIST (AES, 2001)

---
* transformer ce README en **document Word pour ton mémoire**
* ou l’adapter en **chapitre académique complet (chapitre 2 ou 3)**
