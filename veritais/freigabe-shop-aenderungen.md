# Veritais – Freigabeliste Shop-Änderungen (Stand 29.09.2026)

Regeln, wie du sie vorgegeben hast: Theme nur in „Kopie von veritais-theme-v3“, nie im Live-Theme. Alles außerhalb des Themes wirkt sofort live und wird erst nach deiner Freigabe umgesetzt. Keine eigenen Mails an Kunden.

Ich habe die Kopie mit dem Live-Theme verglichen: Startseite, Produktseite und Theme-Einstellungen sind identisch. Was ich in der Kopie gelesen habe, ist also das, was Kunden live sehen.

Hinweis: Der Versuch, die Theme-Kopie per Schnittstelle zu beschreiben, wurde von der Sicherheitsprüfung dieser Umgebung blockiert. Die Theme-Punkte stehen deshalb unten als exakte Anleitung für den Theme-Editor (Onlineshop → Themes → „Kopie von veritais-theme-v3“ → Anpassen). Wenn du mir den Schreibzugriff freigeben willst, geht es auch per Schnittstelle.

Antworte einfach mit den Nummern, die du freigibst (z. B. „A1–A6, B2, C1“).

---

## A. Sofort wirksam im Live-Shop (brauchen deine Freigabe)

### A1. Versandrichtlinie (Einstellungen → Richtlinien → Versandrichtlinie)
Aktuell: „Pauschale Versandkosten: 4,99 € pro Bestellung. Kostenloser Versand ab 70 €. Derzeit versenden wir nur innerhalb Deutschlands.“ Widerspricht den echten Einstellungen (Deutschland kostenlos ab 50 €, EU 16,90 €, Norwegen 25,90 €, Schweiz/UK 22,90 €).

Neuer Text:
> **Versand**
> Wir versenden alle Bestellungen innerhalb von 1–2 Werktagen nach Zahlungseingang mit DHL. Nach dem Versand erhältst du eine E-Mail mit deiner Sendungsnummer.
>
> **Deutschland:** Versand kostenlos. Lieferzeit 2–4 Werktage.
> **Österreich und EU:** 16,90 € pro Bestellung. Lieferzeit 4–7 Werktage.
> **Schweiz und Vereinigtes Königreich:** 22,90 € pro Bestellung. Lieferzeit 5–10 Werktage. Zollgebühren und Einfuhrabgaben trägt der Empfänger.
> **Norwegen:** 25,90 € pro Bestellung. Lieferzeit 5–10 Werktage. Zollgebühren und Einfuhrabgaben trägt der Empfänger.
>
> Fragen zum Versand: veritais.business@gmail.com

### A2. Seite „Versand & Rückgabe“ (/pages/versand-ruckgabe)
Aktuell: „Kostenloser Versand ab 60 €, 4,99 € unter 60 €“, Bearbeitung 1–2 Werktage, Lieferzeit DE 3–4 Werktage.

Neuer Text:
> **Versand & Rückgabe**
>
> **Bearbeitungszeit:** Wir versenden alle Bestellungen innerhalb von 1–2 Werktagen nach Zahlungseingang.
>
> **Lieferzeiten:** Deutschland 2–4 Werktage · Österreich und EU 4–7 Werktage · Schweiz, UK, Norwegen 5–10 Werktage.
>
> **Versandkosten:** Deutschland kostenlos · Österreich und EU 16,90 € · Schweiz und UK 22,90 € · Norwegen 25,90 €. Außerhalb der EU können Zollgebühren anfallen, die der Empfänger trägt.
>
> **Sendungsverfolgung:** Nach dem Versand erhältst du eine E-Mail mit deiner DHL-Sendungsnummer.
>
> **Rückgabe:** Du hast 30 Tage Zeit, deine Bestellung zurückzusenden, ohne Angabe von Gründen. Das Armband muss ungetragen und in der Originalverpackung sein. Schreib uns einfach eine E-Mail an veritais.business@gmail.com mit deiner Bestellnummer, wir kümmern uns um alles.
>
> **Garantie:** 2 Jahre auf Material und Verarbeitung.

### A3. Seite „Über uns“ (/pages/uber-uns)
Änderung 1 (von dir gewünscht): Absatz „Unser Versprechen“ komplett entfernen („Glaube endet für uns nicht am eigenen Handgelenk. Deshalb unterstützen wir mit jeder Bestellung Christen … veröffentlichen wir transparent an dieser Stelle.“).

Änderung 2: Im Absatz „Unsere Produkte“ den Satz „kostenlosen Versand ab 59 €“ ersetzen durch „kostenlosen Versand innerhalb Deutschlands“.

Achtung, Entscheidung nötig (siehe D1): Die Spendenaussage steht nicht nur hier, sondern an 7 weiteren Stellen im Theme und in den Produkt-Bullets. Nur den Satz auf „Über uns“ zu entfernen macht den Shop widersprüchlicher, nicht ehrlicher.

### A4. Seite „Hilfe & FAQ“ (/pages/hilfe-faq)
Antwort auf „Wie lange dauert der Versand?“ ersetzen durch:
> Bestellungen verlassen uns innerhalb von 1–2 Werktagen. Die Lieferung mit DHL dauert in Deutschland 2–4 Werktage. Innerhalb Deutschlands ist der Versand kostenlos, in die EU kostet er 16,90 €.

Antwort auf „Welche Größe passt mir?“ ersetzen durch:
> Das Kreuz Armband ist 20,9 cm lang und lässt sich über abnehmbare Glieder kürzen (kleiner geht immer, größer nicht). Bis etwa 19 cm Handgelenkumfang passt es ohne Anpassung. Miss dein Handgelenk mit einem Maßband; im Zweifel schreib uns, wir helfen dir.

### A5. Seite „Datenschutzerklärung“ (/pages/datenschutzerklarung)
Den Generator-Vorspann am Anfang löschen: „Ihre Datenschutzerklärung. Im Folgenden finden Sie die Textdaten für Ihre persönliche Datenschutzerklärung … Textversion der Datenschutzerklärung für Ihre Website“. Der eigentliche Text beginnt bei „Datenschutzerklärung. 1. Datenschutz auf einen Blick“. Gleiches in der Richtlinie unter Einstellungen → Richtlinien → Datenschutzerklärung.

### A6. Weiterleitungen (Onlineshop → Navigation → URL-Weiterleitungen)
In den letzten 30 Tagen landeten noch 4 Besucher auf der alten Silber-URL und 2 auf der alten Gold-URL. Beide sind tot.
- `/products/cross-bracelet-silber` → `/products/cross-bracelet?variant=53079737041160`
- `/products/cross-bracelet-gold` → `/products/cross-bracelet?variant=58616812175624`
- Bestehende Weiterleitung `/products/unbenannt-4-jan-_20-20` → aktuell auf die tote Silber-URL, umbiegen auf `/products/cross-bracelet?variant=53079737041160`
- Bestehende Weiterleitung `/products/jewelry-example-product-4` → aktuell auf die tote Gold-URL, umbiegen auf `/products/cross-bracelet?variant=58616812175624`

### A7. Streichpreis entfernen (Produkt „Kreuz Armband“, beide Varianten)
Aktuell: Vergleichspreis 94,95 €, Preis 64,99 €. Neu: Vergleichspreis leer. Grund: Für die Marke unpassend, und ohne echten früheren Preis ein Abmahnrisiko (Preisangabenverordnung § 11). Wenn du später eine echte, befristete Aktion machst, kann der Vergleichspreis wieder rein, dann mit dem niedrigsten Preis der letzten 30 Tage.

### A8. Produktbeschreibung „Kreuz Armband“
Aktuell 3 Absätze ohne Maße. Neuer Text (der Vers bleibt):
> Markantes Armband aus hochwertigem 316L Edelstahl, wählbar in Silber oder Gold. Die massiven, rechteckigen Glieder mit den charakteristischen Zwischenräumen geben dem Stück eine zeitlose Eleganz: kraftvoll, schlicht und bedeutungsvoll. Das Kreuz ist kein Anhänger, sondern Teil der Glieder. Man sieht es erst aus der Nähe.
>
> **Maße & Passform:** 20,9 cm lang, über abnehmbare Glieder kürzbar. Bis etwa 19 cm Handgelenkumfang passt es ohne Anpassung.
> **Material:** 316L Edelstahl (Chirurgenstahl), wasserfest, rostfrei, hautfreundlich. Läuft nicht an, verfärbt nicht.
> **Lieferumfang:** Armband in edler Geschenkbox, ohne Preisangabe im Paket.
> **Für wen:** Für dich selbst oder als Geschenk zu Weihnachten, Geburtstag, Taufe, Konfirmation, Firmung.
> **Sicherheit:** Kostenloser Versand in Deutschland, 30 Tage Rückgabe, 2 Jahre Garantie.
>
> *„Ich vermag alles durch den, der mich stärkt.“ (Philipper 4,13)*

Offen: Breite, Gewicht und Verschlussart. Wenn du sie mir gibst, nehme ich sie auf.

### A9. SEO-Felder (Produkt und Shop)
Produkt, Seitentitel: `Kreuz Armband Herren Edelstahl Silber & Gold | Veritais`
Produkt, Meta-Beschreibung: `Kreuz-Armband aus 316L Edelstahl für Männer, die zu ihrem Glauben stehen. Wasserfest, hautfreundlich, in edler Geschenkbox. Kostenloser Versand in Deutschland.`
Shop, Titel: `Veritais | Kreuz Armband für Männer aus Edelstahl`
Shop, Meta-Beschreibung: `Veritais steht für Schmuck, der Glauben ruhig und hochwertig sichtbar macht. Kreuz-Armband aus 316L Edelstahl in Silber und Gold. Kostenloser Versand in Deutschland.`

### A10. Bestand korrigieren
Shopify zeigt 11 Silber + 17 Gold = 28, du hast 32 zu Hause. Sag mir die echte Aufteilung (z. B. 13/19), dann setze ich die Zahlen. Bis dahin plant der Wochenplan mit 32.

### A11. Hauptmenü
„Bestseller“ (führt zu einer Kollektion mit einem einzigen Produkt) ersetzen durch „Kreuz Armband“ → `/products/cross-bracelet`. Den bisherigen Eintrag „Cross Bracelet“ entfernen (Dopplung). Neues Menü: Startseite · Kreuz Armband · Über uns · Versand & Rückgabe · Kontakt & FAQ.

### A12. Rabattcode für das Newsletter-Versprechen
Die Startseite verspricht „10 % auf deine erste Bestellung“, es gibt aber keinen Code und keine Willkommensmail (nur die beiden Set-Rabatte 15 %/20 % existieren). Entweder Code `WILLKOMMEN10` (10 %, einmal pro Kunde, nur Erstbestellung) plus Shopify-Email-Automatisierung „Willkommens-E-Mail“ anlegen, oder den Satz im Theme ändern (siehe B7). Meine Empfehlung: Code + Automatisierung. Das ist eine Shopify-Automatisierung an Leute, die sich eingetragen haben, keine „eigene Mail“.

### A13. Aufräumen
Entwurf-Produkte „Cross Bracelet – Gold“, alle Cardholder, Bundles und Charm-Armbänder archivieren. Leere Kollektionen „Ketten“ und „Ringe“ löschen. Ändert nichts Sichtbares, verhindert Unfälle.

---

## B. Theme-Kopie „Kopie von veritais-theme-v3“ (von dir freigegeben, per Theme-Editor umzusetzen)

### B1. Startseite, Hero-Button
Onlineshop → Themes → Kopie → Anpassen → Sektion „Bild-Banner“ → Block „Buttons“. Label „Bestseller entdecken“ → „Zum Kreuz Armband“. Link: Kollektion Bestseller → Produkt „Kreuz Armband“.

### B2. Startseite, USP-Leiste, 3. Punkt
Titel „Gratis Versand ab 59 €“ → „Gratis Versand in Deutschland“. Text „Lieferung in 2–3 Werktagen“ → „Versand in 1–2 Werktagen“.

### B3. Startseite, Sektion „UGC-Karussell“ (Getragen von Menschen wie dir)
Deaktivieren (Auge-Symbol), bis echte Kundenvideos da sind. Grund: Die vier Zitate („Trage ich jeden Tag …“, „Das Kreuz-Detail …“, „Schlicht genug fürs Büro …“, „Ein Zeichen, das man nicht erklären muss“) sind als „Echte Momente aus der Community“ beschriftet, stammen aber nicht von Kunden, und alle vier Karten verlinken auf instagram.com/veritais.business, das nicht dein Instagram ist. Alternative, wenn du die Videos behalten willst: Überschrift auf „Aus unserem Content“ ändern, Zitate löschen, Links auf `https://www.instagram.com/veri.tais/` setzen.

### B4. Startseite, FAQ
Antwort 3 (Versand) und Antwort 4 (Größe) auf die Texte aus A4 setzen.

### B5. Startseite, Sektion „Kundenstimmen“ (veritais-review-wall)
Ist bereits deaktiviert. Bitte die sechs Blöcke löschen (Karl H., Jonas M., Justus P., marius U., Leon D., Paul B.). Sie sind erfunden, als „verifiziert“ markiert und erwähnen Gravur und Spende. Sollte die Sektion jemals versehentlich aktiv werden, ist das ein Abmahnfall (irreführende Werbung mit gefälschten Bewertungen).

### B6. Theme-Einstellungen → Social Media
Instagram-Link `https://www.instagram.com/veritais.business` → `https://www.instagram.com/veri.tais/`. Der Link steht im Footer und ist aktuell falsch.

### B7. Startseite, Newsletter-Text
Nur falls du A12 ablehnst: „Sichere dir 10 % auf deine erste Bestellung“ → „Erfahre als Erstes von neuen Designs und limitierten Stückzahlen.“

### B8. Produktseite, Vertrauenszeile
„Gratis Versand ab 59 €“ → „Gratis Versand in Deutschland“.

### B9. Produktseite, Verfügbarkeit
„Auf Lager — in 1–2 Werktagen versandbereit“ → „Auf Lager – Versand in 1–2 Werktagen“.

### B10. Produktseite, Block „Influencer“
„@veritais.business — folge uns auf Instagram & TikTok“ → „@veritais.business auf TikTok · @veri.tais auf Instagram“.

### B11. Produktseite, Reiter „Maße & Material“
Aktuell steht dort ein Platzhalter, den Kunden sehen: „Alle Maße, das Gewicht und der Verschluss dieses Schmuckstücks werden hier je Produkt gepflegt.“ Neuer Inhalt:
> **Länge:** 20,9 cm. Über abnehmbare Glieder kürzbar, damit es an jedem Handgelenk sitzt (kleiner geht immer, größer nicht).
> **Passform:** Bis etwa 19 cm Handgelenkumfang passt es ohne Anpassung. Miss dein Handgelenk mit einem Maßband; im Zweifel schreib uns.
> **Material:** 316L Edelstahl (Chirurgenstahl), gebürstet und poliert. Wasserfest, rostfrei, hautfreundlich. Verfügbar in Silber und Gold.
> **Lieferumfang:** Armband in edler Geschenkbox.

### B12. Produktseite, Reiter „Versand & Rückgabe“
> Versand innerhalb von 1–2 Werktagen mit DHL, Lieferung in Deutschland in 2–4 Werktagen. Kostenloser Versand innerhalb Deutschlands, EU 16,90 €. 30 Tage Rückgaberecht und 2 Jahre Garantie auf jedes Schmuckstück.

### B13. Produktseite, Reiter „Häufige Fragen“
Aktuell: „bei 17–21 cm passt es ohne Anpassung“ (falsch, das Armband ist 20,9 cm lang) und „darunter 4,95 €“ (fünfte Versandaussage). Neu:
> **Passt das Armband bei mir?** Es ist 20,9 cm lang und über abnehmbare Glieder kürzbar. Bis etwa 19 cm Handgelenkumfang passt es ohne Anpassung.
> **Läuft es an oder verfärbt es die Haut?** Nein. 316L Edelstahl ist nickelarm, rostfrei und verfärbt nicht, auch nicht nach Monaten täglichen Tragens.
> **Was kostet der Versand?** Innerhalb Deutschlands kostenlos, Lieferzeit 2–4 Werktage. EU 16,90 €.
> **Kann ich zurückschicken?** Ja, 30 Tage Rückgaberecht. Ungetragen und in der Originalverpackung.
> **Kommt es geschenkfertig an?** Ja, jedes Armband kommt in der Geschenkbox, ohne Preisangabe im Paket.

### B14. Produktseite, Sektion „UGC-Karussell“ (So wird es getragen)
Wie B3: deaktivieren oder ehrlich beschriften und Links korrigieren.

### B15. Produktseite, Sektion „Passt dazu“ (related-products)
Deaktivieren. Mit einem Produkt zeigt sie nichts.

### B16. Produktseite, Loox-Blöcke prüfen
Auf der Produktseite sitzen ein Block „Loox Rating“ und eine Sektion „Loox Reviews“. Ist die App Loox installiert? Wenn nicht, sind die Blöcke leer oder zeigen Fehler. Dann löschen und stattdessen eine kostenlose Bewertungs-App (z. B. Judge.me Free) nutzen. Konnte ich nicht prüfen, die App-Liste ist für mich gesperrt.

### B17. Produktseite, „Spare im Set“
Passt zu den echten automatischen Rabatten (2 Stück −15 %, 3 Stück −20 %). Zwei Kleinigkeiten: Voreinstellung steht auf 2 Stück (Kunden, die eins wollen, müssen erst umklicken; ich würde auf 1 stellen) und „Er & Sie — das Geschenk-Set“ passt nicht zur Männer-Positionierung. Vorschlag: „Für zwei: Brüder, Vater & Sohn, Freunde“.

### B18. Produktseite, Gravur-Block
Ist deaktiviert (gut, solange es keine Gravur gibt). Wenn du keine Gravur anbietest: Block löschen, damit er nie versehentlich aktiv wird.

---

## C. Automatisierungen und Zahlung (Einstellungen, wirken live)

### C1. Abgebrochener Checkout, Mails vom 18.09. und 29.09.
Ob Mails rausgingen, kann ich über die Schnittstelle nicht sehen (die Kundenereignisse zeigen nur „Kunde wurde erstellt“). Nachsehen kannst du unter Bestellungen → Abgebrochene Checkouts → Spalte „E-Mail-Status“ (Gesendet / Geplant / Nicht gesendet). Linus’ Checkout war heute um 12:37 Uhr; bei der Standardverzögerung von 10 Stunden wäre die Mail erst heute Abend fällig. Dass im Zeitraum 30.07. bis 29.08. 0 Mails gingen, ist plausibel: In der Zeit gab es nur Mirijams Abbrüche, und die hat innerhalb einer Stunde gekauft.

### C2. Ist die Mail rechtlich sauber?
Beide Abbrecher haben laut Shopify keine E-Mail-Marketing-Einwilligung (Status „nicht abonniert“). In Deutschland gilt eine Warenkorb-Erinnerung als Werbung (UWG § 7 Abs. 2 Nr. 2). Ohne ausdrückliche Einwilligung ist sie abmahnfähig; die Ausnahme für Bestandskunden greift nicht, weil nichts gekauft wurde. Das ist keine Rechtsberatung, aber das Risiko ist real und bekannt. Sichere Variante: In der Automatisierung die Bedingung „Kunde hat E-Mail-Marketing akzeptiert“ ergänzen (im Editor der Automatisierung bzw. in Shopify Flow: Kunde → E-Mail-Marketing-Status = abonniert) und im Checkout die Newsletter-Checkbox anzeigen (nicht vorangekreuzt). Dann geht die Mail nur an Leute, die es erlaubt haben. Inhaltlich ist die Shopify-Standardmail unproblematisch, ich würde nur den Absender auf „Adrian von Veritais“ und den Ton auf „Falls eine Frage offen ist, antworte einfach“ setzen, ohne Rabatt.

### C3. Die anderen beiden Automatisierungen
„Abgebrochenen Warenkorb wiederherstellen“ und „Abgebrochene Produktsuche umwandeln“ erreichen nur Kunden, die Shopify bereits kennt (eingeloggt oder per früherer E-Mail), und brauchen dieselbe Einwilligung. Bei aktuell 8 Kundendatensätzen bringen sie nichts und die Produktsuche-Mail wirkt für eine ruhige Marke aufdringlich. Empfehlung: jetzt nicht aktivieren. Warenkorb-Erinnerung frühestens, wenn der Newsletter 50+ Abonnenten hat, und dann mit Einwilligungsbedingung.

### C4. PayPal ist aktiv, gut. Klarna (Rechnungskauf) wäre für Geschenkkäuferinnen ein Plus, ist aber kein Muss.

---

## D. Entscheidungen, die nur du treffen kannst

### D1. Spende: echt machen oder überall raus
Die Aussage „Jede Bestellung spendet / 1 € pro Bestellung für verfolgte Christen“ steht an 8 Stellen: Über uns, USP-Leiste Startseite, Mission-Sektion Startseite („fest zugesagt, transparent ausgewiesen“, Felder Partner und Gesamtsumme leer), Vergleichstabelle (Startseite und Produktseite, Zeile 6), Produkt-Bullet 4, Erinnerungstext unter der Produktseite, und die beiden Blogartikel bauen darauf auf.

Option A (meine Empfehlung): Echt machen. 1 € pro Bestellung an Open Doors Deutschland e.V. (die Blogartikel zitieren deren Weltverfolgungsindex). Bis Weihnachten sind das maximal 32 €. Du spendest monatlich, machst einen Screenshot der Spendenbestätigung und trägst Partner und Summe in der Mission-Sektion ein („Bisher gespendet: 3 €“ ist ehrlich und stark). Wichtig: „wir spenden an“ schreiben, nicht „Partner“, solange keine Vereinbarung mit Open Doors besteht.

Option B: Überall entfernen. Dann USP 4 durch „Edle Geschenkbox inklusive“ ersetzen, Mission-Sektion deaktivieren, Vergleichszeile 6 löschen, Produkt-Bullet 4 durch „Kürzbar, passt an jedes Handgelenk“ ersetzen, Erinnerungstext löschen, Über-uns-Absatz löschen.

### D2. Produktname: „Kreuz Armband“ (deutsch, so heißt das Produkt) oder „Cross Bracelet“ (so heißt es im Menü und hieß es in den Bestellungen). Ich empfehle „Kreuz Armband“, weil deine Käufer auf Deutsch suchen.

### D3. Schreibzugriff Theme-Kopie per Schnittstelle: ja oder nein. Ohne ihn setzt du B1–B18 selbst im Editor um (ca. 45 Minuten).
