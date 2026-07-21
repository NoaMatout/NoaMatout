# Noa Matout

**Ingénieur Systèmes et Réseaux** — Reims, France

Je conçois, automatise et sécurise des infrastructures de production. Au quotidien :
un parc mixte Windows / Linux d'environ 180 serveurs, industrialisé avec Ansible,
sur socle VMware vSphere et Azure VMware Solution.

En parallèle, je co-développe **ZON**, un SaaS de coaching sportif — où je m'occupe
du développement et de la sécurité applicative.

---

## Stack

**Systèmes**
Windows Server · Active Directory · Debian / RHEL · Intune

**Automatisation**
Ansible · PowerShell · Python · inventaires dynamiques · patch management

**Virtualisation & Cloud**
VMware vSphere · Azure VMware Solution · Azure

**Sauvegarde & PRA**
Veeam Backup & Replication

**Sécurité**
Durcissement système · analyse de malware · sécurité applicative
(Supabase RLS, authentification, webhooks Stripe)

---

## Projets

### 🏋️ ZON — SaaS de coaching sportif

Plateforme de coaching hybride : builder de programmes d'entraînement,
facturation Stripe intégrée, application iOS / Android pour les athlètes.

- Site : [justzon.com](https://justzon.com)
- App Store : [Zōn – Workout Tracker & Coach](https://apps.apple.com/us/app/z%C5%8Dn-workout-tracker-coach/id6758308655)
- Stack : Swift · Supabase · Stripe
- Mon rôle : développement et sécurité applicative

*Projet co-développé. Code propriétaire — non open source.*

### ☎️ [cucm-call-forwarding](https://github.com/NoaMatout/cucm-call-forwarding)

Renvois d'appel inter-sites sur Cisco CUCM. Détection des chaînes et des
boucles de renvoi, classification graduée de l'état réel des sites, et
écritures compensées sur une API qui n'offre aucune transaction — avec
vérification du rétablissement par relecture plutôt que par absence d'erreur.

Python · AXL / SOAP · 83 tests, 91 % de couverture

### 🔧 [ansible-server-management](https://github.com/NoaMatout/ansible-server-management)

Gestion d'un parc mixte Windows / Linux : mises à jour Windows pilotées par
Ansible en remplacement de WSUS (fenêtres de maintenance, déploiement par
vagues, rapports) et provisionnement de VMs vSphere avec socle de base.

Ansible · PowerShell · vSphere · ansible-lint profil production en CI

### 🦠 [Malware_Analyzer](https://github.com/NoaMatout/Malware_Analyzer)

Analyse de fichiers suspects via l'API VirusTotal v3. Recherche par SHA-256
avant tout envoi : un fichier n'est transmis que si son empreinte est inconnue
et que l'envoi est demandé explicitement.

Python · VirusTotal API v3

*Ces trois projets sont des réimplémentations génériques, écrites à partir de
problèmes rencontrés en production. Ils ne contiennent aucune donnée
d'infrastructure réelle.*

---

## Contact

- **LinkedIn** — [noa-matout](https://www.linkedin.com/in/noa-matout/)
- **Email** — noamatout@gmail.com
