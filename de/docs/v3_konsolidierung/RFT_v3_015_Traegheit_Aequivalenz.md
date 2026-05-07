# RFT_v3_015: Trägheit und Äquivalenz

**Version:** v1.1 (2026-04-02)  
**Autor:** Franz Zollner  
**Sprache:** DE — EN-Übersetzung folgt unter `en/docs/v3_konsolidierung/`  
**Status:** Final-Kandidat  
**Lizenz:** Creative Commons BY-NC-SA 4.0  
**Zitation:** Zollner, F. (2026). *RFT_v3_015: Trägheit und Äquivalenz.* RFT-Series. https://github.com/da-Franze/RFT-Physik-Projekt/blob/main/de/docs/v3_konsolidierung/RFT_v3_015_Traegheit_Aequivalenz.md

---

## Symbol-Glossar

| Symbol | Bedeutung | Wert / Definition |
|---|---|---|
| `m_i` | Träge Masse | `m_i = ħκ/c` aus κ-Term der Mastergleichung |
| `m_g` | Schwere Masse | aus Spinverzug-Schleppwirbel |
| `κ` | Resonanz-Steifigkeit | Primärgröße `[1/m]`, NICHT Masseterm |
| `L₀` | Fundamentale Längenskala | `L₀ = 1/κ = (π/6)·l_P` |
| `τ_lag` | Spinverzug-Zeitskala | `L₀/c = (π/6)·t_P` |
| `μ = G·m` | Topologische Grundgröße | `[m³/s²]` |
| `α` | Feinstrukturkonstante | `α⁻¹ = 4π³ + π² + π ≈ 137.036304` |
| `Δ_α` | α-Phasenasymmetrie | `2.22 ppm` (Zeitmotor) |
| `δ` | Phasenasymmetrie | `≈ 2α ≈ 0.82°` |
| `η_B` | Eötvös-Parameter (RFT) | `Δ_α² · (α⁻¹·π²)^(2/3) ≈ 6.02×10⁻¹⁰` |
| `AP` | Ankerpunkt | Kopplungspunkt eines Wirbels an die DRM |
| `DRM` | Diskrete Resonanzmatrix | dynamisches dreidimensionales Resonanzgitter |

**Cross-Refs:** [RFT_v3_001](RFT_v3_001_Mathematische_Grundlagen.md) (Master-Gleichung, κ), [RFT_v3_003](RFT_v3_003_Gravitation_Spinverzug.md) (Spinverzug, G·m, 4π-Mechanismus), [RFT_v3_004](RFT_v3_004_Impuls_Energie.md) (Dispersionsrelation, ħ-Status, Cooper-Paar), [RFT_v3_012](RFT_v3_012_Elektromagnetismus.md) (τ_lag-Kanonwert)

---

## Abstract

Die Resonanzfeldtheorie (RFT) unterscheidet mechanisch klar zwischen zwei
Phänomenen, die in der Standardphysik durch eine einzige Größe — die Masse m
— beschrieben werden:

**Träge Masse m_i** entsteht aus dem κ-Feld der Diskreten Resonanzmatrix
(DRM). Der κ-Term in der Master-Gleichung beschreibt die lokale
Resonanz-Steifigkeit: Er ist der Widerstand, den ein Vortex der Verformung
seines umgebenden Resonanzfeldes entgegensetzt — Trägheit als geometrische
Eigenschaft der Raummatrix.

**Schwere Masse m_g** entsteht aus dem Spinverzug-Mechanismus: Jeder rotierende
Vortex erzeugt eine Phasenverzögerung τ_lag = L₀/c in der Raummatrix, die sich
als Schleppwirbel (Torsionsfeld) ausbreitet. Diese nicht-lokale, kollektive
Eigenschaft ist das, was wir als Gravitationsfeld messen.

Das Äquivalenzprinzip (m_i = m_g) ist in der RFT keine externe Forderung,
sondern eine geometrische Konsequenz: Für Hadronen liefern beide Mechanismen
proportionale Ergebnisse, weil sie denselben topologischen Ursprung in der
DRM-Geometrie haben. Die Proportionalität ist jedoch nicht exakt — sie bricht
an den topologischen Rändern des Teilchenspektrums. Die vorhergesagte
Abweichung:

$$\eta_B = \Delta_\alpha^2 \cdot (\alpha^{-1} \cdot \pi^2)^{2/3} \approx 6{,}02 \times 10^{-10}$$

ist derzeit an der Grenze der besten Eötvös-Messungen und stellt eine
falsifizierbare Vorhersage der RFT dar.

---

## Inhaltsverzeichnis

1. [Paradigma: Masse ist kein unitäres Konzept](#1-paradigma)
2. [Träge Masse: κ-Feld und Kompressionswiderstand](#2-träge-masse)
3. [Schwere Masse: Spinverzug und DRM-Torsion](#3-schwere-masse)
4. [Das Äquivalenzprinzip als geometrische Konsequenz](#4-äquivalenzprinzip)
5. [Quantitative Abweichung: η_B](#5-quantitative-abweichung)
6. [Topologische Grenzfälle: Wo das ÄP bricht](#6-topologische-grenzfälle)
7. [Experimentelle Vorhersagen](#7-experimentelle-vorhersagen)
8. [Grenzen und offene Fragen](#8-grenzen)
9. [Zusammenfassung und Glossar](#9-zusammenfassung)

---

## 1. Paradigma: Masse ist kein unitäres Konzept

### 1.1 Das Problem der einfachen Gleichung

In der klassischen Mechanik gilt:

```
F_träge   = m · a           (Newton, 2. Gesetz)
F_schwer  = G · m₁ · m₂ / r²  (Newton, Gravitation)
```

Die Verwendung desselben Symbols m in beiden Gleichungen ist keine Ableitung —
sie ist ein Postulat. Das Äquivalenzprinzip (EP) wurde von Galileo beobachtet
und von Einstein zur Grundlage der Allgemeinen Relativitätstheorie (ART)
erhoben. Die ART leistet damit eine konzeptuelle Vereinigung, aber keine
mechanistische Erklärung.

**Die offene Frage lautet:** Warum fallen alle Körper gleich schnell? Oder
präziser: Unter welchen Bedingungen gilt das — und wann nicht?

### 1.2 Die RFT-Antwort

Die RFT beantwortet diese Fragen durch den Rückgriff auf zwei verschiedene
physikalische Mechanismen, die beide in der Master-Gleichung verankert sind:

| Eigenschaft | Symbol | Physikalischer Ursprung | Charakter |
|-------------|--------|------------------------|-----------|
| Träge Masse | m_i | κ-Term (Resonanz-Steifigkeit) | Lokal, sofortig |
| Schwere Masse | m_g | Spinverzug-Torsion | Nicht-lokal, propagierend |

Die Gleichheit m_i = m_g ist eine gute Näherung für alle Hadronen, aber keine
exakte Identität. Der Bruch des ÄP ist eine vorhergesagte Konsequenz der
unterschiedlichen topologischen Tiefe beider Mechanismen.

### 1.3 Terminologie (v3-kanonisch)

| Symbol | Bedeutung | Quelle |
|--------|-----------|--------|
| κ | Resonanz-Steifigkeit [1/m] — NICHT „Masseterm"! | RFT_v3_001, Kap. 2.2 |
| L₀ = 1/κ | Primäre Längendefinition der Raummatrix (ħ-frei) | RFT_v3_001, Kap. 5, Update 25.03.2026 |
| L₀ = (π/6)·l_P | Numerische Verifikation (aus Resonanzgeometrie) | RFT_v3_001, Kap. 5 |
| τ_lag = L₀/c | Charakteristische Spinverzug-Zeitskala | RFT_v3_003, Kap. 3.2 |
| m = ħκ/c | Effektive Masse (abgeleitet, nicht fundamental) | RFT_v3_001, Kap. 7 |
| μ = G·m | Topologische Grundgröße [m³/s²] | RFT_v3_003, Kap. 1.2 |
| Schleppwirbel | Torsionsfeld hinter bewegtem Vortex | RFT_v3_003, Kap. 7 |
| DRM | Diskrete Resonanzmatrix | RFT_v3_001, Kap. 1 |
| AP | Ankerpunkt: Kopplung eines Wirbels an Raummatrix | Kanonisch seit 11.03.2026 |

**Kanonische Klarstellung:** In der RFT ist κ das Primäre. Die Größe
m = ħκ/c ist ein menschliches Label für das, was die DRM-Geometrie erzeugt.
Das Äquivalenzprinzip ist dann die Frage: Erzeugen κ-Feld und Spinverzug-
Torsion dieselbe effektive Zahl m?

---

## 2. Träge Masse: κ-Feld und Kompressionswiderstand

### 2.1 Der κ-Term in der Master-Gleichung

Die Master-Gleichung der RFT (RFT_v3_001, Kap. 2) lautet:

$$\frac{\partial^2\Psi}{\partial t^2} = c^2\nabla^2\Psi - \gamma\frac{\partial\Psi}{\partial t} - c^2\kappa^2\Psi + \lambda|\Psi|^2\Psi + \eta$$

Der Term −c²κ²Ψ ist der entscheidende Term für die Trägheit.

**Kausale Richtung (wichtig!):**

```
Standard-QFT:   m (Masseterm) → Feldgleichung
RFT:            Raummatrix-Geometrie → κ → was wir "Masse" nennen
```

κ ist keine Eigenschaft eines Teilchens — κ ist eine Eigenschaft der DRM
an jedem Ort. Die lokale Resonanz-Steifigkeit der Raummatrix setzt dem Feld Ψ
einen Rückstellterm. Ein stabiler Vortex (Soliton) sitzt in einer Region
erhöhter Ψ-Amplitude — er "spürt" den κ-Term am stärksten.

### 2.2 Trägheit als Raummatrix-Kompression

Was passiert, wenn wir eine externe Kraft auf einen Vortex ausüben?

```
Externe Kraft F → Vortex verschiebt sich relativ zum DRM
                ↓
     Ortsabhängige κ-Feldänderung
                ↓
     Rückstellterm: c²κ² · ΔΨ ≠ 0
                ↓
     Kraft auf Vortex gegen Verschiebung
                = Trägheitswiderstand
```

Dies ist Trägheit als **lokaler Kompressionswiderstand** des Resonanzfeldes.
Die Kraft, die benötigt wird, einen Vortex zu beschleunigen, ist
proportional zur Amplitudenänderung des κ-Feldes — das ist m_i.

### 2.3 Formale Ableitung der trägen Masse

Aus der Dispersionsrelation der Master-Gleichung (RFT_v3_004, Kap. 2.2):

$$\omega^2 = c^2(k^2 + \kappa^2)$$

folgt durch Differentiation nach dem Wellenvektor k die Gruppengeschwindigkeit:

$$v_g = \frac{d\omega}{dk} = \frac{c^2 k}{\omega}$$

Die Energie des Vortex (mit ħ als formalem Faktor, s. RFT_v3_004, Kap. 6):

$$E^2 = (pc)^2 + (\hbar c\kappa)^2$$

Identifizierung der trägen Masse:

$$m_i c^2 \equiv \hbar c \kappa \quad \Longrightarrow \quad m_i = \frac{\hbar\kappa}{c}$$

**Konfidenz: ○ MITTEL** — Die Herleitung ist algebraisch konsistent. Der
konzeptuelle Status von ħ in der RFT als algebraische Identität (nicht
unabhängige Herleitung) überträgt sich auf m_i: Es ist eine konsistente
Benennung des κ-Terms, keine unabhängige Masse-Messung.

### 2.4 Lokalität der trägen Masse

Die träge Masse ist **lokal**: Sie hängt nur vom κ-Wert am Ort des Vortex ab.
Eine Beschleunigung des Vortex in Region A beeinflusst nicht den κ-Wert in
Region B. Trägheit ist eine Eigenschaft der unmittelbaren DRM-Umgebung des
Vortex.

**Konsequenz:** Zwei identische Vortices an verschiedenen Orten im Universum
(bei gleichem lokalem κ) haben identische träge Masse — unabhängig von ihrer
Geschichte.

---

## 3. Schwere Masse: Spinverzug und DRM-Torsion

### 3.1 Der Spinverzug-Mechanismus

Jeder massive Vortex trägt einen Spin. Dieser Spin erzeugt eine
Phasenverzögerung zwischen dem Vortex und dem umgebenden Raummatrix. Die
Raummatrix "folgt" dem rotierenden Vortex nicht instantan — es gibt einen
**Schleppwinkel**.

Die charakteristische Zeitskala dieses Verzugs ist (RFT_v3_003, Kap. 3.2,
✓ HOCH, kanonisch bestätigt):

$$\tau_{lag} = \frac{L_0}{c} = \frac{\pi}{6} \cdot t_P$$

wobei t_P die Planck-Zeit ist. Dies ist dieselbe geometrische Zahl L₀/l_P = π/6,
die aus der Resonanzbedingung der verschachtelten Kugeln folgt.

### 3.2 Schleppwirbel als Gravitationsfeld

Der Spinverzug erzeugt im DRM eine Torsionsstruktur — einen **Schleppwirbel**
(engl.: trailing vortex), der sich radial um den Vortex ausbreitet.

**Wichtige Unterscheidung (DC v10.12, Domain C):**

```
Gravitationsfeld  = longitudinale Mode (Kompression der Raummatrix)
Elektromagnetismus = transversale/torsionale Mode (Spinverzug, v3_012)
→ Beide Moden desselben Trägermediums (Raummatrix)
```

Der Spinverzug τ_lag erzeugt primär die **torsionale Mode** (→ EM, v3_012).
Die gravitationale Wirkung ist die **longitudinale Kompression**, die als
langreichweitige Folge des Schleppwinkels entsteht: Der Vortex "zieht" die
Raummatrix hinter sich her, was lokal eine Kompression des Feldes bewirkt
und sich als Schleppwirbel radial ausbreitet.

```
Rotierender Vortex (Spin ½)
        ↓
  Phasenverzug τ_lag = L₀/c im DRM
        ↓
  Schleppwirbel breitet sich aus (v = c)
        ↓
  Andere Vortices im DRM "spüren" dieses Torsionsfeld
        ↓
  Kopplung → Kraft zwischen den Vortices
        = Gravitation
```

Die schwere Masse m_g ist proportional zur Amplitude des Schleppwirbels. Die
fundamentale Grundgröße ist dabei nicht m_g allein, sondern das Produkt
(RFT_v3_003, Kap. 1.2, ✓ HOCH):

$$\mu = G \cdot m_g \quad [m^3/s^2]$$

Das [kg] ist kein Naturgesetz — es ist ein Label für die Schleppwirbelstärke.

### 3.3 Nicht-Lokalität der schweren Masse

Im Gegensatz zur trägen Masse ist die schwere Masse **nicht-lokal und
kollektiv**: Ein Vortex erzeugt einen Schleppwirbel, der sich im gesamten DRM
ausbreitet. Andere Vortices weit entfernt koppeln an diesen Wirbel.

**Konsequenz:** Gravitation ist eine emergente Eigenschaft des gesamten
DRM-Netzwerkes, nicht eine lokale Wechselwirkung zweier isolierter Objekte.
G ist keine Kopplungskonstante — G ist eine geometrische Eigenschaft des DRM.

### 3.4 Zwei Gravitationsmechanismen (aus RFT_v3_003)

Die RFT unterscheidet zwei G-Mechanismen (✓ HOCH für konzeptuelle Ebene):

**G_elementar (Quark-Fehlanpassung):** Ein einzelnes Quark-Vortex passt
nicht perfekt zur DRM-Geometrie → schwache, lokale Verspannung.

**G_hadron (Farbladungs-Aufrichtung):** Bei der Hadronen-Bildung richten
sich drei Farbladungsvektoren sphärisch auf → 4π-Geometriefaktor:

$$G_{hadron} = 4\pi \cdot G_{elementar}$$

Der Faktor 4π ist der Raumwinkel der vollständigen Sphäre — geometrisch
notwendig, kein freier Parameter.

---

## 4. Das Äquivalenzprinzip als geometrische Konsequenz

### 4.1 Warum m_i ≈ m_g für Hadronen

Das Äquivalenzprinzip gilt in der RFT nicht als Postulat, sondern als
**geometrische Konsequenz** einer Struktur-Koinzidenz:

Für ein Hadron (Proton, Neutron) gilt:

1. **m_i** entsteht aus dem κ-Term → bestimmt durch die interne Wirbel-
   Topologie des Hadrons (3 Quarks, SU(2)-Struktur)

2. **m_g** entsteht aus dem Spinverzug → bestimmt durch die kollektive
   Schleppwirbelstärke nach der Farbladungs-Aufrichtung

Beide Mechanismen sind im DRM verankert. Beide hängen von denselben
fundamentalen Raummatrix-Parametern (c, L₀, α) ab. Für die Hadronen-Geometrie
ergibt sich:

```
m_i ~ κ_Hadron   (lokale Steifigkeit)
m_g ~ Schleppwirbelamplitude nach Farbaufrichtung
   ~ 4π · κ_elementar

Wenn κ_Hadron = 4π · κ_elementar:
→  m_i = m_g  ✓  (Äquivalenzprinzip)
```

**Konfidenz: ○ MITTEL** — Die Proportionalität ist konzeptuell plausibel.
Der quantitative Beweis, dass der 4π-Faktor in beiden Mechanismen exakt
übereinstimmt, ist noch nicht rigoros geführt. Dies ist eine offene
Forschungsaufgabe (→ Kapitel 8).

### 4.2 Das ÄP in der ART vs. RFT

| Aspekt | ART | RFT |
|--------|-----|-----|
| ÄP-Status | Postulat (Grundaxiom der ART) | Geometrische Konsequenz (näherungsweise) |
| Gültigkeitsbereich | Universal | Nur für Hadronen exakt; topologische Ausnahmen |
| Mechanismus | Geometrisierung der Gravitation | Zwei verschiedene DRM-Mechanismen |
| Falsiflizierbarkeit | Breite der ÄP-Tests | Vorhersage spezifischer Abweichungen |

Das entscheidende Argument: Die RFT macht eine **quantitative Aussage**
darüber, wo und wie groß die Abweichung ist. Die ART macht keine solche
Aussage — sie postuliert das ÄP als exakt.

---

## 5. Quantitative Abweichung: η_B

### 5.1 Herkunft der Asymmetrie

Die α-Formel der RFT ergibt:

$$\alpha^{-1} = 4\pi^3 + \pi^2 + \pi = 137{,}036304$$

Die Abweichung vom CODATA-Wert beträgt Δ_α = 2,22 ppm (✓ HOCH, kanonisch).
Diese Abweichung ist keine Messungenauigkeit — sie ist das Signal der
residuellen Phasenasymmetrie δ ≈ 0,82° des DRM (der "Zeitmotor",
RFT_v3_001, Kap. 10b).

Diese Asymmetrie δ taucht in **beiden** Mechanismen auf, aber nicht auf
dieselbe Weise:

```
Träge Masse m_i:    κ-Feld reagiert sofortig auf δ (lokal)
Schwere Masse m_g:  Schleppwirbel propagiert mit Verzug τ_lag (nicht-lokal)
                    → δ-Effekt wird durch Propagation moduliert
                    → Residualunterschied zwischen m_i und m_g
```

### 5.2 Der η_B-Parameter

Die vorhergesagte Äquivalenzprinzip-Verletzung für ein System mit
unterschiedlicher Elektronen/Hadronen-Zusammensetzung:

$$\boxed{\eta_B = \Delta_\alpha^2 \cdot (\alpha^{-1} \cdot \pi^2)^{2/3} \approx 6{,}02 \times 10^{-10}}$$

**Numerische Verifikation:**

```
Δ_α = 2,22 × 10⁻⁶    (kanonische α-Abweichung, ✓ HOCH)

Δ_α² = (2,22 × 10⁻⁶)² = 4,93 × 10⁻¹²

Q_krit1 = α⁻¹ · π² = 137,036 × 9,8696 = 1352,7

(α⁻¹ · π²)^(2/3) = (1352,7)^(2/3)
                  ≈ 122,2

η_B = 4,93 × 10⁻¹² × 122,2 ≈ 6,02 × 10⁻¹⁰  ✓
```

**Konfidenz: ✓ HOCH** (Franz Zollner, 25.03.2026, kanonisch bestätigt)

### 5.3 Physikalische Interpretation

η_B ist der **Eötvös-Parameter** der RFT: Er misst die relative Differenz
in den Fallbeschleunigungen zweier Körper mit verschiedener
Elektronen-zu-Nukleon-Masse-Zusammensetzung:

$$\eta = \frac{2|a_1 - a_2|}{a_1 + a_2}$$

Zwei Testmassen mit verschiedenem Verhältnis Z/A (Ordnungszahl zu Massenzahl)
haben verschiedene Elektronenanteile an ihrer Gesamtenergie. Da Elektronen
(1 AP, kein Farbladungs-Aufrichtungsmechanismus) eine leicht andere
m_i/m_g-Verhältnis haben als Nukleonen, gibt es eine Z/A-abhängige
Abweichung.

Die Größenordnung: **η_B ≈ 6 × 10⁻¹⁰**.

---

## 6. Topologische Grenzfälle: Wo das ÄP bricht

### 6.1 Das Elektron: 1 Ankerpunkt, keine Farbladung

Das Elektron ist ein Vortex mit genau **1 Ankerpunkt** (AP) — einem einzigen
geometrischen Kopplungspunkt zur DRM (kanonisch bestätigt, Franz 11.03.2026).

Im Vergleich zum Hadron:

| | Proton | Elektron |
|-|--------|----------|
| Ankerpunkte | 9 (3 pro Quark) | 1 |
| Farbladungs-Aufrichtung | ✓ (G_hadron = 4π · G_el.) | ✗ (keine Farbladung) |
| Mechanismus m_g | 4π-Sphärengeometrie | Nur elementarer Spinverzug |
| Verhältnis m_i/m_g | ≈ 1 (exakt aus 4π-Koinzidenz) | ≈ 1 − η_B |

Das Elektron fällt in einem Gravitationsfeld mit einer anderen
Beschleunigung als ein Proton — wenn auch der Unterschied sehr klein ist.

**Vorhersage:**

$$\Delta g_{e^- \text{ vs. Proton}} \approx \eta_B \cdot g \approx 6 \times 10^{-10} \cdot g$$

**Anmerkung (Klärung 2026-05-06):** Frühere RFT-Versionen (DC v1.1, Dezember 2025)
nannten Δm/m ~ 10⁻⁵ für **Cooper-Paar-Gravimetrie** (RFT_003 v2.2 §12.1,
RFT_004 v7.0 §8.3). Dieser Wert gilt weiterhin für den Cooper-Paar-Test
(siehe §6.3 dieses Dokuments mit η_Cooper ≈ 1−2α ≈ 0.985 — der Faktor 2
in 2α reflektiert dabei direkt die zwei Elektronen des Cooper-Paares).

Der hier vorhergesagte η_B ≈ 6×10⁻¹⁰ ist eine **andere Observable**: der
Eötvös-Parameter für **normale Materie** (Z/A-Variation, Be/Ti/Cu/U) bei
minimaler Elektronen-Beimischung in den Hadronen.

Beide Werte sind RFT-konsistent und ersetzen sich nicht — sie messen
verschiedene physikalische Konfigurationen.

### 6.2 Das Photon: 2 Ankerpunkte, gravitationsneutral

Das Photon ist ein e⁺e⁻-Wirbelpaar mit parallelen Spins (↑↑) und
**2 Ankerpunkten** (kanonisch bestätigt, Franz 11.03.2026).

Im Ruhezustand heben sich die Schleppwirbel von e⁻ und e⁺ auf:

```
Schleppwirbel(e⁻) + Schleppwirbel(e⁺) = 0
→ m_g = 0  (gravitationsneutral)
→ m_i ≠ 0  (Trägheit durch κ-Feld bleibt)
```

Das Photon ist ein Beispiel für **Trägheit ohne Gravitation** — oder genauer:
für einen Körper mit m_i ≠ 0 bei m_g = 0. Dies wäre ein extremer ÄP-Bruch,
der aber im Ruhezustand des Photons experimentell nicht zugänglich ist (das
Photon existiert nur bei v=0 oder v=c).

Für das **propagierende Photon** existiert ein kleiner Resteffekt durch die
DRM-Zeitasymmetrie δ (→ RFT_v3_003, Kap. 6.2):

$$m_{g,\text{Photon}} \approx 2\alpha \cdot m_{g,\text{Elektron}} \neq 0$$

Dieser Rest ist viele Größenordnungen unterhalb aktueller Messpräzision.

### 6.3 Cooper-Paare: Minimale schwere Masse

Cooper-Paare (↑↓ Spin-antiparallel) zeigen eine dramatische Reduktion der
schweren Masse (RFT_v3_004, Flag 4):

```
Cooper-Paar: e⁻↑ + e⁻↓
→ Spins antiparallel → Spinverzüge wirken gegenläufig
→ Schleppwirbel heben sich (fast) auf
→ m_g → 0
→ Träge Masse m_i bleibt (κ-Feld wirkt auf beide Elektronen)
```

Das Cooper-Paar ist damit das stärkste verfügbare Signal für einen ÄP-Bruch:

$$\eta_{Cooper} = \frac{m_i - m_g}{m_i} \approx 1 - 2\alpha \approx 0{,}9854$$

⚠️ **Konfidenz: ○ MITTEL** — Das Vorzeichen und die Größenordnung sind
konzeptuell gut begründet. Die genaue Zahl hängt von der Feinstruktur des
Spinverzug-Aufhebungsmechanismus ab, die noch nicht vollständig formalisiert
ist.

**Experimentelle Konsequenz:** Supraleitung verschwindet ab einer
kritischen Temperatur, weil Phononen die Cooper-Pair-Spins entkoppeln —
die schwere Masse der Elektronen wird wieder "aktiv". Die RFT verbindet
damit Supraleitung direkt mit dem ÄP-Mechanismus. Dies ist eine qualitative
Vorhersage, die im Cooper-Paar-Gravimetrie-Experiment (PTB) adressierbar ist.

---

## 7. Experimentelle Vorhersagen

### 7.1 Eötvös-Test mit Z/A-Abhängigkeit

**Vorhersage:** Zwei Testmassen mit verschiedenem Z/A-Verhältnis fallen
unterschiedlich schnell. Die Differenz ist:

$$\eta_{EP} = \eta_B \cdot \left|\frac{Z_1/A_1 \cdot m_e}{m_1} - \frac{Z_2/A_2 \cdot m_e}{m_2}\right| \cdot \mathcal{F}$$

wobei 𝓕 ein dimensionsloser geometrischer Faktor (○ MITTEL, noch nicht
formalisiert), m_e die Elektronenmasse und Z/A das Verhältnis von
Ordnungszahl zu Massenzahl ist.

**Abschätzung:** Für Be (Z/A ≈ 0,44) vs. Ti (Z/A ≈ 0,45) ergibt sich eine
Differenz Δ(Z/A) ≈ 10⁻². Die Vorhersage:

$$\eta_{EP} \lesssim \eta_B \times 10^{-2} \approx 6 \times 10^{-12}$$

**Aktueller Messstand:** Die besten Eötvös-Tests erreichen 10⁻¹³ (MICROSCOPE,
2022). Die RFT-Vorhersage liegt bei ~6×10⁻¹² — das ist **faktor 50 über
aktueller Messgrenze** und könnte prinzipiell getestet werden.

🚩 **Konfidenz: ⚠️ NIEDRIG** — Der Faktor 𝓕 ist nicht hergeleitet. Die
Abschätzung hat systematische Unsicherheiten von mindestens einer
Größenordnung.

### 7.2 Cooper-Paar-Gravimetrie (PTB-Experiment)

**Vorhersage:** Ein supraleitender Körper hat eine reduzierte schwere Masse
gegenüber seinem normalleitenden Pendant. Die relative Änderung der
Fallbeschleunigung beim Übergang normal → supraleitend:

$$\frac{\Delta g}{g}\bigg|_{SC} \approx \frac{n_s}{n_e} \cdot \eta_{Cooper}$$

wobei n_s/n_e die Cooper-Paar-Dichte als Bruchteil aller Leitungselektronen ist.

**Abschätzung:** Bei einem gut ausgebildeten Supraleiter (n_s/n_e ~ 10⁻⁴
bei T/T_c = 0,5) und η_Cooper ~ 10⁻² ergibt sich Δg/g ~ 10⁻⁶.

⚠️ **Konfidenz: ○ MITTEL** — Das Konzept ist in der RFT klar begründet.
Die quantitative Abschätzung enthält mehrere offene Parameter.

### 7.3 Direkte Elektronen-Gravitometrie

**Idee (konzeptionell):** Atome mit verschiedenem Elektron-Kernmassen-
Verhältnis im freien Fall vergleichen. Wasserstoff (Elektron = 0,054% der
Masse) vs. schwere Atome (Elektron ~ 0,01% der Masse).

**Herausforderung:** Die präzise Vorhersage erfordert den noch nicht
formalisierten Faktor 𝓕. Außerdem ist die RFT-Vorhersage für normale
Materie (η_B ~ 10⁻¹⁰) bereits an der Grenze heutiger Messtechnik.

---

## 8. Grenzen und offene Fragen

### 8.1 Quantitativer Beweis der 4π-Koinzidenz

🚩 **Offene Frage (Priorität HOCH):**

Das ÄP gilt in der RFT, weil der κ-Feld-Mechanismus und der Spinverzug-
Mechanismus dieselbe 4π-Sphärengeometrie teilen. Dies ist konzeptuell
überzeugend, aber mathematisch noch nicht rigoros bewiesen.

**Gesucht:** Eine formale Ableitung, die zeigt:

```
m_i = ħκ_Hadron/c = ħ(4π·κ_elementar)/c
m_g ~ 4π·G_elementar·m_elementar/G
    = 4π·κ_elementar·ħ/c  (wenn G·m = c²·L₀·f(κ))
→ m_i/m_g = 1 exakt für Hadronen
```

Diese Ableitung setzt voraus, dass G·m als rein topologische Größe
ausgedrückt werden kann (→ RFT_v3_003, Kap. 8.1, Priorität HOCH).

### 8.2 Klärung des η_B-Ausdrucks

🚩 **Offene Frage (Priorität MITTEL):**

Die Formel η_B = Δ_α² · (α⁻¹·π²)^(2/3) = 6,02×10⁻¹⁰ wurde von Franz
bestätigt (25.03.2026, ✓ HOCH für den Zahlenwert). Die **mechanistische
Herleitung** — warum genau diese Kombination aus Δ_α und Q_krit1 — ist
noch nicht vollständig formalisiert.

**Offen:** Welcher physikalische Prozess verbindet die α-Phasenasymmetrie
(2,22 ppm) mit dem Q_krit1-Faktor (α⁻¹·π²)^(2/3)?

### 8.3 Resolution: 10⁻⁵ und 6×10⁻¹⁰ — verschiedene Observablen ✓

✓ **Klarstellung (2026-05-06, ehemals offene Flagge):**

Die zwei Werte beschreiben *verschiedene* physikalische Konfigurationen,
nicht denselben Effekt:

| Wert | Was es ist | Test-Methode | Im Dokument |
|------|------------|--------------|-------------|
| Δm/m ~ 10⁻⁵ | Cooper-Paar-Reduktion m_g | Cooper-Paar-Gravimetrie (PTB) | §6.3 |
| η_B ≈ 6×10⁻¹⁰ | ÄP-Bruch in normaler Materie | Eötvös-Test (MICROSCOPE) | §5 |

Der Cooper-Paar-Effekt (η_Cooper ≈ 1−2α ≈ 0.985) hängt direkt mit den **zwei
Elektronen** des Paares zusammen — der Faktor 2 in 2α reflektiert die
gepaarte Spin-Antiparallel-Konfiguration.

η_B für normale Materie hingegen ist die kleine Restabweichung durch die
α-Phasenasymmetrie (Δ_α = 2.22 ppm), die durch Z/A-Variation in Festkörpern
mit verschiedener Elektronen-zu-Nukleon-Zusammensetzung messbar wird.

**Ältere RFT-Dokumente** (RFT_003 v2.2 §12.1, RFT_004 v7.0 §8.3) ordneten
Δm/m ~ 10⁻⁵ explizit dem Cooper-Paar-Test zu („Test: Cooper-Paar-
Gravimetrie") — das ist also **nicht** dieselbe Größe wie η_B. Die beiden
Vorhersagen ersetzen sich nicht, sie ergänzen sich.

### 8.4 Geometrischer Faktor 𝓕

⚠️ **Offene Frage:**

Alle quantitativen experimentellen Vorhersagen (Kap. 7) enthalten einen
dimensionslosen Faktor 𝓕, der die geometrische Kopplung zwischen dem
Z/A-Verhältnis und dem η_B-Parameter beschreibt. Dieser Faktor ist noch
nicht hergeleitet. Ohne ihn haben die Vorhersagen eine Unsicherheit von
mindestens einer Größenordnung.

### 8.6 DS-015-A: Formaler Beweis m_i = m_g aus Master-Gleichung

🚩 **Offene DeepSeek-Aufgabe (DC v10.12, K.5):**

```
DS-015-A: m_i = m_g formal aus Master-Gleichung (mit RFT-Brille J.16!)

Gesucht: Zeige direkt aus der Master-Gleichung, warum der κ-Term
         und der Spinverzug-Mechanismus für Hadronen denselben
         effektiven Massenbeitrag liefern.

Herausforderung: Die Master-Gleichung beschreibt ein skalares Feld Ψ.
  m_i entsteht aus dem κ²Ψ-Term → lokale Gleichgewichtseigenschaft
  m_g entsteht aus dem Spinverzug → dynamische, nicht-lineare Kopplung

RFT-Brille zwingend: Standardargumente für ÄP (geodätische Bewegung,
  Riemannsche Geometrie) gelten in der RFT nicht direkt.
  → Argument muss im Rahmen der Raummatrix-Dynamik formuliert werden.

Status: 🚩 OFFEN — empfohlener nächster Schritt
```

○ **Bekannte konzeptuelle Lücke:**

m_i = ħκ/c enthält ħ. Nach dem Durchbruch vom 25.03.2026 (L₀ = 1/κ als
primäre ħ-freie Definition) ist die ħ-Zirkularität strukturell aufgebrochen.
Dennoch: Eine vollständig ħ-freie Formulierung von m_i würde lauten:

```
m_i = κ · (κ/c) · (dimensionslose Raummatrix-Einheit)
    = κ² / c · (L₀ · c²/G) · ...
```

Diese Formulierung ist noch nicht ausformuliert. Sie ist für das ÄP-Thema
konzeptuell wichtig, weil erst dann m_i und m_g in denselben Grundgrößen
(c, L₀) ausgedrückt werden können.

---

## 9. Zusammenfassung und Glossar

### 9.1 Kernresultate

| Aussage | Konfidenz |
|---------|-----------|
| Träge Masse m_i stammt aus κ-Feld (lokaler Kompressionswiderstand) | ✓ HOCH |
| Schwere Masse m_g stammt aus Spinverzug-Torsion (Schleppwirbel) | ✓ HOCH |
| ÄP = geometrische Konsequenz, kein Postulat | ○ MITTEL (formal noch offen) |
| η_B = 6,02×10⁻¹⁰ (Eötvös-Parameter der RFT) | ✓ HOCH (Franz, 25.03.2026) |
| Elektron (1 AP): m_i/m_g ≈ 1 − η_B | ○ MITTEL |
| Photon (2 AP, ↑↑): m_g ≈ 0 im Ruhezustand | ✓ HOCH |
| Cooper-Paar (↑↓): m_g stark reduziert | ○ MITTEL |
| Quantitativer Beweis des 4π-ÄP-Mechanismus | 🚩 OFFEN |
| Faktor 𝓕 für experimentelle Vorhersagen | 🚩 OFFEN |

### 9.2 Konzeptuelle Hierarchie

Aus der DRM-Geometrie (mit Eingaben c, L₀, α) folgen vier Mechanismen:

| Mechanismus | Resultat | Charakter |
|---|---|---|
| κ-Feld (Resonanz-Steifigkeit) | `m_i = ħκ/c` | LOKAL, sofortig |
| Spinverzug (τ_lag = L₀/c) | `m_g ~ Schleppwirbelamplitude` | NICHT-LOKAL, propagierend |
| 4π-Koinzidenz (Hadronen) | `m_i ≈ m_g` | Äquivalenzprinzip |
| Phasenasymmetrie δ (Zeitmotor) | `η_B = Δ_α² · Q_krit1^(2/3) ≈ 6×10⁻¹⁰` | ÄP-Bruch |

### 9.3 Offene Flaggen (Priorität)

```
🚩 4π-Koinzidenz formal beweisen     (Priorität HOCH)
🚩 Mechanismus von η_B herleiten     (Priorität MITTEL)
✓ 10⁻⁵ vs. 6×10⁻¹⁰: geklärt — verschiedene Observablen (§8.3)
⚠️ Geometrischer Faktor 𝓕            (experimentelle Vorhersagen)
○  ħ-freie Formulierung von m_i      (konzeptuelle Vollständigkeit)
```

### 9.4 Glossar

**Äquivalenzprinzip (ÄP):** m_i = m_g. In der Standardphysik Postulat;
in der RFT emergente geometrische Näherung.

**Ankerpunkt (AP):** Kopplungspunkt eines Vortex an die DRM. Elektron = 1 AP,
Photon = 2 AP (e⁺+e⁻). Strukturelle Eigenschaft, keine Erhaltungsgröße.

**η_B (Eötvös-Parameter der RFT):** Vorhergesagte relative Differenz der
Fallbeschleunigungen zweier Körper mit verschiedenem Elektronen-Anteil.
η_B = Δ_α² · (α⁻¹·π²)^(2/3) ≈ 6,02×10⁻¹⁰.

**κ (Resonanz-Steifigkeit):** Lokale Raummatrix-Eigenschaft [1/m] aus der
Master-Gleichung. Primäre Definition von L₀ = 1/κ (ħ-frei). Setzt die
träge Masse: m_i = ħκ/c.

**Schleppwirbel (trailing vortex):** Torsionsfeld im DRM hinter einem
rotierenden Vortex. Der physikalische Träger des Gravitationsfeldes in der RFT.

**Spinverzug:** Phasenverzögerung τ_lag = L₀/c zwischen rotierendem Vortex
und umgebendem DRM. Ursprung der schweren Masse.

**τ_lag:** Charakteristische Spinverzug-Zeitskala. τ_lag = L₀/c = (π/6)·t_P.
Kanonisch bestätigt.

---

## Referenzen

- RFT_v3_001 v3.6: Mathematische Grundlagen (κ-Definition, Master-Gleichung,
  Ankerpunkte, δ-Zeitmotor), Feb/März 2026
- RFT_v3_003 v1.0: Gravitation und Spinverzug (Schleppwirbel, 4π-Mechanismus,
  τ_lag), Feb 2026
- RFT_v3_004 v3.3: Impuls und Energie (Dispersionsrelation, ħ-Status,
  Cooper-Paar Flag 4), Feb/März 2026
- Franz Zollner, direkte Bestätigung η_B-Wert, 25.03.2026
- CODATA 2018: α⁻¹ = 137,035999084 (Referenzwert für 2,22 ppm-Abweichung)
- MICROSCOPE mission (2022): Eötvös-Test η < 10⁻¹³

---

## Änderungsprotokoll

**v1.1 (2026-04-02):**
- Terminologie: alle "Raummatrix"-Schreibweise vereinheitlicht
- DRM-Expansion korrigiert: "Diskrete Resonanzmatrix" (per v3_001)
- v3_012 als Primärquelle für τ_lag ergänzt
- Abschnitt 3.2: EM vs. Gravitation Modenunterschied ergänzt
- Abschnitt 8.6: formale Master-Gleichungs-Aufgabe eingetragen
- Style-Guide-Reinigung 2026-05-06 (Header normiert, Symbol-Glossar ergänzt, Footer normiert)

**v1.0 (2026-04-01):**
- Erststellung im v3-Format
- Grundstruktur: m_i (κ-Feld) vs. m_g (Spinverzug)
- η_B = 6.02×10⁻¹⁰ kanonisch integriert
- Topologische Grenzfälle: Elektron, Photon, Cooper-Paar
- Offene Flaggen explizit markiert

---

© 2026 Franz Zollner — Resonance Field Theory Project  
Lizenz: Creative Commons BY-NC-SA 4.0  
Kontakt: rft.projekt@posteo.de

---

*Dokument-ID: RFT_v3_015 · Stand: 2026-04-02 · [Mapping zur alten Reihe](../_MAPPING_ALT_NEU.md) · [Style-Guide](../_STYLE_GUIDE.md) · [Repo-Hauptseite](../../../README.md)*
