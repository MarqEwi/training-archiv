# Trainingsarchiv

Privates Archiv der Trainingstage: ein Ordner pro Tag mit Fotos (PM5, Coach-Plan), Garmin- und
Concept2-Exporten, Tagesauswertung und Coach-Text. Wird vom Repo `laufanalyse` befüllt
(`scripts/archiv.py`, Skill `/archiv`) und von der NAS STEVENAS nach `/volume1/Grundlagen/training/archiv`
gespiegelt (`nas/training-sync`).

```
<Jahr>/<YYYY-MM-DD> <Titel>/    z. B. 2026/2026-09-20 Hyrox Training
  fotos/           Bilder + index.md (Beschreibung je Bild)
  garmin/          Exporte aus Garmin Connect (summary.md, analysis.json, laps.csv, timeseries.csv, raw/)
  concept2/        Einheiten aus dem Concept2 Logbook und vom PM5-Foto
  auswertung.md    Tagesauswertung
  coach.txt        Textbaustein an den Coach (mit RPE)
  index.json       Manifest
```

Enthält Gesundheitsdaten. Nicht öffentlich machen.
