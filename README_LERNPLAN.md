# 📚 Lernplan: Zwischentest 2 - Buchführung

## ✅ Machbarkeits-Check: Verstehst du das Grundprinzip?

Lass uns mit einem ganz einfachen Beispiel starten. Wenn du das verstehst, kannst du den Rest auch!

### Das Grundprinzip: "Soll an Haben"

**Die Regel ist simpel:**
- **Links steht SOLL** (Wo kommt's hin? / Was wird mehr?)
- **Rechts steht HABEN** (Wo kommt's her? / Was wird weniger?)

**Buchungssatz-Format:**
```
Konto im SOLL  an  Konto im HABEN    Betrag €
```

---

## 🎯 Beispiel 1: Eröffnungsbilanz (EBK)

**Situation:** Dein Unternehmen startet mit folgenden Werten:
- Kasse: 5.000 €
- Bank: 10.000 €
- Verbindlichkeiten: 3.000 €
- Eigenkapital: 12.000 €

**Wie buchst du das?**

Die Eröffnungsbilanz wird in T-Konten übertragen:

**Schritt 1:** Eröffnungsbilanzkonto (EBK) anlegen

```
          EBK
─────────────────────────
Soll    |    Haben
        |
```

**Schritt 2:** Alle Aktivkonten (Vermögen) stehen links in der Bilanz → buchen im SOLL
```
Kasse           an  EBK         5.000 €
Bank            an  EBK        10.000 €
```

**Schritt 3:** Alle Passivkonten (Kapital) stehen rechts in der Bilanz → buchen im HABEN
```
EBK             an  Verbindlichkeiten    3.000 €
EBK             an  Eigenkapital        12.000 €
```

**T-Konten nach Eröffnung:**

```
          Kasse                          Bank
─────────────────────       ─────────────────────
S       |       H           S       |       H
5.000   |                   10.000  |


    Verbindlichkeiten                 Eigenkapital
─────────────────────       ─────────────────────
S       |       H           S       |       H
        |   3.000                   |   12.000
```

**✅ Check:** Verstehst du das? Aktiva (Vermögen) links = Soll, Passiva (Kapital) rechts = Haben?

---

## 🎯 Beispiel 2: Einkauf von Waren (MIT Vorsteuer!)

**Situation:** Du kaufst Waren für 1.000 € netto. Die Mehrwertsteuer beträgt 19% = 190 €. Du zahlst also insgesamt 1.190 € bar.

**Denkweise:**
1. Waren kommen ins Lager → **Wareneinkauf** wird MEHR → Soll
2. Vorsteuer kannst du zurückholen → **Vorsteuer** ist eine Forderung → Soll
3. Geld geht aus der Kasse → **Kasse** wird WENIGER → Haben

**Buchungssatz:**
```
Wareneinkauf          an  Kasse        1.000 €
Vorsteuer 19%         an  Kasse          190 €
```

**Oder zusammengefasst:**
```
Wareneinkauf       1.000 €    an  Kasse    1.190 €
Vorsteuer 19%        190 €
```

**T-Konten:**

```
     Wareneinkauf                      Vorsteuer 19%
─────────────────────       ─────────────────────
S       |       H           S       |       H
1.000   |                   190     |


          Kasse
─────────────────────
S       |       H
5.000   |   1.190
        |
Saldo:  3.810
```

**✅ Check:** Verstehst du, dass Vorsteuer IMMER auf der Soll-Seite steht? (Du kriegst sie zurück!)

---

## 🎯 Beispiel 3: Laufende Kosten buchen (Miete, Zinsen)

**Situation:** Du zahlst 500 € Miete per Banküberweisung.

**Denkweise:**
1. Miete ist ein Aufwand → **Mietaufwand** entsteht → Soll
2. Geld geht vom Bankkonto → **Bank** wird weniger → Haben

**Buchungssatz:**
```
Mietaufwand        an  Bank        500 €
```

**T-Konten:**

```
     Mietaufwand                          Bank
─────────────────────       ─────────────────────
S       |       H           S       |       H
500     |                   10.000  |   500
```

**Weitere typische Aufwandskonten:**
- Zinsaufwand an Bank
- Löhne und Gehälter an Bank/Kasse
- Versicherungen an Bank

**✅ Check:** Alle Aufwände stehen im SOLL! Merke dir das!

---

## 🎯 Beispiel 4: Privatkonten (Entnahmen & Einlagen)

### Entnahme (Geld raus für privat)

**Situation:** Du entnimmst 200 € aus der Kasse für private Zwecke.

**Buchungssatz:**
```
Privatentnahmen    an  Kasse        200 €
```

**T-Konten:**
```
    Privatentnahmen                      Kasse
─────────────────────       ─────────────────────
S       |       H           S       |       H
200     |                   3.810   |   200
```

### Einlage (Geld rein vom Inhaber)

**Situation:** Du legst 1.000 € privates Geld ins Unternehmen ein (Banküberweisung).

**Buchungssatz:**
```
Bank               an  Privateinlagen    1.000 €
```

**T-Konten:**
```
          Bank                        Privateinlagen
─────────────────────       ─────────────────────
S       |       H           S       |       H
9.500   |                           |   1.000
1.000   |
```

**✅ Check:** Entnahmen = Soll (wie Aufwand), Einlagen = Haben (wie Ertrag)

---

## 🔄 Die Abschlusskette (DAS WICHTIGSTE!)

Das ist der Kern des Tests! Du musst diese Kette verstehen:

### Schritt 1: T-Konten aufstellen und Salden bilden

Alle Geschäftsvorfälle sind gebucht. Jetzt rechnest du für jedes Konto:
- **Saldo = Summe Soll - Summe Haben** (oder umgekehrt, je nachdem welche Seite größer ist)

### Schritt 2: GuV (Gewinn- und Verlustrechnung) erstellen

**Regel:**
- Alle **Aufwandskonten** (stehen im Soll) → Schließen auf **GuV im SOLL**
- Alle **Ertragskonten** (stehen im Haben) → Schließen auf **GuV im HABEN**

**Buchungssätze zum Abschluss:**
```
GuV    an    Wareneinkauf       (Saldo vom Wareneinkauf)
GuV    an    Mietaufwand        (Saldo vom Mietaufwand)
GuV    an    Zinsaufwand        (Saldo vom Zinsaufwand)
...

Umsatzerlöse    an    GuV       (Saldo von Umsatzerlöse) ← ACHTUNG: Nicht im Test!
```

**GuV-Konto:**
```
                GuV
─────────────────────────────────
Soll (Aufwand)  |  Haben (Ertrag)
─────────────────────────────────
Wareneinkauf    |  Umsatzerlöse
Mietaufwand     |
Zinsaufwand     |
                |
Saldo = Gewinn  |  (wenn Haben > Soll)
        oder    |
        Verlust |  (wenn Soll > Haben)
```

**Gewinn oder Verlust ermitteln:**
- **Gewinn:** Erträge > Aufwendungen → Saldo steht im SOLL der GuV
- **Verlust:** Aufwendungen > Erträge → Saldo steht im HABEN der GuV

### Schritt 3: Gewinn/Verlust auf Eigenkapital buchen

**Bei Gewinn:**
```
GuV    an    Eigenkapital    (Gewinn)
```

**Bei Verlust:**
```
Eigenkapital    an    GuV    (Verlust)
```

### Schritt 4: Privatkonten auf Eigenkapital buchen

```
Eigenkapital    an    Privatentnahmen    (Saldo)
Privateinlagen  an    Eigenkapital       (Saldo)
```

**Eigenkapitalkonto nach Abschluss:**
```
             Eigenkapital
─────────────────────────────────
Soll            |  Haben
─────────────────────────────────
Anfangsbestand  |  Anfangsbestand
(aus EBK)       |  (aus EBK)
                |
Privatentnahmen |  Gewinn (aus GuV)
Verlust         |  Privateinlagen
                |
                |  Saldo = Neues EK
```

### Schritt 5: Alle Bestandskonten auf SBK (Schlussbilanzkonto) buchen

**Regel:**
- Alle **Aktivkonten** (Vermögen) → Abschluss auf **SBK im HABEN**
- Alle **Passivkonten** (Kapital) → Abschluss auf **SBK im SOLL**

**Buchungssätze:**
```
SBK    an    Kasse              (Saldo)
SBK    an    Bank               (Saldo)
SBK    an    Vorsteuer          (Saldo)

Verbindlichkeiten    an    SBK  (Saldo)
Eigenkapital         an    SBK  (Saldo, nach GuV-Abschluss!)
```

**Schlussbilanz (SBK):**
```
           Schlussbilanz (SBK)
─────────────────────────────────────────
Aktiva (Soll)       |  Passiva (Haben)
─────────────────────────────────────────
Kasse               |  Eigenkapital (neu)
Bank                |  Verbindlichkeiten
Vorsteuer           |
─────────────────────────────────────────
Summe Aktiva        |  Summe Passiva
(muss gleich sein!)
```

---

## 📝 Zusammenfassung: Die 5-Schritte-Formel

1. **EBK buchen** (Eröffnung)
2. **Geschäftsvorfälle buchen** (Einkäufe, Kosten, Privat)
3. **GuV erstellen** (Aufwände & Erträge abschließen → Gewinn/Verlust)
4. **Eigenkapital aktualisieren** (GuV + Privatkonten)
5. **SBK erstellen** (Alle Bestandskonten abschließen)

---

## 🎓 Was du JETZT tun solltest:

### Test 1: Kannst du diese Buchungssätze bilden?

Versuche folgende Situationen zu buchen (Lösungen unten):

1. Du kaufst eine Maschine für 5.000 € netto + 19% MwSt., zahlst bar.
2. Du zahlst 300 € Zinsen per Bank.
3. Du entnimmst 500 € aus der Kasse für privat.
4. Dein Eigenkapital zu Jahresbeginn war 20.000 €. Übertrage es vom EBK.

### Lösungen:

1. **Maschinen 5.000 € an Kasse 5.950 €**  
   **Vorsteuer 19% 950 €**

2. **Zinsaufwand 300 € an Bank 300 €**

3. **Privatentnahmen 500 € an Kasse 500 €**

4. **EBK an Eigenkapital 20.000 €**

---

## ✅ Wenn du das verstanden hast:

**→ Du bist bereit!** Die Prüfung besteht aus genau diesen Elementen.

**Nächster Schritt:** Schau dir die konkreten Fallstudien an:
- **Fallstudie 5 & 6:** Basis-Buchungen
- **Fallstudie 9:** Kompletter Durchlauf (OHNE Verkäufe!)
- **Fallstudie 10:** Abschreibungen

---

## 📌 Wichtige Eselsbrücken:

| Was?                     | Wo?   | Warum?                                    |
|--------------------------|-------|-------------------------------------------|
| **Wareneinkauf**         | Soll  | Aufwand (kostet Geld)                     |
| **Vorsteuer**            | Soll  | Forderung (kriegst du zurück)             |
| **Mietaufwand**          | Soll  | Aufwand                                   |
| **Zinsaufwand**          | Soll  | Aufwand                                   |
| **Privatentnahmen**      | Soll  | Wie Aufwand (Geld raus)                   |
| **Privateinlagen**       | Haben | Wie Ertrag (Geld rein)                    |
| **Kasse/Bank** (Abgang) | Haben | Wird weniger                              |
| **Kasse/Bank** (Zugang) | Soll  | Wird mehr                                 |
| **Eigenkapital (EBK)**   | Haben | Passivseite der Bilanz                    |
| **Verbindlichkeiten**    | Haben | Schulden = Passivseite                    |

---

## 🚀 Du schaffst das!

Wenn du diese Basics verstehst, ist der Rest nur Wiederholung. Konzentriere dich auf:
1. **Soll an Haben** richtig anwenden
2. **Vorsteuer** nie vergessen
3. **Abschlusskette** auswendig können

**Viel Erfolg bei deinem Zwischentest 2! 💪**
