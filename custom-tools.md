
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




**ℹ️ Le code source des outils personnalisés n’est pas publié et peut être partagé sur demande.**
