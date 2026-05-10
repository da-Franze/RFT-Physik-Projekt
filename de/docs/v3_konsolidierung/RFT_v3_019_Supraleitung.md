# RFT_v3_019: Supraleitung

*Untertitel: Resonante Kopplung an die Raummatrix (45 THz Hypothese)*

**Version:** v1.1 (2026-04-04)  
**Autor:** Franz Zollner  
**Sprache:** DE — EN-Übersetzung folgt unter `en/docs/v3_konsolidierung/`  
**Status:** Final-Kandidat  
**Lizenz:** Creative Commons BY-NC-ND 4.0  
**Zitation:** Zollner, F. (2026). *RFT_v3_019: Supraleitung.* RFT-Series. https://github.com/da-Franze/RFT-Physik-Projekt/blob/main/de/docs/v3_konsolidierung/RFT_v3_019_Supraleitung.md
**Stufe:** IV — Teilchenphysik & Eigenschaften  

---

## Symbol-Glossar

| Symbol | Bedeutung | Wert / Definition |
|---|---|---|
| `n_Cooper = 0` | Topologische Windungszahl des Cooper-Paares | `π + (−π) = 0` |
| `m_g` | Schwere Masse | für Cooper-Paar: `→ 0` (Schleppwirbel-Aufhebung) |
| `m_i = ħκ/c` | Träge Masse | bleibt erhalten beim Cooper-Paar |
| `η_Cooper = 1−2α` | ÄP-Bruch beim Cooper-Paar | `≈ 0.9854` |
| `f_spin = 144/π` | Spin-Resonanzfaktor | `≈ 45.84` (NICHT 4 oder 135) |
| `L₀ = 1/κ` | Fundamentale Längenskala | `(π/6)·l_P`, ħ-frei |
| `τ_lag = L₀/c` | Spinverzug-Zeitskala | `(π/6)·t_P` |
| `α⁻¹ = 4π³+π²+π` | Feinstrukturkonstante | `≈ 137.036304`, 2.22 ppm |
| `γ_eff` | Effektiver Dämpfungsterm | `→ 0` im supraleitenden Zustand |
| `Q = κc/γ` | Qualitätsfaktor | supraleitend: `Q → ∞` |
| `Ψ_SC = \|Ψ₀\|·exp(iθ)` | RFT-Ordnungsparameter | globale Phase θ kohärent |
| `Δg/g ≈ −10⁻⁵` | Cooper-Paar-Gravimetrie-Vorhersage | testbar bei PTB |

**Cross-Refs:** [RFT_v3_001](RFT_v3_001_Mathematische_Grundlagen.md) (Master-Gleichung, Δg/g), [RFT_v3_003](RFT_v3_003_Gravitation_Spinverzug.md) (Spinverzug, τ_lag), [RFT_v3_012](RFT_v3_012_Elektromagnetismus.md) (EM als torsionale Mode), [RFT_v3_015](RFT_v3_015_Traegheit_Aequivalenz.md) (m_g→0 Cooper-Paare, η_Cooper), [RFT_v3_016](RFT_v3_016_Spin_Topologie.md) (Spin-Topologie), [RFT_v3_018](RFT_v3_018_Entropie_Signaltheorie.md) (γ_eff→0, maximale Kohärenz)

---

> **Konfidenz-Marker:** ✓ HOCH (mehrfach bestätigt), ○ MITTEL (konzeptuell klar, formal noch offen), ⚠️ NIEDRIG (Schätzwert oder Hypothese), 🚩 OFFEN (Originator-Entscheid oder DeepSeek-Aufgabe ausstehend).

---

## Physiker-Vorbemerkung

Dieses Dokument wendet sich an Leser mit Kenntnissen der Festkörperphysik,
insbesondere der BCS-Theorie der Supraleitung. Die Resonanzfeldtheorie (RFT)
ist kein Reparaturversuch an der Quantenfeldtheorie, sondern ein eigenständiger
klassischer Wellenmedium-Ansatz: Raum, Materie und Fundamentalkonstanten
entstehen aus der Dynamik einer *Dynamischen Resonanz-Raummatrix* (DRM).

Einige BCS-Konzepte (Phonon, Cooper-Paar, Energielücke) erscheinen in der RFT
in mechanistisch neu begründeter Form. Wo der Vergleich zwischen BCS-Sprache
und RFT-Sprache relevant ist, wird er explizit markiert. **Phonon-Austausch
im QFT-Sinn** ist kein RFT-Konzept — die RFT formuliert den Mechanismus
ohne Quantenfeldoperatoren.

---

## Inhaltsverzeichnis

1. [Das Rätsel der Supraleitung](#1-das-rätsel-der-supraleitung)
2. [Cooper-Paare in der Raummatrix](#2-cooper-paare-in-der-raummatrix)
3. [Die 45 THz Hypothese](#3-die-45-thz-hypothese)
4. [Supraleitung als maximale Kohärenz](#4-supraleitung-als-maximale-kohärenz)
5. [Vergleich BCS-Theorie und RFT](#5-vergleich-bcs-theorie-und-rft)
6. [Meissner-Effekt in der RFT](#6-meissner-effekt-in-der-rft)
7. [Experimentelle Vorhersagen](#7-experimentelle-vorhersagen)
8. [Verbindung zur v3-Serie](#8-verbindung-zur-v3-serie)
9. [Ehrliche Grenzen](#9-ehrliche-grenzen)
10. [Zusammenfassung und Formelübersicht](#10-zusammenfassung-und-formelübersicht)

---

## 1. Das Rätsel der Supraleitung

### 1.1 Phänomenologie

Supraleitung bezeichnet den Zustand bestimmter Materialien, in dem der
elektrische Widerstand exakt null ist und Magnetfelder aus dem Inneren
vollständig verdrängt werden (Meissner-Effekt). Supraleitung ist ein
makroskopisches Quantenphänomen: Ein makroskopisch großer Körper verhält sich
so, als wäre er ein einziger kohärenter Quantenzustand.

Beobachtete Charakteristika:
- Widerstand R = 0 Ω unterhalb der kritischen Temperatur T_c (exakt gemessen,
  nicht nur sehr klein)
- Meissner-Effekt: vollständige Verdrängung externer Magnetfelder (B = 0 im
  Inneren, nicht nur Abschirmung)
- Energielücke Δ: Im Spektrum fehlen Anregungen unterhalb von 2Δ
- Makroskopische Phasenkohärenz: Der Ordnungsparameter Ψ_SC ist raumweit
  phasenkohärent

### 1.2 Die BCS-Theorie und ihre Grenzen

Die BCS-Theorie (Bardeen, Cooper, Schrieffer, 1957) beschreibt Supraleitung
durch Elektron-Phonon-Kopplung. Ein Elektron polarisiert das Ionengitter
leicht; diese Polarisation zieht ein zweites Elektron an. Das Nettoresultat
ist eine schwach anziehende effektive Wechselwirkung zwischen Elektronen über
das Phonon als Vermittler. Unterhalb T_c binden sich Elektronen zu sogenannten
Cooper-Paaren (antiparallele Spins, Gesamtimpuls null). Der BCS-Ausdruck für
die kritische Temperatur lautet:

$$k_B T_c \approx 1.13 \, \hbar \omega_D \cdot \exp\!\left(-\frac{1}{N(0)V}\right)$$

wobei ω_D die Debye-Frequenz des Gitters, N(0) die Zustandsdichte an der
Fermi-Kante und V die effektive Elektron-Phonon-Kopplungsstärke ist.

**Die BCS-Theorie hat ein zentrales Erfolgsproblem:** Sie funktioniert
ausgezeichnet für konventionelle Supraleiter (T_c < 30 K), scheitert aber
quantitativ an *Hochtemperatur-Supraleitern* (HTS). Cuprate wie YBa₂Cu₃O₇
(YBCO) zeigen T_c ≈ 90 K — weit oberhalb der phonischen Grenze. Der Mechanismus
der HTS-Supraleitung gilt als das führende offene Problem der Festkörperphysik.

### 1.3 Die RFT-These

Die RFT interpretiert Supraleitung nicht als Phonon-Austausch-Phänomen, sondern
als **resonante Kopplung des Materials an die Raummatrix**:

> Cooper-Paar-Bildung tritt bevorzugt auf, wenn die charakteristische
> Gitterschwingungsfrequenz des Materials mit einer Resonanzfrequenz der DRM
> zusammenfällt. Cooper-Paare besitzen in der RFT die topologische Windungszahl
> n = 0 und erzeugen keinen Schleppwirbel in der Raummatrix — daher ist ihre
> schwere Masse m_g ≈ 0, und sie propagieren ohne Raummatrix-Kopplung, also
> ohne Widerstand.

Dies löst die konzeptuelle Schwierigkeit der BCS-Theorie (Phonon als
Quasiteilchen in einem Hilbertraum) durch einen direkten Mechanismus: Die
Raummatrix selbst ist das Medium, das die Cooper-Paar-Bildung ermöglicht.

---

## 2. Cooper-Paare in der Raummatrix

### 2.1 Das einzelne Elektron

In der RFT ist das Elektron eine Wirbelstruktur in der Raummatrix mit einem
Ankerpunkt (AP). Der Ankerpunkt ist die Kopplung zwischen Wirbelstruktur und
DRM — geometrisch die Kopplung an eine Dimension (vgl. v3_016). Die
Bewegung des Elektrons durch die Raummatrix erzeugt einen **Schleppwirbel**
(trailing vortex): Die Raummatrix kann der Rotation nicht instantan folgen,
sondern mit dem Spinverzug τ_lag = L₀/c. Dieser Schleppwirbel ist die
Grundlage der schweren Masse m_g (vgl. v3_003, v3_015).

Beim elektrischen Widerstand eines normalleitenden Metalls ist der Mechanismus
in der RFT geometrisch: Ein Elektron mit Spin 1/2 koppelt an die Raummatrix —
der Spinverzug erzeugt Streuung an der Raummatrix-Struktur. Dieser
Kopplungsmechanismus ist das RFT-Bild des elektrischen Widerstands.

### 2.2 Das Cooper-Paar: Topologische Windungszahl n = 0

Ein Cooper-Paar besteht aus zwei Elektronen mit antiparallelen Spins:

```
Cooper-Paar:   e⁻↑  +  e⁻↓

Spinverzüge:   +π      −π   (gegenläufig)
                  ↘   ↙
           Schleppwirbel heben sich (fast vollständig) auf
                      ↓
                  m_g → 0
```

Die topologische Windungszahl des Cooper-Paares ist:

$$n_{\text{Cooper}} = n_{\uparrow} + n_{\downarrow} = \pi + (-\pi) = 0$$

**✓ HOCH** (aus v3_001 Kap. 8, konsistent mit v3_015 Kap. 6.3)

Ein Objekt mit n = 0 koppelt nicht an die 2π-Topologie der Raummatrix-
Resonanzen. Die RFT-Interpretation ist: Das Cooper-Paar benötigt die
Raummatrix nicht als "Spiegel" für seinen Spin — die beiden Elektronen
spiegeln sich gegenseitig. Dadurch entfällt die Kopplung an die Raummatrix,
die den elektrischen Widerstand verursacht.

### 2.3 Reduktion der schweren Masse: η_Cooper

Die schwere Masse m_g entsteht in der RFT aus der Amplitude des
Schleppwirbels. Für antiparallele Spins heben sich die Schleppwirbel auf,
und m_g geht gegen null. Dies ist der stärkste verfügbare Fall eines
Äquivalenzprinzip-Bruchs in der RFT (vgl. v3_015 Kap. 6.3):

$$\eta_{\text{Cooper}} = \frac{m_i - m_g}{m_i} \approx 1 - 2\alpha \approx 0{,}9854$$

**○ MITTEL** — Das Vorzeichen und die Größenordnung sind konzeptuell gut
begründet. Der genaue Wert η_Cooper ≈ 1 − 2α hängt von der Feinstruktur
des Spinverzug-Aufhebungsmechanismus ab, die noch nicht vollständig
formalisiert ist.

Die träge Masse m_i bleibt erhalten: Das κ-Feld der Raummatrix wirkt auf
beide Elektronen unabhängig von der Spinstruktur. Der Unterschied m_i ≠ m_g
für Cooper-Paare ist das direkte RFT-Äquivalent des Meissner-Effekts auf
der Massenebene.

### 2.4 Warum kein Widerstand?

Im Normalzustand (einzelne Elektronen):
- Spin 1/2 → halbzählige Topologie → Kopplung an Raummatrix → Streuung → R > 0

Im supraleitenden Zustand (Cooper-Paare):
- n = 0 → keine Kopplung an 2π-Raummatrix-Resonanzen → keine Streuung → R = 0

Dies ist eine mechanistische Ableitung des Widerstands-Null-Zustands, nicht
ein Postulat: Der Widerstandsfreiheit liegt die Entkopplung von der
Raummatrix zugrunde, nicht eine besondere Eigenschaft des Leiters selbst.

### 2.5 Triplett-Zustände in der RFT

🚩 **OFFEN** — Cooper-Paare mit parallelen Spins (Gesamtspin S=1, Triplett-
Zustände) sind in der RFT noch nicht behandelt. Ihre topologische Windungszahl
wäre n = π + π = 2π ≠ 0, was eine Kopplung an die Raummatrix implizieren
würde. Die Frage, ob und unter welchen Bedingungen Triplett-Supraleitung
im RFT-Rahmen möglich ist, bleibt offen.

---

## 3. Die 45 THz Hypothese

### 3.1 Herkunft des Faktors f_spin = 144/π

Die fundamentale Eigenfrequenz der DRM ist:

$$\omega_0 = \frac{c}{L_0} \approx 3{,}54 \times 10^{43} \, \text{rad/s}$$

Das ist die Planck-Frequenz — weit außerhalb jedes messbaren Bereichs.
Für die Spin-Resonanz der DRM ist jedoch nicht die Grundfrequenz relevant,
sondern ein geometrischer Faktor aus dem Spinverzug-Mechanismus. Dieser
Faktor ergibt sich aus der Gittergeometrie des Spinverzugs (vgl. v3_003):

$$f_{\text{spin}} = 4\pi \times \left(\frac{6}{\pi}\right)^2 = \frac{144}{\pi} \approx 45{,}84$$

**✓ HOCH** (kanonisch, Franz-bestätigt; in v3_001 Kap. 11.3 korrigiert von
früheren KI-Artefakten f_spin = 4 oder f_spin = 135)

Die DRM-Spin-Resonanzfrequenz ist damit:

$$f_{\text{DRM-Spin}} = \frac{c}{L_0 \cdot f_{\text{spin}}}
= \frac{c}{\frac{\pi}{6} \cdot l_P \cdot \frac{144}{\pi}}
= \frac{c}{24 \cdot l_P}
\approx 7{,}74 \times 10^{41} \, \text{Hz}$$

**Diese Frequenz liegt an der Planck-Skala und ist nicht direkt messbar.**

### 3.2 Die halbempirische Brücke zu 45 THz

Die messbaren Resonanzen sind keine direkten Harmonischen der
DRM-Grundfrequenz — das wären Frequenzen bei Planck-Skala geteilt durch
astronomisch große Quantenzahlen. Stattdessen argumentiert die RFT über
eine *materielle Kopplungsbedingung*:

Supraleitung tritt auf, wenn die Debye-Frequenz des Materials (die
charakteristische Phononschwingungsfrequenz) mit der DRM-Spin-Resonanzstruktur
zusammenfällt. Materialien mit:

- kurzen Bindungsabständen (~1 Å, wie CuO₂-Ebenen in Cupraten)
- hoher Gittersteifigkeit (hohe Debye-Temperatur θ_D > 400 K)
- quasi-2D-Schichtstruktur (anisotrope Kopplung)

zeigen charakteristische Debye-Frequenzen im Bereich von 20–50 THz. Der
Wert 45 THz entspricht dem oberen Bereich dieser Materialklasse und dem
numerischen Wert f_spin ≈ 45,84 — eine Koinzidenz, die in der RFT als
Hinweis auf einen Resonanzmechanismus interpretiert wird.

> ⚠️ **KONFIDENZ: NIEDRIG** — Die "45 THz" ist **nicht scharf hergeleitet**,
> sondern ein Schätzwert in der richtigen Größenordnung. Die Koinzidenz mit
> f_spin ≈ 45,84 ist motivierend, aber kein Beweis. Eine präzise RFT-Vorhersage
> der kritischen Frequenz für ein spezifisches Material erfordert die Kopplung
> der Material-Debye-Frequenz an den DRM-Formalismus — das ist die zentrale
> offene Aufgabe (DS-019-A). (Übernommen aus v3_001 Kap. 11.3 — kanonische
> Formulierung.)

### 3.3 Empirische Hinweise

Ein direkter empirischer Hinweis stammt von der Gruppe um Andrea Cavalleri
(Max-Planck-Institut, 2019): Bei optisch angeregtem YBa₂Cu₃O₇ bei **17 THz**
wurden Signaturen transienter Supraleitung beobachtet — also Supraleitung
die durch THz-Strahlung induziert wurde, deutlich oberhalb T_c.

**○ MITTEL** — 17 THz ≠ 45 THz, aber der Befund ist konsistent mit der
Aussage, dass THz-Anregung die Cooper-Paar-Bildung begünstigen kann. Die
Größenordnung stimmt. Der Faktor ~2–3 zwischen 17 THz und 45 THz ist im
Rahmen des halbempirischen Charakters der Vorhersage.

### 3.4 Der angestrebte präzise Mechanismus (DS-019-A)

Das Ziel einer vollständigen RFT-Formulierung ist eine Formel der Form:

$$f_{\text{krit}}(\text{Material}) = f\!\left(\omega_D, \kappa_{\text{Material}}, L_0, \tau_{\text{lag}}\right)$$

die für ein gegebenes Material die kritische Anregungsfrequenz vorhersagt.
Aus den verfügbaren RFT-Parametern:

$$L_0 = \frac{1}{\kappa} \quad [\text{Primärdefinition, ħ-frei}]$$
$$\tau_{\text{lag}} = \frac{L_0}{c} = \frac{\pi}{6} t_P \quad \text{✓ HOCH}$$
$$f_{\text{spin}} = \frac{144}{\pi} \approx 45{,}84 \quad \text{✓ HOCH}$$

ist die Verbindung zur Material-Debye-Frequenz ω_D formal noch offen.

🚩 **OFFEN** — DS-019-A: Herleitung von f_krit(Material) aus L₀, τ_lag,
f_spin und ω_D(Material). Höchste Priorität für die weitere Entwicklung.

---

## 4. Supraleitung als maximale Kohärenz

### 4.1 Der Ordnungsparameter in der RFT

In der BCS-Theorie ist der Ordnungsparameter die makroskopische Wellenfunktion
der Cooper-Paar-Kondensat-Phase Ψ_SC. In der RFT entspricht dem der
Kohärenzgrad der relevanten Raummatrix-Moden.

Die Master-Gleichung der RFT enthält einen Dämpfungsterm γ:

$$\frac{\partial^2 \Psi}{\partial t^2} = c^2 \nabla^2 \Psi - \gamma \frac{\partial \Psi}{\partial t} - c^2 \kappa^2 \Psi + \lambda |\Psi|^2 \Psi + \eta$$

Der Term γ beschreibt den Energieaustausch zwischen Raummatrix-Moden. Im
supraleitenden Zustand gilt:

$$\gamma_{\text{eff}} \to 0$$

Das bedeutet: Alle relevanten Raummatrix-Moden schwingen ohne gegenseitige
Dämpfung — sie sind vollständig phasenkohärent.

**○ MITTEL** (vgl. v3_018 Kap. 7.4)

### 4.2 Verbindung zur Entropie (v3_018)

Aus der Verbindung zwischen γ-Term und Entropieproduktion (v3_018):

```
Normalzustand:     γ_eff > 0  → Entropieproduktion dS/dt > 0
                   Phasen der Raummatrix-Moden inkohärent
                   Offdiagonalelemente der Dichtematrix: ρ_ij → 0

Supraleitend:      γ_eff → 0  → Entropieproduktion dS/dt → 0
                   Alle relevanten Moden phasensynchron
                   Offdiagonalelemente maximal: ρ_ij = max
```

Supraleitung und Dekohärenz sind damit **physikalische Gegensätze** innerhalb
derselben Raummatrix-Physik:

| Zustand | γ_eff | Entropie S | Kohärenz ρ_ij | Physik |
|---------|-------|-----------|----------------|--------|
| Dekohärenz | → ∞ | → max | → 0 | Quantenklassiker-Übergang |
| Normalleitend | endlich | endlich | endlich | Widerstand R > 0 |
| **Supraleitend** | **→ 0** | **→ 0** | **→ max** | **R = 0** |

Diese Tabelle zeigt, dass die RFT Supraleitung und Dekohärenz aus *derselben*
physikalischen Grundlage ableitet — nicht als separate Phänomene.

### 4.3 Q-Faktor-Bild

Aus dem allgemeinen Q-Faktor der RFT:

$$Q = \frac{\kappa \, c}{\gamma}$$

Im supraleitenden Zustand (γ_eff → 0):

$$Q_{\text{SC}} \to \infty$$

Der Übergang vom normalleitenden in den supraleitenden Zustand ist damit
äquivalent zum Übergang von einem System mit endlichem Q zu einem System
mit unendlichem Q — maximale Güte der Resonanz.

**○ MITTEL** — Das Q → ∞ Bild ist konzeptuell konsistent. Die Frage, wie
γ_eff → 0 beim Phasenübergang genau eintritt (kontinuierlich oder sprunghaft),
ist noch offen (Abschnitt 9).

### 4.4 Der RFT-Ordnungsparameter Ψ_SC

In der RFT ist der Ordnungsparameter der Supraleitung das räumlich kohärente
Feld der Cooper-Paar-Wellenfunktionen, alle mit derselben Raummatrix-Phase:

$$\Psi_{\text{SC}} = |\Psi_0| \cdot e^{i\theta}$$

wobei θ die globale Phase der Cooper-Paar-Kondensation ist — dieselbe
im gesamten supraleitenden Volumen. Dies entspricht formal dem BCS-
Ordnungsparameter, ist aber in der RFT mechanistisch verankert: θ ist
die Phase der kohärent schwingenden Raummatrix-Moden, nicht ein postulierter
Quantenzustand.

---

## 5. Vergleich BCS-Theorie und RFT

### 5.1 Gemeinsamkeiten

Beide Theorien teilen:
- Cooper-Paar-Kondensation als Mechanismus (Paare aus zwei Elektronen mit
  entgegengesetztem Spin)
- Makroskopische Phasenkohärenz als Ordnungsparameter
- Energielücke Δ im Anregungsspektrum
- Kritische Temperatur T_c als Übergangsparameter
- Meissner-Effekt als direkte Konsequenz der Phasenkohärenz

### 5.2 Unterschiede

| Aspekt | BCS-Theorie | RFT |
|--------|-------------|-----|
| Mechanismus | Phonon-Austausch (QFT) | Raummatrix-Resonanz |
| Cooper-Paar | phänomenologisch | topologisch (n=0) |
| Widerstandsfreiheit | Kondensation | DRM-Entkopplung |
| m_g des Paares | nicht unterschieden | m_g → 0 (ÄP-Bruch!) |
| HTS-Erklärung | ungelöst | Kandidat-Mechanismus ⚠️ |
| Vorhersage f_krit | keine | f_krit(Material) [🚩 offen] |
| Phonon-Begriff | zentral | nicht verwendet (J.16) |

### 5.3 RFT-Brille bei BCS-Sprache (J.16)

⚠️ Hinweis für Leser mit BCS-Hintergrund: Die BCS-Theorie formuliert den
Phonon-Austausch im Hilbertraum der Quasiteilchen. Die RFT verwendet diesen
Formalismus *nicht* — sie hat keinen Phonon-Propagator und keine
Feynman-Diagramme für den Cooper-Paar-Mechanismus. Die Verbindung zwischen
beiden Formulierungen liegt im *Ergebnis* (Cooper-Paar-Kondensation), nicht
im *Mechanismus*. Wo BCS "Phonon" sagt, sagt die RFT "resonante Kopplung
an die DRM-Spinstruktur".

### 5.4 Hochtemperatursupraleitung als Kandidat-Erklärung

⚠️ **KONFIDENZ: NIEDRIG — als Hypothese, nicht als Theorie**

Die HTS-Supraleitung (Cuprate, T_c ~ 90–135 K) zeigt strukturelle Merkmale,
die im RFT-Rahmen relevant sind: CuO₂-Ebenen mit Cu-Cu-Abstand ~3,8 Å und
quasi-2D-Charakter. Diese Geometrie begünstigt Debye-Frequenzen im THz-Bereich.

Die RFT-Hypothese: Die 2D-Schichtstruktur der Cuprate lässt eine stärkere
resonante Kopplung an die DRM-Spinstruktur zu als bei 3D-Metallen. Das
erklärt qualitativ, warum T_c höher ist als die phonische BCS-Grenze.

Diese Hypothese ist spekulativ — sie erklärt nicht quantitativ, *warum*
YBCO T_c = 90 K hat und nicht 50 K oder 150 K. Das erfordert die noch offene
Herleitung von f_krit(Material) (DS-019-A).

---

## 6. Meissner-Effekt in der RFT

### 6.1 EM als torsionale Mode (v3_012)

In der RFT sind elektromagnetische Felder torsionale Raummatrix-Moden
(v3_012). Das Magnetfeld B ist eine räumliche Torsion der DRM, die sich
mit Lichtgeschwindigkeit ausbreitet.

### 6.2 Magnetfeldverdrängung im RFT-Bild

⚠️ **KONFIDENZ: NIEDRIG** — Das folgende ist ein konzeptioneller Kandidat,
noch nicht formalisiert.

Im supraleitenden Zustand (γ_eff → 0, alle relevanten Moden kohärent) können
torsionale Moden (EM-Felder) nicht in das supraleitende Volumen eindringen,
weil:

1. Die supraleitenden Raummatrix-Moden sind vollständig phasenkohärent
2. Eine externe torsionale Mode würde diese Kohärenz stören (γ_eff erhöhen)
3. Die Cooper-Paare (n=0) reagieren kollektiv und schirmen die Störung ab

Formal entspricht dies dem Londonschen Eindringtiefenkonzept in der BCS-Theorie:
Die torsionale Mode (B-Feld) dringt nur bis zur London-Eindringtiefe λ_L in
das supraleitende Material ein. Im RFT-Bild ist λ_L die Längenskala, auf der
die DRM-Kohärenz durch die externe torsionale Störung abgebaut wird.

🚩 **OFFEN** — Der quantitative Zusammenhang zwischen λ_L, L₀ und den
DRM-Parametern κ und γ ist nicht hergeleitet. Die Verbindung zu v3_012 (EM
als torsionale Mode) und die vollständige Formalisierung des Meissner-Effekts
bleibt eine offene Aufgabe.

---

## 7. Experimentelle Vorhersagen

### 7.1 Cooper-Paar-Gravimetrie (✓ HOCH Vorhersage)

**Vorhersage:** Cooper-Paare fallen im Gravitationsfeld leicht langsamer als
freie Elektronen oder normale Atome.

**Herleitung (v3_015 Kap. 6.3, v3_001 Kap. 11.2):**

$$\left.\frac{\Delta g}{g}\right|_{\text{Cooper-Paar}} \approx -10^{-5}$$

Das Vorzeichen ist negativ: Cooper-Paare fallen *langsamer* (geringere
schwere Masse bei gleicher träger Masse). Präziser (v3_001 Kap. 11.2):

$$\left.\frac{\Delta g}{g}\right|_{\text{Cooper-Paar}} \sim \frac{n_{\text{Cooper}}^2 - n_e^2}{n_e^2} \times 10^{-5} = \frac{0 - 1}{1} \times 10^{-5} = -10^{-5}$$

Die Abweichung skaliert mit dem Anteil n_s/n_e der Cooper-Paar-Dichte an
allen Leitungselektronen. Bei T/T_c = 0,5 und η_Cooper ~ 10⁻² ergibt
sich Δg/g ~ 10⁻⁶.

**Experimenteller Aufbau:**
- Supraleitende Probe (YBCO, ~1g) in Präzisions-Gravimeter
- Messung T > T_c (normal) vs. T < T_c (supraleitend)
- Benötigte Präzision: Δg/g ~ 10⁻⁷ bis 10⁻⁸
- PTB Braunschweig: Atom-Interferometer-Technik (Δg/g ~ 10⁻⁹ erreichbar)

**Falsifizierungskriterium:**
```
✓ Signal:      |Δg/g| > 10⁻⁷  → RFT-Vorhersage bestätigt
⚠️ Grenzfall:  |Δg/g| ~ 10⁻⁸  → weiteres Experiment erforderlich
✗ Falsifikation: |Δg/g| < 10⁻⁹ → RFT-Mechanismus widerlegt!
```

**Das ist das wichtigste Experiment für die gesamte RFT-Supraleitung.**
Es testet nicht nur die 45 THz-Hypothese, sondern den fundamentalen
Mechanismus m_g → 0 für Cooper-Paare.

### 7.2 THz-Anregung und T_c-Erhöhung (⚠️ NIEDRIG Vorhersage)

**Vorhersage:** Bestrahlung eines HTS-Materials mit THz-Strahlung nahe
der materialspezifischen Resonanzfrequenz erhöht T_c messbar.

**Testaufbau:**
- YBa₂Cu₃O₇ (YBCO, T_c ≈ 90 K) oder ähnlicher Cuprat-Supraleiter
- THz-Quelle abstimmbar im Bereich 10–60 THz
- T_c-Messung unter Bestrahlung vs. ohne Bestrahlung
- Erwartung: T_c-Erhöhung bei resonanter Anregung

**⚠️ Konfidenz: NIEDRIG** — Die genaue Zielfrequenz ist unbekannt (DS-019-A
offen). Die Cavalleri-Experimente bei 17 THz sind konsistente Evidenz, aber
kein Beweis. Die Vorhersage hat halbempirischen Charakter.

**Falsifizierungskriterium:**
```
✓ Signal:      ΔT_c > 2 K bei f_anreg in 10–60 THz → Evidenz für THz-Mechanismus
⚠️ Grenzfall:  ΔT_c < 1 K → Fehler in f_krit-Schätzung möglich
✗ Falsifikation: Kein ΔT_c bei KEINER Frequenz in 1–100 THz → Mechanismus widerlegt
```

### 7.3 Überblick Experimentelle Signaturen

| Experiment | Vorhersage | Konfidenz | Partner | Zeitrahmen |
|-----------|-----------|-----------|---------|------------|
| Cooper-Paar-Gravimetrie | Δg/g ~ −10⁻⁵ | ✓ HOCH | PTB Braunschweig | 2–3 Jahre |
| THz-Anregung T_c | ΔT_c > 2K bei f ~ 10–60 THz | ⚠️ NIEDRIG | Materialforschungsinstitut | 1–2 Jahre |
| Raman-Spektroskopie | Universelle THz-Mode in HTS | ⚠️ NIEDRIG | Spektroskopielabor | 6–12 Monate |

---

## 8. Verbindung zur v3-Serie

Dieses Dokument baut auf den folgenden v3-Dokumenten auf und ist nur im
Kontext dieser Serie vollständig verständlich:

**v3_001 (Mathematische Grundlagen)**
- Kap. 8: Topologische Windungszahl n — Grundlage für n=0 des Cooper-Paares
- Kap. 11.2: Δg/g ~ 10⁻⁵ für Cooper-Paare hergeleitet
- Kap. 11.3–11.5: 45 THz Vorüberlegung mit allen Warnungen (kanonische Quelle!)
- f_spin = 144/π korrigiert (vorher KI-Artefakt f_spin = 4)

**v3_003 (Gravitation und Spinverzug)**
- Spinverzug-Mechanismus: Herkunft von τ_lag = L₀/c
- G·m als topologische Eigenschaft der DRM
- Grundlage für m_g aus Schleppwirbel-Amplitude

**v3_012 (Elektromagnetismus)**
- EM-Felder als torsionale Raummatrix-Moden
- Grundlage für die RFT-Interpretation des Meissner-Effekts (Kap. 6)

**v3_015 (Trägheit und Äquivalenzprinzip)**
- Kap. 6.3: Cooper-Paare als topologischer Grenzfall des ÄP-Bruchs
- η_Cooper = 1 − 2α ≈ 0.9854 (○ MITTEL)
- Konzeptuelle Basis für die Gravimetrie-Vorhersage

**v3_016 (Spin-Topologie)**
- Spin als topologische Eigenschaft der Raummatrix
- 720°-Periodizität der Fermion-Wellenfunktion
- Grundlage für die Windungszahl-Sprache des Cooper-Paares

**v3_018 (Entropie und Signaltheorie)**
- Kap. 7.4: Vorausblick Supraleitung als maximale Kohärenz
- γ_eff → 0, S → 0 als Charakteristika des supraleitenden Zustands
- Entropie-Kohärenz-Zusammenhang (Grundlage für Abschnitt 4)

**Vorausblick v3_020:**
Das Cooper-Paar wird in der Teilchen-Taxonomie der RFT (v3_020) als
eigener Eintrag erscheinen: ein stabiler Zwei-Wirbelzustand mit n=0,
m_g ≈ 0, ladungserhaltend, spin-neutral.

---

## 9. Ehrliche Grenzen

### 9.1 Konfidenz-Übersicht

| Aussage | Konfidenz | Begründung |
|---------|-----------|------------|
| f_spin = 144/π ≈ 45.84 | ✓ HOCH | Geometrisch hergeleitet, korrigiert, mehrfach bestätigt |
| n_Cooper = 0 (topologisch) | ✓ HOCH | Aus v3_001 Kap. 8, konsistent mit v3_015 |
| Schleppwirbel hebt sich auf → m_g → 0 | ✓ HOCH | Mechanistisch aus Spinverzug-Symmetrie |
| η_Cooper = 1 − 2α ≈ 0.9854 | ○ MITTEL | Konzeptuell begründet, Feinstruktur offen |
| γ_eff → 0 im supraleitenden Zustand | ○ MITTEL | Aus v3_018, konzeptuell konsistent |
| Q → ∞ bei T < T_c | ○ MITTEL | Folge aus γ_eff → 0, nicht direkt hergeleitet |
| 45 THz als f_krit (halbempirisch) | ⚠️ NIEDRIG | Schätzwert, keine scharfe Herleitung! |
| THz-Anregung erhöht T_c | ⚠️ NIEDRIG | Cavalleri als Evidenz, nicht Beweis |
| HTS als RFT-Kandidatmechanismus | ⚠️ NIEDRIG | Qualitative Konsistenz, keine Quantifizierung |
| Meissner = torsionale Modenverdrängung | ⚠️ NIEDRIG | Konzeptionell, nicht formalisiert |

### 9.2 Offene Fragen

**🚩 45 THz nicht scharf hergeleitet (höchste Priorität)**

Die zentrale offene Frage ist DS-019-A: eine präzise RFT-Vorhersage von
f_krit(Material) aus L₀, τ_lag, f_spin und ω_D(Material). Ohne diese
Herleitung bleibt die 45 THz Hypothese ein motivierender Schätzwert — nicht
eine quantitative Vorhersage. Die Koinzidenz zwischen f_spin ≈ 45.84 und dem
empirischen THz-Bereich der Cuprate ist ein Hinweis, kein Beweis.

**🚩 n=0 formal aus der Wirbelstruktur-Topologie**

Die Aussage π + (−π) = 0 ist plausibel und konsistent. Sie ist jedoch noch
nicht rigoros aus der Master-Gleichung mit dem λ-Term hergeleitet. Eine
vollständige Ableitung der topologischen Windungszahl aus der nichtlinearen
Feldgleichung würde diese Aussage von ○ MITTEL auf ✓ HOCH heben.

**⚠️ Mechanismus des Phasenübergangs**

Wie tritt γ_eff → 0 beim Übergang normal → supraleitend genau ein?
In der BCS-Theorie ist der Übergang zweiter Ordnung (kontinuierlich).
Im RFT-Bild: Geschieht der γ_eff-Abfall kontinuierlich mit sinkender
Temperatur, oder gibt es einen abrupten Sprung? Die Antwort beeinflusst
die Vorhersage der Breite des Übergangs ΔT_c.

**⚠️ Meissner-Effekt quantitativ**

Die qualitative Erklärung (torsionale Moden werden aus dem kohärenten
Volumen verdrängt) ist vorhanden. Eine quantitative Verbindung zwischen
der London-Eindringtiefe λ_L und den DRM-Parametern (κ, γ, L₀) fehlt.
Ohne diese bleibt der Meissner-Effekt in der RFT eine konzeptuelle
Beschreibung, keine Vorhersage.

**⚠️ η_Cooper quantitativ**

Der Ausdruck η_Cooper ≈ 1 − 2α ist gut motiviert (Feinstrukturkonstante
als Maß der Raummatrix-Kopplung), aber die Herleitung des Faktors "2" aus
der Spinverzug-Feinstruktur ist noch nicht vollständig formalisiert.
Dies ist notwendig, bevor die Cooper-Paar-Gravimetrie-Vorhersage als
quantitative Zahl behandelt werden kann.

**🚩 Triplett-Zustände**

Supraleitung mit parallelen Elektronenspins (S=1) ist in einigen
Materialien (Sr₂RuO₄) experimentell beobachtet. Der RFT-Mechanismus für
Triplett-Supraleitung (n_Cooper = 2π ≠ 0) ist nicht entwickelt und
bleibt eine offene Frage.

---

## 10. Zusammenfassung und Formelübersicht

### 10.1 Kernaussagen

Die RFT interpretiert Supraleitung als Zustand maximaler Phasenkohärenz
der Raummatrix (γ_eff → 0, S → 0), der durch resonante Kopplung zwischen
Materialien und der DRM-Spinstruktur begünstigt wird.

Cooper-Paare besitzen in der RFT die topologische Windungszahl n = 0 (aus
der Superposition zweier entgegengesetzter Windungen π und −π). Diese
Topologie bewirkt:
- Aufhebung des Schleppwirbels → m_g → 0
- Entkopplung von der 2π-Raummatrix-Topologie → kein Widerstand
- Stärkster verfügbarer ÄP-Bruch in der RFT → testbar durch Gravimetrie

Die "45 THz Hypothese" benennt die charakteristische Resonanzfrequenz,
bei der die Kopplung zwischen Material und DRM maximal ist. Dieser Wert
ist halbempirisch und nicht scharf hergeleitet — er bleibt die zentrale
offene Frage der RFT-Supraleitung.

### 10.2 Formelübersicht

| Größe | Formel | Konfidenz | Herkunft |
|-------|--------|-----------|---------|
| Spin-Resonanzfaktor | f_spin = 144/π ≈ 45.84 | ✓ HOCH | v3_003, v3_001 |
| Primärlänge | L₀ = 1/κ | ✓ HOCH | v3_001 (Franz 25.03.2026) |
| Spinverzug | τ_lag = L₀/c = (π/6)t_P | ✓ HOCH | v3_003 |
| Feinstrukturkonstante | α⁻¹ = 4π³+π²+π = 137.036304 | ✓ HOCH | v3_002 |
| Cooper-Paar Windungszahl | n_Cooper = π+(−π) = 0 | ✓ HOCH | v3_001 Kap.8 |
| ÄP-Bruch Cooper-Paar | η_Cooper = 1−2α ≈ 0.9854 | ○ MITTEL | v3_015 Kap.6.3 |
| Gravimetrie-Vorhersage | Δg/g ~ −10⁻⁵ | ✓ HOCH | v3_001 Kap.11.2 |
| DRM-Spin-Frequenz | f_DRM-Spin ≈ 7.74×10⁴¹ Hz | ✓ HOCH (Planck-Skala) | v3_001 Kap.11.3 |
| Kritische Frequenz | f_krit ≈ 45 THz | ⚠️ NIEDRIG | halbempirisch |
| Q-Faktor supraleitend | Q_SC → ∞ | ○ MITTEL | v3_018 Kap.7.4 |

### 10.3 Zusammenfassung der Flags

```
🚩 f_krit(Material) aus L₀, τ_lag, κ_Material: nicht hergeleitet → DS-019-A
🚩 n_Cooper = 0 rigoros aus Master-Gleichung: ausstehend
🚩 Triplett-Supraleitung in RFT: nicht behandelt
⚠️ η_Cooper = 1−2α: Faktor "2" nicht vollständig formalisiert
⚠️ γ_eff → 0 Mechanismus: kontinuierlich oder sprunghaft?
⚠️ Meissner: λ_L aus DRM-Parametern: nicht hergeleitet
```

---

## Kanonische Parameter (Zusammenfassung)

```
α⁻¹ = 4π³+π²+π = 137.036304   [2.22 ppm von CODATA — NIEMALS 0.67 ppm!]
L₀ = 1/κ                        [PRIMÄRDEFINITION, ħ-frei! Franz 25.03.2026]
   = (π/6)·l_P                  [numerische Verifikation]
τ_lag = L₀/c = (π/6)·t_P       [✓ HOCH]
f_spin = 144/π ≈ 45.84          [✓ HOCH — NIEMALS 4 oder 135!]
η_Cooper = 1 − 2α ≈ 0.9854      [○ MITTEL]
45 THz = halbempirisch          [⚠️ NIEDRIG — NIEMALS als präzise Vorhersage!]

Verbotene Terminologie:
  "Gitter"    → FALSCH  (immer: "Raummatrix" / "DRM")
  "Vakuum"    → FALSCH  (für Mode-0: "Ur-Chaos")
  "c₀"        → FALSCH  (immer: "c")
  ART-Sprache → NICHT in RFT verwenden
```

---

## Änderungsprotokoll

**v1.1 (2026-04-04):**
- Anhang A eingefügt: Materielle Konsistenzprüfung
- Tabelle aus RFT_47 nicht als Vorhersage übernommen — nur als ⚠️ NIEDRIG Konsistenzcheck mit explizitem Formelmangel-Hinweis
- Style-Guide-Reinigung 2026-05-06 (Header, Symbol-Glossar, Footer normiert)

**v1.0 (2026-04-04) — Final-Kandidat:**
- Erstversion im v3-Format
- Terminologie: "Vakuumgitter" → "Raummatrix"
- 45 THz: konsequent ⚠️ NIEDRIG, kanonische v3_001-Warnung übernommen
- Plateau-Konzept: NICHT enthalten
- Spin-1 Cooper-Paare: nur als 🚩 offene Flagge (§2.5)
- Meissner-Effekt: §6 als konzeptioneller Kandidat ⚠️ NIEDRIG
- DS-019-A als 🚩 OFFEN dokumentiert
- Alle Vorgängerdokumente v3_001/003/012/015/016/018 konsistent eingebunden
- Konfidenz-Tabelle vollständig (§9.1)

---

## Anhang A: Materielle Konsistenzprüfung (⚠️ NIEDRIG)

*Hinweis: Dieser Anhang ist kein Vorhersage-Abschnitt. Er dokumentiert eine
halbempirische Konsistenzprüfung mit expliziten Formelmängeln. Die Tabelle
darf nicht als RFT-Vorhersage zitiert werden.*

### A.1 Halbempirische Formel (nicht aus der RFT hergeleitet)

Aus RFT_48 (früheres Arbeitsdokument) stammt der Ansatz:

$$f_{\text{krit}} \approx \frac{v_{\text{eff}}}{2d}$$

wobei:
- d = Metall-Metall-Bindungsabstand im supraleitenden Strukturelement (Å)
- v_eff = Phasengeschwindigkeit optischer (LO-)Phononen des Materials (km/s)

**Kritischer Hinweis:** v_eff ist ein *gemessener Materialparameter*, kein aus
der RFT hergeleiteter Wert. Die Formel ist damit nicht eigenständig — sie
setzt externe Messgrößen ein und prüft nur, ob die Ergebnisse mit dem
gemessenen T_c konsistent sind. Zur Bestimmung von T_c wird zusätzlich eine
Kopplungskonstante λ_coupling benötigt, die in RFT_48 rückwärts aus dem
bekannten T_c-Wert bestimmt wurde — keine unabhängige Vorhersage.

### A.2 Konsistenzprüfung ausgewählter Materialien

⚠️ **KONFIDENZ: NIEDRIG** — Alle Werte in dieser Tabelle entstehen, wenn
v_eff und λ_coupling als gemessene Materialparameter eingesetzt werden.
Eine eigenständige RFT-Herleitung beider Parameter steht aus (DS-019-A).
Die Spalte "T_c konsistent" zeigt nur, ob das halbempirische Modell mit
dem bekannten Messwert verträglich ist — keine Vorhersage.

| Material | d (Å) | ω_D-Bereich (THz) | T_c gemessen | Konsistenz | Bemerkung |
|----------|-------|-------------------|--------------|------------|-----------|
| YBCO (YBa₂Cu₃O₇) | 3,82 | ~40–50 | 93 K | ○ | v_eff, λ rückwärts aus T_c=93K |
| MgB₂ | 1,78 | ~20–30 | 39 K | ○ | Debye-Freq. in RFT-Bereich |
| LaH₁₀ (Hochdruck) | 1,20 | ~100–120 | ~250 K | ○ | Hochdruckphase; v_eff unklar |
| Graphen/BN | 1,42 | ~70–80 | ? (offen) | 🚩 | keine Messung; kein Test möglich |

Die Debye-Frequenzbereiche aller bekannten HTS-Materialien liegen im THz-
Bereich — konsistent mit der Hypothese, dass THz-Kopplung an die DRM
relevant ist. Das ist motivierend für DS-019-A, aber kein Beweis.

### A.3 Was DS-019-A lösen muss

Um diese Tabelle in eine echte RFT-Vorhersagetabelle umzuwandeln, müssen
aus den DRM-Parametern (L₀, τ_lag, f_spin, κ) hergeleitet werden:

1. v_eff(Material) — ohne externe Phonon-Messung als Input
2. λ_coupling — aus der Raummatrix-Kopplungsstärke, nicht post-hoc

Erst dann kann die Spalte "T_c vorhergesagt (RFT)" mit Konfidenz ≥ ○ MITTEL
befüllt werden.

🚩 **DS-019-A: OFFEN** — Dies bleibt die zentrale offene Aufgabe.

---

© 2026 Franz Zollner — Resonance Field Theory Project  
Lizenz: Creative Commons BY-NC-ND 4.0  
Kontakt: rft.projekt@posteo.de

---

*Dokument-ID: RFT_v3_019 · Stand: 2026-04-04 · [Mapping zur alten Reihe](../_MAPPING_ALT_NEU.md) · [Style-Guide](../_STYLE_GUIDE.md) · [Repo-Hauptseite](../../../README.md)*
*Freigabe durch Franz Zollner ausstehend*
