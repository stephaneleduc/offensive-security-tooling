
# Custom Tools

Outils et scripts développés personnellement afin d’automatiser ou faciliter
certaines phases de tests d’intrusion, notamment lors de laboratoires
Offensive Security, Hack The Box et CTF.

Tous les outils ont été développés et utilisés exclusivement dans des
environnements autorisés et contrôlés.

---

## 🛠️ Scripts développés

### JWT RSA Weak Key Exploitation Tool
**Langage :** Python  

**Objectif :**  
Exploiter une implémentation faible de signature JWT basée sur RSA.

**Description :**  
Script développé pour exploiter une vulnérabilité cryptographique présente sur une machine Hack The Box volontairement vulnérable.  
L’analyse du mécanisme de génération et de distribution des clés RSA (via JWK exposé dans les tokens JWT) a permis d’identifier une mauvaise pratique : l’utilisation d’un facteur premier de taille insuffisante lors de la construction de la clé (`n = p × q`).

Le script automatise la factorisation du module RSA, la reconstruction de la clé privée et la génération de tokens JWT signés (RS256) avec des privilèges élevés.

Le développement s’est appuyé sur la compréhension du fonctionnement de RSA et des JWT, avec une assistance ponctuelle d’outils d’IA pour accélérer l’implémentation.

**Contexte d’utilisation :**  
- Hack The Box (machine volontairement vulnérable)  
- Pentest applicatif  
- Exploitation cryptographique

---

### Kali Workspace Initialization Script
**Langage :** Bash  

**Objectif :**  
Automatiser et standardiser la préparation de l’environnement de travail lors du démarrage d’une nouvelle machine ou d’un Pro Lab.

**Description :**  
Script Bash développé pour initialiser rapidement un espace de travail Kali Linux dédié à une cible.  
Il automatise la création de l’arborescence de travail, l’ouverture d’un environnement multi-terminaux préconfiguré et le lancement des outils et services couramment utilisés lors des premières phases d’un test d’intrusion.

Le script intègre également l’ouverture d’outils de prise de notes afin de favoriser une documentation continue et structurée tout au long de l’engagement.

L’objectif est de réduire le temps de mise en place, d’éviter les oublis et de garantir une méthodologie reproductible d’une machine à l’autre.

**Contexte d’utilisation :**  
- Hack The Box  
- Pro Labs Hack The Box  
- Environnement Kali Linux

---



---

**ℹ️ Le code source des outils personnalisés n’est pas publié et peut être partagé sur demande.**
