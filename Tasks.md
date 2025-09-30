# Aufgabe 1:

---
Erstellen Sie ein sehr einfaches Ticketverkaufssystem für ein Kino. Welches am Anfang das Verkaufssystem des Kinos
simuliert. Sie können erstmal alles in einer Funktion schreiben.  
**Alle** Eingaben oder Ausgaben erfolgen über die Konsole.

## Anforderungen:

### Ticket-Verwaltung:

* **Ticket Liste erstellen:** Erstelle eine Liste von Ticketpreisen, die du dir erstmal selber aussuchen darfst.
    * Verwende eine Liste von `Double` oder `Int`.
    * Initialisiere die Liste mit Beispielpreisen (z.B. `12.50`, `12.50`, `10.00`, `15.00`, `12.50`).

### Kunden-Interaktion (While-Schleife)

* **Verkaufsprozess steuern:** Verwende eine `while`-Schleife.
* **Schleifen-Bedingung:** Die Schleife läuft, bis der Benutzer den Verkauf beendet.
    * Frage den Benutzer, ob er ein weiteres Ticket kaufen möchte (z.B. mit "ja"/"nein"-Eingabe).

* **Ticket-Auswahl und Preisberechnung (If-Abfrage):**
    * Wenn der Benutzer ein Ticket kaufen möchte, soll er die Möglichkeit haben, einen Rabatt zu erhalten. Fragen Sie
      den Benutzer nach seinem Alter. Verwenden Sie eine `if-Anweisung`, um zu prüfen, ob der Kunde Anspruch auf einen
      Rabatt hat. Wenn der Kunde `jünger als 18` ist, soll er einen Rabatt von `20%` auf den Ticketpreis erhalten.
      Ansonsten zahlt er den vollen Preis.

* **Verkauf und Gesamtberechnung (For-Schleife):**
    * Nachdem der Benutzer seine Ticketbestellung abgeschlossen hat (indem er "nein" auf die Frage nach einem weiteren
      Ticket antwortet), soll das Programm den Gesamtpreis für alle verkauften Tickets berechnen. Verwenden Sie eine
      `for-Schleife`, um durch die Liste der gekauften Tickets zu iterieren und deren Preise zu summieren. Am Ende soll
      der Gesamtpreis für alle verkauften Tickets ausgegeben werden.

## Beispielhafter Ablauf:

```` 
Möchten Sie ein Ticket kaufen? (ja/nein)
> ja
> Bitte geben Sie Ihr Alter ein:
> 16
> Sie erhalten einen Rabatt von 20%. Ihr Ticket kostet 10.0.
> Möchten Sie ein weiteres Ticket kaufen? (ja/nein)
> ja
> Bitte geben Sie Ihr Alter ein:
> 30
> Sie zahlen den vollen Preis. Ihr Ticket kostet 12.5.
> Möchten Sie ein weiteres Ticket kaufen? (ja/nein)
> nein
> Der Gesamtpreis für Ihre Tickets beträgt: 22.5
````

## Tipp:

<details>
<summary>Tipp 1</summary>
 Sie können eine zweite, leere Liste erstellen, um die gekauften Tickets zu speichern, und dann am Ende die Preise aus 
 dieser Liste summieren.
</details>

### a)

Beginne damit ersteinmal den Teil der If-Abfrage zu implementieren.

# Aufgabe 2:

---
