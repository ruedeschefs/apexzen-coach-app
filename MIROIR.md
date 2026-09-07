<!-- MIROIR-ORGANIZEN
MIROIR - ne pas editer ici.
Source unique : H:\ORGANIZEN_EMPIRE\07_PROJECTS\apexzen-coach
Genere le : 2026-09-07
Toute modification faite dans ce depot est un incident, pas une contribution :
elle sera ecrasee a la prochaine synchronisation. On edite la source, jamais le miroir.
MIROIR-ORGANIZEN -->

# MIROIR - Apexzen Coach - releases

## Ce depot ne fait pas foi

Ce depot est un **miroir**. La source unique est le disque du quartier general :

    H:\ORGANIZEN_EMPIRE\07_PROJECTS\apexzen-coach

Un miroir sert aux sessions qui n'ont pas le disque : cloud, mobile, VPS, sous-agent.
**Il montre, il ne decide jamais.** Une modification faite directement ici est un
incident, pas une contribution : elle sera ecrasee a la prochaine synchronisation.

Regle complete : `CLAUDE.md` §0.1 de l'empire, decision `DEC-2026-09-07-001`.

## Pourquoi ce fichier existe

Le 2026-08-31, un audit lance depuis une session cloud a lu ce type de depot en croyant
lire le quartier general, et a rendu un rapport fonde sur une copie. Rien n'indiquait
qu'il s'agissait d'une copie. Ce fichier est la reponse a cette panne.

## Ce que porte ce depot

Depot de distribution uniquement : APK Android de la beta. Pas de code source.

**Par ou entrer :** `README.md` et l'onglet Releases.

## Ecart connu avec la source

Rattachement deduit du nom, NON VERIFIE.

## Verifier la coherence

```bash
# depuis l'arborescence du QG
python 04_TOOLS/etat-empire/empire.py doctor
python 04_TOOLS/etat-empire/empire.py sync plan --depot apexzen-coach-app
```
