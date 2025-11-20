# 20-11-25

## Reset du Switch

Supprimer les fichiers de config dans le working et dans le certified

```cfg
rm /flash/working/*.cfg
rm /flash/certified/*/cfg
```
Redémarre le switch

```cfg
reload all
```

## Changer le nom du switch

Configurer le nom du switch

```cfg
system name <name>
```


