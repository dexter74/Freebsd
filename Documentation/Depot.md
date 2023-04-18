#### Activer les dépôts FreeBSD:
```bash
sed 's/enabled: yes/enabled: no/' /usr/local/etc/pkg/repos/local.conf;
sed 's/enabled: no/enabled: yes/' /usr/local/etc/pkg/repos/FreeBSD.conf;
```

#### Mise à jour de la liste des Packages
```bash
pkg update;
```

#### Mise à niveau des paquets
```bash
pkg upgrade;
```
