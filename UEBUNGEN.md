# 📝 Übungsaufgaben: Fallstudien 5, 6, 9 & 10

## 🎯 Übung 1: Basis - Eröffnung und erste Buchungen

### Aufgabe:

Dein Unternehmen hat folgende Anfangsbestände zum 01.01.:

- Kasse: 8.000 €
- Bank: 25.000 €
- Maschinen: 15.000 €
- Verbindlichkeiten: 10.000 €
- Eigenkapital: 38.000 €

Im Januar passiert Folgendes:

1. Kauf von Waren für 3.000 € (netto) + 19% MwSt., Zahlung bar
2. Mietzahlung 1.200 € per Bank
3. Privatentnahme 500 € aus der Kasse
4. Kauf einer Maschine für 5.000 € (netto) + 19% MwSt., per Bank

**Aufgaben:**
a) Buche die Eröffnung (EBK)
b) Buche alle Geschäftsvorfälle
c) Stelle T-Konten auf und bilde die Salden

---

### Lösung:

#### a) Eröffnungsbuchungen:

```
1. Kasse              an  EBK         8.000 €
2. Bank               an  EBK        25.000 €
3. Maschinen          an  EBK        15.000 €
4. EBK                an  Verbindlichkeiten   10.000 €
5. EBK                an  Eigenkapital        38.000 €
```

**Kontrolle:** Soll-Seite EBK = 48.000 €, Haben-Seite EBK = 48.000 € ✓

#### b) Geschäftsvorfälle:

```
1. Wareneinkauf     3.000 €    an  Kasse      3.570 €
   Vorsteuer 19%      570 €

2. Mietaufwand                 an  Bank       1.200 €

3. Privatentnahmen             an  Kasse        500 €

4. Maschinen        5.000 €    an  Bank       5.950 €
   Vorsteuer 19%      950 €
```

#### c) T-Konten:

```
                  Kasse
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    EBK     8.000   |    Waren    3.570
                    |    Privat     500
    ─────────────────────────────
            8.000   |            4.070
    Saldo:  3.930   |
    ─────────────────────────────


                  Bank
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    EBK    25.000   |    Miete    1.200
                    |    Masch.   5.950
    ─────────────────────────────
           25.000   |            7.150
    Saldo: 17.850   |
    ─────────────────────────────


                Maschinen
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    EBK    15.000   |
    Bank    5.000   |
    ─────────────────────────────
    Saldo: 20.000   |
    ─────────────────────────────


              Vorsteuer 19%
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    Kasse     570   |
    Bank      950   |
    ─────────────────────────────
    Saldo:  1.520   |
    ─────────────────────────────


             Wareneinkauf
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    Kasse   3.000   |
    ─────────────────────────────
    Saldo:  3.000   |
    ─────────────────────────────


              Mietaufwand
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    Bank    1.200   |
    ─────────────────────────────
    Saldo:  1.200   |
    ─────────────────────────────


            Privatentnahmen
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    Kasse     500   |
    ─────────────────────────────
    Saldo:    500   |
    ─────────────────────────────


          Verbindlichkeiten
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
                    |    EBK   10.000
    ─────────────────────────────
                    |    Saldo 10.000
    ─────────────────────────────


            Eigenkapital
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
                    |    EBK   38.000
    ─────────────────────────────
                    |    Saldo 38.000
    ─────────────────────────────
```

---

## 🎯 Übung 2: Kompletter Abschluss

### Aufgabe:

Fortsetzung von Übung 1. Jetzt machen wir den Jahresabschluss!

**Aufgaben:**
a) Erstelle die GuV (Gewinn- und Verlustrechnung)
b) Buche den Gewinn/Verlust auf Eigenkapital
c) Buche die Privatkonten auf Eigenkapital
d) Erstelle die Schlussbilanz (SBK)

---

### Lösung:

#### a) GuV erstellen:

**Abschlussbuchungen der Aufwandskonten:**
```
GuV    an    Wareneinkauf     3.000 €
GuV    an    Mietaufwand      1.200 €
```

**GuV-Konto:**
```
                 GuV
    ─────────────────────────────
    Soll (Aufwand)  |  Haben (Ertrag)
    ─────────────────────────────
    Wareneinkauf 3.000  |  (keine Erträge)
    Mietaufwand  1.200  |
    ─────────────────────────────
    Summe:       4.200  |  Summe: 0
    ─────────────────────────────
                        |  Saldo (Verlust): 4.200
```

**Ergebnis:** Verlust von 4.200 € (weil keine Umsatzerlöse!)

#### b) Verlust auf Eigenkapital buchen:

```
Eigenkapital    an    GuV    4.200 €
```

**Eigenkapital nach GuV:**
```
            Eigenkapital
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    GuV     4.200   |    EBK   38.000
    ─────────────────────────────
            4.200   |           38.000
                    |    Saldo  33.800
    ─────────────────────────────
```

#### c) Privatkonten auf Eigenkapital buchen:

```
Eigenkapital    an    Privatentnahmen    500 €
```

(Keine Privateinlagen in dieser Aufgabe)

**Eigenkapital final:**
```
            Eigenkapital
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    GuV     4.200   |    EBK   38.000
    Privat    500   |
    ─────────────────────────────
            4.700   |           38.000
                    |    Saldo  33.300
    ─────────────────────────────
```

#### d) Schlussbilanz (SBK):

**Abschlussbuchungen:**
```
SBK    an    Kasse                3.930 €
SBK    an    Bank                17.850 €
SBK    an    Maschinen           20.000 €
SBK    an    Vorsteuer            1.520 €

Verbindlichkeiten    an    SBK   10.000 €
Eigenkapital         an    SBK   33.300 €
```

**Schlussbilanz in Kontenform:**
```
                Schlussbilanz zum 31.01.
    ───────────────────────────────────────────────
    Aktiva                  |    Passiva
    ───────────────────────────────────────────────
    Kasse           3.930   |    EK         33.300
    Bank           17.850   |    Verbind.   10.000
    Maschinen      20.000   |
    Vorsteuer       1.520   |
    ───────────────────────────────────────────────
    Summe:         43.300   |    Summe:     43.300
    ───────────────────────────────────────────────
```

**✓ Bilanz ist ausgeglichen!**

---

## 🎯 Übung 3: Abschreibung (AfA)

### Aufgabe:

Dein Unternehmen hat eine Maschine für 12.000 € (netto) gekauft.
Die Nutzungsdauer beträgt 6 Jahre.

**Aufgaben:**
a) Berechne die jährliche Abschreibung (linear)
b) Buche die Abschreibung für ein Jahr
c) Zeige das T-Konto "Maschinen" nach Abschreibung

---

### Lösung:

#### a) Berechnung:

```
Jährliche Abschreibung = Anschaffungswert / Nutzungsdauer
                       = 12.000 € / 6 Jahre
                       = 2.000 € pro Jahr
```

#### b) Buchungssatz:

```
Abschreibungen    an    Maschinen    2.000 €
```

**Erklärung:**
- Abschreibungen sind Aufwand → Soll
- Maschinen verlieren an Wert → Haben

#### c) T-Konto Maschinen:

**Vor Abschreibung:**
```
              Maschinen
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    Kauf   12.000   |
    ─────────────────────────────
    Saldo: 12.000   |
    ─────────────────────────────
```

**Nach Abschreibung:**
```
              Maschinen
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    Kauf   12.000   |    AfA    2.000
    ─────────────────────────────
           12.000   |            2.000
    Saldo: 10.000   |    (= Buchwert)
    ─────────────────────────────
```

**T-Konto Abschreibungen:**
```
            Abschreibungen
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
    Masch.  2.000   |
    ─────────────────────────────
    Saldo:  2.000   |
    ─────────────────────────────
```

**Wichtig:** In der GuV erscheinen die Abschreibungen als Aufwand!

```
GuV    an    Abschreibungen    2.000 €
```

---

## 🎯 Übung 4: Einkauf auf Ziel (Verbindlichkeiten)

### Aufgabe:

Du kaufst Waren für 2.000 € (netto) + 19% MwSt. **auf Ziel** (= auf Kredit, zahlbar in 30 Tagen).

**Aufgaben:**
a) Buche den Einkauf
b) Buche die spätere Zahlung per Bank
c) Zeige die T-Konten

---

### Lösung:

#### a) Einkauf auf Ziel:

```
Wareneinkauf     2.000 €    an    Verbindlichkeiten    2.380 €
Vorsteuer 19%      380 €
```

**Erklärung:** Kein Geld fließt sofort! Stattdessen entsteht eine Schuld (Verbindlichkeiten).

#### b) Spätere Zahlung:

```
Verbindlichkeiten    an    Bank    2.380 €
```

**Erklärung:** Schuld wird bezahlt, Bankkonto sinkt.

#### c) T-Konten:

**Nach Einkauf:**
```
            Wareneinkauf                    Vorsteuer 19%
    ─────────────────────────    ─────────────────────────
    S       |       H            S       |       H
    2.000   |                    380     |


          Verbindlichkeiten
    ─────────────────────────────
    Soll            |    Haben
    ─────────────────────────────
                    |    Eink.  2.380
    ─────────────────────────────
                    |    Saldo  2.380
    ─────────────────────────────
```

**Nach Zahlung:**
```
          Verbindlichkeiten                    Bank
    ─────────────────────────────    ─────────────────────────
    Soll            |    Haben       Soll      |    Haben
    ─────────────────────────────    ────────────────────────
    Bank    2.380   |    Eink. 2.380  (alt)   |    Verb. 2.380
    ─────────────────────────────    ────────────────────────
            2.380   |          2.380
    Saldo:      0   |
    ─────────────────────────────
```

---

## 🎯 Übung 5: Mix - Privatkonten und Einkauf

### Aufgabe:

1. Du legst 5.000 € privates Geld auf das Firmenkonto ein (Bank)
2. Du kaufst Waren für 1.500 € (netto) + 19% MwSt., Zahlung bar
3. Du entnimmst 800 € aus der Kasse für private Zwecke
4. Du zahlst 600 € Versicherung per Bank

**Aufgabe:** Buche alle Vorgänge!

---

### Lösung:

```
1. Bank                      an    Privateinlagen      5.000 €

2. Wareneinkauf    1.500 €   an    Kasse               1.785 €
   Vorsteuer 19%     285 €

3. Privatentnahmen           an    Kasse                 800 €

4. Versicherungsaufwand      an    Bank                  600 €
```

**Kontrollfrage:** Welche Konten gehen in die GuV?
- Wareneinkauf (Aufwand)
- Versicherungsaufwand (Aufwand)

**Welche Konten gehen auf Eigenkapital?**
- Privateinlagen (erhöht EK)
- Privatentnahmen (senkt EK)

---

## 🎓 Selbsttest: Kannst du das?

Versuche folgende Aufgabe **ohne Lösung** zu machen:

### Aufgabe:

Anfangsbestände:
- Kasse: 3.000 €
- Bank: 12.000 €
- Eigenkapital: 15.000 €

Geschäftsvorfälle:
1. Kauf Maschine 6.000 € netto + 19% MwSt., bar
2. Wareneinkauf 800 € netto + 19% MwSt., Bank
3. Miete 400 € per Bank
4. Privatentnahme 200 € Kasse
5. Abschreibung Maschine 1.200 € (für das Jahr)

**Mach den kompletten Abschluss:**
- EBK
- Buchungssätze
- T-Konten
- GuV
- Eigenkapital mit GuV und Privatkonten
- SBK

---

**Tipp:** Wenn du diese Aufgabe schaffst, bist du bereit für den Test! 💪

**Viel Erfolg!** 🚀
