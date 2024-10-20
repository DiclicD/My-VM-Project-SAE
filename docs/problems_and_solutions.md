# Problèmes rencontrés et solutions

## 1. Problème de réseau sur VirtualBox
### Description :
Lors de la configuration des machines virtuelles, la connexion réseau ne fonctionnait pas correctement.
### Solution :
Nous avons modifié le paramètre réseau en sélectionnant l'option "Pont réseau", ce qui a résolu le problème.

## 2. Réinitialisation du mot de passe sous Debian
### Description :
Lors de l'installation de Debian, j'avais oublié le mot de passe administrateur.
### Solution :
Nous avons suivi les étapes suivantes :
1. Redémarrer la machine et accéder au menu GRUB.
2. Modifier les options de démarrage pour ajouter `init=/bin/bash`.
3. Réinitialiser le mot de passe avec la commande `passwd`.
4. Redémarrer la machine.
