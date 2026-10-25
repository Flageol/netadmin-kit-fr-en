# Kit NetAdmin FR/EN

Bilingual network templates and diagnostic tools for documenting your work.
Modèles réseau bilingues et outils de diagnostic pour documenter vos interventions.

**[Store / Boutique — Payhip](https://payhip.com/b/aPeEB)** · Launch price / Prix de lancement : **39 CAD**, one-time payment / paiement unique. Check the offered version before purchasing / Vérifiez la version proposée avant l’achat.

## Interface screenshots / Captures de l’interface

Actual NetAdmin v7 screenshots with fictional sample data. / Captures réelles de NetAdmin v7 avec des données fictives de démonstration.

### Overview / Vue d’ensemble

PC diagnostics and PDF/Excel export controls. / Diagnostic du PC et accès aux exports PDF et Excel.

![NetAdmin v7 overview — fictional sample data](https://github.com/user-attachments/assets/708b6859-aed2-4db0-82df-f53cfa2d948c)

### Network discovery / Découverte réseau

Example of detected devices, MAC addresses and open TCP ports. / Exemple d’appareils détectés, d’adresses MAC et de ports TCP ouverts.

![NetAdmin v7 network discovery — fictional sample data](https://github.com/user-attachments/assets/79cd97d5-eb6f-4b51-b4be-2cb940a57a08)

### Change request / Demande de changement

Prefilled CAB to complete, save and export. / CAB prérempli à compléter, sauvegarder et exporter.

![NetAdmin v7 CAB — demo draft](https://github.com/user-attachments/assets/07f62f57-7e26-4454-8d01-6ce4430764bb)

## English

The kit includes Word change-request, test and rollback templates, a fictional worked example, Excel VLAN/IP/interconnection inventories, Markdown/CSV copies and a basic Bash diagnostic.

### Newly prepared version: v7

- Automatic Windows diagnostics without entering an IP address.
- Local web page with overview, inventory, tests/routes, network discovery and editable CAB.
- Genuine .xlsx export with six sheets: Inventory, Routes, Tests, CAB, Discovery and TCP Ports.
- PDF export through browser printing, for the current section or full dossier.
- Save edited CAB fields in a standalone HTML page that can be reopened later.
- Optional active discovery of local private IPv4 devices, available MAC addresses, detection evidence and open TCP ports.

**Launching v7:** extract the entire ZIP. Double-click `START_NETADMIN.cmd` for local diagnostics, or `NETWORK_DISCOVERY.cmd` to add discovery. The browser opens after collection. Rerun the launcher to refresh the snapshot.

Discovery uses the default-route IPv4 interface and the PC’s local /24 slice, or its actual smaller subnet, with **at most 254 addresses**. Tested TCP ports: **22, 53, 80, 135, 139, 443, 445, 3389, 5985, 8080, 8443 and 9100**. Other VLANs, public ranges and UDP ports are not automatically explored.

OPEN means a TCP connection was accepted; CLOSED means it was refused; NO_RESPONSE means no connection was established within the deadline. Devices may block these checks, and neighbor-cache entries may be stale. An open port does not establish service identity or a vulnerability. Use discovery on your own or an authorized network.

Requires Windows 10/11, Windows PowerShell 5.1 and a modern browser. No server installation, network configuration changes or permanent PowerShell policy changes. Organizational policies still apply. Device configurations and switch VLANs are not automatically retrieved.

**Release status: v7 has been prepared and tested locally. The Payhip download has not yet been replaced with v7. This public repository documents the features and does not distribute the paid ZIP.**

See the [free English preview](PREVIEW_EN.md).

## Français

Le kit comprend des modèles Word de demande de changement, de tests et de retour arrière, un exemple fictif rempli, ainsi que des inventaires Excel VLAN, IP et interconnexions. Des copies Markdown/CSV et un diagnostic Bash simple sont également inclus.

### Nouvelle version préparée : v7

- Diagnostic Windows automatique, sans adresse IP à saisir.
- Page web locale : vue d’ensemble, inventaire, tests et routes, découverte réseau et CAB modifiable.
- Export Excel .xlsx avec six feuilles : Inventaire, Routes, Tests, CAB, Découverte et Ports TCP.
- Export PDF par l’impression du navigateur, pour la section affichée ou le dossier complet.
- Sauvegarde du CAB modifié dans une page HTML autonome, à rouvrir plus tard.
- Découverte active facultative : adresses IP, MAC disponibles, source de détection et ports TCP ouverts.

**Lancement v7 :** extraire tout le ZIP. Double-cliquer sur `DEMARRER_NETADMIN.cmd` pour le diagnostic local, ou `DECOUVERTE_RESEAU.cmd` pour ajouter la découverte réseau. La page s’ouvre après la collecte. Relancer le CMD pour actualiser les données.

La découverte utilise l’interface ayant la route IPv4 par défaut, sur le bloc /24 contenant le PC ou son sous-réseau réel s’il est plus petit : **254 adresses maximum**. Ports TCP testés : **22, 53, 80, 135, 139, 443, 445, 3389, 5985, 8080, 8443 et 9100**. Les autres VLAN, les plages publiques et les ports UDP ne sont pas explorés automatiquement.

OPEN : connexion TCP acceptée. CLOSED : connexion refusée. NO_RESPONSE : aucune connexion établie dans le délai. Un appareil peut bloquer les tests; le cache voisin peut contenir des entrées anciennes. Un port ouvert ne confirme ni l’identité du service ni une vulnérabilité. Utiliser la découverte sur votre réseau ou avec l’autorisation de son responsable.

Prérequis : Windows 10/11, Windows PowerShell 5.1 et navigateur moderne. Aucun serveur à installer. Aucune configuration réseau ni politique PowerShell permanente n’est modifiée; les politiques de votre organisation restent applicables. Le programme ne récupère pas automatiquement les configurations Cisco/Fortinet ou les VLAN des commutateurs.

**État de diffusion : la v7 a été préparée et testée localement. Le fichier Payhip n’a pas encore été remplacé par la v7. Ce dépôt présente les fonctionnalités; il ne distribue pas le ZIP payant.**

Consultez [l’aperçu gratuit en français](APERCU_FR.md).

## Scope and rights / Portée et droits

Generated CAB documents remain **unapproved drafts**. Complete decisions, owners, backups, approvals and rollback before implementation. Review internal names and addresses before sharing exports.

Le CAB généré reste un **brouillon non approuvé** : compléter les décisions, responsables, sauvegardes, approbations et retour arrière avant une intervention. Relire les noms et adresses internes avant de partager les exports.

Fictional examples to adapt to your environment. No Cisco or Fortinet affiliation. You may adapt the previews for internal changes. Redistribution of the paid kit is not authorized.

Exemples fictifs à adapter à votre environnement. Aucune affiliation à Cisco ou Fortinet. Les deux aperçus peuvent être adaptés pour vos changements internes. La redistribution du kit payant n’est pas autorisée.
