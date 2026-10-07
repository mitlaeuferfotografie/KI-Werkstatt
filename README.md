# KI-Werkstatt

## Was das ist
Begleitseite zum Workshop „Mehr Zeit für Unterricht“ (Information und Workshop im Kollegium, 90 Minuten, KI als Arbeitserleichterung für Lehrkräfte). Statische Seite ohne Build-Schritt.

| Datei | Inhalt |
|---|---|
| `index.html` | Workshop-Seite (4 aufklappbare Schritte, Kopiervorlagen, Beispiele). Präsentation in Schritt 1 als Knopf und eingebettete Ansicht (relativer Link). |
| `KI-Werkstatt-Praesentation.pdf` | Präsentation, 18 Folien, Stand 05.10.2026 |
| `impressum.html` | Impressum (§ 18 Abs. 1 MStV, Schuladresse) und Datenschutz |

## Auftrag: hochladen, aber NICHT veröffentlichen
1. Privates GitHub-Repository `KI-Werkstatt` im Konto anlegen, mit dem auch die anderen Apps laufen (mitlaeuferfotografie).
2. Alle Dateien dieses Ordners auf den Branch `main` pushen. Commit-Nachricht: „KI-Werkstatt: Workshop-Seite, Präsentation, Impressum“.
3. **GitHub Pages NICHT einschalten.** Das Repo bleibt privat.
   Beispiel: `gh repo create KI-Werkstatt --private --source . --push`

## Später veröffentlichen (erst wenn Peter es ausdrücklich sagt)
- Im kostenlosen GitHub-Tarif geht Pages nur mit öffentlichem Repo: Repo auf **public** stellen, dann Settings → Pages → Branch `main`, Ordner `/ (root)`.
- Adresse danach: `https://mitlaeuferfotografie.github.io/KI-Werkstatt/`
- Achtung: Öffentlich heißt, auch die PDF mit den Material-Ausschnitten ist für alle abrufbar. Vorher prüfen, dass keine Namen oder Daten von Kindern darin stehen.

## Regeln für Änderungen
- Keine externen Ressourcen einbinden (keine Google Fonts, keine CDNs, kein Tracking). Nur Systemschriften.
- Impressum und Datenschutz-Link im Footer von `index.html` nicht entfernen.
- Sprache: gendergerecht (Kolleg*innen, Lehrkräfte), „Level 1–3“ für die KI-Nutzung, „Prompt“ statt „Auftrag“ für Eingaben an die KI.
- Feste Botschaften: KI ist Werkzeug der Lehrkräfte, nicht der Kinder. KI korrigiert oder bewertet keine Kinderarbeiten oder Prüfungen.
- Dateiablage im Text nur als „unser OneDrive“ benennen, keine Team- oder Ordnerstruktur nennen (noch nicht beschlossen).
- Eine zweite Fassung derselben Seite liegt intern im SharePoint „Medien FAQs“ (Seite KI-Werkstatt). Inhaltliche Änderungen gegebenenfalls dort ebenfalls nachziehen.
