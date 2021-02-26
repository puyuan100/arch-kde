# arch-kde

## the way to lock the panel and widgets
```
qdbus-qt5 org.kde.plasmashell /PlasmaShell evaluateScript "lockCorona (true)"  ; this is to lock 
qdbus-qt5 org.kde.plasmashell /PlasmaShell evaluateScript "lockCorona (false)" ; this is to unlock
```
