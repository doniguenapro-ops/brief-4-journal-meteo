# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | — | M01 |
| humiditeAiPct |Humidité relative de l'air | nombre| entre 0 et 100| %| 75|
| date | date du relevé|texte |format AAAA-MM-JJ |- |2026-10-15 |  
| temperatureC | teperature en degré celcuce| nombre|un nombre, négatif ou décimal possible | °C| 27|
| PluieMm| pluie du jour|nombre | un nombre positif ou nul|mm | 0|

id:texte non vide, absent des données;temperatureC:un nombre, négatif ou décimal possible;date:format AAAA-MM-JJ;humiditeAiPct:entre 0 et 100; PluieMm:un nombre positif ou nul

Sources: SUJET.md;donnees/releves.json
