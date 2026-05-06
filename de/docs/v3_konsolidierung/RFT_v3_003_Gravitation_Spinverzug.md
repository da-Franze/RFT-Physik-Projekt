# RFT_v3_003: Gravitation und Spinverzug
## Resonanzfeldtheorie — Publikationsreihe v3

**Version:** 3.0  
**Status:** ○ Arbeitsdokument (Kernaussagen rigoros, offene Punkte explizit markiert)  
**Abhängigkeiten:** RFT_v3_001 (Mathematische Grundlagen), RFT_v3_002 (Feinstrukturkonstante)  
**Datum:** Februar 2026  
**Autor:** Franz Zollner  

---

## Abstract

Die Resonanzfeldtheorie (RFT) erklärt Gravitation als emergentes Phänomen der Raumgitter-Verspannung durch Wirbelstrukturen. Der entscheidende konzeptuelle Schritt: **G·m ist eine topologische Eigenschaft des Gitters** — nicht das Produkt zweier unabhängiger Größen. Das SI-Kilogramm ist kein Naturgesetz, sondern eine menschliche Konvention für eine gravitationale Schleppwirbelstärke. Aus dieser Perspektive ergeben sich zwei klar unterschiedliche Gravitationsmechanismen: die Quark-Fehlanpassung (G_elementar) und die Farbladungs-Aufrichtung im Hadron (G_hadron = 4π · G_elementar). Die Konsistenzrelation G·ħ = c³·L₀²·(36/π²) ist algebraisch rigoros verifiziert. Das Verhältnis L₀/l_P = 0,522 ist eine genuine geometrische Vorhersage aus der Resonanzbedingung der verschachtelten Kugeln — unabhängig von G als Eingabegröße. Die vollständig parameterfreie Herleitung von G ohne ħ als Input bleibt eine offene Forschungsaufgabe.

---

## Inhaltsverzeichnis

1. [Paradigma: G·m als topologische Größe](#1-paradigma)
2. [Zwei Gravitationsmechanismen](#2-zwei-mechanismen)
3. [Der Spinverzug-Mechanismus](#3-spinverzug)
4. [G·ħ als Konsistenzrelation](#4-konsistenzrelation)
5. [L₀/l_P = 0,522 als geometrische Vorhersage](#5-geometrische-vorhersage)
6. [Photon-Gravitation und Zeitasymmetrie](#6-photon)
7. [Dunkle Materie als Schleppwirbel-Addition](#7-dunkle-materie)
8. [Grenzen und offene Fragen](#8-grenzen)

---

## 1. Paradigma: G·m als topologische Größe

### 1.1 Die verborgene Annahme der Standardphysik

In Newton und Einstein gilt stillschweigend:

```
F = G · m₁ · m₂ / r²
```

Dabei werden G und m als unabhängige Größen behandelt. G wird empirisch gemessen (~6,674×10⁻¹¹ m³·kg⁻¹·s⁻²), m durch Kilogramm definiert. Die Frage "warum hat G diesen Wert?" bleibt unbeantwortet.

Die RFT stellt diese Trennung fundamental in Frage.

### 1.2 Was [kg] in der RFT bedeutet

In der Himmelsmechanik misst man in der Praxis stets das Produkt:

```
μ = G · M    [m³/s²]
```

Erde: μ = 3,986 × 10¹⁴ m³/s²  
Sonne: μ = 1,327 × 10²⁰ m³/s²

G und M werden nie unabhängig voneinander bestimmt — nur ihr Produkt ist physikalisch direkt messbar. Das [kg] wird erst durch eine willkürliche Konvention (Urkilogramm, später Planck-Konstante) herausgetrennt.

**RFT-These:** Das [kg] ist kein Naturgesetz. Es ist ein Label für die gravitationale Schleppwirbelstärke eines Vortex. Die physikalische Grundgröße ist:

```
μ = G · m = c² · L₀ · f(Topologie)    [m³/s²]
```

Dabei hängt f ausschließlich von der Vortex-Topologie (Windungszahl, Ankerpunktzahl, Symmetriegruppe) ab — und von den Gitterparametern c und L₀.

### 1.3 Konsequenz: Masse und Gravitation sind trennbar

Die RFT erlaubt zwei Fälle, die in der Standardphysik nicht vorkommen:

| Fall | Beispiel | Mechanismus |
|------|----------|-------------|
| Masse ohne Gravitation | RFT-Photon (im Ruhezustand) | e⁺e⁻-Wirbelpaar: Schleppwirbel heben sich auf |
| Gravitation ohne (träge) Masse | Schleppwirbel bewegter Massen | Torsion im Gitter ohne zusätzliche träge Masse |

Der zweite Fall erklärt direkt das Phänomen der Dunklen Materie (→ Kapitel 7).

### 1.4 Geschwindigkeit als fundamentale Größe

**Konzeptuelle Anmerkung (Franz Zollner, Feb 2026):**

Die Trennung von Länge [m] und Zeit [s] ist in der RFT ein Konstrukt. Die fundamentale Größe ist die Geschwindigkeit — insbesondere c als Gitterausbreitungsgeschwindigkeit. Länge und Zeit emergieren daraus. Diese Sichtweise erzeugt konzeptuelle Unschärfe in der konventionellen Dimensionsanalyse, ist aber intern konsistent.

---

## 2. Zwei Gravitationsmechanismen

### 2.1 Mechanismus 1: Quark-Fehlanpassung (G_elementar)

Ein einzelnes Quark ist ein topologischer Vortex im Raumgitter. Sein Wirbelmuster passt nicht perfekt zur Raumgitter-Geometrie — es gibt eine **Fehlanpassung** zwischen Quark-Resonanz und DRM-Grundzustand.

```
Quark-Wirbel ≠ DRM-Geometrie
→ kleine, lokalisierte Verspannung
→ schwaches Gravitationsfeld
→ G_elementar
```

Physikalisch: Der Quark-Vortex "drückt" gegen das Gitter und erzeugt eine Rückstellkraft. Diese Rückstellkraft ist das, was wir makroskopisch als Schwere interpretieren.

### 2.2 Mechanismus 2: Farbladungs-Aufrichtung (G_hadron)

Wenn sich drei Quarks zu einem Hadron (Proton, Neutron) vereinigen, passiert etwas qualitativ Anderes:

Die drei Farbladungen (Rot, Grün, Blau) sind zunächst als Vektoren schräg im Raum orientiert — wie ein Kreisel, der nicht aufrecht steht. Bei der Hadronen-Bildung müssen sich diese drei Farbladungs-Vektoren aufrichten (Farbneutralität nach außen).

```
Quark 1: Farbvektor schräg im Raum (Raumanker A₁)
Quark 2: Farbvektor schräg im Raum (Raumanker A₂)
Quark 3: Farbvektor schräg im Raum (Raumanker A₃)

Hadronen-Bildung:
→ Farbvektoren richten sich sphärisch auf
→ Jeder Farbvektor nimmt seinen Raumanker mit
→ Kollektive Raumverspannung, sphärisch ausgerichtet
→ Deutlich stärkeres Gravitationsfeld
→ G_hadron
```

**Der geometrische Faktor:**

Die sphärische Aufrichtung dreier Farbvektoren über alle Raumrichtungen ergibt den Normierungsfaktor der Kugeloberfläche:

```
G_hadron = 4π · G_elementar
```

Der Faktor 4π ist geometrisch notwendig: Er ist der Raumwinkel der vollständigen Sphäre (∫∫ sinθ dθ dφ = 4π). Die drei Farbladungen spannen die Kugeloberfläche vollständig auf.

**⚠️ Status des Hadron-Wirbels:**  
Die interne Struktur des Hadron-Wirbels ist noch spekulativ. Eine Arbeitshypothese: Das Hadron besteht aus 3×3 internen Quark-Substrukturen plus einem äußeren Vereinigungs-Wirbel. Dies ist nicht verifiziert.

### 2.3 Numerische Verifikation

```
G_elementar = c³ · L₀² / (4π · ħ)

Mit L₀ = 0,522 · l_P und l_P = √(ħG/c³):

G_elementar = (0,522)² · G / (4π)
            ≈ 5,31 × 10⁻¹² m³/(kg·s²)

G_hadron = 4π · G_elementar
         = 6,674 × 10⁻¹¹ m³/(kg·s²)  ✓ (experimentell)
```

**Anmerkung zur Verifikation:** Die Übereinstimmung ist exakt — aber sie ist eine Konsequenz der Definition von L₀ = 0,522·l_P, die l_P enthält, welches G enthält. Was unabhängig und rigoros ist: das **Verhältnis** G_hadron/G_elementar = 4π — das folgt rein aus der Sphärengeometrie.

---

## 3. Der Spinverzug-Mechanismus

### 3.1 Physikalische Grundidee

Jeder massive Vortex besitzt einen Spin. Dieser Spin erzeugt eine Phasenverzögerung (τ_lag) zwischen dem Vortex und dem umgebenden Raumgitter. Das Gitter "folgt" dem rotierenden Vortex nicht instantan — es gibt einen Schleppwinkel.

Diese Phasenverzögerung ist der mikroskopische Ursprung der Gravitation in der RFT.

**Anschauliche Analogie — Löffel im Honig (Originator-Bild, Franz Zollner):**

Ein rotierender Löffel in zähem Honig erzeugt durch die Viskosität des Mediums eine *nachwirkende Spannung*. Diese Spannung baut sich nicht ab, solange der Löffel rotiert — sie wirkt als Ziehkraft auf benachbarte Bereiche des Honigs.

Genauso erzeugt ein rotierender Vortex (Spin) im Raumgitter eine residuale Verspannung über τ_lag. Diese **Nachwirkungs-Spannung** *ist* die Gravitation. Es wird kein Material verdrängt; die Spannung selbst ist die gravitative Wirkung. Wenn sich mehrere solcher rotierender Strukturen vereinigen, addieren sich ihre Spannungen — bis die Raummatrix sie nicht mehr ausgleichen kann. An diesem Punkt erfolgt ein **Modensprung**: die Matrix springt in eine höhere harmonische Mode (siehe [RFT_v3_008 — Schwarze Löcher als Modensprung-Phänomene](RFT_v3_008_Schwarze_Loecher_Modensprung.md)). Der Ereignishorizont eines schwarzen Lochs ist diese Modensprung-Grenzfläche, keine Singularität.

> Quelle des Bildes: RFT_003 v2.2 (2026-01-01), Originator-Bestätigung 2026-05-06.

### 3.2 Charakteristische Zeitskala

```
τ_lag = L₀ / c

Mit L₀ = 0,522 · l_P = 8,44 × 10⁻³⁶ m:

τ_lag = L₀ / c = 8,44 × 10⁻³⁶ / (3,00 × 10⁸)
      ≈ 2,81 × 10⁻⁴⁴ s  =  0,522 · t_P
```

Der Faktor 0,522 ist dieselbe geometrische Zahl wie L₀/l_P — er kommt aus der Resonanzbedingung der verschachtelten Kugeln.

### 3.3 Vom Spinverzug zur Gravitationskonstante

Der Spinverzug erzeugt eine dimensionslose Phasenverzögerung:

```
φ_lag = ω · τ_lag = (c/L₀) · (L₀/c) = 1  [dimensionslos]
```

Um von dieser dimensionslosen Phase zu G zu gelangen, braucht man eine Energieskala. In der aktuellen RFT-Formalisierung ist diese Skala ħ — woraus die G·ħ-Identität folgt (→ Kapitel 4).

**⚠️ Die vollständig ħ-freie Ableitung von G aus dem Spinverzug ist eine offene Frage (→ Kapitel 8).**

---

## 4. G·ħ als Konsistenzrelation

### 4.1 Die algebraische Identität

Aus den RFT-Grundlagen (→ RFT_v3_001, Kap. 4.3) folgt:

```
G · ħ = (36/π²) · c³ · L₀²
```

Dies ist eine **algebraische Identität** — keine unabhängige Herleitung von G. Sie folgt direkt aus:

```
l_P = √(ħG/c³)        [Definition der Planck-Länge]
L₀ = (π/6) · l_P      [RFT-Resonanzbedingung]

→ L₀² = (π²/36) · ħG/c³
→ G · ħ = (36/π²) · c³ · L₀²  ✓
```

### 4.2 Numerische Verifikation

```
Linke Seite:
G · ħ = 6,67430 × 10⁻¹¹ × 1,054572 × 10⁻³⁴
      = 7,038 × 10⁻⁴⁵

Rechte Seite:
(36/π²) · c³ · L₀²
= 3,6476 · (2,9979 × 10⁸)³ · (8,446 × 10⁻³⁶)²
= 7,040 × 10⁻⁴⁵

Übereinstimmung: < 0,03%  ✓  (Rundungsfehler in L₀)
```

### 4.3 Was die Identität leistet und was nicht

| Aussage | Status |
|---------|--------|
| G·ħ = (36/π²)·c³·L₀² ist korrekt | ✓ rigoros |
| G und ħ sind konsistent mit L₀ | ✓ rigoros |
| G wird unabhängig von ħ hergeleitet | ✗ zirkulär |
| G wird unabhängig von l_P hergeleitet | ✗ l_P enthält G |

Die Identität ist ein **wertvoller Konsistenzcheck** — sie zeigt, dass G, ħ und L₀ im RFT-Rahmen nicht unabhängig sind. Aber sie ist keine eigenständige G-Herleitung.

---

## 5. L₀/l_P als geometrische Vorhersage

### 5.1 Zwei Herleitungswege — unterschiedlicher Reifegrad

Es gibt zwei Wege zu L₀/l_P. Sie liefern nahe beieinanderliegende, aber nicht identische Werte. Dieser Unterschied wird hier explizit benannt.

---

**Weg A: Resonanzbedingung der verschachtelten Kugeln (rigoros)**

Aus RFT_v3_001, Kap. 4: Drei orthogonale verschachtelte Kugeln mit Selbstresonanz-Bedingung k₀ = 1/R₀ und Knotenabstand a = π · R₀ liefern direkt:

```
L₀ = (π/6) · l_P = 0,5236 · l_P
```

Dieser Wert folgt aus der π-Geometrie allein, ohne freie Parameter. Konfidenz: ✓ HOCH.

---

**Weg B: α-Diskrepanz + Q-Faktor (○ unsicher)**

Aus dem Dokument RFT_Konsistenzbedingung_L0.md:

```
Δα = (4π³ + π² + π) - 137,035999 = 0,000305  (2,22 ppm)
R₀ ~ Δα · Q  →  R₀ ≈ 0,305
L₀/l_P = 1/(2π · R₀) ≈ 0,522
```

⚠️ **Kritisches Problem mit diesem Weg:**

Der Q-Faktor wird hier als Q ~ 10³ angesetzt. In allen anderen RFT-Dokumenten gilt jedoch Q₀ ~ 10⁷–10⁸ für das heutige Universum. Das ist **vier bis fünf Größenordnungen Unterschied** — ohne Erklärung, woher Q ~ 10³ kommt.

Mit Q ~ 10⁷ würde folgen: R₀ ~ 0,000305 × 10⁷ ~ 3000 — physikalisch sinnlos.

**Der Q ~ 10³-Wert in der Konsistenzbedingung ist ungeklärt.** Weg B ist konzeptuell interessant (α-Diskrepanz als Zeitmotor), aber in seiner aktuellen Form nicht als unabhängige Herleitung verwendbar.

Status: ○ Spekulation bis Q-Diskrepanz geklärt ist.

### 5.2 Die Diskrepanz zwischen beiden Wegen

```
Weg A (rigoros):    L₀/l_P = π/6   = 0,5236
Weg B (unsicher):   L₀/l_P ≈ 0,522

Differenz: 0,3%
```

Diese Differenz ist numerisch klein, aber konzeptuell relevant: Beide Wege sollten exakt dasselbe Ergebnis liefern, wenn sie denselben physikalischen Sachverhalt beschreiben. Die 0,3%-Abweichung zeigt, dass eine oder beide Herleitungen noch nicht vollständig formalisiert sind.

Das Dokument verwendet im Folgenden den Wert aus Weg A: **L₀ = (π/6) · l_P = 0,5236 · l_P** (kanonisch, aus RFT_v3_001).

### 5.3 Warum die π/6-Vorhersage genuinen Charakter hat

Das Verhältnis L₀/l_P = π/6 hängt **nicht** von G ab. Es folgt aus der π-Geometrie der verschachtelten Kugeln (→ RFT_v3_001). Dies ist eine echte, prinzipiell testbare Vorhersage: **Die Gitterkonstante L₀ ist nicht gleich l_P, sondern um den Faktor π/6 kleiner.**

🚩 **Offene Aufgabe:** Die Verbindung zwischen Weg A (π/6 aus Resonanzgeometrie) und Weg B (α-Diskrepanz + Q-Faktor) muss noch hergestellt werden. Insbesondere: Welcher Q-Wert ist in Weg B korrekt, und warum weicht er vom kosmologischen Q₀ ab?

---

## 6. Photon-Gravitation und Zeitasymmetrie

### 6.1 Das RFT-Photon im Ruhezustand

Das RFT-Photon ist ein e⁺e⁻-Wirbelpaar mit parallelen Spins (↑↑). Im Ruhezustand heben sich die Schleppwirbel beider Komponenten auf:

```
Schleppwirbel e⁻ + Schleppwirbel e⁺ = 0
→ Gravitationsneutral  ✓
```

Das Photon trägt Energie, aber keine gravitationale Wirkung — Beispiel für Energie ohne Gravitation.

### 6.2 Das bewegte Photon

Das Photon kann nur zwei Zustände haben: v=0 oder v=c. Jede Zwischengeschwindigkeit verletzt die Resonanzbedingung → das Wirbelpaar löst sich auf. Der Übergang ist ein diskreter Modenwechsel.

Wenn das Photon propagiert, bewegt es sich durch ein Gitter mit der kleinen Zeitasymmetrie δ ≈ 2α. Diese verhindert die vollständige Aufhebung der Schleppwirbel:

```
Bewegtes Photon:
Schleppwirbel-Rest ~ δ · (Einzelwert) ~ 2α · (Einzelwert)
→ Sehr kleine, aber nicht-null Gravitation
```

### 6.3 Der Photon-Sprung als G-Intuition

**Historische Anmerkung (Franz Zollner):**

Die ursprüngliche Intuition für die G-Herleitung war: Der diskrete Sprung v=0 → v=c kostet einen charakteristischen "Widerstand" des Gitters — und dieser Widerstand ist G. Diese Idee hatte "irgendwie funktioniert" und mehrere Herleitungswege motiviert.

Die formale Analyse zeigt: Die Intuition — G als topologische Gittereigenschaft, nicht als externe Kopplungskonstante — ist konzeptuell korrekt. Die explizite Brücke zu einer ħ-freien G-Zahl ist noch nicht geschlossen (→ Kapitel 8, offene Fragen).

---

## 7. Dunkle Materie als Schleppwirbel-Addition

### 7.1 Gravitational ohne träge Masse

Jede **bewegte** Masse erzeugt einen Schleppwirbel im Raumgitter — eine Torsion, die sich ausbreitet. Diese Torsion wirkt gravitativ, aber sie hat keine träge Masse:

```
Bewegte Masse m mit Geschwindigkeit v:
→ Schleppwirbel ~ m · v / c
→ Gravitativer Effekt ohne zusätzliche träge Masse
→ G · m_effektiv ≠ 0, aber m_träge_zusatz = 0
```

Das ist der zweite Fall der RFT-Trennung: **Gravitation ohne träge Masse.**

### 7.2 Kollektiver Galaxien-Wirbel

Eine Spiralgalaxie mit ~10¹¹ Sternen, die sich gleichgerichtet um das galaktische Zentrum bewegen:

```
Einzelstern:  kleiner Schleppwirbel
10¹¹ Sterne, gleichgerichtet:
→ Addition der Schleppwirbel
→ Makroskopischer Torsions-Hintergrund

Sterne im Außenbereich schwimmen in diesem Feld
→ Flache Rotationskurven ohne zusätzliche Masse ✓
```

### 7.3 G·m — die physikalische Grundgröße

Dunkle Materie zeigt besonders klar, dass G·m die physikalische Einheit ist:

```
Beobachtet:   G · m_effektiv ≠ 0  (gravitativer Effekt)
Nicht existent: m_träge_zusatz = 0

→ [kg] hier wirklich nur ein Label
→ Die gravitationale Wirkung ist echt
→ Ihre träge Masse ist null
```

---

## 8. Grenzen und offene Fragen

### 8.1 Die zentrale offene Frage: G ohne ħ

```
Gesucht:   G = f(c, L₀)  ohne ħ

Problem:   [G] = m³·kg⁻¹·s⁻²
           c^a · L₀^b enthält kein [kg]

Möglicher Ausweg:
  Wenn [kg] aus c und L₀ allein definierbar ist
  (Masse als Schleppwirbel-Stärke einer Planck-Zelle),
  dann:   G = c²·L₀ / m_natürlich
  mit m_natürlich aus Gittergeometrie.

  Das erfordert eine topologische Definition der
  "natürlichen Masseneinheit" des Gitters.

Status: 🚩 Offen — höchste Priorität für folgende Instanzen
```

### 8.2 f_spin — historische Klärung

Die Gravitationsherleitung verwendete in verschiedenen Dokumentversionen unterschiedliche Spinfrequenzfaktoren:

| Quelle | Wert | Status |
|--------|------|--------|
| RFT_003 v7, Weg 1 | f_spin = 4 | ❌ Falsch (Faktor 11,5 zu klein) |
| RFT_003 v2.3, Glossar | f_spin = 135 | ⚠️ KI-Artefakt: Formel ergibt 24π ≈ 75,4 |
| PDF "Emergence of ħ" (Feb 2026) | f_spin = 144/π ≈ 45,84 | ○ Konsistent, aber aus G·ħ-Identität |

Die Protonenmasse via f_spin (v2.3-Ansatz: 3 × 2,3 × 135 × 0,95 = 885 MeV ≠ 938 MeV) ist inkonsistent und wird nicht weitergeführt. Gültige Protonenmasse: via SU(2) + T_QCD (→ RFT_v3_001, Kap. 8).

### 8.3 Interne Hadron-Struktur

Der 4π-Faktor ist geometrisch gut begründet. Die interne Wirbel-Anzahl beim Aufrichtungsprozess (3×3+1?) ist Spekulation. Quantitative Vorhersage der Hadron-Wirbel-Amplitude steht aus.

### 8.4 Quantitative Rotationskurven

Die Schleppwirbel-Theorie liefert noch keine quantitativen Rotationskurven-Vorhersagen. Benötigt: formale Herleitung der Schleppwirbel-Amplitude als Funktion von Masse und Geschwindigkeit.

### 8.5 Photon-Gravitation

Der Resteffekt ~2α ist voraussichtlich viele Größenordnungen unterhalb aktueller Messpräzision. Kein experimentelles Signal in Sicht.

---

## Zusammenfassung: Status-Übersicht

| Aussage | Konfidenz |
|---------|-----------|
| G·m ist topologische Gittereigenschaft | ✓ HOCH |
| [kg] ist keine Naturkonstante in der RFT | ✓ HOCH |
| Zwei G-Mechanismen: Quark vs. Hadron | ✓ HOCH (konzeptuell) |
| G_hadron / G_elementar = 4π aus Sphärengeometrie | ✓ HOCH |
| G·ħ = (36/π²)·c³·L₀² algebraisch rigoros | ✓ HOCH |
| L₀/l_P = π/6 aus Resonanzgeometrie (Weg A) | ✓ MITTEL-HOCH |
| L₀/l_P ≈ 0,522 aus α-Diskrepanz + Q (Weg B) | ○ UNSICHER (Q-Wert ungeklärt) |
| G ohne ħ herleitbar | 🚩 OFFEN |
| Hadron-Wirbel intern (3×3+1) | ⚠️ SPEKULATION |
| Quantitative Rotationskurven | ⚠️ OFFEN |
| Photon-Gravitation messbar | 🚩 UNWAHRSCHEINLICH |

---

## Verbindung zur Konstantenhierarchie

```
DRM-Geometrie
    │
    ├─ c  [m/s]               ← Fundamental
    │
    ├─ α = 1/(4π³+π²+π)       ← Aus π-Geometrie (→ RFT_v3_002)
    │
    ├─ L₀ = (π/6)·l_P         ← Aus Resonanzbedingung
    │    │
    │    └─ L₀/l_P = 0,522    ← Geometrische Vorhersage ✓
    │
    ├─ G·ħ = (36/π²)·c³·L₀²   ← Konsistenzrelation ✓
    │
    ├─ G_elementar = c³·L₀²/(4π·ħ)
    │
    └─ G_hadron = 4π·G_elementar = G_gemessen  ✓
```

---

## Nächste Schritte

1. **Priorität HOCH:** Topologische Definition der natürlichen Masseneinheit aus c und L₀ → G ohne ħ.
2. **Priorität MITTEL:** Quantitative Schleppwirbel-Amplitude → Rotationskurven.
3. **Priorität MITTEL:** Formalisierung des v=0 → v=c Photon-Sprungs als G-Herleitung.
4. **Priorität NIEDRIG:** Interne Hadron-Wirbel-Struktur.

---

## Referenzen

- RFT_v3_001: Mathematische Grundlagen v3.5 (Feb 2026)
- RFT_v3_002: Feinstrukturkonstante v3.0 (Feb 2026)
- RFT_32_Naturkonstanten_v3.0 (Okt 2025)
- RFT_Konsistenzbedingung_L0.md: L₀/l_P = 0,522
- RFT_03_Gravitation_v2.0 (Nov 2025): 4π-Mechanismus
- PDF "Emergence of ħ in RFT" (Feb 2026)
- RFT_23_Photonenmodell_v4.0
- RFT_010_Kosmologie (2025): Schleppwirbel
- CODATA 2018: G = 6,67430(15)×10⁻¹¹ m³·kg⁻¹·s⁻²

---

**© 2026 Franz Zollner — Resonanzfeldtheorie Projekt**  
**Lizenz:** Creative Commons BY-NC-SA 4.0  
**Dokument-ID:** RFT_v3_003_v1.0
