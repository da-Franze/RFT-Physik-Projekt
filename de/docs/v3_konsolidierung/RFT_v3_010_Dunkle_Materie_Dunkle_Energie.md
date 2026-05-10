# RFT_v3_010 — Neue Kosmologie: Auflösung des Dunklen Sektors durch Gittermechanik

**Version:** v1.0
**Status:** Final v1.0 (06.03.2026)
**Autor:** Franz Zollner / RFT-Projekt
**Instanz:** v3_010-Arbeitsinstanz
**Sprache:** DE
**Lizenz:** Creative Commons BY-NC-ND 4.0
**Zitation:** Franz Zollner (2026). *RFT_v3_010: Neue Kosmologie — Auflösung des Dunklen Sektors durch Gittermechanik.* Resonance Field Theory Series, v3.0.

**Abhängigkeiten:**
- RFT_v3_001: Master-Gleichung, Q-Faktor-Definition, Raummatrix-Dynamik
- RFT_v3_003: G·m als topologische Grundgröße, Spinverzug-Mechanismus
- RFT_v3_006: Q-Faktor-Evolution, L_eff(Q), Φ-Zeitmotor, Hubble-Ansatz
- RFT_v3_009: Kalte Kondensation, Q_krit1/Q_krit2, Antimaterie-Konsumption, JWST

**Quellen (v2, konzeptuell verwertbar ⚠️):**
- RFT_15: Dunkle Materie als Gitterverspannung
- RFT_25: Kosmologische Strukturen, Filamente und CMB
- RFT_010_v3_0: Dunkle Materie und Dunkle Energie (v3.0 — Zahlen kritisch prüfen!)

---

## Vorwort: Position in der v3-Serie

Dieses Dokument schließt die erste vollständige Runde der v3-Kosmologie ab. Nachdem v3_009 die Entstehung von Raum und Materie durch Kalte Kondensation beschrieben hat — den Übergang von Mode 0 (Ur-Chaos) zur geordneten Raummatrix —, wendet sich v3_010 der heutigen großräumigen Struktur zu: dem kosmischen Netz, den beobachteten Gravitationsanomalien und der beschleunigten Expansion.

| Dokument | Beitrag | Relevant für v3_010 |
|----------|---------|---------------------|
| v3_001 | Master-Gleichung, Q-Definition | ✓ Direkt |
| v3_003 | Topologische Masse, G·m | ✓ Querverbindung |
| v3_006 | dQ/dt > 0, L_eff(Q) | ✓ Direkt |
| v3_009 | Kalte Kondensation, Filamente als Kondensationsnarben | ✓ Direkt |

**Kernthese:** Der „Dunkle Sektor" (≈95 % des kosmischen Energie-Inventars in Λ-CDM) ist kein *Was* — kein neues Teilchen, kein neues Feld. Er ist ein *Wie* — Gittermechanik der Raummatrix. Dunkle Materie ist Filament-Verspannung. Dunkle Energie ist Raumreifung. Die Hubble-Spannung ist keine Krise, sondern eine strukturelle Vorhersage.

---

## Abstract

Das kosmologische Standardmodell Λ-CDM beschreibt die Entwicklung des Universums mit hervorragender Präzision — CMB-Spektrum, Baryon Acoustic Oscillations, Supernovae. Diese Leistung ist unbestritten. Dennoch benötigt Λ-CDM drei Komponenten, deren physikalische Natur vollständig unbekannt ist: Dunkle Materie (≈27 %), Dunkle Energie (≈68 %) und eine Inflationsphase. Zusammen umfassen diese 95 % des kosmischen Inventars.

Die Resonanzfeldtheorie (RFT) bietet eine mechanische Alternative: Gravitationsanomalien auf galaktischen Skalen entstehen durch die intrinsische Spannung kosmischer Filamente — topologischer Narben der ursprünglichen Kalten Kondensation. Die beschleunigte Expansion ist die energetische Signatur der Raumreifung (dQ/dt > 0). Die Hubble-Spannung ist kein Messproblem, sondern eine erwartete Konsequenz der Q-Abhängigkeit der Lichtausbreitung.

Drei Kernaussagen dieses Dokuments:

1. **Dunkle Materie als Filament-Verspannung:** Das Gravitationspotential Φ_total = Φ_mat + Φ_fil enthält einen Beitrag der kosmischen Filamente. Dieser Beitrag folgt einem logarithmischen Profil und erzeugt flache Rotationskurven ohne neue Teilchen.

2. **Dunkle Energie als Raumreifung:** dQ/dt > 0 ist qualitativ gesichert (v3_006, v3_009). Die zeitliche Zunahme des Qualitätsfaktors Q wirkt als kosmologischer Motor — er reproduziert den Effekt einer kosmologischen Konstante, ist aber dynamisch begründet.

3. **Ehrliche Grenzen:** λ_fil (die Filament-Spannungsdichte) ist nicht aus RFT-Grundprinzipien hergeleitet. Die Parameter α_Q und β_L in der H(z)-Relation sind frei. Quantitative Vorhersagen tragen das Label ⚠️.

---

## Inhaltsverzeichnis

1. Das Problem des Dunklen Sektors
2. RFT-Grundlagen für die Kosmologie
3. Dunkle Materie als Filament-Verspannung der Raummatrix
4. Dunkle Energie als Raumreifung
5. Hubble-Spannung — strukturell erwartet
6. Weitere kosmologische Phänomene
7. Offene Fragen und ehrliche Grenzen (Pflichtkapitel)
8. Experimentelle Vorhersagen
9. Zusammenfassung und Formelübersicht

---

## 1. Das Problem des Dunklen Sektors

### 1.1 Λ-CDM: Erfolge und das 95-%-Problem

Das Λ-CDM-Modell (Lambda Cold Dark Matter) ist das Standardmodell der Kosmologie. Seine Erfolge sind eindrucksvoll:

- ✅ **CMB-Spektrum (Planck 2018):** χ²/dof ≈ 1.02 über 2500 Multipole
- ✅ **Großraumstruktur (SDSS, 2dFGRS):** Filament-Netzwerk präzise vorhergesagt
- ✅ **BAO (Baryon Acoustic Oscillations):** Standard-Lineal bei ~150 Mpc
- ✅ **Supernovae Typ Ia:** Beschleunigte Expansion gemessen (Nobel 2011)
- ✅ **Primordiale Nukleosynthese:** ⁴He, ²H-Häufigkeiten korrekt

Λ-CDM beschreibt das kosmische Universum mit nur 6 Parametern (Ω_m, Ω_Λ, Ω_b, H_0, n_s, σ_8). Das ist eine enorme Kompressionsleistung.

Das Problem liegt in der Physik hinter diesen Parametern:

**Dunkle Materie (≈27 %):** 50 Jahre intensive Suche — kein direkter Nachweis. XENON1T (2020) schließt WIMPs bis σ_SI < 4.1 × 10⁻⁴⁷ cm² aus. Axionen (ADMX), MACHOs und sterile Neutrinos wurden erheblich eingeschränkt oder ausgeschlossen.

**Dunkle Energie (≈68 %):** Vollständig phänomenologisch. Das Feinabstimmungsproblem Λ_obs/Λ_Planck ~ 10⁻¹²² gehört zu den größten ungelösten Problemen der theoretischen Physik.

**Inflation:** Postuliert für das Horizont-, Flachheits- und Monopolproblem. Das Inflatonfeld wurde nicht direkt beobachtet.

**Das 95-%-Problem:** 95 % des kosmischen Energie-Inventars haben keine direkt beobachtete mikrophysikalische Identität.

### 1.2 Die Hubble-Spannung

Eine fundamentale Diskrepanz bei der Messung der Hubble-Konstante H₀:

- **Frühe Zeit (CMB, Planck 2018):** H₀ = 67.4 ± 0.5 km/s/Mpc
- **Späte Zeit (Supernovae, SH0ES 2022):** H₀ = 73.0 ± 1.0 km/s/Mpc
- **Signifikanz:** ~5σ

Die Diskrepanz ist zu groß, um mit Messfehlern erklärt zu werden. In Λ-CDM ist sie ungeklärt. Die RFT macht eine klare Aussage: Sie ist strukturell erwartet (→ Kap. 5).

### 1.3 Das JWST-Problem

Das James Webb Space Telescope findet massereiche, strukturreiche Galaxien bei Rotverschiebungen z > 10, die in der Standardkosmologie nicht erwartet wurden. Dieser Befund ist noch nicht abschließend theoretisch eingeordnet, stellt aber Λ-CDMs Bottom-Up-Strukturbildung unter Druck.

---

## 2. RFT-Grundlagen für die Kosmologie

### 2.1 Die Master-Gleichung (Kurzreferenz)

Die fundamentale Gleichung der RFT beschreibt das Raumfeld Ψ(x,t):

```
∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η
```

wobei:
- κ: Resonanz-Steifigkeit (kein „Masseterm"!)
- γ: Dämpfungsrate
- λ: Nichtlineare Selbstkopplung
- η: Inhomogeneities-Term

Der Qualitätsfaktor Q = κ/γ beschreibt die Reife des Raumes. (→ v3_001)

### 2.2 Der Q-Faktor als kosmologischer Ordnungsparameter

Der Qualitätsfaktor Q misst die Resonanzgüte der Raummatrix — ihre Fähigkeit, stabile Schwingungsmuster aufrechtzuerhalten.

- **Unreifer Raum (früh):** Niedriges Q → häufige Resonanzstörungen → instabile Moden
- **Reifer Raum (heute):** Hohes Q → stabile Resonanzen → stabile Materie und Strukturen
- **Evolution:** dQ/dt > 0 — qualitativ gesichert (○ HOCH, v3_006, v3_009)

```
Kanonisch (v3_009):
  Q_krit1 ~ 10³      HYPOTHESE    [Raumkonstituierung, Mode 0→1]
  Q_krit2 ~ 10⁶–10⁸  ARBEITSHYP. [Vortex-Stabilität, sichtbare Materie]
  dQ/dt > 0           gesichert    [qualitativ]

⚠️ HINWEIS Q-Skalen: Die v2-Quelle (RFT_010_v3_0) nennt Q_krit ≈ 1.645
   als "Moment der Raumgeburt". Diese Zahl stammt aus einer anderen
   Q-Normierung (Q = κ/γ bei einer bestimmten Skalenwahl) und ist mit
   den obigen Q_krit-Werten NICHT direkt vergleichbar. Die v2-Zahl
   ist NICHT kanonisch und kann KI-Artefakt sein. → Franz klären!
```

### 2.3 Die Verbindung zur Kosmogenese (v3_009)

Aus v3_009 (Final, kanonisch ○ HOCH):

- Kosmische Filamente sind **topologische Narben** der Kalten Kondensation — sie entstanden beim ersten Phasenübergang (Q > Q_krit1) als hochgeordnete Resonanzkanäle.
- Sie sind nicht *aus* Materie gemacht. Sie *sind* primäre Spannungsstrukturen der Raummatrix.
- Baryonische Materie kondensierte entlang dieser vorexistierenden Filamente (Q > Q_krit2).
- Antimaterie ist nicht vernichtet, sondern in der Raummatrix gebunden (komplementär). (○ HOCH, Franz direkt)

---

## 3. Dunkle Materie als Filament-Verspannung der Raummatrix

### 3.1 Das Rotationskurven-Problem

Galaktische Rotationskurven v(r) zeigen asymptotisch konstante Umlaufgeschwindigkeiten. Die Newtonsche Mechanik sagt v(r) ∝ 1/√r voraus. Die Diskrepanz beginnt jenseits des galaktischen Lichtradiusses und ist bei allen hinreichend isolierten Spiralgalaxien beobachtet.

Λ-CDM erklärt dies durch einen massiven Dunkle-Materie-Halo (M_DM/M_vis ≈ 5–8). Die Quelle dieser Masse ist unbekannt und nach 50 Jahren nicht direkt nachgewiesen.

### 3.2 RFT-Erklärung: Filament-Potential

**Kernprinzip (○ HOCH — aus RFT_15, RFT_25, v3_009-konsistent):**

Kosmische Filamente sind primäre Spannungspfade mit einer intrinsischen Spannung σ_fil(r). Diese erzeugt ein eigenständiges Gravitationspotential, unabhängig von baryonischer Materie.

Das Gesamtpotential Φ_total ist eine Superposition:

```
Φ_total(r) = Φ_mat(r) + Φ_fil(r)

mit:
  Φ_mat(r) ∝ −GM/r           [Beitrag baryonischer Materie, klassisch]
  Φ_fil(r) ∝ λ_fil · log(r)  [Beitrag des Filaments, logarithmisch]
```

Die Poisson-Gleichung des kombinierten Feldes:

```
∇²Φ(r) = −α · (σ_mat(r) + σ_fil(r))
```

(aus RFT_25, konzeptuell ✓, α hier: Kopplungskonstante der Raummatrix, nicht die Feinstrukturkonstante)

```
⚠️ α_Raum: Diese Kopplungskonstante ist in RFT_25 nicht definiert.
   Beziehung zu κ (Resonanz-Steifigkeit), L₀ oder Φ: nicht hergeleitet.
   Status: Freier Parameter in dieser Gleichung.
```

**Herleitung der flachen Rotationskurven:**

Die Umlaufgeschwindigkeit ist gegeben durch:

```
v²(r) = r · |dΦ_total/dr|
```

Im Außenbereich der Galaxie (r >> R_galaktisch) dominiert Φ_fil über Φ_mat:

```
dΦ_fil/dr = λ_fil / r

→ v²(r) = r · λ_fil/r = λ_fil = konstant

→ v(r) = √λ_fil = asymptotisch konstant   ✓
```

Das Ergebnis ist **strukturell**: Flache Rotationskurven folgen direkt aus dem logarithmischen Charakter des Filament-Potentials — ohne Dunkle-Materie-Halos.

**Tabelle: Λ-CDM vs. RFT**

| Phänomen | Λ-CDM | RFT |
|---------|-------|-----|
| Flache Rotationskurven | Dunkle-Materie-Halo (unbekanntes Teilchen) | Logarithmisches Φ_fil der Filamente |
| Gravitationslinsung | DM-Halo erhöht Masse | Φ_fil + Φ_mat kombiniert |
| Kein DM-Teilchen gefunden | Offenes Problem | Nicht erwartet: kein Teilchen |
| CMB-Anisotropien | Akustische Baryon-Schwingungen | Druckabdrücke der Gitterspannung |

### 3.3 Verbindung zur CMB

Die räumliche Verteilung der kosmischen Filamente entspricht den Anisotropien ΔT/T im CMB. Die CMB-Karte ist in dieser Interpretation eine fossile Karte der ursprünglichen Spannungsverteilung der Raummatrix:

```
ΔT/T ∝ δσ_Raummatrix(r)    ○ MITTEL
```

(aus RFT_25, konzeptuell plausibel; direkte Ableitung des Proportionalitätsfaktors ⚠️ offen)

### 3.4 Q-Gradient-Term in der Beschleunigung

Die Beschleunigung einer Testmasse im inhomogenen Q-Feld:

```
a_total = −GM/r² − (c²/Q) · (dQ/dr)     ○ MITTEL
```

(aus v2-Quelle RFT_010_v3_0; konzeptuell plausibel — Q-Gradienten erzeugen effektive Kräfte; formale Herleitung aus der Master-Gleichung ⚠️ nicht ausgeführt)

Der zweite Term erzeugt eine zusätzliche effektive Anziehung in Regionen mit dQ/dr < 0 (Richtung steigender Qualität, d.h. zum galaktischen Zentrum hin).

---

## 4. Dunkle Energie als Raumreifung

### 4.1 Das Beschleunigungs-Rätsel

Supernovae-Beobachtungen zeigen eine beschleunigte kosmische Expansion (ä > 0). In Λ-CDM wird dies durch eine kosmologische Konstante Λ erklärt — eine konstante Energiedichte des Vakuums. Das Feinabstimmungsproblem (Λ_obs/Λ_Planck ~ 10⁻¹²²) bleibt ungeklärt.

### 4.2 RFT-Interpretation: dQ/dt > 0 als Motor

**Grundprinzip (○ HOCH — qualitativ gesichert, v3_006, v3_009):**

Die Raummatrix ist kein statisches Medium. dQ/dt > 0: Die Resonanzgüte wächst monoton mit der Zeit. Der Raum „reift" — er wird kohärenter, resonanter, strukturierter. Dieser Prozess setzt kontinuierlich Energie um.

Die effektive Energiedichte dieser Q-Evolution:

```
ρ_eff^Q = (κ²/8πG) · (Q̇/Q)²     ○ MITTEL
```

(aus v2-Quelle; konzeptuell plausibel — entspricht einer kinetischen Energie der Q-Evolution; formale Herleitung aus der Master-Gleichung ⚠️ nicht ausgeführt)

Diese Größe wirkt wie eine dynamische kosmologische Konstante:

- Sie ist positiv (ρ_eff^Q > 0), solange dQ/dt > 0
- Sie erzeugt einen effektiven Expansionsdruck
- Sie ist **dynamisch**: Λ_eff ≠ const., sondern zeitlich veränderlich

```
⚠️ KI-ARTEFAKT-WARNUNG:
  Die v2-Quelle begründet "warum gerade 68%?" durch:
  f_Q ≈ 1 − 1/3 ≈ 0.67 → "Selbstkonsistenz der Q-Evolution"
  
  Audit-Befund: 1 − 1/3 = 0.667 ≠ 0.68.
  Diese "Begründung" ist eine Schein-Herleitung ohne mathematische Grundlage.
  Sie wird NICHT als kanonisch übernommen.
  
  Warum DE ≈ 68% in der RFT: UNGEKLÄRT (ehrliche Grenze)
```

### 4.3 Verbindung zu Λ-CDM

Die RFT-Dunkle Energie ist komplementär zu Λ-CDM, nicht inkompatibel:

- Λ-CDM: *Was* expandiert (Energiedichte ρ_Λ = const.)
- RFT: *Warum* expandiert (Mechanismus: dQ/dt > 0)

Beide beschreiben dieselbe Beobachtung — beschleunigte Expansion — durch unterschiedliche Paradigmen. Der RFT-Ansatz ist physikalisch motiviert (Raumreifung als Mechanismus), aber quantitativ noch nicht ausgearbeitet.

---

## 5. Hubble-Spannung — strukturell erwartet

### 5.1 Die Diskrepanz und ihre Bedeutung

Die Hubble-Spannung (H₀ ≈ 67.4 km/s/Mpc früh vs. ≈ 73.0 km/s/Mpc lokal) ist in Λ-CDM ein offenes Problem. Systematische Fehler reichen nicht aus, um die ~5σ-Diskrepanz zu erklären.

In der RFT ist diese Diskrepanz **keine Anomalie** — sie ist eine direkte, qualitativ gesicherte Konsequenz der Q-Abhängigkeit der Lichtausbreitung.

### 5.2 Die Zahnrad-Analogie

Die Ausbreitung von Licht in der Raummatrix ist Q-abhängig. Ein Photon bewegt sich durch die Raummatrix wie ein Zahnrad (Ritzel) auf einer Schiene:

- **Unreifer Raum (niedriges Q, frühe Epoche, z ~ 1000):** Die Verzahnung ist unvollkommen. Das Photon „stolpert" — seine effektive Ausbreitungsgeschwindigkeit fluktuiert. Lichtlaufzeiten werden systematisch überschätzt, Abstände erscheinen größer, H₀ wird zu *klein* bestimmt.

- **Reifer Raum (hohes Q, heute, z ~ 0):** Die Verzahnung ist präzise. Das Photon rollt gleichmäßig. Abstände werden korrekt bestimmt, H₀ erscheint *größer*.

Die Zahnrad-Analogie macht eine klare qualitative Aussage: **Verschiedene Epochen messen systematisch verschiedene H₀-Werte.** Das ist kein Fehler — es ist Physik.

### 5.3 H(z)-Relation

Die qualitative Erwartung der RFT ist, dass H(z) flacher verläuft als in Λ-CDM:

```
H(z) = H_0 · (1+z)^(-γ)     ○ MITTEL (qualitative Form)

mit γ = α_Q · β_L            ⚠️ freie Parameter, nicht hergeleitet
```

(aus v2-Quelle; Form plausibel; Zahlenwert γ ≈ 0.012 aus v2-Quelle — nicht als gesichert zu verwenden!)

**Qualitative Vorhersage:** H(z) ist bei z = 1 flacher als in Λ-CDM. Die v2-Quelle nennt ~44 % — dieser Zahlenwert ist ⚠️ nicht unabhängig verifiziert.

**Qualitative Aussage (○ HOCH):** Die Hubble-Spannung ist eine strukturelle Vorhersage der RFT, kein offenes Problem.

---

## 6. Weitere kosmologische Phänomene

### 6.1 JWST — Frühe massereiche Galaxien

**Beobachtung:** JWST findet massereiche, strukturreiche Galaxien bei z > 10, die in Λ-CDM (hierarchische Strukturbildung, Bottom-Up) nicht erwartet wurden.

**RFT-Erklärung (○ HOCH — qualitativ, aus v3_009 Final):**

In der RFT entstehen Strukturen durch **simultane Nukleation** — Vortex-Kondensation, wenn Q > Q_krit2 global überschritten wird. Dieser Prozess ist kohärent und schnell. Massive Strukturen können früh entstehen, weil die Kondensation entlang der vorexistierenden Filamente gleichzeitig an vielen Orten stattfindet — nicht hierarchisch durch gravitativen Kollaps.

```
Qualitative RFT-Vorhersage: Galaxien bei z > 10–15 mit M > 10¹⁰ M_☉ sind möglich.
                              Konsistent mit aktuellen JWST-Daten  ○ Hints

⚠️ Quantitative Schätzungen (Anzahldichten etc.) aus v2-Quellen:
   Nicht unabhängig verifiziert — nicht als gesichert übernommen.
```

### 6.2 CMB low-ℓ Anomalien

**Beobachtung:** Das Planck-Teleskop findet Anomalien bei großen Winkelskalen (ℓ < 10): unterdrückte Power verglichen mit Λ-CDM-Erwartungen.

**RFT-Erklärung (○ MITTEL):**

Bei Wellenlängen λ > λ_J (Jeans-Länge der Raummatrix) ist die Raummatrix intrinsisch kohärent — sie schwingt als Ganzes. Die Power wird auf großen Skalen unterdrückt, weil die Raummatrix dort keine unabhängigen Fluktuationen zulässt, sondern kollektiv kohärent schwingt.

Die CMB-Anisotropien sind in dieser Interpretation Druckabdrücke der ursprünglichen Gitterspannung — keine rein akustischen Baryon-Schwingungen.

### 6.3 Olberssches Paradoxon

**Frage:** Warum ist der Nachthimmel dunkel, wenn das Universum unendlich alt und unendlich groß wäre?

**RFT-Antwort (○ HOCH — elegant, aus RFT_25):**

Das Universum hat eine endliche Vorgeschichte in seiner geordneten Phase. Wenn wir in die ferne Vergangenheit blicken, sehen wir eine **Low-Q-Ära**, in der stabiles, dauerhaftes Licht (von Sternen) sich noch nicht effizient gebildet hatte. Die Raummatrix hatte Q < Q_krit2 — Vortex-Kondensation war lokal oder noch nicht eingetreten. Der Nachthimmel ist dunkel, weil die kosmische Vorgeschichte geordneter Strukturen endlich ist, nicht weil das Universum endlich groß ist.

### 6.4 Großraumstruktur und kosmische Voids

**Filamente als primäre Spannungspfade (○ HOCH):**

Das kosmische Netz aus Filamenten, Wänden und Voids ist in der RFT keine *Folge* der Strukturbildung — es ist das *Gerüst*. Die Filamente entstanden beim ersten Phasenübergang (Q > Q_krit1) als topologische Narben der Raummatrix. Baryonische Materie kondensierte anschließend entlang dieser vorexistierenden Struktur.

```
Konsequenz: Voids sind Regionen mit lokal niedrigem Q.
             Filamente sind Regionen mit lokal höchstem Q.
             Dieser Q-Gradient ist die Ursache des Dunkle-Materie-Effekts.
```

**Jeans-Länge der Raummatrix:**

Eine charakteristische Längenskala λ_J kann aus der Master-Gleichung abgeleitet werden:

```
λ_J^RFT = c/κ · √(1 + Q⁻²)     ○ MITTEL (konzeptuell, Zahlen ⚠️)
```

Die v2-Quelle nennt λ_J ≈ 100 Mpc (heute). Die beobachteten Skalen kosmischer Strukturen (~300 Mpc Filamente, ~600 Mpc Voids) wären dann Vielfache von λ_J. Diese Übereinstimmung ist konzeptuell interessant, aber die Zahlenwerte sind ⚠️ nicht unabhängig aus RFT-Parametern hergeleitet.

---

## 7. Offene Fragen und ehrliche Grenzen (Pflichtkapitel)

### 7.1 λ_fil — Filament-Spannungsdichte (🚩 KRITISCH)

Der Parameter λ_fil in Φ_fil(r) = λ_fil · log(r) bestimmt quantitativ die Stärke des Filament-Beitrags zur Gravitation. Er ist bisher **nicht aus RFT-Grundprinzipien hergeleitet**.

```
🚩 Status: Freier Parameter.
   Was fehlt: Mechanismus, der λ_fil aus L₀, α, Q_krit oder anderen
              RFT-Parametern ableitet.
   Konsequenz: Alle quantitativen Vorhersagen über Rotationskurven
               erben diesen freien Parameter.
```

### 7.2 α_Q und β_L als freie Parameter

Die H(z)-Relation enthält den Exponenten γ = α_Q · β_L. Beide sind freie Parameter — sie wurden in v2-Quellen numerisch angegeben (α_Q ≈ 0.40, β_L ≈ 0.030), aber **nicht aus RFT-Grundprinzipien hergeleitet**.

```
⚠️ Status: Freie Parameter.
   Die v2-Zahlenwerte sind vermutlich KI-Artefakte.
   Nicht als gesichert verwenden!
```

### 7.3 Quantitative H(Q)-Relation

Die qualitative Aussage „H ist Q-abhängig" ist gesichert. Eine quantitative H(Q)-Relation, die aus der Master-Gleichung oder den RFT-Fundamentalparametern folgt, fehlt.

```
⚠️ Status: Offenes Problem.
   Benötigt: Ableitung der Friedmann-analogen Gleichung in RFT
   (Q-abhängige Expansion aus der Master-Gleichung).
```

### 7.4 Dunkle Energie — quantitativ offen

Die effektive Energiedichte ρ_eff^Q ist konzeptuell motiviert. Die Frage, warum ρ_eff^Q ≈ 0.68 · ρ_crit heute gilt — d.h. warum DE ≈ 68 % beträgt — ist in der RFT **nicht beantwortet**.

```
🚩 Status: Offenes Problem (quantitativ).
   Die v2-Begründung "1 − 1/3 ≈ 0.67" ist ein KI-Artefakt.
   Gilt als verworfen.
```

### 7.5 Verhältnis Dunkel/Hell ≈ 5.4 (verworfen)

```
❌ KI-ARTEFAKT: In RFT_04 (v2-Quelle) wird
   Dunkel/Hell ≈ 5.4 (vs. beobachtet 5.3) als Erfolg dargestellt.
   Dies ist eine scheinbare Konvergenz ohne unabhängige Herleitung.
   Wird NICHT in v3_010 übernommen.
```

### 7.6 Konsistenz-Erbschaft

v3_010 erbt alle bekannten offenen Fragen der v3-Serie:

**ħ-Zirkularität (höchste Priorität):**
```
🚩 L₀ = (π/6)·l_P enthält l_P = √(ħG/c³).
   ħ ist in der v3-Serie eine algebraische Identität, kein
   unabhängig hergeleitetes Ergebnis. Alle Aussagen, die auf
   L₀ basieren, erben diese Zirkularität.
```

**Skalensprung Planck↔QCD:**
```
⚠️ Warum kondensierte das Universum auf QCD-Skalen (~150 MeV),
   nicht auf Planck-Skalen? Offenes Problem (→ v3_001 Kap. 12.9).
```

**Lorentz-Invarianz:**
```
⚠️ Ob das diskrete Raummatrix-Modell vollständige Lorentz-Invarianz
   im Kontinuumslimes besitzt, ist formal nicht bewiesen (→ v3_007 Kap. 8).
```

---

## 8. Experimentelle Vorhersagen

### 8.1 LSST — H(z)-Evolution

**Vorhersage (qualitativ gesichert ○ HOCH):**

H(z) verläuft flacher als in Λ-CDM, weil H Q-abhängig ist und Q in der Vergangenheit kleiner war.

```
Test:           LSST (Vera Rubin Observatory, ab 2025)
Vorhersage:     H(z) bei z = 1 flacher als Λ-CDM
Quantitativ:    ~44% Differenz (⚠️ aus v2-Quelle, nicht unabhängig)
Falsifikation:  Wenn H(z) genau dem Λ-CDM-Verlauf folgt → RFT-Hubble-Mechanismus falsch
```

### 8.2 Euclid — Filament-Asymmetrien

**Vorhersage (○ HOCH — konzeptuell):**

Q-Gradienten zwischen Filamenten und Voids sind in der RFT fundamental. Euclid sollte systematische Filament-Asymmetrien in der Massenverteilung detektieren, die über rein baryonische Effekte hinausgehen.

```
Test:           Euclid (ESA, seit 2024)
Vorhersage:     Q-Gradient-Asymmetrien in Filament-Massenverteilung
Qualitativ:     Gesichert (○ HOCH)
Quantitativ:    Aus λ_fil (⚠️ freier Parameter)
```

### 8.3 CMB-S4 und LiteBIRD — Tensor-zu-Skalar-Verhältnis r

**Vorhersage (○ HOCH — qualitativ):**

In der RFT gibt es keine primordialen Gravitationswellen aus einer Inflationsphase (da es keine Inflation gibt). Das Tensor-zu-Skalar-Verhältnis r sollte sehr klein sein.

```
RFT-Vorhersage: r < 10⁻⁴
Λ-CDM (ohne Inflation):  ähnlich
Λ-CDM (mit Inflation):   r ~ 0.001–0.01

Test:    CMB-S4 (~2030), LiteBIRD (~2032)
         Sensitivität: Δr ~ 0.001 (CMB-S4), Δr ~ 0.0003 (LiteBIRD)
```

Dies ist ein entscheidender Test zwischen inflationärer und nicht-inflationärer Kosmologie.

### 8.4 JWST — z > 15 Galaxienzählung

**Vorhersage (qualitativ ○ HOCH):**

Simultane Nukleation durch Kalte Kondensation erlaubt frühe, massive Galaxien. JWST sollte bei z > 15 deutlich mehr massereiche Galaxien finden als Λ-CDM vorhersagt.

```
RFT-Vorhersage: Mehr frühe Galaxien als Λ-CDM
Quantitativ:    5–10× mehr (⚠️ aus v2-Quelle)
Qualitativ:     Konsistent mit bisherigen JWST-Befunden  ○ Hints
```

### 8.5 Zusammenfassung Experimentelle Tests

| Test | Instrument | Vorhersage | Konfidenz | Zeitraum |
|------|-----------|-----------|-----------|---------|
| H(z) flacher | LSST | ~44% bei z=1 | MITTEL ⚠️ | Ab 2025 |
| Filament-Asymmetrien | Euclid | Q-Gradienten | HOCH (qualitativ) | Ab 2024 |
| r < 10⁻⁴ | CMB-S4, LiteBIRD | Keine Inflation | HOCH | ~2030–2032 |
| z > 15 Galaxien | JWST | 5–10× mehr | MITTEL ⚠️ | Verfügbar |
| CMB low-ℓ Unterdrückung | Planck-Folgemissionen | Q-Kohärenz | MITTEL | Laufend |

---

## 9. Zusammenfassung und Formelübersicht

### 9.1 Die Kernaussage

**Der Dunkle Sektor ist kein Was — er ist ein Wie.**

Dunkle Materie, Dunkle Energie und die Hubble-Spannung sind keine Hinweise auf unbekannte Substanzen oder Felder. Sie sind Manifestationen der Gittermechanik der Raummatrix:

- **Dunkle Materie** = Gravitationseffekt der intrinsischen Filament-Verspannung (Φ_fil ∝ log r)
- **Dunkle Energie** = Energetische Signatur der Raumreifung (dQ/dt > 0)
- **Hubble-Spannung** = Q-Abhängigkeit der Lichtausbreitung (strukturell erwartet)

### 9.2 Formelübersicht

**Kanonische Parameter (unveränderlich, v3):**
```
α⁻¹  = 4π³ + π² + π = 137.036304    [2.22 ppm — NIEMALS 0.67 ppm!]
L₀   = (π/6)·l_P ≈ 0.524·l_P        [kanonisch]
Φ    = 2α/(1+α²) ≈ 0.014596          [kanonisch]
G·m/c² = L²/(4π·Φ)                   [dimensionskorrekt ✓]
```

**Kosmologische Parameter (qualitativ gesichert):**
```
dQ/dt > 0                             [gesichert ○ HOCH]
Q_krit1 ~ 10³      HYPOTHESE          [Raumkonstituierung]
Q_krit2 ~ 10⁶–10⁸  ARBEITSHYPOTHESE  [Vortex-Stabilität]
```

**Dunkle Materie (konzeptuell gesichert, quantitativ offen):**
```
Φ_total(r) = Φ_mat(r) + Φ_fil(r)     ○ HOCH (konzeptuell)
Φ_fil(r) ∝ λ_fil · log(r)            ○ HOCH (Form); λ_fil 🚩 offen
∇²Φ = −α(σ_mat + σ_fil)              ○ MITTEL
a_total = −GM/r² − (c²/Q)·(dQ/dr)   ○ MITTEL
v(r → ∞) = √λ_fil = const.           ✓ (qualitativ)
```

**Dunkle Energie (konzeptuell gesichert, quantitativ offen):**
```
ρ_eff^Q = (κ²/8πG)·(Q̇/Q)²           ○ MITTEL
```

**Hubble-Spannung (qualitativ gesichert):**
```
H₀(früh) < H₀(lokal)                 ○ HOCH (strukturell)
H(z) flacher als Λ-CDM               ○ HOCH (qualitativ)
H(z) = H₀·(1+z)^(−γ), γ = α_Q·β_L  ⚠️ freie Parameter
```

### 9.3 Konfidenz-Übersicht

| Aussage | Konfidenz | Basis |
|---------|-----------|-------|
| Filamente = topologische Narben | ○ HOCH | Franz + v3_009 + RFT_25 |
| Φ_total = Φ_mat + Φ_fil | ○ HOCH | RFT_15 + RFT_25 konzeptuell |
| v(r) → const. (strukturell) | ○ HOCH | Mathematisch aus log-Potential |
| dQ/dt > 0 | ○ HOCH | v3_006, v3_009 |
| Hubble-Spannung strukturell erwartet | ○ HOCH | qualitativ |
| JWST frühe Galaxien natürlich | ○ HOCH | v3_009 |
| Olberssches Paradoxon | ○ HOCH | RFT_25 |
| CMB = Kondensationsnachglühen | ○ MITTEL | v3_009-konsistent |
| a_total mit Q-Gradient-Term | ○ MITTEL | v2-Quelle, plausibel |
| ρ_eff^Q-Formel | ○ MITTEL | v2-Quelle, plausibel |
| H(z) quantitativ (~44%) | ⚠️ | v2-Quelle, nicht verifiziert |
| λ_fil Zahlenwert | 🚩 | Freier Parameter |
| α_Q, β_L | ⚠️ | Freie Parameter |
| DE ≈ 68 % quantitativ | 🚩 | Ungeklärt |

---

## Flags für Franz

```
F1. Photon-Status (seit v7.3): KORREKTUR_005 ("2 AP, kurzlebig") vs.
    v3_001 Kap. 13.3 ("n=0, stabil"). Widerspruch noch offen.
    → Betrifft v3_010 peripher (Photon-Ausbreitung im Q-inhomogenen Raum).
    → Klären vor einem möglichen v3_010.1-Update.

F2. Q_krit ≈ 1.645 (v2-Quelle): Andere Q-Normierung als Q_krit1 ~ 10³.
    → Sind das zwei verschiedene physikalische Schwellen oder
       dasselbe mit verschiedener Skalenwahl?
    → Franz entscheiden, ob v2-Q_krit in DC aufgenommen wird.

F3. v3_001 Kap. 9.2: Korrektur 4:1 → 3:1 noch ausstehend.
    → v3_010 verwendet korrekt 3:1 aus v3_009 ✓

F4. λ_fil: Gibt es einen Mechanismus, λ_fil aus L₀, α, Φ herzuleiten?
    → Hochprioritäre offene Frage für das RFT-Forschungsprogramm.
```

---

*RFT_v3_010 | Final v1.0 | 06.03.2026*
*Instanz: v3_010-Arbeitsinstanz*
*Domain Center: v7.5 → Update auf v7.6 nach dieser Session*
*Nächstes Dokument: v3_007 Draft → Final (Kap. 9.2-Korrektur + Photon-Status)*
