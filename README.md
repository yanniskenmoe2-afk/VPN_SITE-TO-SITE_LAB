KENMOE DOUNBI YANNIS

Étudiant en Systèmes et Réseaux | Administration IT | Objectif Cybersécurité

Concevoir. Configurer. Sécuriser. Documenter.

Étudiant en troisième année à l'Institut Africain d'Informatique (IAI), au Cameroun, option Systèmes et Réseaux, je développe mes compétences à travers des travaux pratiques et des laboratoires consacrés à la conception, au déploiement, à l'administration et à la sécurisation des infrastructures informatiques.

Mon parcours me permet d'explorer plusieurs domaines complémentaires : la commutation et le routage, la segmentation des réseaux, les services d'infrastructure, l'administration des systèmes Linux, la virtualisation et la sécurité des communications.

À travers des environnements de simulation et des laboratoires virtuels, je m'exerce à configurer des équipements, à mettre en œuvre des services réseau, à analyser les problèmes de connectivité et à vérifier le fonctionnement des solutions déployées.

Mon objectif est de contribuer à la mise en place d'infrastructures informatiques fiables, performantes et sécurisées, tout en progressant vers une spécialisation en cybersécurité.

Je considère chaque laboratoire comme une occasion de transformer les connaissances théoriques en compétences techniques vérifiables, avec une attention particulière portée à la documentation, aux tests et à l'analyse des résultats.

---

À propos de moi

- 🎓 Formation : étudiant en troisième année à l'IAI Cameroun, option Systèmes et Réseaux.
- 💻 Administration systèmes : intérêt pour Linux, Ubuntu Server, la virtualisation, les services réseau et la gestion des environnements informatiques.
- 🌐 Réseaux informatiques : configuration des VLAN, routage inter-VLAN, adressage IP, DHCP, relais DHCP, ACL et diagnostic de connectivité.
- 🔀 Switching et routing : étude des mécanismes de commutation, de segmentation, de routage statique et dynamique, ainsi que des protocoles de redondance et d'agrégation de liens.
- 🔐 Sécurité réseau : mise en œuvre de règles de pare-feu, étude des VPN IPsec site-à-site, filtrage du trafic et contrôle des communications entre réseaux.
- 🧪 Laboratoires pratiques : conception de topologies, configuration d'équipements, tests fonctionnels, dépannage et validation des résultats.
- 📊 Supervision et détection : découverte des solutions de supervision de sécurité, des systèmes de détection d'intrusion et de l'analyse des événements réseau.
- 📁 Documentation technique : rédaction de README, réalisation de schémas d'architecture et organisation de projets avec Git et GitHub.
- 🎯 Objectif professionnel : évoluer dans l'administration des systèmes et réseaux, puis approfondir mes compétences en sécurité des infrastructures et en cybersécurité.

Compétences techniques

Domaine| Technologies et notions
Switching| VLAN, ports d'accès, trunks, STP/PVST, EtherChannel
Routing| Routage inter-VLAN, SVI, VLANIF, Router-on-a-Stick, routage statique, notions de RIP, OSPF et EIGRP
Adressage et services réseau| IPv4, IPv6, subnetting, VLSM, DHCP, DHCP Relay, DNS, SLAAC, DHCPv6
Contrôle des communications| ACL, filtrage du trafic, segmentation réseau et contrôle d'accès
Équipements et simulation réseau| Cisco Packet Tracer, Huawei eNSP
Sécurité réseau| pfSense, VPN IPsec, règles de pare-feu et diagnostic des tunnels
Systèmes et virtualisation| Linux, Ubuntu Server, VMware, virtual box 
Services d'infrastructure| BIND9, Postfix, Dovecot, Roundcube
Supervision et détection| Wazuh, Suricata, notions de SIEM, IDS/IPS et analyse d'anomalies réseau
Documentation et conception| Markdown, Git, GitHub, draw.io

Ces domaines correspondent à des compétences pratiquées, étudiées ou en cours d'approfondissement selon les technologies. Les projets associés permettent de préciser le niveau de mise en œuvre et les résultats obtenus.

---

Projets pratiques

1. VPN IPsec site-à-site avec pfSense

Objectif : étudier et mettre en œuvre l'interconnexion de deux réseaux locaux distants à travers un tunnel VPN IPsec, afin de comprendre les mécanismes de communication sécurisée entre sites.

Environnement : pfSense, VMware et deux réseaux locaux virtuels.

Travaux réalisés ou étudiés :

- Déploiement de deux pare-feu pfSense dans un environnement virtualisé.
- Configuration des interfaces WAN et LAN et identification des réseaux de chaque site.
- Paramétrage des phases 1 et 2 d'IPsec.
- Définition des réseaux locaux concernés par le tunnel et des paramètres de négociation.
- Configuration des règles de filtrage nécessaires aux communications.
- Vérification de l'état du tunnel et analyse des informations de diagnostic.
- Tests de connectivité entre les équipements et les réseaux distants.
- Recherche des causes possibles d'échec de communication à partir des règles de pare-feu, du routage et des journaux.

Compétences mobilisées : VPN, pare-feu, adressage IP, virtualisation, diagnostic réseau et analyse des communications intersites.

Documentation et résultats : "Consulter le laboratoire VPN" (https://github.com/yanniskenmoe2-afk/VPN_SITE-TO-SITE_LAB)

2. Segmentation VLAN et routage inter-VLAN avec Huawei eNSP

Objectif : concevoir un réseau local segmenté en plusieurs VLAN et permettre la communication entre les réseaux virtuels à l'aide des interfaces VLANIF.

Environnement : Huawei eNSP.

Travaux réalisés :

- Analyse de la topologie et définition des VLAN nécessaires à la segmentation.     
- Création et configuration des VLAN sur les équipements.
- Affectation des ports aux VLAN correspondants.
- Configuration des interfaces VLANIF pour assurer le routage inter-VLAN.
- Vérification de l'adressage et des passerelles des différents réseaux.
- Tests de connectivité entre les équipements d'un même VLAN et entre les VLAN.
- Analyse des erreurs de configuration pouvant empêcher la communication.

Compétences mobilisées : switching, segmentation logique, interfaces VLANIF, routage inter-VLAN et dépannage.

Documentation : "Découvrir mes projets Huawei" (https://github.com/yanniskenmoe2-afk)

3. Réseau Cisco : VLAN, DHCP, relais DHCP et ACL

Objectif : mettre en place une architecture réseau segmentée permettant l'attribution automatique des adresses IP, le routage entre les VLAN et le contrôle des communications par listes de contrôle d'accès.

Environnement : Cisco Packet Tracer, avec trois routeurs et plusieurs segments réseau.

Travaux réalisés :

- Création de quatre VLAN : 10, 20, 30 et 40.
- Organisation des réseaux virtuels pour séparer logiquement les équipements.
- Configuration des pools DHCP sur le routeur central.
- Mise en place d'un relais DHCP sur un autre routeur pour transmettre les requêtes des clients vers le serveur DHCP.
- Configuration du routage inter-VLAN de type Router-on-a-Stick.
- Mise en œuvre d'ACL pour filtrer les communications et contrôler l'accès à certains services, notamment HTTP.
- Vérification de l'attribution des adresses IP, des passerelles et de la connectivité.
- Utilisation de commandes de diagnostic pour examiner les baux DHCP, les interfaces et les règles de filtrage.

Compétences mobilisées : switching, routing, DHCP, DHCP Relay, ACL, adressage IP et dépannage réseau.

Documentation : "Retrouver mes projets Cisco" (https://github.com/yanniskenmoe2-afk)

---

Ma démarche technique

Pour chaque projet, je privilégie une approche structurée inspirée des méthodes utilisées en administration des infrastructures informatiques :

1. Analyser le besoin : comprendre les objectifs, identifier les contraintes et déterminer les services attendus.
2. Concevoir l'architecture : élaborer la topologie, organiser les segments réseau et définir le plan d'adressage.
3. Configurer les équipements : appliquer les paramètres nécessaires aux routeurs, commutateurs, pare-feu et services système.
4. Valider le fonctionnement : vérifier les communications, l'attribution des adresses, le routage et les règles de filtrage.
5. Diagnostiquer les incidents : analyser les configurations, les journaux et les résultats des commandes de test pour identifier les erreurs.
6. Documenter les résultats : présenter les choix techniques, les commandes utiles, les schémas et les captures qui démontrent le fonctionnement.
7. Améliorer la solution : identifier les limites du laboratoire et les améliorations possibles en matière de performance, de disponibilité et de sécurité.

L'objectif est de produire des laboratoires reproductibles, compréhensibles et techniquement documentés, qui permettent de suivre le raisonnement adopté et de vérifier les résultats obtenus.

---

Objectifs d'évolution

Je souhaite approfondir progressivement mes connaissances et mes compétences dans les domaines suivants :

- Administration système : maîtrise plus avancée de Linux, des services réseau, des permissions et de l'automatisation des tâches.
- Architecture réseau : approfondissement du switching, du routage dynamique, de la haute disponibilité et du dépannage.
- Sécurité des infrastructures : renforcement des connaissances en pare-feu, VPN, segmentation et contrôle d'accès.
- Supervision et détection : développement de compétences autour des SIEM, de la centralisation des journaux et des systèmes IDS/IPS.
- Analyse réseau : compréhension du trafic, investigation des incidents et détection des comportements anormaux.
- Automatisation et Machine Learning : exploration de méthodes permettant d'améliorer l'administration et la détection d'anomalies réseau.
- Cybersécurité : progression vers des pratiques de sécurisation, d'audit et de surveillance des infrastructures informatiques.

Ces axes constituent ma feuille de route d'apprentissage et de spécialisation. Ils orientent les futurs laboratoires que je souhaite développer et documenter dans mon portfolio.

---

Me contacter

Je suis ouvert aux opportunités de stage, aux échanges techniques et aux projets collaboratifs dans les domaines des systèmes, des réseaux et de la cybersécurité.

- GitHub : "yanniskenmoe2-afk" (https://github.com/yanniskenmoe2-afk)
- Email : yanniskenmoe2@gmail.com

---

Portfolio en évolution — chaque projet documenté représente une étape dans mon parcours vers la conception, l'administration et la sécurisation des infrastructures informatiques.
