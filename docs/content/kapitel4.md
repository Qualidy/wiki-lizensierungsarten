# Kapitel 4 – Rechtliche Grundlagen

<div class="kurs-progress">
  <div class="step done"></div>
  <div class="step done"></div>
  <div class="step done"></div>
  <div class="step active"></div>
  <div class="step"></div>
</div>

<div class="lernziele" markdown>
<h3>Was du heute lernst</h3>

- Das Urheberrecht (UrhG) verstehen und auf Software anwenden
- Den Unterschied zwischen Urheberrecht und Markenrecht erklären
- Das Copyright-Symbol einordnen und internationale Unterschiede kennen
- Ein EULA lesen, verstehen und kritische Klauseln erkennen
</div>

---

## 4.1 Urheberrecht

Das **Urheberrecht** schützt **geistige Schöpfungen** – also das, was ein Mensch kreativ erschaffen hat. In Deutschland ist es im **Urheberrechtsgesetz (UrhG)** geregelt.

### Was schützt das Urheberrecht?

- Literarische Werke (Romane, Texte, Gedichte)
- Musik
- Bilder, Fotos, Grafiken
- **Software / Computerprogramme** (§ 69a UrhG)
- Datenbanken (§ 87a UrhG)

!!! info "Software ist automatisch geschützt"
    In Deutschland entsteht das Urheberrecht **automatisch** mit der Schöpfung. Es muss **nicht** beantragt oder eingetragen werden. Sobald du Code schreibst, bist du der Urheber – ohne jegliche Formalitäten.

### Wichtige Grundsätze

- Das Urheberrecht liegt immer beim **Schöpfer** (Entwickler, Autor, Künstler)
- Es ist **nicht übertragbar** – man kann nur Nutzungsrechte (Lizenzen) vergeben
- Das Urheberrecht gilt in Deutschland 70 Jahre nach dem Tod des Urhebers

### Urheberrecht bei Arbeitsaufträgen

!!! warning "Ausnahme: Angestelltenverhältnis"
    Wenn ein Arbeitnehmer im Rahmen seines Arbeitsverhältnisses Software entwickelt, gehen die **ausschließlichen Nutzungsrechte** automatisch auf den **Arbeitgeber** über (§ 69b UrhG). Das Urheberrecht selbst bleibt aber beim Entwickler.

---

## 4.2 Markenrecht

Das **Markenrecht** schützt **Zeichen**, die zur Unterscheidung von Waren und Dienstleistungen dienen. Es schützt also keine Werke, sondern **Identität und Herkunft**.

### Was ist eine Marke?

Eine Marke kann sein:
- Ein **Name** (z. B. „Microsoft", „Apple")
- Ein **Logo** (z. B. das Apple-Logo)
- Ein **Schriftzug** in besonderer Gestaltung
- Eine **Farbe** oder ein **Klang** (in Ausnahmefällen)

### Unterschied zum Urheberrecht

| | Urheberrecht | Markenrecht |
|---|---|---|
| Schützt | Werke (Texte, Code, Bilder) | Zeichen (Namen, Logos) |
| Entsteht | Automatisch | Durch Eintragung (oder Benutzung) |
| Läuft ab | 70 Jahre nach Tod | Verlängerbar (alle 10 Jahre) |
| Zweck | Schöpfer schützen | Kunden vor Verwechslung schützen |

### Relevanz im IT-Alltag

Wenn du eine App entwickelst und ihr einen Namen gibst, der einem eingetragenen Markennamen ähnelt, droht eine **Abmahnung** – unabhängig davon, ob du den Code selbst geschrieben hast.

---

## 4.3 Copyright

**Copyright** ist das internationale Pendant zum deutschen Urheberrecht. Das bekannte Symbol ist **©**.

Das © bedeutet: „Dieses Werk ist urheberrechtlich geschützt."

!!! info "Wichtig"
    In Deutschland ist das © **nicht notwendig**, um Schutz zu genießen – er entsteht automatisch. Das Symbol ist trotzdem üblich, weil es Nutzern signalisiert, dass der Urheber sein Recht beansprucht.

### USA vs. Deutschland

| | USA | Deutschland |
|---|---|---|
| System | Copyright | Urheberrecht (UrhG) |
| Entsteht | Automatisch (seit 1989) | Automatisch |
| Übertragbar | Ja (Copyright assignable) | Nein (nur Nutzungsrechte) |
| Schutzdauer | 70 Jahre nach Tod | 70 Jahre nach Tod |

Der größte Unterschied: In den USA kann das Copyright vollständig auf eine andere Person oder ein Unternehmen übertragen werden. In Deutschland ist das Urheberrecht **unübertragbar** – nur Nutzungsrechte können vergeben werden.

---

## 4.4 EULA – End User License Agreement

Ein **EULA** (End User License Agreement) ist der Lizenzvertrag, den du akzeptierst, wenn du Software installierst oder nutzt. Das Kleingedruckte, das die meisten ohne Lesen durchklicken.

!!! warning "Rechtliche Bindung"
    Ein EULA ist ein **rechtlich bindender Vertrag**. Was drin steht, gilt – auch wenn man ihn nicht gelesen hat. Allerdings sind sittenwidrige oder überraschende Klauseln in Deutschland oft unwirksam (AGB-Recht).

### Typische Inhalte eines EULAs

| Abschnitt | Inhalt |
|---|---|
| Lizenzumfang | Wie viele Geräte, welche Nutzungsart |
| Verbote | Reverse Engineering, Weitergabe, Vermietung |
| Datenerhebung | Welche Nutzerdaten werden gesammelt |
| Haftungsausschluss | Hersteller haftet nicht für Schäden durch die Software |
| Kündigung | Wann und wie die Lizenz endet |
| Geltendes Recht | Welches Recht (welches Land) gilt |

### Praxisbeispiel: Kritische EULA-Klauseln

**Klausel A:**  
*„The software may collect usage data to improve user experience."*

→ Bedeutet: Die Software sammelt Daten. Wichtig für DSGVO-Compliance im Unternehmen!

**Klausel B:**  
*„You may not install the software on more than one device at a time."*

→ Bedeutet: Auch wenn du zwei PCs hast, darf die Software nur auf einem gleichzeitig laufen.

**Klausel C:**  
*„This agreement is governed by the laws of the State of California."*

→ Bedeutet: Bei Rechtsstreitigkeiten gilt kalifornisches Recht – nicht deutsches.

---

## Aufgaben – Kapitel 4

{{ task(file="tasks/tag4_01.yaml") }}

{{ task(file="tasks/tag4_02.yaml") }}

{{ task(file="tasks/tag4_03.yaml") }}

{{ task(file="tasks/tag4_04.yaml") }}

{{ task(file="tasks/tag4_05.yaml") }}
