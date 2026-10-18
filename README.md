# VPN IPsec site-à-site avec pfSense sous VMware

## Présentation
Ce laboratoire porte sur l’étude d’un VPN IPsec site-à-site entre deux pare-feu pfSense virtualisés sous VMware. La topologie a été dessinée avec draw.io et l’environnement réseau est simulé avec des machines virtuelles.

## Objectifs
- Comprendre le rôle d’un VPN site-à-site.
- Relier deux réseaux locaux distants à travers des interfaces WAN.
- Préparer les paramètres IPsec des deux pare-feu.
- Vérifier la connectivité et diagnostiquer les problèmes du tunnel.

## Architecture logique
- **Site 1 :** réseau LAN derrière pfSense 1.
- **Site 2 :** réseau LAN derrière pfSense 2.
- **WAN :** réseaux de transit reliant les interfaces externes des pare-feu.
- **Tunnel IPsec :** liaison logique qui transporte le trafic autorisé entre les LAN.

La topologie détaillée est représentée séparément dans le schéma draw.io du projet.

## Étapes principales
1. Créer les machines virtuelles pfSense et leurs interfaces réseau.
2. Vérifier l’adressage WAN et LAN ainsi que la connectivité du réseau de transit.
3. Configurer les réseaux locaux et les règles de pare-feu nécessaires.
4. Définir des paramètres IPsec compatibles sur les deux pare-feu : phase 1, phase 2, réseaux locaux et distants.
5. Autoriser le trafic nécessaire dans les règles de pare-feu.
6. Vérifier l’état du tunnel et tester la communication entre les postes des deux sites.

## Contrôles et diagnostic
- Vérifier que les interfaces WAN ont des adresses dans les réseaux attendus.
- Confirmer que les deux WAN peuvent communiquer à travers le réseau de transit.
- Vérifier la correspondance des paramètres IPsec des deux côtés.
- Examiner l’état du tunnel et les journaux IPsec.
- Tester d’abord la connectivité locale, puis la communication entre les deux LAN.

## Résultat attendu
Lorsque les interfaces, les routes, les règles de pare-feu et les paramètres IPsec sont correctement configurés, les hôtes autorisés des deux LAN peuvent communiquer à travers le tunnel chiffré.

## Environnement
- Virtualisation : VMware
- Pare-feu : pfSense
- VPN : IPsec site-à-site
- Schéma de topologie : draw.io

## Compétences démontrées
- Virtualisation de pare-feu.
- Adressage et diagnostic réseau.
- Notions de VPN IPsec site-à-site.
- Analyse des journaux et résolution de problèmes.

> **À compléter avant publication :** ajouter le schéma draw.io exporté en PNG, le plan d’adressage utilisé et des captures d’écran montrant l’état du tunnel et les tests de connectivité. Ne publiez aucune clé pré-partagée ni aucun secret dans le dépôt.
