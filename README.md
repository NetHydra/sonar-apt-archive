## A NetHydra [SONAR](https://nethydra.github.io/doc/Introduction/wiki-sonar) apt archive

this package help you to initialize [SONAR](https://nethydra.github.io/doc/Introduction/wiki-sonar) mirror into your standard NetHydra Machine (NetHydra Express) easily.
however we would to suggest you to use/install [SONAR](https://nethydra.github.io/doc/Introduction/wiki-sonar) image for better Experience.

## Installing

On NetHydra machine:

```
nethydra@nethydra:~# apt update && apt install -y sonar-apt-archive
```

After process is done you need to update the machine

```
nethydra@nethydra:~# apt update
```

Finally you could install package from [SONAR](https://nethydra.github.io/doc/Introduction/wiki-sonar) mirror. as example we would to check [MISP](https://nethydra.github.io/doc/tools/sonar-tools-misp)

```
nethydra@nethydra:~# apt show misp
[...]
```

