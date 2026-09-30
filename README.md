# bookbugs-public

Öffentliche Dateien für bookbugs.de, die eine abrufbare URL brauchen.

- `assets/` – og:image u. ä.
- `feed/feed.json` – monatlicher Buchauswahl-Feed für die Brevo-Vorschau-Mail (wird jeden Monat überschrieben)
- `covers/` – Buchcover für die Mail, Pauschalnamen `phase{N}_{hauptbuch|alternative_1|alternative_2}.jpg`, jeden Monat überschrieben (Cache-Schutz über `?v=YYYYMM` in der image_url im Feed)

Keine Kundendaten in dieses Repo.
