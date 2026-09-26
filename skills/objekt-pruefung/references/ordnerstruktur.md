# Ordnerstruktur und Dateinamen

## Struktur

```
<Objekt>/                      z. B. Berlin_Musterstr-12
├── 00_Bericht/
├── 01_Expose/
├── 02_Mieter/                 Mieterliste, Mietverträge, Mietkonten
├── 03_Grundbuch_Kataster/     Grundbuch, Flurkarte, Lageplan, Baulasten
├── 04_Flaechen_Plaene/        Flächenberechnung, Grundrisse, Schnitte
├── 05_Technik_Energie/        Energieausweis, Instandhaltung, Wartung, Fotos
├── 06_Recht_Genehmigungen/    Baugenehmigungen, Denkmalschutz, WEG-Unterlagen
├── 07_Finanzen_Kosten/        Nebenkosten, Versicherungen, OP-Listen
├── 08_Sonstiges/
└── _Original/                 unveränderte Kopie des Eingangsordners
```

## Dateinamen

`<Objekt>_<Kürzel>_<Beschreibung>_<JJJJ-MM-TT>.<ext>`

- **Objekt**: Ort_Straße-Hausnr., ohne Leer- und Sonderzeichen (ä→ae, ß→ss)
- **Kürzel**: aus `checkliste.md` (EXP, ML, GB, FL, MV …)
- **Beschreibung**: kurz, z. B. `Einheit-03_Mueller`, `Abt-I-III`
- **Datum**: Dokumentdatum bzw. Stichtag; unbekannt → `o-D`

Beispiele:
- `Berlin_Musterstr-12_ML_Mieterliste_2026-08-31.xlsx`
- `Berlin_Musterstr-12_GB_Grundbuchauszug_2026-07-15.pdf`
- `Berlin_Musterstr-12_MV_Einheit-03_Mueller_2019-04-01.pdf`

Dubletten: Suffix `_DUPLIKAT` anhängen, nicht löschen.
