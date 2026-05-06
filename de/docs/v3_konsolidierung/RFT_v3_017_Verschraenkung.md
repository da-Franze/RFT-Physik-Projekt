# RFT_v3_017: Verschränkung

*Untertitel: Nicht-Lokalität durch gemeinsame Resonanz-Moden (Topologische Identität)*

**Version:** v1.0 (2026-04-04)  
**Autor:** Franz Zollner  
**Sprache:** DE — EN-Übersetzung folgt unter `en/docs/v3_konsolidierung/`  
**Status:** Final-Kandidat  
**Lizenz:** Creative Commons BY-NC-SA 4.0  
**Zitation:** Zollner, F. (2026). *RFT_v3_017: Verschränkung.* RFT-Series. https://github.com/da-Franze/RFT-Physik-Projekt/blob/main/de/docs/v3_konsolidierung/RFT_v3_017_Verschraenkung.md
**Stufe:** IV — Teilchenphysik & Eigenschaften  

---

## Symbol-Glossar

| Symbol | Bedeutung | Wert / Definition |
|---|---|---|
| `Ψ(x₁,x₂,t)` | Gemeinsames Führungsfeld zweier Teilchen | im 6D-Konfigurationsraum, nicht-separierbar bei Verschränkung |
| `λ` | Nichtlinearer Selbstkopplungsterm | Quelle der Nicht-Separierbarkeit |
| `κ` | Resonanz-Steifigkeit | Primärgröße, NICHT Masseterm |
| `L₀ = 1/κ` | Fundamentale Längenskala | ħ-frei |
| `α⁻¹ = 4π³+π²+π` | Feinstrukturkonstante | `≈ 137.036304`, 2.22 ppm CODATA |
| `Φ = 2α/(1+α²)` | Geometrie-Faktor | `≈ 0.014596` |
| `S₁ = −Tr(ρ₁ log ρ₁)` | Verschränkungs-Entropie | > 0 ↔ topologische Identität |
| `E(θ_A,θ_B)` | Bell-Korrelation | `−cos(θ_A−θ_B)` |
| `S = 2√2` | CHSH-Parameter (Bell-Verletzung) | `≈ 2.828` |
| `τ_D` | Dekohärenzzeit | qualitativ aus κ, γ, L₀ (formal offen) |
| `AP` | Ankerpunkt | Wirbel-zu-DRM-Kopplung |
| `DRM` | Diskrete Resonanzmatrix | dynamisches 3D-Resonanzgitter |

**Cross-Refs:** [RFT_v3_001](RFT_v3_001_Mathematische_Grundlagen.md) (Master-Gleichung, κ, L₀), [RFT_v3_006](RFT_v3_006_Zeit_Emergenz.md) (Zeitpfeil, Φ), [RFT_v3_007](RFT_v3_007_Raum_Topologie_3D_Emergenz.md) (Raumtopologie), [RFT_v3_011 Teil 5](RFT_v3_011_Teil5_Anwendungen.md) (Kap. 16-17, Primärquelle), [RFT_v3_016](RFT_v3_016_Spin_Topologie.md) (AP-Topologie), [RFT_v3_018](RFT_v3_018_Entropie_Signaltheorie.md) (Dekohärenz & Entropie, parallel)

---

> **Konfidenz-Marker:** ✓ HOCH (mehrfach bestätigt), ○ MITTEL (konzeptuell klar, formal noch offen), ⚠️ NIEDRIG (Arbeitshypothese), 🚩 OFFEN (Originator-Entscheid oder DeepSeek-Aufgabe ausstehend). Offene Fragen werden explizit dokumentiert, nicht verschwiegen.

---

## Inhaltsverzeichnis

1. Das Rätsel der Verschränkung — Spuk oder Struktur?
2. Gemeinsame Resonanz-Moden — Der physikalische Mechanismus
3. Topologische Identität — Kernkonzept der RFT
4. Bell's Theorem und die RFT
5. EPR-Paradoxon: Auflösung in der RFT
6. Dekohärenz als Grenze der Verschränkung
7. Experimentelle Konsequenzen
8. Verknüpfung mit der v3-Serie
9. Ehrliche Grenzen
10. Zusammenfassung und Formelübersicht

---

## 1. Das Rätsel der Verschränkung

### 1.1 Die Beobachtung

Zwei Teilchen können in einem gemeinsamen Quantenzustand präpariert werden,
der nicht als Produkt zweier unabhängiger Zustände geschrieben werden kann.
Wenn man anschließend an einem der Teilchen eine Messung vornimmt —
gleichgültig ob in einem Labor auf der Erde oder, hypothetisch, am anderen
Ende der Galaxie — liefert das zweite Teilchen augenblicklich ein damit
korreliertes Ergebnis. Diese Korrelation übertrifft alles, was mit lokalen
Ursachen erklärt werden kann.

```
Experiment (schematisch):
  Quelle erzeugt verschränktes Paar
       │
       ├─────── Teilchen 1 → Alice (misst Spin)
       │
       └─────── Teilchen 2 → Bob (misst Spin)

Alice misst: ↑
Bob misst sofort: ↓  (egal wie weit entfernt!)
Korrelation: E(θ=0°) = -1  (perfekte Antikorrelation)
```

Die Standardformulierung (Bell-Zustand, Spin-Singulett):

```
|Ψ⟩ = (1/√2)(|↑↓⟩ - |↓↑⟩)

Diese Superposition ist NICHT faktorisierbar:
|Ψ⟩ ≠ |ψ₁⟩ ⊗ |ψ₂⟩  für beliebige Einzelzustände |ψ₁⟩, |ψ₂⟩
```

Die winkelsabhängige Korrelation lautet:

```
E(θ_A, θ_B) = -cos(θ_A - θ_B)

z.B. θ_A = θ_B = 0°: E = -1  (perfekt antikorreliert)
     θ_A - θ_B = 90°: E =  0  (unkorreliert)
```

### 1.2 Das Problem: Lokalität oder Nicht-Lokalität?

Einstein bezeichnete diese Korrelation als „spukhafte Fernwirkung" und
lehnte sie als inkonsistent mit der Relativitätstheorie ab. Sein Argument
(Einstein, Podolsky, Rosen 1935): Wenn die Quantenmechanik vollständig ist
und dennoch solche Nicht-Lokalität impliziert, dann verletzt sie grundlegende
Prinzipien der klassischen Physik. Wenn sie diese Prinzipien nicht verletzt,
muss sie unvollständig sein.

John Bell formalisierte 1964 diese Spannung: Er zeigte, dass keine Theorie
mit *lokalen* verborgenen Variablen die quantenmechanischen Korrelationen
reproduzieren kann. Die Natur ist entweder nicht-lokal oder nicht-realistisch —
eine der beiden Annahmen muss fallen.

```
Bells Ungleichung (CHSH-Form):
  |E(a,b) − E(a,b') + E(a',b) + E(a',b')| ≤ 2   (lokal realistisch)

Quantenmechanische Vorhersage:
  |S_QM| = 2√2 ≈ 2.828  (verletzt die Ungleichung!)

Experimente (Aspect 1982; Zeilinger 1998 u.v.m.):
  |S_exp| > 2  (QM bestätigt, lokale verborgene Variablen widerlegt)
```

### 1.3 Die RFT-These

Die RFT antwortet auf dieses Rätsel mit einem klaren mechanistischen Bild:

> **Verschränkung ist kein Mysterium und kein „Spuk".**
>
> Verschränkte Teilchen sind nicht zwei getrennte Objekte mit seltsamer
> Fernwirkung. Sie sind **topologisch ein einziges Objekt** — eine
> gemeinsame Wirbelkonfiguration der Raummatrix, die räumlich ausgedehnt ist.
>
> Nicht-Lokalität = Topologische Identität der gemeinsamen Resonanz-Mode.
> Kein Signal wird übertragen. Keine Kausalitätsverletzung.
> Die Korrelation war immer im gemeinsamen Führungsfeld kodiert.

Dies ist nicht bloß eine neue Interpretation derselben Mathematik. Es ist
eine physikalisch substanzielle Aussage über die Struktur des Raums selbst:
Die Raummatrix (DRM) ist das Medium, das die „Verbindung" der verschränkten
Teilchen trägt — nicht als abstraktes mathematisches Objekt, sondern als
reale resonante Feldkonfiguration.

---

## 2. Gemeinsame Resonanz-Moden

### 2.1 Das Führungsfeld für zwei Teilchen

Ausgangspunkt ist die RFT-Master-Gleichung (v3_001):

```
∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η
```

(Der η-Term beschreibt externe Anregung; für die isolierte Verschränkungs-Konfiguration ohne externe Kopplung gilt η = 0. Er wird hier dennoch explizit aufgeführt, um die Konsistenz mit v3_001 zu wahren.)

Für ein einzelnes Teilchen beschreibt Ψ(x, t) dessen Wellenfunktion in der
Raummatrix. Das Teilchen selbst ist ein stabiler Wirbel (Soliton) in diesem
Feld; seine Position und Bewegung werden durch das Führungsfeld Ψ bestimmt.

Für **zwei Teilchen** erweitert sich das Bild auf einen
6-dimensionalen Konfigurationsraum:

```
Ψ = Ψ(x₁, x₂, t)

wobei x₁ = Position von Teilchen 1
      x₂ = Position von Teilchen 2
```

Dieses gemeinsame Führungsfeld ist eine einzige, nicht trennbare
Feldkonfiguration in der Raummatrix. Es ist *nicht* die Summe oder das
Produkt zweier unabhängiger Einzelfelder.

### 2.2 Nicht-Separierbarkeit: Was genau bedeutet das?

Ein Zwei-Teilchen-Zustand heißt *separierbar*, wenn das gemeinsame Führungsfeld
als Produkt zweier Einzelfelder geschrieben werden kann:

```
Separierbar:     Ψ(x₁, x₂, t) = Ψ₁(x₁, t) · Ψ₂(x₂, t)
Verschränkt:     Ψ(x₁, x₂, t) ≠ Ψ₁(x₁, t) · Ψ₂(x₂, t)   für beliebige Ψ₁, Ψ₂
```

Im separierbaren Fall bewegt sich Teilchen 1 unabhängig von Teilchen 2:
sein Führungsfeld kennt die Position des anderen nicht. Im verschränkten
Fall ist das gemeinsame Führungsfeld topologisch verknüpft: die Bewegung
jedes Teilchens hängt von der aktuellen Konfiguration des gesamten
Zwei-Teilchen-Feldes ab.

### 2.3 Die Führungsgleichungen für verschränkte Teilchen

Aus dem gemeinsamen Führungsfeld Ψ(x₁, x₂, t) folgen die
Führungsgeschwindigkeiten beider Teilchen (analog Bohm, aber auf
das RFT-Führungsfeld angepasst — siehe v3_011 Kap. 11.3 und 16.3):

```
v₁(t) = f(∇₁Ψ(x₁(t), x₂(t), t), Ψ(x₁(t), x₂(t), t))
v₂(t) = f(∇₂Ψ(x₁(t), x₂(t), t), Ψ(x₁(t), x₂(t), t))
```

wobei ∇₁ den Gradienten nach x₁ bezeichnet und ∇₂ entsprechend nach x₂.

**Entscheidende Konsequenz:** Die Führungsgeschwindigkeit von Teilchen 1
hängt von der Position x₂ von Teilchen 2 ab — und umgekehrt. Diese
Kopplung ist nicht-lokal und *instantan* im Sinne des Führungsfeldes.
Sie überträgt jedoch keine Information (Kap. 4.3).

⚠️ Hinweis (RFT-Brille, J.16): Die obige Führungsgleichung ist in der
Sprache analoger Bohm'scher Mechanik formuliert. Das RFT-Führungsfeld
v ∝ −∇V_eff aus der Master-Gleichung erfüllt dieselbe Kontinuitätsgleichung.
Beide Formulierungen sind für den Zwei-Teilchen-Fall äquivalent
(v3_011 Kap. 16.3, Hinweis). ○ MITTEL

### 2.4 Entstehung gemeinsamer Moden: Der λ-Term

Wie entstehen verschränkte Paare? Im Bild der Raummatrix durch eine
Wechselwirkung, bei der zwei Wirbel aus einem gemeinsamen Mutterwirbel
hervorgehen — oder durch direkte Kopplung zweier Wirbel über den
nichtlinearen Term der Master-Gleichung.

Der λ-Term in der Master-Gleichung:

```
λ|Ψ|²Ψ

ist der Nichtlinearitätsterm. Er ist entscheidend:
  → Ohne λ: lineare Wellengleichung → keine Solitone, keine stabilen Teilchen
  → Mit λ: nichtlineare Selbstkopplung → stabile Wirbel (Teilchen), Solitone
```

Wenn zwei Wirbel durch diesen Term wechselwirken, koppeln ihre Felder
so, dass das resultierende Zwei-Teilchen-Feld Ψ(x₁, x₂) nicht mehr als
Produkt geschrieben werden kann. Die Nichtlinearität mischt die
Freiheitsgrade untrennbar.

**Kandidat-Argumentation (○ MITTEL):** Man prüfe, ob ein Produktansatz
Ψ(x₁, x₂) = Ψ₁(x₁)·Ψ₂(x₂) in der Zwei-Teilchen-Master-Gleichung
konsistent ist, sobald λ ≠ 0. Der nichtlineare Term wird dann:

```
λ|Ψ|²Ψ = λ|Ψ₁|²|Ψ₂|² · Ψ₁ · Ψ₂
```

Im Allgemeinen erzeugt die zeitliche Entwicklung unter dieser Kopplung
Terme, die sich nicht mehr in das Produkt-Format einordnen lassen:
die Rückkopplung von |Ψ₂|² auf Ψ₁ erzeugt eine Abhängigkeit, die
Ψ₁ von x₂ abhängig macht. Das Produkt wird zur nicht-separierbaren
Gesamtwellenfunktion.

🚩 DS-017-A (Priorität HOCH): Formale Verifikation dieser Argumentation
aus der Master-Gleichung ohne Hilbertraum-Voraussetzungen. Kann gezeigt
werden, dass nach einer λ-Term-Wechselwirkung Ψ(x₁, x₂) generisch
nicht-separierbar ist?

### 2.5 Persistenz der gemeinsamen Mode

Nach der Erzeugung des verschränkten Paares trennen sich die beiden
Teilchen räumlich. Das gemeinsame Führungsfeld Ψ(x₁, x₂, t) besteht
jedoch fort. Es ist eine Eigenschaft der Raummatrix — keine zusätzliche
„Verbindung", die extra hergestellt werden müsste, sondern die
ursprüngliche topologische Verknüpfung der gemeinsamen Mode.

```
Entstehung:
  t < 0: Mutterwirbel (z.B. Photon), Ψ(x,t) einfach
  t = 0: Zerfall/Wechselwirkung → λ-Term koppelt Teilchen
  t > 0: Ψ(x₁, x₂, t) — eine Feldkonfiguration, zwei Wirbel

Räumliche Trennung:
  |x₁ - x₂| → groß
  Ψ(x₁, x₂) bleibt nicht-separierbar!  (solange keine Dekohärenz)
```

Die Persistenz dieser nicht-separierbaren Feldkonfiguration ist der
RFT-Mechanismus hinter der Langreichweite von Verschränkung.
Wie weit sie reicht und unter welchen Bedingungen sie abbricht,
diskutiert Kapitel 6 (Dekohärenz).

---

## 3. Topologische Identität — Kernkonzept der RFT

### 3.1 Definition (○ MITTEL — Franz-Entscheid empfohlen)

Der Leitbegriff dieses Dokuments laut Dokumentenübersicht (Franz Zollner,
Feb 2026) ist „Topologische Identität". Er ist bisher in der v3-Serie nicht
formal definiert. Folgender Kandidat wird vorgeschlagen:

> **Definition (Topologische Identität) — ○ MITTEL:**
>
> Zwei Ankerpunkte/Wirbel in der Raummatrix heißen *topologisch identisch*,
> wenn ihre gemeinsame Resonanz-Mode Ψ(x₁, x₂, t) nicht in unabhängige
> Einzelmoden faktorisiert werden kann. Der Konfigurationsraum dieser
> Mode trägt eine nicht-triviale topologische Struktur (nicht-verschwindende
> Verschränkungs-Entropie: S = −Tr(ρ₁ log ρ₁) > 0), die durch räumliche
> Trennung allein nicht aufgehoben wird.
>
> In RFT-Sprache: Die beiden Wirbel sind Aspekte *eines* topologischen
> Objekts in der Raummatrix, nicht zwei getrennte Objekte mit Fernwirkung.

🚩 Franz-Entscheid: Ist „Topologische Identität" die richtige Bezeichnung?
Welche topologische Eigenschaft ist präzise gemeint — Windungszahl,
Modenstruktur, κ-Konfiguration? (Auch DS-017-B)

### 3.2 Was genau ist „topologisch identisch"?

Um den Begriff greifbar zu machen, helfen drei Beschreibungsebenen:

**Ebene 1 (anschaulich):**
```
Zwei verschränkte Teilchen = zwei „Enden" eines einzigen
dreidimensionalen Resonanzmusters in der Raummatrix.

Analogie: Ein Möbius-Band hat zwei scheinbar getrennte Randpunkte,
die aber topologisch zusammenhängen — kein Schnitt zwischen ihnen
kann die Topologie des Bandes zerstören, ohne das Band selbst zu
verändern.

Besser (RFT-spezifisch): Die Raummatrix-Mode Ψ(x₁, x₂) ist ein
zusammenhängendes Objekt im Konfigurationsraum ℝ⁶.
```

**Ebene 2 (physikalisch):**
```
Messung an Teilchen 1 = lokales „Abtasten" einer Eigenschaft
des gemeinsamen Konfigurationsraum-Feldes.

Das Ergebnis ist sofort bekannt für Teilchen 2, weil:
→ Es keine zwei getrennte Realitäten für x₁ und x₂ gibt.
→ Es gibt nur eine: Ψ(x₁, x₂, t) — und diese ist
  bezüglich x₁ und x₂ topologisch verknüpft.
```

**Ebene 3 (formal, ○ MITTEL):**
```
Nicht-Separierbarkeit ↔ nicht-triviale Verschränkungs-Entropie:

  ρ₁ = Tr₂(|Ψ⟩⟨Ψ|)  (reduzierte Dichtematrix Teilchen 1)
  S₁ = −Tr(ρ₁ log ρ₁) > 0  ↔ Topologische Identität!

Für Bell-Zustand |Ψ⟩ = (1/√2)(|↑↓⟩ − |↓↑⟩):
  S₁ = log(2) ≈ 0.693  (maximal verschränkt für 2-Niveau-System)
  → Maximale topologische Identität! ✓

⚠️ RFT-Brille (J.16): Diese Formeln verwenden Hilbertraum-Sprache.
In der diskreten Raummatrix ist S₁ eine effektive Beschreibung der
Nicht-Separierbarkeit — kein fundamentales Axiom.
```

### 3.3 Vergleich mit dem Photon: Ähnlichkeit und Unterschied

Ein wichtiger Vergleich, der explizit geklärt werden muss:

**Photon = 2 AP (e⁻ + e⁺) — kanonisch (Franz, 11.03.2026, ✓ HOCH):**

```
Photon:
  e⁻ (1 AP, links-zirkular) + e⁺ (1 AP, rechts-zirkular) = 2 AP
  → Ein gebundenes, propagierendes Objekt
  → Stabil durch Wirbelgeometrie
  → Nicht trennbar ohne Annihilation (oder Paarproduktion)

Verschränktes Paar (z.B. e⁻e⁺ nach Photon-Zerfall):
  e⁻ (1 AP) + e⁺ (1 AP) = 2 getrennte Teilchen
  → Räumlich separierbar (keine gebundene Wirbelstruktur mehr)
  → Verbunden durch gemeinsames Führungsfeld Ψ(x₁, x₂)
  → Trennbar: Dekohärenz bricht topologische Identität
```

**Der Mechanismus ist ähnlich, die Situation verschieden:**

```
Gemeinsamkeit:
  Beide: Zwei APs teilen eine gemeinsame Raummatrix-Konfiguration.
  Beide: Das gemeinsame Objekt ist nicht als Produkt separierbar.

Unterschied:
  Photon: gebunden, kompakt, propagierend — beide APs am selben Ort
  Verschränkung: getrennt, ausgedehnt — APs weit voneinander entfernt,
                 aber durch Ψ(x₁, x₂) topologisch verbunden
```

Kurz: Das Photon ist ein *lokal gebundenes* Zwei-AP-Objekt; die
Verschränkung ist eine *räumlich ausgedehnte* gemeinsame Feldkonfiguration.
Der Grundmechanismus (gemeinsame Raummatrix-Mode) ist derselbe —
aber die Randbedingungen unterscheiden sich wesentlich.

---

## 4. Bells Theorem und die RFT

### 4.1 Was Bell's Theorem beweist

Bell (1964) bewies: Keine Theorie, die Folgendes annimmt, kann die
quantenmechanischen Korrelationen reproduzieren:

```
Bell-Annahmen (klassisch):
  (L) Lokalität:  A(a, λ) hängt nicht von b oder λ_B ab
  (R) Realismus:  λ existiert vor der Messung (verborgene Variable)
  (D) Determinismus: Ergebnisse A, B ∈ {-1, +1} eindeutig

Folgerung (Bell-CHSH-Ungleichung):
  |S| = |E(a,b) − E(a,b') + E(a',b) + E(a',b')| ≤ 2

Experiment: |S| ≈ 2.828 > 2  →  Bell-Annahmen verletzt!
```

### 4.2 Warum Bell's Theorem die RFT nicht ausschließt (RFT-Brille, J.16)

Bell's Beweis schließt *lokale* verborgene Variablen aus. Die RFT hat
verborgene Variablen — nämlich den präzisen Zustand des gemeinsamen
Führungsfeldes Ψ(x₁, x₂) — aber diese sind explizit **nicht-lokal**.

⚠️ RFT-Brille (J.16): Bell's Beweis arbeitet in der Sprache der
kontinuierlichen Quantenfeldtheorie (Hilbertraum, Operatoren,
Dichtematrix). In der diskreten Raummatrix sind diese Strukturen
nicht a priori gegeben. Der RFT-Mechanismus muss daher in
eigener Sprache formuliert werden:

```
Bell-Lokalität fordert:
  A(a, λ_A) unabhängig von b und λ_B

RFT-Führungsfeld:
  v₁(t) hängt von x₂(t) ab!  (über Ψ(x₁, x₂))
  → Bell-Lokalität ist in der RFT NICHT erfüllt!
  → Bell's Theorem SCHLIESST RFT NICHT AUS! ✓

RFT ist also eine Theorie mit nicht-lokalen verborgenen Variablen.
Die verborgene Variable = Führungsfeld-Konfiguration Ψ(x₁, x₂).
```

**Warum die RFT die Bell-Korrelationen reproduziert:**

Das gemeinsame Führungsfeld Ψ(x₁, x₂) ist so konstruiert, dass es
exakt dieselben Korrelationen erzeugt wie die Standardformulierung:

```
E_RFT(θ_A, θ_B) = -cos(θ_A - θ_B)

→ CHSH-Parameter: S_RFT = 2√2 ≈ 2.828 ✓
→ Identisch mit QM-Vorhersage!
→ Konsistent mit allen Bell-Tests! ✓
```

### 4.3 Die verborgene Variable in der RFT

In der Standardformulierung nach Bell ist eine „verborgene Variable" λ eine
Größe, die das Messergnis eindeutig festlegt, aber dem Beobachter nicht
direkt zugänglich ist. In der RFT ist diese verborgene Variable:

```
λ_RFT = vollständige Konfiguration von Ψ(x₁, x₂, t)

Enthält:
  - Wirbel-Konfiguration bei x₁: Stärke, Phase, Orientierung
  - Wirbel-Konfiguration bei x₂: Stärke, Phase, Orientierung
  - Gemeinsame Modenstruktur: topologische Verbindung

Nicht-lokal:
  → λ_RFT ist nicht in „λ_A bei x₁" und „λ_B bei x₂" teilbar
  → Es ist eine einzige, unteilbare Feldkonfiguration im ℝ⁶!
```

Deterministisch: Gegeben die vollständige Konfiguration Ψ(x₁, x₂, t₀)
zum Zeitpunkt t₀, sind alle späteren Messungsergebnisse prinzipiell
bestimmt. Die scheinbare Zufälligkeit folgt aus der Unkenntnis der
genauen Anfangsbedingungen des Führungsfeldes.

### 4.4 Terminologie: „Nicht-Lokalität" in der RFT

Um Missverständnisse zu vermeiden:

```
NICHT gemeint: "Nicht-lokale Wirkung" (suggeriert Signal-Übertragung)
GEMEINT:        "Topologische Identität der gemeinsamen Mode"

Die Korrelation entsteht nicht dadurch, dass bei Messung von x₁
ein Signal zu x₂ geschickt wird. Sie ist bereits im gemeinsamen
Führungsfeld Ψ(x₁, x₂) kodiert — die Messung deckt sie auf.

Analogie (nur anschaulich):
  Zwei "Endpunkte" einer einzigen Raummatrix-Konfiguration.
  Wenn man den einen Endpunkt "misst", erfährt man etwas über
  die gesamte Konfiguration — auch über den anderen Endpunkt.
  Kein Signal fließt: Die Information war immer dort.
```

---

## 5. EPR-Paradoxon — Auflösung in der RFT

### 5.1 Das EPR-Argument (1935)

Einstein, Podolsky und Rosen formulierten ihr Paradoxon wie folgt:
Wenn die Quantenmechanik vollständig ist, impliziert sie nicht-lokale
Wirkungen, die der Relativitätstheorie widersprechen. Wenn sie die
Relativitätstheorie respektiert, muss sie unvollständig sein (es fehlen
„Elemente der Realität").

```
EPR-Dilemma:
  ENTWEDER QM vollständig → nicht-lokale Wirkung (Einstein: inakzeptabel!)
  ODER     QM unvollständig → verborgene Variablen

EPR-Präferenz: Unvollständigkeit + verborgene Variablen
```

### 5.2 Die RFT-Antwort

Die RFT gibt Einstein in einem wesentlichen Punkt Recht:

```
Einstein hatte Recht:
  Es gibt tatsächlich eine nicht-lokale Struktur (Führungsfeld Ψ(x₁,x₂)).
  Die Korrelation ist real und physikalisch begründet.

Aber Einstein lag in einem Punkt falsch:
  Nicht-Lokalität ≠ nicht-lokale Wirkung.
  Eine Korrelation ist keine Kausalität.
```

**Die RFT-Auflösung in drei Schritten:**

```
Schritt 1: Beide Teilchen entstehen aus einer gemeinsamen
           Wechselwirkung (λ-Term) → gemeinsames Führungsfeld
           Ψ(x₁, x₂) wird erzeugt (topologische Identität).

Schritt 2: Die Teilchen trennen sich räumlich, aber das gemeinsame
           Führungsfeld Ψ(x₁, x₂, t) bleibt bestehen.
           → Die Korrelation ist bereits vollständig im Feld kodiert.

Schritt 3: Alice „misst" = ihr Detektor koppelt lokal an Teilchen 1.
           Das Messergebnis deckt auf, welchen Aspekt das gemeinsame
           Feld Ψ hat — und damit auch, welches Ergebnis Bob erhalten wird.
           → Kein Signal gesendet. Korrelation war immer dort. ✓
```

### 5.3 Kein Widerspruch zur speziellen Relativitätstheorie

Die Relativitätstheorie verbietet die Übertragung von Information
schneller als Licht. Die RFT respektiert dies:

```
Was NICHT passiert (RFT):
  ✗ Alice sendet Signal zu Bob
  ✗ Energie oder Information fließt von x_A nach x_B
  ✗ Änderung der Raummatrix bei x_A beeinflusst kausale Struktur bei x_B

Was PASSIERT (RFT):
  ✓ Messung bei x_A = lokale Interaktion mit globalem Objekt Ψ(x₁,x₂)
  ✓ Das globale Objekt hat immer eine definierte Korrelationsstruktur
  ✓ Bob „erfährt" diese Struktur bei seiner Messung (ebenfalls lokal)
  ✓ Erst durch klassische Kommunikation (≤ c) können sie die
    Korrelation als solche identifizieren

No-Signaling-Theorem:
  P(Bob's Ergebnis b | Alice misst) = P(Bob's Ergebnis b | Alice misst nicht)
  → Bob kann ohne Alices Mitteilung (auf klassischem Kanal) nicht
    feststellen, ob Alice gemessen hat oder nicht! ✓
```

### 5.4 „Realität" in der RFT: Eine physikalische Position

Die EPR-Diskussion dreht sich wesentlich um die Frage, ob Teilchen vor
der Messung „definierte Eigenschaften" haben. Die RFT nimmt hier eine
klare physikalische Position ein:

```
RFT-Position:
  Ja, Teilchen haben definierte Eigenschaften vor der Messung!

  Aber: Diese Eigenschaften sind nicht die klassischen Eigenschaften
  (Position, Impuls als unabhängige Größen), sondern Aspekte des
  gemeinsamen Führungsfeldes Ψ(x₁, x₂).

  „Eigenschaft von Teilchen 1" existiert nicht unabhängig von
  Teilchen 2 — weil es kein unabhängiges Feld Ψ₁(x₁) gibt.
  Es gibt nur das gemeinsame Feld Ψ(x₁, x₂).

  Das ist Realismus — aber nicht lokal-klassischer Realismus.
  Es ist topologischer Realismus:
  → Die gemeinsame Feldkonfiguration ist real und bestimmt die Ergebnisse.
  → Sie kann nicht in zwei lokale Realitäten aufgeteilt werden.
```

---

## 6. Dekohärenz als Grenze der Verschränkung

### 6.1 Warum Verschränkung nicht ewig währt

Das gemeinsame Führungsfeld Ψ(x₁, x₂, t) wird nicht nur durch die
Dynamik der zwei verschränkten Teilchen bestimmt. Es steht in Wechselwirkung
mit der gesamten Raummatrix-Umgebung: anderen Wirbeln, thermischen
Fluktuation, dem κ-Feld der Raummatrix selbst.

Diese Kopplung an die Umgebung bewirkt **Dekohärenz**: Die topologische
Identität der gemeinsamen Mode wird schrittweise durch Umgebungskopplungen
„gemessen" und dadurch aufgelöst.

```
RFT-Bild der Dekohärenz:
  t = 0:  Ψ(x₁, x₂) — nicht-separierbar (topologische Identität)
  t > 0:  Wechselwirkung mit Umgebungswirbeln bei x₁ und x₂
  t = τ_D: Ψ ≈ Ψ₁(x₁) · Ψ₂(x₂) — effektiv separierbar
           → Topologische Identität aufgebrochen! ✗
```

### 6.2 Dekohärenz als Umgebungsverschränkung

Der Dekohärenz-Mechanismus ist in der Sprache der RFT kein Sonderfall,
sondern dieselbe Physik in anderer Richtung: Die verschränkten Teilchen
verschränken sich mit der Umgebung. Dadurch verteilt sich die
topologische Identität auf ein immer größeres System, bis die paarweise
Korrelation zwischen Teilchen 1 und Teilchen 2 für praktische Zwecke
verschwindet.

```
Formales Bild (RFT-Brille bei Lindblad-Formalismus! J.16):

  ∂ρ/∂t = −(i/ħ)[H, ρ] + Σ_k γ_k (L_k ρ L_k† − ½{L_k†L_k, ρ})

⚠️ Lindblad-Gleichung: QFT-Formalismus (Hilbertraum, Operatoren).
   In der RFT: L_k entspricht Kopplung der Wirbel an Umgebungs-κ-Moden.
   Die strukturelle Aussage ist übertragbar; die formale Herleitung aus
   der Master-Gleichung steht aus (→ v3_018, DS-018).

Qualitative RFT-Aussage (○ MITTEL):
  Dekohärenzzeit τ_D ~ 1/(n_U · σ_int · v_U)

  n_U  = Dichte der Umgebungswirbel (thermische Anregungen)
  σ_int = effektiver Wechselwirkungsquerschnitt (aus κ und L₀)
  v_U  = typische Geschwindigkeit der Umgebungswirbel
```

### 6.3 Wann bricht die topologische Identität?

Die qualitative Grenze: Die topologische Identität ist aufgebrochen,
sobald die Umgebung „genug Information" über den Zustand der einzelnen
Teilchen enthält, um zwischen den beiden Komponenten des Führungsfeldes
zu unterscheiden.

```
Grenzfälle:
  Isoliert, T → 0:  τ_D → ∞   (Verschränkung langlebig)
  Viele Umgebungswirbel, hohe T: τ_D kurz (schnelle Dekohärenz)

RFT-Kandidat (⚠️ NIEDRIG — quantitativ nicht aus kanonischen
Parametern hergeleitet):
  τ_D ~ τ_int / (Q_system/Q_umgebung)

  τ_int = typische Wechselwirkungszeit der Raummatrix-Moden
  Q = Gütefaktor (aus κ, γ, L₀)

🚩 Quantitative Herleitung von τ_D aus Master-Gleichung und
   kanonischen Parametern (κ, γ, L₀, c): offen → v3_018
```

### 6.4 Verbindung zu v3_018

Dekohärenz ist das zentrale Thema des parallelen Dokuments v3_018
(Entropie & Signaltheorie). Der vorliegende Abschnitt beschränkt sich
auf die für Verschränkung relevante Aussage: Dekohärenz bricht die
topologische Identität, indem die gemeinsame Mode sich in Wechselwirkung
mit der Umgebung auf mehrere, effektiv separate Moden aufteilt.

Die Frage „ab wann" ist eine quantitative Frage, die v3_018 ausarbeitet.

---

## 7. Experimentelle Konsequenzen

### 7.1 Vergleich RFT und Standardquantenmechanik

In den meisten experimentell zugänglichen Situationen macht die RFT
dieselben Vorhersagen wie die Standardquantenmechanik:

```
RFT-Vorhersagen identisch mit QM:
  ✓ E(θ_A, θ_B) = -cos(θ_A - θ_B)
  ✓ CHSH: S = 2√2 ≈ 2.828 (Bell-Verletzung)
  ✓ Keine FTL-Kommunikation
  ✓ Born-Regel (Mechanismus: Führungsfeld-Statistik)

Begründung: Identische Vorhersagen, weil das gemeinsame Führungsfeld
Ψ(x₁, x₂) dieselbe Mathematik trägt wie die QM-Wellenfunktion —
aber mit physikalischer Interpretation statt abstrakter Beschreibung.
```

Ehrlich formuliert: Im Bereich der Verschränkungs-Experimente (Bell-Tests,
EPR-Korrelationen, Quantenkryptographie, Quantenteleportation) unterscheidet
sich die RFT experimentell *nicht* von der Standardquantenmechanik.
Hier ist die RFT eine alternative Interpretation, keine alternative Theorie.

### 7.2 Mögliche Unterschiede: Offene Fragen

Langfristig könnten Unterschiede auftreten in Bereichen, wo die
nicht-lineare Struktur der Master-Gleichung (λ-Term) oder die
diskrete Raummatrix-Struktur (L₀ ~ l_P) relevant wird:

```
Kandidaten für Unterschiede (⚠️ NIEDRIG — spekulativ):

1. Hochenergie-Präzisionstests:
   Bei Energien nahe der Planck-Skala könnte die diskrete L₀-Struktur
   der Raummatrix zu Abweichungen vom Kontinuum-QM-Bild führen.
   Status: Weit außerhalb aktueller experimenteller Reichweite.

2. GHZ-Zustände (Drei-Teilchen-Verschränkung):
   |GHZ⟩ = (1/√2)(|↑↑↑⟩ + |↓↓↓⟩)
   In der RFT: Drei Wirbel mit gemeinsamer Raummatrix-Mode.
   Prediction: Identisch mit QM, aber RFT-Mechanismus: gemeinsame
   Mode in ℝ⁹ (Konfigurationsraum für 3 × ℝ³).
   Offen: Stabilität der gemeinsamen Mode mit wachsender AP-Zahl.
   🚩 Nicht ausgearbeitet.

3. Verschränkung in gekrümmter Raummatrix:
   Bei starker Gravitation (nahe BH, v3_008):
   Wie verhält sich die gemeinsame Mode, wenn die Raummatrix selbst
   in Mode 2 übergeht? Spekulativ, kein Formalismus.
```

### 7.3 Quantenkryptographie im RFT-Bild

Quantenkryptographie (QKD) nutzt die Nicht-Lokalität der Verschränkung
zur sicheren Schlüsselverteilung. Im RFT-Bild:

```
BB84 / E91 in der RFT:
  Sicherheit beruht auf: topologische Identität der gemeinsamen Mode
  → Jede Abhör-Messung durch Eve = Dekohärenz der gemeinsamen Mode
  → Messfehler von Alice und Bob: erkennbar ✓

Mechanismus:
  Eve's Detektor koppelt an das gemeinsame Führungsfeld Ψ(x₁,x₂).
  → Das Feld wird durch Eves Detektor modifiziert (Dekohärenz teilweise)
  → Alice und Bob können statistisch feststellen, dass Ψ gestört wurde
  ✓ Konsistent mit Standardaussagen zur QKD-Sicherheit
```

---

## 8. Verknüpfung mit der v3-Serie

### 8.1 v3_001: Master-Gleichung

Der λ-Term der Master-Gleichung ist der Ursprung der Verschränkung
(Kap. 2.4). Ohne λ = 0 wäre die Theorie linear: Superposition wäre
möglich, aber echte nicht-separierbare Zwei-Teilchen-Moden wären
nicht aus Einzelmoden erzeugbar. Der nichtlineare λ-Term ist der
Mechanismus, der topologische Identität generiert.

### 8.2 v3_006: Zeitpfeil und Führungsfeld

Der Zeitpfeil in der RFT entsteht aus einer leichten Modenasymmetrie
(Φ = 2α/(1+α²) ≈ 0.01460). Das Führungsfeld Φ ist der Motor des
Zeitpfeils. Das Führungsfeld Ψ(x₁, x₂) im Verschränkungskontext ist
dasselbe Feld — es bestimmt auch die zeitliche Entwicklung der
verschränkten Konfiguration.

Die Frage der Lorentz-Invarianz des simultanen Updates der topologischen
Identität bei Messung ist direkt mit der Diskussion in v3_006 und v3_011
Kap. 21.3 verbunden: Die Messstatistik ist Lorentz-invariant, auch wenn
das Führungsfeld selbst kein bevorzugtes Bezugssystem vermeidet.

### 8.3 v3_007: Raumtopologie — warum 3D entscheidend ist

Die 3D-Struktur der Raummatrix (v3_007) ist der Rahmen, in dem
topologische Identität überhaupt definiert werden kann. In 1D wäre
kein Wirbel möglich; in 2D fehlen stabile Soliton-Strukturen; erst
in 3D gibt es die geometrische Grundlage für stabile Ankerpunkte
und damit für die Träger der topologischen Identität.

### 8.4 v3_011 Kap. 16–17: Ausgangspunkt

Dieses Dokument vertieft und formalisiert die Kapitel 16 und 17 von
v3_011 Teil 5. Die Kernaussagen bleiben:

```
Aus v3_011 Kap. 16.3 (✓ HOCH, übernommen):
  Verschränkung = gemeinsames Führungsfeld Ψ(x₁, x₂, t)
  → Nicht separierbar: Ψ(x₁,x₂) ≠ Ψ₁(x₁)·Ψ₂(x₂)
  → v₁ hängt von x₂ ab (und umgekehrt) → instantane Kopplung

Aus v3_011 Kap. 17.4 (✓ HOCH, übernommen):
  RFT: nicht-lokal (Führungsfeld!) + deterministisch
  → Bell's Theorem schließt RFT nicht aus
  → S_RFT = 2√2 ✓ (identisch mit QM)

Neu in v3_017:
  → Begriff „Topologische Identität" definiert (○ MITTEL)
  → λ-Term als Entstehungsmechanismus ausgeführt
  → Photon-Vergleich präzisiert
  → Dekohärenz als Grenze ausgeführt (→ v3_018)
  → RFT-Brille bei Bell explizit (J.16)
```

### 8.5 v3_016: AP-Topologie

v3_016 behandelt die 720°-Periodizität der Wirbelstruktur und AP als
Dimensionskopplungen. Dies ist relevant für die formale Grundlage des
Begriffs „Topologische Identität": Die Topologie, um die es geht,
ist die der Wirbelstruktur im Konfigurationsraum.

🚩 Verbindung v3_016 → v3_017: Kann „Topologische Identität" präzise
über Windungszahlen der Wirbel in ℝ⁶ definiert werden? Formale
Ausarbeitung ausstehend.

---

## 9. Ehrliche Grenzen

### 9.1 Konfidenz-Tabelle

| Aussage | Konfidenz | Quelle |
|---|---|---|
| Verschränkung = gemeinsames Führungsfeld Ψ(x₁,x₂) | ✓ HOCH | v3_011 Kap. 16.3 |
| v₁ hängt von x₂ ab (nicht-lokale Kopplung) | ✓ HOCH | v3_011 Kap. 16.3 |
| E_RFT(θ) = -cos(θ), S = 2√2 | ✓ HOCH | v3_011 Kap. 17.4 |
| RFT ist nicht-lokal → Bell nicht anwendbar | ✓ HOCH | v3_011 Kap. 17.4 |
| Keine FTL-Signalübertragung (No-Signaling) | ✓ HOCH | v3_011 Kap. 16.4 |
| λ-Term erzeugt Nicht-Separierbarkeit | ○ MITTEL | Kap. 2.4; DS-017-A offen |
| Topologische Identität (Definition) | ○ MITTEL | Kap. 3.1; Franz-Entscheid |
| Persistenz gemeinsamer Mode über große Distanzen | ○ MITTEL | Kap. 2.5 |
| Dekohärenz bricht topologische Identität | ○ MITTEL | Kap. 6; formal → v3_018 |
| τ_D quantitativ aus kanonischen Parametern | ⚠️ NIEDRIG | Kap. 6.3; → v3_018 |
| GHZ-Zustände in RFT | 🚩 OFFEN | Kap. 7.2 |
| Lorentz-Invarianz des Führungsfeldes | 🚩 OFFEN | v3_011 Kap. 21.3 |
| Formale Definition über Windungszahl in ℝ⁶ | 🚩 OFFEN | Kap. 8.5 |

### 9.2 Offene Fragen im Detail

**🚩 „Topologische Identität" — formale Definition:**

Der Begriff ist konzeptuell klar (gemeinsame, nicht-separierbare
Raummatrix-Mode), aber die präzise topologische Eigenschaft —
Windungszahl? Modenstruktur? κ-Konfiguration im ℝ⁶? — ist nicht
formal ausgearbeitet. Dies ist der dringlichste offene Punkt.

→ DS-017-B: Welche RFT-interne Größe entspricht der
„Topologischen Identität"?
→ Franz-Entscheid: Ist der Begriff selbst kanonisch?

**🚩 λ-Term und Nicht-Separierbarkeit (DS-017-A):**

Die qualitative Argumentation (Kap. 2.4) macht plausibel, dass der
nichtlineare Term die Entstehung von Verschränkung ermöglicht. Eine
formale Ableitung aus der Master-Gleichung in RFT-eigenem Formalismus
(ohne Hilbertraum-Tensorprodukt) steht aus.

**🚩 Reichweite der Verschränkung:**

Warum bleibt topologische Identität über Lichtjahre erhalten (in
Abwesenheit von Dekohärenz)? Die Raummatrix-Mode Ψ(x₁, x₂) ist
ein globales Objekt — es gibt keinen Mechanismus, der es räumlich
„abschwächt", solange keine Umgebungskopplung vorliegt. Diese
Aussage ist physikalisch plausibel, aber formal nicht aus der
Master-Gleichung bewiesen.

**⚠️ Lorentz-Invarianz des simultanen Updates:**

Bei Messung an x₁ „aktualisiert" das gemeinsame Führungsfeld sich
instantan. In welchem Bezugssystem ist dieses Update „simultan"?
Die Messstatistik ist Lorentz-invariant (kein Signal), aber das
Führungsfeld selbst wählt scheinbar ein bevorzugtes Bezugssystem.
Dies ist eine bekannte Spannung in allen Bohmianischen Theorien
und in der RFT gleichfalls offen (v3_011 Kap. 21.3). Als offene
Frage dokumentieren, nicht überspielen.

**⚠️ Dekohärenzzeit quantitativ:**

τ_D aus kanonischen Parametern (κ, γ, L₀, c) herzuleiten ist eine
offene Aufgabe für v3_018. Die qualitative Aussage (Umgebungskopplung
bricht topologische Identität) ist robust; die Zahl ist offen.

### 9.3 Was diese Grenzen bedeuten

```
Diese offenen Fragen schwächen die Kernthese nicht:

Gesichert (✓ HOCH):
  → Verschränkung = gemeinsames Führungsfeld
  → RFT ist nicht-lokal, Bell nicht anwendbar
  → Keine FTL-Kommunikation
  → Identische Bell-Vorhersagen wie QM

Offen (aber kein Widerspruch):
  → Formale Definition "Topologische Identität"
  → λ-Term-Beweis (DS-017-A)
  → Lorentz-Invarianz des Führungsfeldes

Ehrlich kommuniziert:
  v3_017 liefert einen mechanistischen Rahmen.
  Die formale Präzision auf Niveau eines rigoros
  abgeleiteten Theorems steht noch aus.
```

---

## 10. Zusammenfassung und Formelübersicht

### 10.1 Die Hauptaussagen

**1. Verschränkung ist topologische Identität (○ MITTEL)**

Verschränkte Teilchen sind nicht zwei Objekte mit seltsamer Fernwirkung.
Sie sind zwei Aspekte *einer* gemeinsamen, nicht-separierbaren
Resonanz-Mode Ψ(x₁, x₂, t) der Raummatrix. Diese nicht-separierbare
Feldkonfiguration ist das, was „Topologische Identität" meint.

**2. Gemeinsames Führungsfeld als physikalisches Substrat (✓ HOCH)**

Das Führungsfeld Ψ(x₁, x₂, t) existiert real im Konfigurationsraum
der Raummatrix. Es koppelt die Bewegungen beider Teilchen nicht-lokal
und instantan — ohne dass dabei ein Signal übertragen wird.

**3. Bell's Theorem schließt die RFT nicht aus (✓ HOCH)**

Bell schließt *lokale* verborgene Variablen aus. Die RFT hat
nicht-lokale verborgene Variablen (das Führungsfeld Ψ(x₁, x₂)).
Kein Widerspruch. Die RFT reproduziert E(θ) = -cos(θ) und
S = 2√2 exakt.

**4. EPR-Paradoxon aufgelöst (✓ HOCH)**

Einstein hatte Recht: Es gibt eine reale, nicht-lokale Struktur.
Aber: Nicht-Lokalität ≠ Signalübertragung. Die Korrelation war immer
im gemeinsamen Führungsfeld kodiert. Keine Kausalitätsverletzung.

**5. Dekohärenz bricht topologische Identität (○ MITTEL)**

Umgebungskopplung führt zur effektiven Separierbarkeit des Feldes.
Quantitative Grenze: v3_018.

### 10.2 Formelübersicht

```
Master-Gleichung (v3_001):
  ∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η

  λ-Term = Quelle der Nicht-Separierbarkeit (Verschränkung)
  η = 0 für isolierte Konfiguration ohne externe Anregung

Zwei-Teilchen-Führungsfeld:
  Ψ(x₁, x₂, t) — nicht separierbar bei Verschränkung:
  Ψ(x₁, x₂, t) ≠ Ψ₁(x₁, t) · Ψ₂(x₂, t)

Führungsfeld-Kopplung:
  v₁ = f(∇₁Ψ(x₁, x₂, t) / Ψ(x₁, x₂, t))  [hängt von x₂ ab!]
  v₂ = f(∇₂Ψ(x₁, x₂, t) / Ψ(x₁, x₂, t))  [hängt von x₁ ab!]

Korrelation (✓ HOCH):
  E_RFT(θ_A, θ_B) = -cos(θ_A - θ_B)

Bell-CHSH-Parameter (✓ HOCH):
  S_RFT = 2√2 ≈ 2.828  (> 2, Bell-Verletzung)

Verschränkungs-Entropie (Konfidenz-Indikator, ○ MITTEL):
  S₁ = −Tr(ρ₁ log ρ₁) > 0  ↔  topologische Identität

Kanonische Parameter (✓ HOCH):
  α⁻¹ = 4π³ + π² + π = 137.036 304  [2.22 ppm von CODATA]
  L₀ = 1/κ  [Primärdefinition, ħ-frei!]
  Φ = 2α/(1+α²) ≈ 0.014 596
```

### 10.3 DeepSeek-Aufgaben

```
DS-017-A (Priorität HOCH):
  Zeige aus der Master-Gleichung ohne Hilbertraum-Voraussetzungen:
  Wenn zwei Wirbel durch den λ-Term wechselwirken, kann das
  resultierende Ψ(x₁, x₂) nicht als Produkt Ψ₁(x₁)·Ψ₂(x₂)
  geschrieben werden.
  → J.16: RFT-Brille anlegen!
  → J.23: Mainstream QFT-Argumente (Tensorprodukt, Hilbertraum)
    herausfiltern — RFT-interne Begründung suchen

DS-017-B (optional, nach Franz-Entscheid):
  Welche RFT-interne Größe entspricht der "Topologischen Identität"?
  Windungszahl der Wirbel im ℝ⁶-Konfigurationsraum?
  κ-Modenstruktur? Führungsfeld-Topologie?
```

---

© 2026 Franz Zollner — Resonance Field Theory Project  
Lizenz: Creative Commons BY-NC-SA 4.0  
Kontakt: rft.projekt@posteo.de

---

*Dokument-ID: RFT_v3_017 · Stand: 2026-04-04 · [Mapping zur alten Reihe](../_MAPPING_ALT_NEU.md) · [Style-Guide](../_STYLE_GUIDE.md) · [Repo-Hauptseite](../../../README.md)*
