# 🔬 RFT-Simulationen & Visualisierungen

**Stand:** 2026-05-05 — Erste Aufstellung. Code-Reproduzierbarkeit folgt.

Dieser Ordner sammelt Simulationen und Visualisierungen, die RFT-Konzepte numerisch demonstrieren oder veranschaulichen.

---

## 🌀 Aktuelle Visualisierungen

### 1. z10 Wirbel-Simulation
![z10 Wirbel-Simulation](../../assets/images/z10_wirbel%20simmulation.png)

**Quelle:** z10-Diskussion (RGM-Phase, Februar 2025)
**Beschreibung:** Numerische Simulation einer Wirbelstruktur in der Resonanzfeld-Mastergleichung. Zeigt Soliton-artige Lokalisation als Vorläufer von Teilchen-Wirbeln.
**Bezug zu v3:** [RFT_v3_001 §2.1 Mastergleichung](../v3_konsolidierung/RFT_v3_001_Mathematische_Grundlagen.md), [v3_004 Impuls/Energie](../v3_konsolidierung/RFT_v3_004_Impuls_Energie.md)
**Code:** noch nicht im Repo (war in z10-Chat-Diskussion)

### 2. Spin-Resonanzen-Simulation (RGM)
![Spin-Resonanzen RGM](../../assets/images/Simulation_Spin-Resonanzen_RGM.png)

**Quelle:** RGM-Phase 2025
**Beschreibung:** Simulation der Spin-Resonanz-Verteilung in der diskreten Resonanzmatrix. Zeigt die topologische Quantisierung von Spin-Zuständen.
**Bezug zu v3:** [RFT_v3_003 Gravitation/Spinverzug](../v3_konsolidierung/RFT_v3_003_Gravitation_Spinverzug.md), [v3_001 §10b](../v3_konsolidierung/RFT_v3_001_Mathematische_Grundlagen.md) (drei Messungen von δ ≈ 0.82°)

### 3. Quark-Wirbel-Simulation
![Quark-Wirbel](../../assets/images/Quak-Wirbel_Simulation.png)

**Quelle:** RGM/SRT-Phase 2025
**Beschreibung:** Visualisierung der Quark-Topologie als Drei-AP-Wirbel auf orthogonalen Gitterachsen.
**Bezug zu v3:** [RFT_v3_013 Starke Wechselwirkung](../v3_konsolidierung/RFT_v3_013_Starke_Wechselwirkung.md), Protonenmassen-Herleitung in [v3_001 §8](../v3_konsolidierung/RFT_v3_001_Mathematische_Grundlagen.md)

---

## 📋 Geplante Simulationen (Code-Reproduzierbarkeit)

Für arXiv-Submission und akademische Reviewbarkeit sollten Simulationen mit Quellcode hinterlegt werden:

| Simulation | Bezug | Status |
|---|---|---|
| α-Herleitung 4π³+π²+π | [v3_002](../v3_konsolidierung/RFT_v3_002_Feinstrukturkonstante.md) | ⏳ Code-Snippet existiert (mpmath, 50 Stellen Genauigkeit) |
| Klein-Gordon-Linearisierung | [v3_001 §10.1](../v3_konsolidierung/RFT_v3_001_Mathematische_Grundlagen.md) | ⏳ symbolisch (sympy) implementierbar |
| Schwebungs-Drift (Zeitpfeil) | [v3_001 §10b.2](../v3_konsolidierung/RFT_v3_001_Mathematische_Grundlagen.md) | ⏳ numerisch (numpy) — δ ≈ 1/(8π³) |
| Resonanz-Soliton in Mastergleichung | [v3_001 §2](../v3_konsolidierung/RFT_v3_001_Mathematische_Grundlagen.md) | ⏳ Reproduktion der z10-Wirbel-Sim mit Code |

---

## 🔗 Cross-References

- **Top-Down-Architektur:** [00_uebersicht/theorie_architektur.md](../00_uebersicht/theorie_architektur.md) — wo passen die Simulationen in die Theorie
- **Chronologie:** [00_uebersicht/formel_chronologie.md](../00_uebersicht/formel_chronologie.md) — wann wurden welche Simulationen erstellt
- **v3-Reihe:** [v3_konsolidierung/](../v3_konsolidierung/) — die kanonische Theorie-Form

---

## 💡 Mitarbeit

Wenn du Code für eine der geplanten Simulationen beitragen möchtest:
1. Forke das Repo
2. Lege deinen Code unter `simulationen/<thema>/` ab (mit README.md, code.py, output/)
3. Pull-Request mit Beschreibung der Methode

Kontakt: rft.projekt@posteo.de

---

*Erstellt: 2026-05-05 · Erste Strukturierung der Simulationsecke. Code-Reproduzierbarkeit folgt schrittweise.*
