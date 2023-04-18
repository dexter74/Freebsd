#### Activer les dépôts FreeBSD:
```bash
sed -i 's/enabled: yes/enabled: no/g' /usr/local/etc/pkg/repos/local.conf;
sed -i 's/enabled: no/enabled: yes/g' /usr/local/etc/pkg/repos/FreeBSD.conf;
```

#### Mise à jour de la liste des Packages
```bash
pkg update;
```

#### Mise à niveau des paquets
```bash
pkg upgrade;
```
