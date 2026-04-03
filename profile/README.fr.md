# NorminUp — Plateforme de Monitoring SaaS Nouvelle Génération

[English Version](README.md)

![NorminUp Banner](https://img.shields.io/badge/NorminUp-v1.1.0-10B981?style=for-the-badge&logo=activity)
![Status](https://img.shields.io/badge/Status-Operational-10B981?style=for-the-badge)
![License](https://img.shields.io/badge/License-Proprietary-blue?style=for-the-badge)

**NorminUp** est une solution de monitoring SaaS haut de gamme conçue pour offrir une visibilité totale et une résilience distribuée. Alliant une esthétique de pointe (**Glassmorphism**) à une intelligence de diagnostic industrielle, NorminUp permet aux entreprises de sécuriser leurs infrastructures critiques avec une précision chirurgicale.

---

## 1. L'Expérience Visuelle & UX
NorminUp redéfinit l'interface de monitoring avec un design **Dark Mode** natif et une fluidité exceptionnelle.
*   **Identité Glassmorphism** : Cartes dépolies, flous d'arrière-plan et bordures ultra-fines pour une interface moderne et non dispersive.
- **Status Widgets** : Widgets dynamiques intégrables pour afficher l'état de vos services directement sur votre site client.
- **Animations Comportementales** : Micro-interactions fluides et pulsations radar pour un feedback temps-réel immersif.

---

## 2. Monitoring Multimodal & Protocoles
Au-delà du simple "ping", NorminUp supervise plus de **11 types de protocoles** :
- **Web & API** : HTTP/S (GET/POST), WebSocket (WSS), Heartbeats.
- **Réseau & DNS** : TCP, ICMP (Ping), DNS (Propagation), Domain (Whois/Expiration).
- **Services Métiers** : Discord Bots (Présence), Docker (Runtime), Databases (MySQL/Redis), Payment Gateways.
- **Rapid-Fire Verification** : Filtrage intelligent des "blips" réseau par des reprises incrémentales avant confirmation d'alerte.

---

## 3. Diagnostics
En cas d'incident, NorminUp ne se contente pas de signaler la panne, il l'analyse en profondeur :
*   **Audit d'Intégrité MD5** : Détection des "Shadow Hacks" en comparant l'empreinte de la page avec les états précédents.
*   **Audit de Chaîne SSL** : Analyse complète du certificat, de l'émetteur et des dates de validité.
*   **Trace de Redirections** : Audit complet des chaînes de redirection (jusqu'à 5 niveaux) pour détecter les boucles infinies.
*   **Security Header Scoring** : Évaluation en temps réel des headers HSTS, CSP, X-Frame-Options et XSS-Protection.

---

## 4. Résilience Edge & P2P
Une architecture distribuée unique pour une fiabilité sans faille :
- **Consensus Distribué** : Les agents Edge communiquent entre eux via le protocole **Gossip** pour confirmer une panne depuis plusieurs points géographiques (évite les faux positifs).
- **Survival Mode** : Si le serveur maître est injoignable, les agents passent en autonomie totale pour envoyer les alertes directement via SMTP, Slack ou Discord.
- **Edge Analytics** : Mise en tampon locale des métriques en cas de déconnexion réseau momentanée.

---

## 5. Infrastructure & Extension
- **Dynamic SSL (Caddy Ask)** : Gestion automatisée des certificats SSL pour les domaines personnalisés (CNAME).
- **Self-Healing Docker** : Automatisation des remédiations (restart de conteneurs) via l'API Dockerode.
- **Public API & Reference** : Documentation complète pour l'intégration programmatique des services de monitoring.

---

<p align="center">
  <b>NorminUp SaaS</b> • L'excellence dans la résilience infrastructurelle. <br>
  <i>© 2026. Tous droits réservés.</i>
</p>
