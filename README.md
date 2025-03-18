# Projet Réseau Switching & VLAN


## Description du Projet
Ce projet consiste à configurer un **réseau de commutation avec redondance et gestion centralisée des VLANs**. Il inclut :
- **VTP (VLAN Trunking Protocol)** pour une gestion centralisée des VLANs.
- **EtherChannel** pour l’agrégation de liens et la redondance.
- **Spanning Tree Protocol (STP)** pour éviter les boucles et garantir la stabilité du réseau.
- **DHCP** pour l’attribution automatique des adresses IP aux clients.
- **Routage Inter-VLAN** permettant la communication entre VLANs via des commutateurs de niveau 3.

##  Topologie du Réseau
Le réseau est conçu pour être **redondant et évolutif** :
- **Deux commutateurs cœur (L3) :** gèrent le routage et le serveur DHCP.
- **Deux commutateurs d’accès (L2) :** connectés aux PC via des VLANs.
- **Liens Trunk et EtherChannel** pour une connectivité fiable et rapide.

- 
##  Fichiers du Projet
-  `project_Full_Switching_Configuration.pkt` → **Fichier Cisco Packet Tracer avec la configuration complète.**
