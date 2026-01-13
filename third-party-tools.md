
# Third-Party Tools

Outils et ressources tiers utilisés dans le cadre d’activités personnelles de
cybersécurité offensive, installés ou consultés manuellement depuis des dépôts
publics (GitHub, GitLab, sites spécialisés), en complément des outils standards
disponibles sur Kali Linux.

Tous les éléments listés sont utilisés exclusivement dans des environnements
autorisés et contrôlés.

---

## 🖥️ Active Directory & environnements Windows

- **PKINITtools**  
  Abus de PKINIT et attaques liées aux certificats Kerberos.  
  https://github.com/dirkjanm/PKINITtools

- **gMSADumper**  
  Lecture et extraction des mots de passe gMSA accessibles.  
  https://github.com/micahvandeusen/gMSADumper

- **PowerSploit**  
  Collection de modules PowerShell pour l’énumération et la post-exploitation Windows.  
  https://github.com/PowerShellMafia/PowerSploit

- **Sysinternals Suite**  
  Outils d’administration Windows utilisés pour l’analyse et la post-exploitation.  
  https://github.com/Sysinternals/sysinternals

- **RunasCs**  
  Exécution de commandes sous un autre contexte utilisateur Windows.  
  https://github.com/antonioCoco/RunasCs

- **JuicyPotato**  
  Exploitation de privilèges Windows via abus de tokens.  
  https://github.com/ohpe/juicy-potato

- **RottenPotatoNG**  
  Variante d’exploitation de privilèges Windows basée sur l’abus de tokens.  
  https://github.com/breenmachine/RottenPotatoNG

- **GodPotato**  
  Exploitation moderne de SeImpersonatePrivilege.  
  https://github.com/BeichenDream/GodPotato

- **winrmexec**  
  Alternative à Evil-WinRM pour l’exécution de commandes via WinRM.  
  https://github.com/ozelis/winrmexec

---

## 🔓 Privilege escalation & abus de configurations

- **GTFOBins**  
  Référence pour l’abus de binaires Linux dans des scénarios de privilege escalation.  
  https://gtfobins.github.io/

- **NFS security tooling**  
  Outils et scripts pour l’exploitation de mauvaises configurations NFS.  
  https://github.com/hvs-consulting/nfs-security-tooling

---

## 🌐 Web, dépôts & artefacts exposés

- **git-dumper**  
  Extraction de dépôts Git exposés via HTTP.  
  https://github.com/arthaud/git-dumper

- **DS_store_exp**  
  Exploitation de fichiers `.DS_Store` exposés pour l’énumération web.  
  https://github.com/lijiejie/ds_store_exp

- **Exploit-DB**  
  Base de données publique d’exploits et de vulnérabilités connues.  
  https://www.exploit-db.com/

- **gitea2hashcat**  
  Conversion de hashes Gitea vers des formats compatibles Hashcat.  
  https://github.com/hashcat/hashcat/blob/master/tools/gitea2hashcat.py

---

## 🔐 Hashes, cracking & secrets

- **CrackStation**  
  Service de cracking de hashes en ligne pour des tests rapides.  
  https://crackstation.net/

- **Credentials.yml.enc Decryptor**  
  Déchiffrement de fichiers `credentials.yml.enc`.  
  https://github.com/mbadanoiu/Credentials.yml.enc_Decryptor

- **McAfee SiteList password decryption**  
  Déchiffrement des mots de passe stockés dans les fichiers `SiteList.xml` de McAfee.  
  https://github.com/funoverip/mcafee-sitelist-pwd-decryption

---

## 🧭 Shells, accès distant & post-exploitation

- **Stable shell on Windows**  
  Techniques pour obtenir un shell interactif stable sous Windows.  
  https://medium.com/@superstar_/how-to-get-full-tty-shell-on-windows-cdff487a11e1

- **ConPtyShell**  
  Obtention de shells Windows interactifs et stables via ConPTY.  
  https://github.com/antonioCoco/ConPtyShell

- **Spawn TTY**  
  Méthodes pour améliorer des shells limités en TTY interactifs.  
  https://wiki.zacheller.dev/pentest/privilege-escalation/spawning-a-tty-shell

- **revshells.com**  
  Générateur de reverse shells multi-langages.  
  https://www.revshells.com/

- **revbshell**  
  Reverse shell en Visual Basic pour environnements Windows.  
  https://github.com/bitsadmin/revbshell

- **Python HTTP POST server**  
  Script Python pour la réception de données via HTTP POST.  
  https://gist.github.com/hawkins/36b7d781d8fa5277d4cb29b6906abe57

---

## 🧪 Conteneurs & environnements

- **XenSpawn**  
  Conteneur Ubuntu minimal (16.04) utilisé pour des scénarios d’évasion ou de tests.  
  https://github.com/X0RW3LL/XenSpawn

---

## 🛠️ Utilitaires & ressources diverses

- **CyberChef**  
  Plateforme d’analyse et de transformation de données (encodage, chiffrement, parsing).  
  https://gchq.github.io/CyberChef/

- **Static nmap binaries**  
  Binaires statiques Nmap pour environnements restreints.  
  https://github.com/andrew-d/static-binaries

- **Bad-PDF**  
  Création de PDF malveillants pour la capture de hashes NTLM.  
  https://github.com/deepzec/Bad-Pdf

- **Astuces nmap**  
  Astuces utiles pour utiliser correctement nmap.
  
  https://www.piirates.fr/nmap-pentest/

---

ℹ️ Les liens sont fournis à titre de référence vers les projets originaux.
