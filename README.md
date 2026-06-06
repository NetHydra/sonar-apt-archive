## A NetHydra SONAR apt archive

this package help you to initialize SONAR mirror into your standard NetHydra Machine (NetHydra Express) easily.
however we would to suggest you to use/install SONAR image for better Experience.

## Installing

On NetHydra machine:

```
nethydra@nethydra:~# apt update && apt install -y sonar-apt-archive
```

After process is done you need to update the machine

```
nethydra@nethydra:~# apt update
```

Finally you could install package from SONAR mirror. as example we would to check MISP

```
nethydra@nethydra:~# apt show misp
[...]
```

