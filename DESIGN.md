# DESIGN.md – KI-Werkstatt (Workshop-Seite fürs Kollegium)

Richtung: modern, ruhig, dunkel. Eine Arbeitsseite, die man im Workshop offen hat: gut lesbar, schnell zu bedienen, mit echten Bildern aus dem eigenen Unterricht statt Dekoration. Nicht aus UXKIN-Beispielen abgeleitet (nicht verbunden), sondern aus dem bisherigen Feedback: dunkel, nicht überladen, keine Tafel-Optik, zeitgemäß.

## Farbe (nur dunkel)
| Token | Wert | Rolle |
|---|---|---|
| bg | #11151C | Seitenhintergrund |
| surface | #181E27 | Kopiervorlagen, Kästen, aufgeklappte Schritte |
| raised | #202835 | Hover, Reiter aktiv |
| border | #2B3442 | Linien, Rahmen |
| text | #EDEFF3 | Fließtext, Überschriften |
| muted | #A2ABBA | Nebentext, Beschreibungen |
| primary | #6FD3C1 | Knöpfe, Links, aktiver Reiter, Fokus |
| on-primary | #0E1A18 | Text auf primary |
| accent | #F5C26B | nur Zeiten und der Hinweis „KI für uns Lehrkräfte“ |
| mark | rgba(245,194,107,.18) | Platzhalter in Kopiervorlagen |
Kontrast: text/bg 15:1, muted/bg 7.6:1, primary/bg 10:1, accent/bg 11:1.

## Typografie
Eine Familie: Nunito Sans (lokal in fonts/, SIL OFL), 400 / 700 / 800.
Skala: 14 · 16 · 18 (Fließtext) · 22 · 28 · 40 · 60 px. Überschriften 800, Zeilenabstand 1.1–1.25, leicht enger gesetzt (−0.02em). Fließtext 1.65. Zeilenlänge max. 70 Zeichen.
Keine Großbuchstaben-Überschriften, keine „·“-Trennzeilen.

## Abstände
8er-Raster (8, 16, 24, 32, 48, 72). Textspalte 760 px, Kopfbereich 1080 px. Abschnitte 72 px Abstand.

## Form und Tiefe
Radius: 8 px (Knöpfe, Felder, Reiter), 14 px (Bilder, Kopiervorlagen). Ein Schatten nur für Bilder: 0 20px 40px rgba(0,0,0,.35). Sonst flach mit 1-px-Linien.

## Komponenten
- Knopf primär: primary-Fläche, on-primary-Text. Sekundär: Rahmen border, Text text. Hover: heller, Fokus: 2 px primary-Ring.
- Leiste oben (fest): Sprungmarken zu den Abschnitten.
- Abschnitte statt Aufklappen: Impuls, Startklar machen, Bauen und prüfen, Ergebnisse zeigen, Zum Weitermachen. Jede Phase hat oben Text links und ein Bild rechts (am Handy darüber).
- Prompts als Karten (surface) mit Buchstabe, Titel, einem Satz und den Knöpfen „Kopieren“ und „Ansehen“; „Ansehen“ öffnet ein Fenster (dialog) mit dem ganzen Prompt.
- Hinweis: linke Linie in accent (Regeln) oder primary (Beispiel „So bei uns“).

## Bilder
Ein Bild pro Phase: Impuls = Titelfolie der Präsentation (bilder/praesentation-titelfolie.jpg), sonst eigene SVG-Grafiken in den Farben der Seite (bilder/startklar.svg, bauen.svg, zeigen.svg). Keine Stockfotos, keine Kinder, keine Namen. Abgerundet 16 px, feiner Rahmen.

## Bewegung
Beim Laden erscheint der Kopf sanft und der Ablauf-Balken füllt sich. Die Phasenbilder blenden beim Scrollen einmal ein. Das Prompt-Fenster öffnet weich. Bei „Bewegung reduzieren“ im System gibt es keine Animation.
