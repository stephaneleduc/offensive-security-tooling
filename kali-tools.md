# Offensive Security Tooling

Outils utilisés régulièrement dans le cadre de
laboratoires de cybersécurité offensive (Offensive Security Labs,
Hack The Box, CTF), exclusivement dans des environnements autorisés
et contrôlés.

---

## 🔍 Reconnaissance & énumération réseau
- **nmap** : scan réseau et identification des services exposés
- **tcpdump** : capture et analyse de trafic réseau en ligne de commande
- **wireshark** : analyse graphique de captures réseau et inspection de protocoles
- **rustscan** : scan de ports ultra-rapide utilisé en amont de nmap
- **ldapsearch** : interrogation manuelle de services LDAP
- **ldapdomaindump** : extraction structurée d’informations Active Directory
- **smbclient** : interaction et exploration de partages SMB
- **enum4linux** : énumération automatisée des services SMB
- **rpcclient** : interaction RPC avec des systèmes Windows
- **snmpwalk** : énumération SNMP basée sur les OID
- **snmp-check** : collecte automatisée d’informations SNMP
- **whatweb** : identification des technologies web utilisées

---

## 🌐 Web & applicatif
- **burpsuite** : interception, modification et analyse du trafic HTTP(S)
- **ffuf** : fuzzing rapide d’URLs, sous-domaines, paramètres et virtual hosts
- **gobuster** : brute-force de contenus et répertoires web
- **nikto** : scan automatisé de vulnérabilités web connues
- **wpscan** : énumération et exploitation de CMS WordPress
- **sqlmap** : exploitation automatisée d’injections SQL

---

## 🖥️ Active Directory & environnements Windows
- **bloodhound** : analyse graphique des chemins d’attaque Active Directory
- **neo4j** : base de données graphique utilisée par BloodHound
- **bloodhound-python** : collecte d’informations AD sans agent
- **sharphound** : collecte d’informations Active Directory pour BloodHound
- **crackmapexec** : framework d’énumération et d’exploitation Active Directory
- **netexec** : successeur moderne de CrackMapExec
- **certipy** : exploitation des services de certificats Active Directory (ADCS)
- **bloodyAD** : modification et abus d’objets Active Directory
- **rubeus** : attaques Kerberos avancées (tickets, delegation, roasting)
- **responder** : empoisonnement réseau et capture de credentials
- **evil-winrm** : accès distant Windows via WinRM
- **impacket-secretsdump** : extraction de secrets et hashes Windows, y compris via attaques DCSync
- **impacket-psexec** : exécution de commandes à distance via SMB
- **impacket-mssqlclient** : interaction avec des serveurs MSSQL
- **impacket-GetUserSPNs** : Kerberoasting
- **impacket-GetADUsers** : énumération des utilisateurs Active Directory
- **impacket-getTGT** : manipulation de tickets Kerberos
- **impacket-reg** : interaction avec le registre Windows à distance

---

## 🔓 Privilege escalation & post-exploitation
- **linpeas** : énumération automatisée pour élévation de privilèges Linux
- **pspy64** : surveillance des processus et tâches planifiées Linux
- **unix-privesc-check** : détection de mauvaises configurations Linux
- **winpeas** : énumération automatisée pour élévation de privilèges Windows
- **mimikatz** : extraction de credentials et secrets Windows
- **pypykatz** : alternative Python à Mimikatz pour extraction mémoire
- **klist** : affichage des tickets Kerberos
- **kdestroy** : suppression des tickets Kerberos

---

## 🔐 Passwords & credentials
- **hashcat** : cracking de hash hors-ligne haute performance
- **john** : cracking de hash et mots de passe
- **hydra** : attaques par force brute sur services réseau
- **keepass2john** : extraction de hash depuis bases KeePass
- **ssh2john** : extraction de hash de clés SSH
- **kpcli** : interaction en ligne de commande avec KeePass

---

## 🧭 Accès distant & pivoting
- **ligolo-proxy** : tunneling et pivoting réseau performant
- **chisel** : tunnel TCP/HTTP pour contournement réseau
- **sshuttle** : VPN-like basé sur SSH pour pivoting
- **proxychains** : redirection du trafic via proxy
- **vncviewer** : accès distant via protocole VNC
- **xfreerdp** : client RDP pour accès graphique distant


---

## 🧪 Exploitation
- **searchsploit** : recherche locale d’exploits publics
- **msfconsole** : framework d’exploitation Metasploit
- **msfvenom** : génération de payloads personnalisés

---

## 🧠 Outils complémentaires
- **exiftool** : analyse de métadonnées de fichiers
- **swaks** : interaction et tests de serveurs SMTP
- **jadx-gui** : décompilation et analyse statique d’APK Android
- **radare2** : framework de reverse engineering en ligne de commande
- **ghidra** : suite de reverse engineering pour l’analyse de binaires

Cette liste n’est pas exhaustive et évolue en fonction des environnements rencontrés
et des besoins opérationnels.
  
