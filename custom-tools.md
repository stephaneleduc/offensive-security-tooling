
# Custom Tools

Outils et scripts développés personnellement afin d’automatiser ou faciliter
certaines phases de tests d’intrusion, notamment lors de laboratoires
Offensive Security, Hack The Box et CTF.

Tous les outils ont été développés et utilisés exclusivement dans des
environnements autorisés et contrôlés.

---

## 🛠️ Scripts développés

### JWT RSA Weak Key Exploitation Script
**Langage :** Python  

**Objectif :**  
Exploiter une implémentation faible de signature JWT basée sur RSA afin de forger des tokens avec des privilèges élevés.

**Description :**  
Script développé pour exploiter une vulnérabilité cryptographique présente sur une machine Hack The Box volontairement vulnérable.  
L’analyse du mécanisme de signature des JWT et du contenu JWK exposé dans les tokens a permis d’identifier une mauvaise génération de clés RSA, rendant le module factorisable.

Le script automatise :
- l’extraction du module RSA depuis le JWT,
- la factorisation du module,
- la reconstruction de la clé privée,
- la génération de nouveaux JWT signés (RS256) avec élévation de privilèges.

Le développement s’est appuyé sur une compréhension du fonctionnement de RSA et des JWT, avec une assistance ponctuelle d’outils d’IA pour accélérer l’implémentation.

**Contexte d’utilisation :**  
- Hack The Box (machine volontairement vulnérable)  
- Pentest applicatif  
- Exploitation cryptographique





**ℹ️ Le code source des outils personnalisés n’est pas publié et peut être partagé sur demande.**
