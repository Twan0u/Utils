# Commandes utiles

## Gestion des Utilisateurs
### Créer un nouvel Utilisateur

```
sudo useradd -m -d /home/user/ -s /bin/bash user
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

## Disk salvation basics

```
sudo fsck /ev/sdb1
```
