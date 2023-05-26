## <p align='center'> Web Service Discovery host daemon </p>

### Configurer WSDD
Le service WSDD permet au machine du réseau de découvrir la machine.
```
NOM=
sed -i -e "/s/TRUENAS/$NOM/g" /etc/local/wsdd.conf;

nano /etc/local/wsdd.conf;
```
