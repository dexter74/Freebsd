## <p align='center'> Web Service Discovery host daemon </p>

### Configurer WSDD
Le service WSDD permet au machine du réseau de découvrir la machine.

```bash
NOM=NAS
sed -i -e "/s/TRUENAS/$NOM/g" /etc/local/wsdd.conf;

nano /etc/local/wsdd.conf;
```
