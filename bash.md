# Commandes utiles

## Gestion des Utilisateurs
### Créer un nouvel Utilisateur

```
sudo useradd -m -d /home/antoine/ -s /bin/bash antoine
```

### Changer de Mot de Passe

```
passwd user
```

## Server Utils
### Log sans mot de passe à un serveur

```
ssh-copy-id user@server
```
