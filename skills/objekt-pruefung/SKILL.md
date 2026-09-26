---
name: objekt-pruefung
description: Prüft die Unterlagen eines Immobilienobjekts (Ankaufsprüfung / Vorab-Due-Diligence) in einem festen Ablauf – Exposé erfassen, Vollständigkeit prüfen, Inhalte abgleichen (Flächen, Mieterliste, Grundbuch), Negativpunkte und interne Positivpunkte herausarbeiten, Unterlagen sortiert und einheitlich benannt ablegen und einen Kurzbericht mit Eckdaten erstellen. Verwenden, wenn der Nutzer einen Ordner mit Objektunterlagen bereitstellt und ein Objekt "prüfen", "durchziehen", "checken" oder "bewerten" lassen will.
---

# Objekt-Prüfung

Der Nutzer stellt einen Ordner mit Unterlagen zu einem Objekt bereit (lokal, SharePoint/OneDrive o. ä.). Arbeite die Schritte **in dieser Reihenfolge** ab. Nichts erfinden: Jede Zahl im Ergebnis braucht eine Quelle (Dokument + Seite). Fehlt eine Angabe, schreibe „nicht vorhanden“.

## 0. Vorbereitung
- Ordnerpfad bestätigen. Alle Dateien rekursiv auflisten (inkl. ZIPs entpacken, E-Mails/Anhänge).
- Jede Datei einem Dokumenttyp aus `references/checkliste.md` zuordnen. Unklare Dateien kurz öffnen.
- **Originale nie verändern oder löschen**, bevor Schritt 6 freigegeben ist.

## 1. Exposé erfassen
Exposé lesen und die Verkäuferangaben als **Soll-Werte** festhalten: Adresse, Objektart, Baujahr, Grundstücksfläche, Wohn-/Nutzfläche (gesamt und je Nutzungsart), Anzahl Einheiten/Stellplätze, Ist-Miete p. a., Soll-/Marktmiete, Leerstand, Kaufpreis, Faktor, Rendite, Energiekennwerte, Besonderheiten.

## 2. Vollständigkeit prüfen
Gegen die Checkliste in `references/checkliste.md` abhaken – mindestens:
- **Mieterliste** (aktuell, mit Fläche, Miete, Vertragsbeginn/-ende, Kaution, Rückstände)
- **Grundbuchauszug** (aktuell, max. ~3 Monate alt, alle Abteilungen)
- **Flächennachweis** (Wohnflächenberechnung / Aufmaß / Pläne)

Ergebnis: Tabelle *vorhanden / fehlt / veraltet / unvollständig* + **Nachforderungsliste** an den Verkäufer.

## 3. Inhaltlicher Abgleich
Kernthemen (Details in `references/checkliste.md`):
1. **Flächen**: Exposé ↔ Flächenberechnung ↔ Summe Mieterliste ↔ Mietverträge.
2. **Mieten**: Exposé-Ist-Miete ↔ Summe Mieterliste ↔ Mietverträge ↔ Kontoauszüge/OP-Liste (falls vorhanden). €/m² je Einheit berechnen.
3. **Leerstand**: Exposé ↔ Mieterliste.
4. **Grundbuch**: Eigentümer = Verkäufer? Flurstücke/Fläche = Exposé? Abt. II (Lasten, Rechte), Abt. III (Grundpfandrechte).
5. **Kennzahlen nachrechnen**: Faktor = Kaufpreis / Jahresnettokaltmiete; Bruttoanfangsrendite = Miete / Kaufpreis.
6. **Baujahr, Energieausweis, Baulasten, Denkmalschutz, Teilungserklärung/WEG** – soweit Unterlagen vorhanden.

Jede Abweichung mit Soll, Ist, Differenz (absolut und %) und Quelle dokumentieren.

## 4. Negativpunkte
Alles, was den Wert mindert oder ein Risiko ist – als Argumente für Preisverhandlung/Nachfragen. Beispiele:
- Tatsächliche Fläche kleiner als im Exposé
- Ist-Miete niedriger als angegeben, Mietrückstände, Leerstand höher
- Befristete/auslaufende Verträge, Klumpenrisiko (ein Mieter > 30 % der Miete), Staffel/Index fehlt
- Belastungen in Abt. II (Wegerecht, Nießbrauch, Vorkaufsrecht), Baulasten
- Schlechter Energiekennwert, Sanierungsstau, fehlende Genehmigungen
- Faktor/Rendite im Exposé falsch berechnet

Je Punkt: Beschreibung, Quelle, geschätzte Auswirkung (€ p. a. / € Kaufpreis, wenn berechenbar), Schwere (hoch/mittel/gering).

## 5. Positivpunkte (intern – nicht an den Verkäufer)
Was uns positiver stimmt als der Verkäufer es darstellt. **Deutlich als INTERN kennzeichnen.** Beispiele:
- Tatsächliche Fläche größer als angegeben
- Mieten deutlich unter Marktniveau → Mietsteigerungspotenzial
- Leerstand gut vermietbar, Ausbau-/Nachverdichtungsreserven (Dachgeschoss, Grundstücksreserve)
- Auslaufende Belastungen, günstige Vertragsklauseln (Index/Staffel)
- Faktor im Exposé konservativ gerechnet

## 6. Ordner sortieren und benennen
Struktur und Namensschema aus `references/ordnerstruktur.md`.
- Erst den **Umbenennungsplan** (alt → neu) als Tabelle zeigen und vom Nutzer freigeben lassen.
- Dann Dateien **kopieren/verschieben** (bevorzugt kopieren, Original-Ordner als `_Original` behalten, sofern der Nutzer nichts anderes sagt).
- Dubletten markieren, nicht löschen.

## 7. Kurzbericht
Bericht nach `templates/bericht.md` erstellen und als `00_Bericht/JJJJ-MM-TT_Objektpruefung_<Objekt>.md` (auf Wunsch zusätzlich .docx/.pdf) im Objektordner ablegen. Die interne Positivliste steht in einem eigenen, gekennzeichneten Abschnitt.

Im Chat am Ende nur kurz zusammenfassen: Eckdaten, Top-3-Negativ, Top-3-Positiv, fehlende Unterlagen, Link/Pfad zum Bericht.
