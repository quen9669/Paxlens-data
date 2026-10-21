# paxlens-data

Miroir public des horaires de transport du Luxembourg au format **GTFS**, recopiés chaque jour
depuis [data.public.lu](https://data.public.lu/en/datasets/horaires-et-arrets-des-transport-publics-gtfs)
par GitHub Actions.

## Contenu

Chaque version du GTFS officiel est publiée dans une [release](../../releases) avec :

- `gtfs.zip` : le fichier officiel, sans aucune modification ;
- `_source.json` : sa provenance (ressource d'origine, date, empreinte sha256, date de copie).

La dernière version est toujours disponible à ces adresses fixes :

```
https://github.com/quen9669/paxlens-data/releases/latest/download/gtfs.zip
https://github.com/quen9669/paxlens-data/releases/latest/download/_source.json
```

Une nouvelle release n'est créée que lorsque le fichier publié change.

## Météo horaire

La release fixe [`meteo`](../../releases/tag/meteo) contient la météo horaire (température à 2 m,
précipitations) de 4 points du Luxembourg (Luxembourg, Ettelbruck, Esch-sur-Alzette, Wasserbillig),
mise à jour chaque nuit depuis le 1er octobre 2026 :

```
https://github.com/quen9669/paxlens-data/releases/download/meteo/meteo_horaire.csv
https://github.com/quen9669/paxlens-data/releases/download/meteo/meteo_source.json
```

Source : [Open-Meteo](https://open-meteo.com/) (archive des prévisions), licence CC-BY 4.0. Heures
en heure locale (Europe/Luxembourg).

## Licence et attribution

Le GTFS provient de data.public.lu et est publié sous licence
[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/). Ce dépôt ne fait que les recopier,
sans les modifier.
