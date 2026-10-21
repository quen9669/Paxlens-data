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

## Licence et attribution

Les données proviennent de data.public.lu et sont publiées sous licence
[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/). Ce dépôt ne fait que les recopier,
sans les modifier.
