# 00 Prérequis

- Serveur Ubuntu avec minimum 4vCPU, 6Go de ram et 50Go de stockage.

## 01 Architecture Réseau

| Information               | Valeur             |
| ------------------------- | ------------------ |
| IP du Firwall             | 172.20.130.1       |
| IP du serveur WAZUH       | 172.20.130.80      |
| IP du serveur Windows     | 172.20.130.10      |
| IP du serveur Nextcloud   | 172.20.130.21<br>  |
| IP du serveur TacticalRMM | 172.20.130.30<br>  |
| IP du serveur Zimbra      | 172.20.130.90<br>  |
| IP du serveur GLPI        | 172.20.130.201<br> |

# 10 Installation du Manager

Exécuter la commande AIO (All In On) pour installer le manager d'agent et la console web serveur de gestion en même temps.

![[assets/Pasted image 20260420113119.png]]

Attendre la fin de l'installation puis désactiver les mises à jour automatique.

![[Pasted image 20260421102103.png]]


Récupérer ensuite l'identifiant et le mot de passe administrateur pour se connecter à la console de gestion.

![[Pasted image 20260421102137.png]]

![[Pasted image 20260420114714.png]]

# 20 Installation des Agents

Ouvrez la page de gestion des déploiements d'agent puis configurer en fonction du matériel

![[Pasted image 20260421102444.png]]

Ne pas oublier de donner l'adresse IP du serveur de management

![[Pasted image 20260421114132.png]]

Il suffit pour finir de copier l'unique commande sur le système client pour installer l'agent.

![[Pasted image 20260507123451.png]]

![[Pasted image 20260507123744.png]]

