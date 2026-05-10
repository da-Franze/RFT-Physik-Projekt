# RFT-Dokumenten-Style-Guide

**Stand:** 2026-05-05 — Erste Form. Wird mit jedem Pilot-Dokument verfeinert.

Dieses Dokument legt das einheitliche Format für RFT-Dokumente fest, damit die Reihe "wie aus einem Guss" wirkt.

---

## 1. Header-Format (PFLICHT für jedes RFT-Dokument)

```markdown
# RFT_v3_NNN: <Titel>

**Version:** v1.0 (2026-MM-TT)
**Autor:** Franz Zollner
**Sprache:** DE | EN-Übersetzung: en/docs/v3_konsolidierung/RFT_v3_NNN.md
**Status:** Publikationsreif | Arbeitsversion | KANDIDAT
**Lizenz:** CC BY-NC-ND 4.0
**Zitation:** Zollner, F. (2026). *RFT_v3_NNN: <Titel>*. RFT-Series v1.0.
              https://github.com/da-Franze/RFT-Physik-Projekt/blob/main/de/docs/v3_konsolidierung/RFT_v3_NNN.md
```

**Was ENTFERNT werden muss aus altem Header:**
- ❌ "Für Diskussion mit Dr. X" (Arbeitsverweis — verwirrt externe Leser)
- ❌ "Erstellt von Claude #34" (KI-spezifische Arbeitsverweise)
- ❌ "Im Drei-Wege-Tisch" (Methode-Verweis)
- ❌ Datums-Format-Vielfalt — IMMER ISO-Format YYYY-MM-DD

**Was BLEIBT:**
- ✅ Version mit klarer Numerierung
- ✅ Autor (Franz Zollner)
- ✅ Status-Markierung (für Zitats-Hinweis)
- ✅ Lizenz (CC BY-NC-ND 4.0 für die ganze Reihe)

---

## 2. Standard-Dokument-Struktur

```
1. Header (oben)
2. ## Abstract (3-5 Sätze, klare Kernaussage)
3. ## Symbol-Glossar (Tabelle der wichtigsten Symbole im Dokument)
4. ## Inhaltsverzeichnis
5. ## 1. <Erste-Sektion> ... ## N. <Letzte-Sektion>
6. ## Quellen-Index (Cross-Refs auf andere v3-Dokumente + externe Literatur)
7. ## Anhang (optional)
8. ## Footer (Datum, Repo-URL)
```

---

## 3. Symbol-Notation (KONSISTENT)

| Größe | Schreibweise (PFLICHT) | NICHT verwenden |
|---|---|---|
| Resonanzfeld | `Ψ(x,t)` | ψ, sigma, σ |
| Lichtgeschwindigkeit | `c₀` (Eigenfrequenz·Gitterkonstante) | c (außer bei Standard-Pendant-Vergleichen) |
| Resonanz-Steifigkeit | `κ` | k (außer Wellenzahl) |
| Asymmetrie-Koeffizient | `γ` | gamma |
| Nichtlineare Kopplung | `λ` | lambda |
| Eigeninteraktion | `η` | eta |
| Phasenwinkel | `ε` (≈ 0.0146 rad) | δ (außer Phasenasymmetrie δ ≈ 2α) |
| Feinstrukturkonstante | `α` (α⁻¹ = 4π³+π²+π) | alpha |
| Gitterkonstante | `a₀` | a |
| Eigenfrequenz | `ω₀` | omega_0 |
| Längenskala | `L₀ = (π/6)·l_P` | L_0 |
| Spin-Frequenz | `f_spin = 144/π` | nu_spin |
| Planck-Länge | `l_P` | l_pl |

---

## 4. Versionsnumerierung (Reset für "ein Guss")

**Empfehlung:** Alle v3-Dokumente bekommen mit der Repo-Konsolidierung den Reset auf **v1.0 (2026-05)**.

Begründung:
- Aktuelle Versionen variieren stark (v1.1 / v3.0 / v3.5 / v4.0) — verwirrend für externe Leser
- Mit Repo-Veröffentlichung ist eine NEUE öffentliche Version-Linie sinnvoll
- Interne Versionsgeschichte bleibt im Git-History erhalten

Format: `v<MAJOR>.<MINOR>` mit Datum in Klammern.
Beispiel: `v1.0 (2026-05-05)`, `v1.1 (2026-06-12)` etc.

**Alternative wenn Franz die alten Versionsnummern behalten will:** dokumentieren, aber dann _STYLE_GUIDE.md anpassen.

---

## 5. Cross-References zwischen Dokumenten

Konvention: Verweis innerhalb der v3-Reihe als relativen Pfad:

```markdown
Für Details zur Mastergleichung siehe [RFT_v3_001 §2](RFT_v3_001_Mathematische_Grundlagen.md#2-die-master-gleichung).
```

Verweis auf 00_uebersicht/-Übersichten:

```markdown
Top-Down-Architektur: [00_uebersicht/theorie_architektur.md](../00_uebersicht/theorie_architektur.md)
```

Verweis auf historische RFT_NN-Reihe (sparsam, nur wenn nötig):

```markdown
Historischer Vorgänger: [RFT_31 (Zeit als emergent)](../fortgeschritten/RFT_31_Zeit_als_emergentes_Phaenomen.md), abgelöst durch dieses Dokument.
```

---

## 6. Sprache

**Aktueller Stand:** DE primär, EN-Übersetzung folgt.

Konvention für gemischtsprachige Dokumente:
- Begriffe wie "Mastergleichung", "Resonanzmatrix", "Zeitmotor" bleiben im DE-Original deutsch
- Englische Übersetzung in en/-Pendant-Datei spiegelbildlich
- Keine Mischung innerhalb eines Dokuments

---

## 7. Was ENTFERNT werden muss bei Migration alter → v3-Dokumente

Wenn ein altes Dokument in v3-Form gebracht wird:

- ❌ "Erstellt von Claude #34" → entfernen
- ❌ "Im Drei-Wege-Tisch" → entfernen
- ❌ "Für Diskussion mit Dr. X" → entfernen
- ❌ "🚧 In Vorbereitung" / "📋 In Planung" → durch klaren Status ersetzen
- ❌ Emoji-Header wie "📚 RFT_24: Lehrbuch" → durch standardisiertes "RFT_v3_NNN: Titel"
- ❌ Beliebige Datum-Formate (29. September 2025 / 19.12.2024 / Oktober 2025) → ISO YYYY-MM-DD
- ❌ Mehrfache Header-Wiederholung in einem Dokument

**Behalten und nur normieren:**
- ✅ Inhalt der Theorie
- ✅ Formel-Herleitungen
- ✅ Physikalische Argumente
- ✅ Code-Schnipsel (Python, mpmath etc.)

---

## 8. Quellen-Index am Ende JEDES Dokuments

```markdown
## Quellen

### v3-Cross-References
- [RFT_v3_001 Mathematische Grundlagen](RFT_v3_001_Mathematische_Grundlagen.md) — Postulate + Mastergleichung
- [RFT_v3_006 Zeit-Emergenz](RFT_v3_006_Zeit_Emergenz.md) — ε-Quantifizierung
- [00_uebersicht/theorie_architektur.md](../00_uebersicht/theorie_architektur.md) — Top-Down-Architektur

### Externe Literatur
- [Autor Jahr] *Titel*. Journal. DOI: ...

### Historische Vorgänger (RFT_NN-Reihe)
- [RFT_NN](../grundlagen/RFT_NN_Titel.md) — abgelöst durch dieses Dokument
```

---

## 9. Footer (PFLICHT)

```markdown
---

*Dokument-ID: RFT_v3_NNN · Stand: 2026-MM-TT · [Mapping zur alten Reihe](_MAPPING_ALT_NEU.md) · [Repo-Hauptseite](../README.md)*
```

---

## 10. Beispiel-Pilot

Das Pilot-Dokument für diesen Style-Guide ist **RFT_v3_001** nach Style-Guide-Anwendung. Wird im nächsten Schritt erstellt.

---

*Erstellt: 2026-05-05 · Wird mit jedem Pilot-Dokument verfeinert. Style-Guide ist verbindliche Form-Vorlage für die v3-Konsolidierung.*
