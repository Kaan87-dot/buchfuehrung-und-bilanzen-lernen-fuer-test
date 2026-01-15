# 📋 Schnellreferenz: Buchungssätze für den Test

## 🧠 Wie du dieses Cheatsheet nutzt (siehe LERNSTRATEGIE.md)

**NICHT SO:** ❌ Passiv durchlesen und hoffen, dass es hängen bleibt  
**SONDERN SO:** ✅ Aktives Recall:
1. Decke die Buchungssätze zu
2. Versuche sie aus dem Kopf aufzuschreiben
3. 10 Sekunden NICHTS tun
4. Dann vergleichen und Fehler markieren
5. Fehlerhafte nochmal aus dem Kopf üben

**💡 FEYNMAN:** Kannst du jeden Buchungssatz in einfachen Worten erklären?

---

## 🎯 Grundregel

```
SOLL an HABEN    Betrag
```

- **SOLL** (links): Wo kommt's hin? / Was wird mehr?
- **HABEN** (rechts): Wo kommt's her? / Was wird weniger?

---

## 📊 1. ERÖFFNUNG (EBK)

### Aktivkonten (Vermögen)
```
Kasse           an  EBK         X €
Bank            an  EBK         X €
Forderungen     an  EBK         X €
Maschinen       an  EBK         X €
```

### Passivkonten (Kapital)
```
EBK             an  Verbindlichkeiten    X €
EBK             an  Eigenkapital         X €
```

**Merke:** Aktiva = Soll, Passiva = Haben

---

## 🛒 2. EINKAUF

### Wareneinkauf (bar)
```
Wareneinkauf     X €    an  Kasse    (X + MwSt) €
Vorsteuer 19%  MwSt €
```

### Wareneinkauf (auf Ziel/Kredit)
```
Wareneinkauf     X €    an  Verbindlichkeiten    (X + MwSt) €
Vorsteuer 19%  MwSt €
```

### Wareneinkauf (per Bank)
```
Wareneinkauf     X €    an  Bank    (X + MwSt) €
Vorsteuer 19%  MwSt €
```

### Anlagenkauf (z.B. Maschine bar)
```
Maschinen        X €    an  Kasse    (X + MwSt) €
Vorsteuer 19%  MwSt €
```

**Wichtig:** Vorsteuer IMMER im Soll!

**🧠 RECALL:** Decke die Buchungssätze oben zu und schreibe sie aus dem Kopf auf!

---

## 💰 3. LAUFENDE KOSTEN

### Miete (Bank)
```
Mietaufwand     an  Bank        X €
```

### Zinsen (Bank)
```
Zinsaufwand     an  Bank        X €
```

### Löhne (Bank)
```
Löhne und Gehälter    an  Bank    X €
```

### Versicherung (Kasse)
```
Versicherungsaufwand    an  Kasse    X €
```

**Merke:** Alle Aufwände = Soll!

**⏸️ PAUSE:** 10 Sekunden nichts tun, dann weitermachen!

---

## 👤 4. PRIVATKONTEN

### Privatentnahme (aus Kasse)
```
Privatentnahmen    an  Kasse        X €
```

### Privatentnahme (von Bank)
```
Privatentnahmen    an  Bank         X €
```

### Privateinlage (bar)
```
Kasse              an  Privateinlagen    X €
```

### Privateinlage (Bank)
```
Bank               an  Privateinlagen    X €
```

**Merke:** Entnahmen = Soll (wie Aufwand), Einlagen = Haben (wie Ertrag)

**🔗 VERBINDUNG:** Warum sind Entnahmen wie Aufwände?  
→ Beide nehmen Geld aus dem Unternehmen  
→ Beide verringern das Eigenkapital

---

## 📉 5. ABSCHREIBUNG (AfA)

### Normale Abschreibung
```
Abschreibungen    an  Maschinen    X €
```

**Erklärung:**
- Abschreibungen = Aufwand (Soll)
- Maschinen = Wert sinkt (Haben)

**Berechnung:**
- **Linear:** Anschaffungswert / Nutzungsdauer
- Beispiel: 10.000 € / 5 Jahre = 2.000 € pro Jahr

---

## 🔄 6. ABSCHLUSSKETTE

### Schritt 1: Aufwands- und Ertragskonten auf GuV

**Aufwandskonten schließen:**
```
GuV    an    Wareneinkauf        (Saldo)
GuV    an    Mietaufwand         (Saldo)
GuV    an    Zinsaufwand         (Saldo)
GuV    an    Abschreibungen      (Saldo)
GuV    an    Löhne und Gehälter  (Saldo)
```

**Ertragskonten schließen:**
```
Umsatzerlöse    an    GuV    (Saldo)
```
⚠️ **NICHT IM TEST** (keine Verkäufe!)

### Schritt 2: GuV auf Eigenkapital

**Bei Gewinn (Haben > Soll):**
```
GuV    an    Eigenkapital    (Gewinn)
```

**Bei Verlust (Soll > Haben):**
```
Eigenkapital    an    GuV    (Verlust)
```

### Schritt 3: Privatkonten auf Eigenkapital

```
Eigenkapital    an    Privatentnahmen    (Saldo)
Privateinlagen  an    Eigenkapital       (Saldo)
```

### Schritt 4: Bestandskonten auf SBK

**Aktivkonten schließen:**
```
SBK    an    Kasse           (Saldo)
SBK    an    Bank            (Saldo)
SBK    an    Vorsteuer       (Saldo)
SBK    an    Maschinen       (Saldo)
```

**Passivkonten schließen:**
```
Verbindlichkeiten    an    SBK    (Saldo)
Eigenkapital         an    SBK    (Saldo)
```

---

## 📊 7. T-KONTEN SCHEMA

### Aktivkonto (z.B. Kasse, Bank)
```
         Konto
─────────────────────
Soll    |    Haben
─────────────────────
Anfang  |    Abgang
Zugang  |
─────────────────────
Summe   |    Summe
Saldo   |
```

### Passivkonto (z.B. Eigenkapital, Verbindlichkeiten)
```
         Konto
─────────────────────
Soll    |    Haben
─────────────────────
Abgang  |    Anfang
        |    Zugang
─────────────────────
Summe   |    Summe
        |    Saldo
```

### Aufwandskonto (z.B. Miete, Zinsen)
```
         Konto
─────────────────────
Soll    |    Haben
─────────────────────
Aufwand |    Abschl.
        |    an GuV
─────────────────────
Summe   |    Summe
```

### Ertragskonto (z.B. Umsatzerlöse)
```
         Konto
─────────────────────
Soll    |    Haben
─────────────────────
Abschl. |    Ertrag
an GuV  |
─────────────────────
Summe   |    Summe
```

---

## 🎯 PRÜFUNGSTIPPS

### Vorgehensweise in der Prüfung:

1. ✅ **Aufgabe lesen** - Was ist gegeben?
2. ✅ **EBK buchen** - Wenn Anfangsbestände gegeben sind
3. ✅ **Geschäftsvorfälle buchen** - Schritt für Schritt
4. ✅ **T-Konten aufstellen** - Übersichtlich!
5. ✅ **Salden bilden** - Soll - Haben (oder umgekehrt)
6. ✅ **GuV erstellen** - Aufwände und Erträge sammeln
7. ✅ **Gewinn/Verlust ermitteln** - Auf EK buchen
8. ✅ **SBK erstellen** - Alle Bestandskonten

### Häufige Fehler vermeiden:

❌ **Vorsteuer vergessen** bei Einkäufen  
✅ **Immer 19% draufrechnen** und im Soll buchen!

❌ **Falsche Seite bei Privatkonten**  
✅ **Entnahmen = Soll, Einlagen = Haben**

❌ **GuV falsch herum**  
✅ **Aufwände = Soll, Erträge = Haben**

❌ **EK-Abschluss vergessen**  
✅ **GuV + Privatkonten auf EK buchen!**

❌ **Aktiva/Passiva verwechselt**  
✅ **Aktiva = Vermögen (Soll), Passiva = Kapital (Haben)**

---

## 📚 Was du NICHT lernen musst:

- ❌ Theorie (HGB, GoB)
- ❌ Verkauf von Waren
- ❌ Verkauf von Anlagevermögen
- ❌ Fallstudien 1, 2, 3, 7, 8

---

## 🚀 Fokus auf:

- ✅ Fallstudie 5 & 6 (Grundlagen)
- ✅ Fallstudie 9 (ohne Verkäufe!)
- ✅ Fallstudie 10 (Abschreibung)

---

## 💡 Eselsbrücken

| Konto                | Seite | Eselsbrücke                        |
|----------------------|-------|------------------------------------|
| Wareneinkauf         | Soll  | "Aufwand kostet Geld"              |
| Vorsteuer            | Soll  | "Kriegen wir zurück = Forderung"   |
| Privatentnahmen      | Soll  | "Geld raus = wie Aufwand"          |
| Privateinlagen       | Haben | "Geld rein = wie Ertrag"           |
| Kasse/Bank Abgang    | Haben | "Wird weniger"                     |
| Kasse/Bank Zugang    | Soll  | "Wird mehr"                        |
| Alle Aufwände        | Soll  | "Kosten = Soll"                    |
| Eigenkapital Start   | Haben | "Rechte Seite der Bilanz = Haben"  |
| Abschreibungen       | Soll  | "Aufwand = Soll"                   |

---

## 🧠 Aktives Recall - Blanktest

**Bevor du zur Prüfung gehst, mach diesen Test:**

**Nimm ein leeres Blatt Papier und schreibe AUS DEM KOPF auf:**

1. Die 5 wichtigsten Buchungssätze
2. Die komplette Abschlusskette (mit Erklärung jedes Schritts)
3. Die T-Konten-Schemas (Aktiv, Passiv, Aufwand, Ertrag)
4. Alle Eselsbrücken

**Zeit:** 10 Minuten  
**Regel:** KEINE Hilfe!

**Dann:**
- Vergleiche mit diesem Cheatsheet
- Was fehlt? → Nochmal lernen!
- Was sitzt? → Perfekt! ✓

**⏸️ 10 SEKUNDEN PAUSE:** Dann mental wiederholen

---

## 💤 Vor dem Schlafen (jeden Abend)

**Mental Rehearsal (im Kopf durchgehen):**

1. Die Abschlusskette (T-Konten → GuV → EK → SBK)
2. Ein Wareneinkauf mit Vorsteuer
3. Die 3 häufigsten Fehler

**Warum?** Dein Gehirn konsolidiert im Schlaf! Bis zu 40% besseres Erinnern!

**🎯 Am Testtag Morgen:**
- NICHT intensiv lernen!
- Nur kurz dieses Cheatsheet durchblättern (5 Min)
- Mental die Abschlusskette durchgehen
- Dann entspannt zum Test! 💪

---

**Viel Erfolg! 💪🎓**
