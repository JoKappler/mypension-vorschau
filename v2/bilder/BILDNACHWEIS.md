# Bildnachweis

| Datei | Quelle | Wofür |
|---|---|---|
| `johanna-pitsch.png` | von mypension.de übernommen, freigestellt, 238 × 376 px (für größere Darstellung das Original besorgen) | Block 2 „Lieber mit einem Menschen reden?“, Knöpfe zum Gespräch, „Über uns“ |
| `rogier-minderhout.png` | von mypension.de/ueberuns/ übernommen (Johannes 12.10.2026), freigestellt, 464 × 580 px | „Über uns“, Wer wir sind |
| `johannes-kappler.png` | von mypension.de/ueberuns/ übernommen (Johannes 12.10.2026), freigestellt, 464 × 580 px | „Über uns“, Wer wir sind |
| `person-platzhalter.svg` | selbst gezeichnet (Kopf und Schultern), keine Rechte Dritter | **Platzhalter** für die Fotos der Beispielpersonen auf den Produktseiten (Daniel, Jana, Lisa, Markus, Sabine), bis Johannes Fotos aussucht; Tausch in `src/inhalt/seiten/produktlinie.ts` |
| `duoton-platzhalter.jpg` | [Oktay Yildiz](https://unsplash.com/@oktayyildiz) auf Unsplash, [Foto](https://unsplash.com/photos/person-riding-bicycle-in-the-road-8DVEsLkB_pU), Unsplash-Lizenz (kostenlos, kommerziell nutzbar) · aus `musterseiten/bilder/ll-linie.jpg`, auf 1.600 px verkleinert | **Platzhalter** für die Duoton-Fassung von Block 2 (`/?block2=duoton`). Zum Start ersetzen durch gekaufte Fotos echter Menschen mit Freigabe (Spezifikation 17). |
| `platzhalter-d.svg`, `-j.svg`, `-l.svg`, `-m.svg`, `-s.svg` | selbst gezeichnet (Initiale in Gold auf Navy), keine Rechte Dritter | **Platzhalter** für Daniel, Jana, Lisa, Markus, Sabine auf den Produktseiten (Version 2), bis Johannes Fotos aussucht; Tausch in `src/inhalt/seiten/produktlinie.ts`, `person()` |

## Version 2 „Lebensmomente“ (17.10.2026): Motive aus dem Bildpool

Alle von [Unsplash](https://unsplash.com), Unsplash-Lizenz (kostenlos, kommerziell nutzbar), heruntergeladen am 07.09.2026 in
2.000 px, hier in 1.600 und 800 px (`scripts/duoton.mjs`). „Duoton“ heißt: Graubild, auf Navy abgebildet (Schatten navy-900,
Lichter höchstens navy-600 bzw. navy-300), damit Schrift darüber lesbar bleibt (gemessen in `e2e/fotos.spec.ts`).

| Datei | Fotograf | Motiv | Wo |
|---|---|---|---|
| `ll-strasse-duoton-*.jpg` | [Urban Vintage](https://unsplash.com/@urban_vintage), [Foto](https://unsplash.com/photos/person-cycling-on-road-distance-with-mountain-during-daytime-VfUN94cUy4o) | Radfahrer, die Straße zieht als Linie durch die Berge | Startseite, hinter der Linie |
| `ll-linie-duoton-*.jpg` | [Oktay Yildiz](https://unsplash.com/@oktayyildiz), [Foto](https://unsplash.com/photos/person-riding-bicycle-in-the-road-8DVEsLkB_pU) | Einzelnes Rad auf gerader Straße | Kopf von `/produkte/` |
| `ll-rad-weit-duoton-*.jpg` | [Alexander Fastovets](https://unsplash.com/@darkmoon_afa), [Foto](https://unsplash.com/photos/a-man-riding-a-bike-down-a-road-under-a-cloudy-sky-Q8NG0KZkFlk) | Radfahrer unter weitem Himmel | Kopf ETF-Rentenversicherung |
| `ll-wasser-duoton-*.jpg` | [Benjamin L. Jones](https://unsplash.com/@boardshortsben), [Foto](https://unsplash.com/photos/man-in-black-and-brown-long-sleeve-shirt-holding-silver-fish-59-SZ--EVvc) | Lachender Mann halb unter Wasser | Kopf ETF-Depot |
| `ll-lichter-duoton-*.jpg` | [Hanna Lazar](https://unsplash.com/@potokvarte), [Foto](https://unsplash.com/photos/couple-dancing-in-a-kitchen-with-fairy-lights-3OgoF9I9YhI) | Paar tanzt in der Küche unter Lichterkette | Kopf Altersvorsorgedepot |
| `ll-gipfel-duoton-*.jpg` | [Mario von Rotz](https://unsplash.com/@mariovr), [Foto](https://unsplash.com/photos/a-man-standing-on-top-of-a-mountain-at-sunset-6-Rx70iv6fQ) | Mensch auf dem Gipfel gegen die Sonne | Kopf Rürup-Rente |
| `ll-huckepack-duoton-*.jpg` | [Toa Heftiba](https://unsplash.com/@heftiba), [Foto](https://unsplash.com/photos/man-giving-woman-piggyback-ride-rpANTTIl9ng) | Huckepack auf der Promenade | Kopf ETF-Lebensversicherung |
| `ll-kueche-*.jpg` | [Hanna Lazar](https://unsplash.com/@potokvarte), [Foto](https://unsplash.com/photos/couple-dancing-in-a-kitchen-doorway-1Nm3DpE8g-o) | Paar tanzt im Küchentürrahmen (in Farbe) | Startseite, Karte „Aufbauen“ |
| `ll-treiben-*.jpg` | [Victor Rosario](https://unsplash.com/@victor_rosario), [Foto](https://unsplash.com/photos/woman-floating-in-clear-turquoise-water-FoueBySPg1E) | Frau treibt im türkisen Wasser (in Farbe) | Startseite, Karte „Auszahlen“ |
| `ll-abend-*.jpg` | [Nico Kotze](https://unsplash.com/@np_kotze), [Foto](https://unsplash.com/photos/father-holding-a-child-on-the-beach-at-sunset-dIDcfzmgrLQ) | Vater hebt Kind am Strand im Abendlicht (in Farbe) | Startseite, Karte „Vererben / Verschenken“ |

### Optimierung 2 (17.10.2026): Köpfe in Farbe, Sabines Moment

Dieselben Motive wie oben, jetzt in Farbe (`scripts/duoton.mjs`, Art „farbe“): Die Köpfe der Produktseiten und von
`/produkte/` zeigen das Foto in Farbe, der Text steht auf dichtem Navy daneben bzw. darunter (gemessen in
`e2e/fotos.spec.ts`). Die `*-duoton-*.jpg` der Köpfe werden nicht mehr verwendet, nur noch `ll-strasse-duoton-*.jpg`.

| Datei | Fotograf | Motiv | Wo |
|---|---|---|---|
| `ll-rad-weit-*.jpg` | [Alexander Fastovets](https://unsplash.com/@darkmoon_afa), [Foto](https://unsplash.com/photos/a-man-riding-a-bike-down-a-road-under-a-cloudy-sky-Q8NG0KZkFlk) | Radfahrer unter weitem Himmel | Kopf ETF-Rentenversicherung, Kreisbild Daniel |
| `ll-wasser-*.jpg` | [Benjamin L. Jones](https://unsplash.com/@boardshortsben), [Foto](https://unsplash.com/photos/man-in-black-and-brown-long-sleeve-shirt-holding-silver-fish-59-SZ--EVvc) | Lachender Mann halb unter Wasser | Kopf ETF-Depot |
| `ll-lichter-*.jpg` | [Hanna Lazar](https://unsplash.com/@potokvarte), [Foto](https://unsplash.com/photos/couple-dancing-in-a-kitchen-with-fairy-lights-3OgoF9I9YhI) | Paar tanzt in der Küche unter Lichterkette | Kopf Altersvorsorgedepot, Kreisbild Lisa |
| `ll-gipfel-*.jpg` | [Mario von Rotz](https://unsplash.com/@mariovr), [Foto](https://unsplash.com/photos/a-man-standing-on-top-of-a-mountain-at-sunset-6-Rx70iv6fQ) | Mensch auf dem Gipfel gegen die Sonne | Kopf Rürup-Rente, Kreisbild Markus |
| `ll-huckepack-*.jpg` | [Toa Heftiba](https://unsplash.com/@heftiba), [Foto](https://unsplash.com/photos/man-giving-woman-piggyback-ride-rpANTTIl9ng) | Huckepack auf der Promenade | Kopf ETF-Lebensversicherung |
| `ll-linie-*.jpg` | [Oktay Yildiz](https://unsplash.com/@oktayyildiz), [Foto](https://unsplash.com/photos/person-riding-bicycle-in-the-road-8DVEsLkB_pU) | Einzelnes Rad auf gerader Straße | Kopf von `/produkte/` |
| `ll-gabelung-*.jpg` | [Jens Lelie](https://unsplash.com/@madebyjens), [Foto](https://unsplash.com/photos/two-roads-between-trees-u0vgcIOQG08) | Zwei Wege zwischen Bäumen | Kreisbild Sabine (statt des Vaters mit Kind am Strand) |

## Gestaltung 4 (17.10.2026): Köpfe mit Foto, Gesichter der Beispielpersonen

Jeder Seitenkopf hat ein Foto in Farbe (`src/daten/fotos.ts`). Neu kopiert: `ll-strasse-800.jpg` und `-1600.jpg` in Farbe
(vorher nur als Duoton), Nachweis oben bei `ll-strasse-duoton-*.jpg`; jetzt im Kopf von `/kosten/`, `/belege/` und `/termin/`.
Weiter verwendet in Farbe: `ll-gipfel` (Rürup-Rente), `ll-treiben` (Auszahlplan; seit 17.10.2026 auch `/rentenfaktor/`), `ll-gabelung` (Produktfinder), `ll-linie`
(Netto-Vergleich, Impressum, Datenschutz, Erstinformation, Cookies, 404), `ll-kueche` (Über uns).

Von Johannes bereitgestellt (Unsplash-Lizenz, Nachweis und Prüfpunkt Bildrechte in `../../bilder-pool/BILDNACHWEIS.md`,
Abschnitt „Von Johannes bereitgestellt“; die Unsplash-Lizenz enthält keine Einwilligung der Abgebildeten, § 22 KUG vor dem
Livegang klären):

| Datei | Fotograf | Motiv | Quelle | Wo |
|---|---|---|---|---|
| `familie-abendfeld-800.jpg`, `-1600.jpg` | Ilya Pavlov | Familie mit Kind auf weitem Feld im Abendlicht, viel Himmel. 5791 × 3866 im Original. | [Foto](https://unsplash.com/photos/XPT-OtA0E-8) | Kopf ETF-Rentenversicherung |
| `freiheit-fahrt-800.jpg`, `-1600.jpg` | Averie Woodard | Frau hält die Hand aus dem Autofenster, Bergstraße. 2738 × 1825 im Original. | [Foto](https://unsplash.com/photos/5d20kdvFCfA) | Kopf ETF-Depot |
| `familie-wiese-800.jpg`, `-1600.jpg` | Jessica Rockowitz | Eltern mit drei Kindern laufen Hand in Hand durch hohes Gras. 6977 × 5372 im Original. | [Foto](https://unsplash.com/photos/5NLCaz2wJXE) | Kopf Altersvorsorgedepot |
| `familie-aussicht-800.jpg`, `-1600.jpg` | Roberto Nickson | Fünf Menschen sitzen nebeneinander und schauen über die Berge. 5472 × 3648 im Original. | [Foto](https://unsplash.com/photos/smJ6XsYy8gA) | Kopf ETF-Lebensversicherung |
| `paar-strandstuehle-800.jpg`, `-1600.jpg` | Tr Ng Tuy T Ly | Älteres Paar in Klappstühlen am hellen Strand, viel freie Fläche. 5184 × 3456 im Original. | [Foto](https://unsplash.com/photos/6VP3cliV5I0) | Kopf `/produkte/` |
| `strand-abend-800.jpg`, `-1600.jpg` | Sean Oulashin | Welle am Strand im warmen Abendlicht. 4621 × 3072 im Original. | [Foto](https://unsplash.com/photos/KMn4VEeEPR8) | Kopf `/fragen/` |
| `gesicht-mann-30-brille-400.jpg`, `-800.jpg` | Christian Buehner | Mann um die 30, Locken, Brille, lacht. | [Foto](https://unsplash.com/photos/DItYlc26zVI) | Gesicht der Beispielperson Daniel auf ihrer Produktseite, immer neben „Ein Beispiel: …“ |
| `gesicht-frau-28-lacht-400.jpg`, `-800.jpg` | Tim Mossholder | Junge Frau vor Holzwand, lacht. | [Foto](https://unsplash.com/photos/9_w16htEhIM) | Gesicht der Beispielperson Jana auf ihrer Produktseite, immer neben „Ein Beispiel: …“ |
| `gesicht-frau-35-blond-400.jpg`, `-800.jpg` | Marina Piano | Frau um die 35, blonde Locken, lacht. | [Foto](https://unsplash.com/photos/LIv3NEnZ3iI) | Gesicht der Beispielperson Lisa auf ihrer Produktseite, immer neben „Ein Beispiel: …“ |
| `gesicht-mann-40-400.jpg`, `-800.jpg` | Christoph Aigner | Mann um die 40, verschränkte Arme, lacht. | [Foto](https://unsplash.com/photos/vhj1DvszLZU) | Gesicht der Beispielperson Markus auf ihrer Produktseite, immer neben „Ein Beispiel: …“ |
| `gesicht-frau-55-400.jpg`, `-800.jpg` | Vitaly Gariev | Frau um die 55, blond, lächelt. | [Foto](https://unsplash.com/photos/PEftiOXEhy8) | Gesicht der Beispielperson Sabine auf ihrer Produktseite, immer neben „Ein Beispiel: …“ |
