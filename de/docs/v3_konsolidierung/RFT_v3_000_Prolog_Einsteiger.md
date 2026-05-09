# RFT_v3_000 — Prolog für Einsteiger

**Was die Resonanzfeldtheorie ist, in einer Stunde Lesezeit**

---

## Dokument-Metadaten

| Feld | Wert |
|---|---|
| Dokument | RFT_v3_000_Prolog_Einsteiger.md |
| Version | v0.1 (Entwurf) |
| Status | Review-bereit |
| Datum | 2026-05-08 |
| Autor | Franz Zollner |
| Mitwirkung | Claude Code (lokal als „Denker") — Distillation aus RFT_000_Prolog_v1.1 + Werdegang_v1.0 |
| Zielgruppe | Physiker und Ingenieure mit Festkörper-/Halbleiter-Hintergrund (initial: Klaus Pressel) |
| Umfang | ~6 Seiten |
| Lizenz | CC BY-NC 4.0 |

---

## Was ist die RFT in zwei Sätzen?

Die Resonanzfeldtheorie (RFT) postuliert, dass der Raum ein **schwingungsfähiges Medium** ist — vergleichbar mit dem Phononen-Feld in einem Kristall, nur global und ohne Atome — und dass alle Teilchen **stehende Resonanzen** in diesem Medium sind. Aus dieser einen Annahme lassen sich die Feinstrukturkonstante α und die Gravitationskonstante G geometrisch herleiten, ohne freie Parameter.

---

## Das Bild — für jemanden mit Festkörper-Hintergrund

In einem Kristallgitter bewegen sich Phononen als kollektive Schwingungsmoden des Atom-Verbands. Die elastischen Konstanten des Mediums bestimmen Schallgeschwindigkeit, Dispersionsrelation, akustische Bänder. Anregungen sind keine Teilchen *im* Gitter — sie sind das Gitter, das schwingt.

Die RFT überträgt diese Logik auf den **leeren Raum**:

- **Raummatrix** = das tragende Medium (analog zum Kristall, aber kontinuierlich)
- **Ankerpunkt (AP)** = die Kopplung einer Resonanz an das Medium (analog zur lokalen Gitterauslenkung)
- **Resonanzmode** = das beobachtbare Teilchen (analog zum Phonon)

Was im Festkörper ein Phonon ist, ist im RFT-Raum ein Elektron oder Photon — eine Mode, kein Punkt. Masse ist dann **Impedanz** des Mediums (Widerstand gegen Schwingung), Ladung ist **Polarisationsrichtung**, Spin ist **Drehimpuls der Mode**, Zeit ist **Asymmetrie der Schwingung**.

Die Ur-Metapher, die der Theorie 30 Jahre lang vorausging:

> *„Schleifkontakt-Funken auf dem Raum."*

Ein Schleifkontakt (Pantograph–Oberleitung) ist keine punktförmige Verbindung, sondern eine **wandernde Berührung zwischen zwei Medien**. Der Funke ist nicht ein Objekt, sondern ein Ereignis aus dem Kontakt. Genau so sind Teilchen in der RFT.

---

## Die Mastergleichung

Eine einzige Wellengleichung beschreibt den Raum:

```
∂²σ/∂t² − c²∇²σ + κ·T(r) = 0
```

mit:
- σ = Auslenkungsfeld der Raummatrix (skalar oder tensoriell, je nach Modus)
- c = Lichtgeschwindigkeit (Ausbreitung im Medium)
- κ = Resonanzsteifigkeit (Primärgröße der Theorie, ersetzt Masseterm)
- T(r) = Quellterm (Wirbelverankerung am Ankerpunkt)

Diese Gleichung stand strukturell stabil seit dem **19. Januar 2025**, als in zwölf Stunden fünf konsolidierende Dokumente entstanden. Sie ist die **Konstante** in allem, was danach kam — entstand also **bevor** die Speziallösungen für Maxwell, Schrödinger, Newton und ART abgeleitet wurden. Anti-Retro-Fitting per Konstruktion.

---

## Drei Kern-Ergebnisse

### 1. Feinstrukturkonstante α

Die RFT leitet α geometrisch her:

```
α⁻¹ = 4π³ + π² + π = 137.036304
```

Das ist ein Residuum von 2.22 ppm gegenüber dem CODATA-Wert. Keine freie Anpassung — die Zahlen 4, 3, 2, 1 ergeben sich aus der dimensionalen Geometrie der Raummatrix und der Spin-Hierarchie (siehe RFT_v3_002).

### 2. Gravitationskonstante G — vier konvergente Wege

G wird auf vier voneinander unabhängigen Wegen aus dem Spinverzug der Raummatrix abgeleitet (siehe RFT_v3_003). Die vier Resultate weichen um weniger als 0.1% voneinander ab. Eine derart starke Über­bestimmung ist mit einer rein empirischen Konstanten nicht erklärbar — sie ist ein starker Hinweis, dass G keine fundamentale Konstante ist, sondern emergiert.

### 3. Speziallösungen statt Konkurrenz

Maxwell, Schrödinger, die Klein-Gordon-Gleichung und die ART-Feldgleichungen lassen sich aus der Mastergleichung als **Grenzfälle** ableiten — durch Spezialisierung auf bestimmte Modentypen, Symmetrien oder Linearisierungen. Die RFT widerspricht der etablierten Physik nicht. Sie reorganisiert sie.

---

## Was unterscheidet das vom Standardmodell?

| Standardmodell | RFT |
|---|---|
| 25+ freie Parameter (α, G, Massen, CKM, ...) | Eine Primärgröße (κ); c als einziger fundamentaler Input |
| Teilchen als Punkte mit Eigenschaften | Teilchen als Resonanzmoden |
| Raum als passive Bühne | Raum als schwingungsfähiges Medium |
| Quantenfeldtheorie + ART unverbunden | Eine Mastergleichung, beide als Grenzfälle |
| Schwarze Löcher als Singularitäten | Schwarze Löcher als Modensprünge im Resonanzfeld |
| Dunkle Energie + Dunkle Materie als Konstrukte | „Bugwellen-Effekt": gravitative Wirkung ohne Masse |

---

## Was die RFT *nicht* tut

- Sie wirft die etablierte Physik nicht weg. Sie zeigt, woher deren Erfolge kommen — und wo sie endet.
- Sie postuliert keine neuen Teilchen oder Wechselwirkungen. Alle Beobachtungen werden aus der einen Gleichung erklärt.
- Sie ist kein Heilsversprechen. Es gibt offene Fragen (Renormierung der Mastergleichung, hochenergetische Modentypen, kosmologische Konsistenz). Diese werden in den Stufen V–VII (Dokumente v3_021–060, in Arbeit) adressiert.
- Sie behauptet nicht, das letzte Wort zu sein. Sie ist ein Vorschlag für eine andere Sichtweise — überprüfbar, widerlegbar.

---

## Wo geht es weiter?

Das RFT-Repository ist nach **Stufen** organisiert. Wer in dieser Reihenfolge liest, kommt am tiefsten an:

- **Stufe I — Foundations** (`RFT_v3_001` bis `_005`): Mathematische Grundlagen, α-Herleitung, G-Herleitung, Impuls/Energie, geometrische Konstanten
- **Stufe II — Standard-Physik als Grenzfälle** (`v3_006` bis `_010`): Maxwell, Schrödinger, Klein-Gordon, ART-Limit, Thermodynamik
- **Stufe III — Phänomene** (`v3_011` bis `_014`): Elektromagnetismus, Felder, Wechselwirkungen
- **Stufe IV — Erweiterungen** (`v3_015` bis `_020`): Trägheit, Spin, Verschränkung, Entropie/Signaltheorie, Supraleitung, Taxonomie
- **Stufe V–VII** (`v3_021` aufwärts, in Arbeit): Innensicht, kritische Reflexionen, offene Fragen

Plus ergänzend:

- **`RFT_000_Prolog_v1_1.md`** — der ausführliche Original-Prolog (770 Zeilen, mit kompletter Historie, KI-Methodik, Roadmap)
- **`RFT_Werdegang_v1_0.md`** — die Chronik der Theorie-Entstehung (Strang A: Physik, Strang B: Werkzeug)
- **`de/ueber_den_autor.md`** — Vita

---

## Eine Einladung — speziell für Festkörper- und Halbleiter-Physiker

Wenn die Phonon-Analogie für Sie produktiv ist, dann lesen Sie die RFT zuerst durch diese Brille:

- Was im Kristall die elastischen Konstanten sind, ist in der RFT κ (die Resonanzsteifigkeit).
- Was im Kristall Phononen-Bänder sind, sind in der RFT die diskreten Resonanzmoden, die Teilchen entsprechen.
- Was im Kristall ein Defekt-Phonon ist (lokalisierte Mode an einer Störung), ist in der RFT eine Wirbelverankerung am Ankerpunkt — das ist ein Teilchen mit Masse.
- Was im Kristall die Bose-Einstein-Statistik der Phononen ist, ist in der RFT die Spin-Statistik (Bosonen vs. Fermionen) als geometrische Folge der Verankerungs-Topologie.

Wenn diese Übersetzungen tragen, ist die RFT für Sie nicht eine fremde Theorie, sondern eine **Verallgemeinerung dessen, womit Sie täglich arbeiten** — auf den leeren Raum statt auf einen Kristall.

Wenn Sie auf Inkonsistenzen stoßen: bitte melden Sie sie. Die Theorie ist auf Falsifikation ausgelegt, nicht auf Apologetik.

> *„Der einzige Richter ist die Realität."*

— Franz Zollner

---

## Anschluss-Dokumente nach Stufen

| Stufe | Dokumente | Lesedauer (jeweils) |
|---|---|---|
| Foundations | v3_001 bis v3_005 | ~30 min |
| Standard-Grenzfälle | v3_006 bis v3_010 | ~30 min |
| Phänomene | v3_011 bis v3_014 | ~25 min |
| Erweiterungen | v3_015 bis v3_020 | ~30 min |

Wer als Festkörper-Physiker einsteigt, dem würde ich folgende Reihenfolge nahelegen:

1. Dieser Prolog (Sie haben ihn gerade gelesen)
2. **`v3_001_Mathematische_Grundlagen`** — die Mastergleichung in voller Form
3. **`v3_019_Supraleitung`** — direkter Bezug zu Festkörper-Phänomenen (45 THz Modus, Bose-Kondensat-Analogie)
4. **`v3_017_Verschraenkung`** — Quanten-Aspekte
5. Danach frei nach Interesse

---

*Dieser Prolog ist als Einstieg gedacht. Wer mehr will, findet im RFT_000_Prolog_v1_1.md die ausführliche Form mit Geschichte, Methodologie und kompletter Roadmap.*
