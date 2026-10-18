# Configuration extraite — `config-pfSense.home.arpa-2.xml`

> Synthèse de la configuration XML fournie. Les secrets sont volontairement exclus. Vérifier les valeurs dans l'interface pfSense avant publication.

## Interfaces

| Élément | Valeur extraite |
|---|---|
| WAN | `em0`, adresse obtenue par DHCP |
| LAN | `em1` — `192.168.2.2/24` |

## IPsec — Phase 1

| Paramètre | Valeur extraite |
|---|---|
| Identifiant IKE | `1` |
| Version IKE | IKEv2 |
| Interface | WAN |
| Adresse du pair configurée (`remote-gateway`) | `192.168.175.143` |
| Authentification | Clé prépartagée (valeur secrète non reproduite) |
| Chiffrement | AES-256-GCM (champ `keylen` du XML : `128`) |
| PRF | SHA-256 |
| Groupe Diffie-Hellman | 14 |
| Durée de vie | `28800` secondes |
| NAT Traversal | Activé |
| DPD | délai `10` s, maximum `5` échecs |
| Description | `vpn vers wan site distant` |

## IPsec — Phase 2

| Paramètre | Valeur extraite |
|---|---|
| Mode | Tunnel |
| Réseau local | LAN (réseau de l'interface LAN : `192.168.2.0/24`) |
| Réseau distant | `192.168.1.0/24` |
| Protocole | ESP |
| Chiffrement | AES-256-GCM |
| PFS | Groupe 14 |
| Durée de vie | `3600` secondes |
| Hôte de vérification | `192.168.1.1` |
| Keepalive | Désactivé |
| Description | `lies vers lan site a` |

