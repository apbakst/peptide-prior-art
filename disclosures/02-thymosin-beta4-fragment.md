---
title: "Half-Life Extended Thymosin β4 Fragment (LKKTETQ) Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: All Rights Reserved — Copyright 2026 Andrew Bakst
---

# Thymosin β4 Fragment (LKKTETQ): Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**Thymosin β4 (Tβ4)** is a 43-amino acid peptide that is a major actin-sequestering protein. The heptapeptide fragment **LKKTETQ** (residues 17-23 of full-length Tβ4) retains key biological activities including promotion of cell migration, wound healing, and anti-inflammatory effects. This fragment is the minimal active sequence responsible for much of Tβ4's regenerative activity.

- **Native Sequence:** `Leu-Lys-Lys-Thr-Glu-Thr-Gln`
- **Single-Letter Code:** `LKKTETQ`
- **Molecular Weight:** ~834 Da
- **Known Stability Issues:** Multiple trypsin-susceptible sites (after Lys² and Lys³); small size leads to rapid renal clearance; susceptible to aminopeptidases (Leu N-terminal) and carboxypeptidases (Gln C-terminal).

### 1.2 Therapeutic Relevance

The LKKTETQ fragment has demonstrated:
- Promotion of dermal wound healing and hair follicle neogenesis
- Anti-inflammatory activity in ocular surface models
- Cardiac tissue repair post-ischemia (as part of Tβ4 activity)
- Promotion of cell migration via interaction with actin cytoskeleton
- Corneal epithelial wound healing

### 1.3 Problem Statement

As a short linear peptide with two adjacent lysine residues, LKKTETQ is extremely susceptible to trypsin-like serine proteases and exopeptidases. Its estimated in vivo half-life is on the order of minutes. Stabilization is required for any systemic therapeutic application.

## 2. Disclosed Modifications

### 2.1 Variant A — Targeted D-Amino Acid / NMe / Aib

**Modified Sequence:**
```
Ac-[NMe-Leu¹]-Lys²-[D-Lys³]-Thr⁴-[Aib⁵]-Thr⁶-[D-Gln⁷]-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| N-terminus | Free amine | Acetyl cap | Aminopeptidase resistance |
| 1 | Leu | NMe-Leu | N-methylation blocks leucine aminopeptidase; preserves hydrophobic side chain |
| 3 | Lys | D-Lys | Disrupts trypsin recognition at the Lys²-Lys³ dibasic site; the ε-amine remains available for any electrostatic interactions |
| 5 | Glu | Aib | α,α-Dimethyl substitution provides steric protection of the central backbone; Glu side chain is lost but the helix-inducing property of Aib may compensate structurally |
| 7 | Gln | D-Gln + amide cap | D-configuration resists carboxypeptidase A; amidation eliminates the terminal carboxyl |

**Expected Impact:** 3-8× increase in serum half-life.

### 2.2 Variant B — Conservative Modifications (Preserve All Side Chains)

**Modified Sequence:**
```
Ac-[D-Leu¹]-[NMe-Lys²]-Lys³-[NMe-Thr⁴]-Glu⁵-Thr⁶-[D-Gln⁷]-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 1 | Leu | D-Leu + Ac | Terminal protection; D-Leu maintains hydrophobic character |
| 2 | Lys | NMe-Lys | N-methylation at the Lys²-Lys³ junction blocks trypsin without removing either Lys side chain |
| 4 | Thr | NMe-Thr | Breaks the protease-susceptible backbone between the dibasic site and the C-terminal half |
| 7 | Gln | D-Gln + NH₂ | C-terminal protection |

**Expected Impact:** 5-10× increase in serum half-life. All original side chains are preserved.

### 2.3 Variant C — β-Amino Acid Insertion

**Modified Sequence:**
```
Ac-Leu¹-Lys²-[β³-hLys³]-Thr⁴-Glu⁵-Thr⁶-Gln⁷-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 3 | Lys | β³-homoLysine | Insertion of one additional backbone methylene at the critical dibasic site. β³-hLys retains the full butylamine side chain of lysine but the α→β backbone switch eliminates trypsin recognition. This creates a local α/β hybrid that is invisible to trypsin-family proteases |

**Expected Impact:** 5-15× increase specifically at the trypsin-susceptible site. Minimal structural perturbation since only one residue is modified.

## 3. Synthesis Considerations

- Standard Fmoc-SPPS on Rink amide resin
- Fmoc-NMe-Leu-OH and Fmoc-NMe-Lys(Boc)-OH require extended coupling (double coupling, HATU)
- Fmoc-D-Lys(Boc)-OH and Fmoc-D-Gln(Trt)-OH are commercially available
- Fmoc-Aib-OH: double coupling with HATU/DIPEA
- Fmoc-β³-hLys(Boc)-OH: commercially available from specialty suppliers (e.g., Bachem, ChemPep)
- Cleavage: TFA/TIS/H₂O (95:2.5:2.5)

## 4. Disclosed Claims (Patent Rights Reserved)

The following claims are publicly disclosed to establish a date of invention. All patent rights are reserved by the author under the 1-year grace period of 35 U.S.C. § 102(b)(1)(A):

1. Any peptide comprising the sequence LKKTETQ or a conservative variant thereof, wherein one or more amino acid residues are replaced with their D-enantiomer, N-methylated form, α-aminoisobutyric acid, or β-amino acid analog
2. Any peptide of claim 1 wherein the N-terminus is capped (acetyl, formyl, or other) and/or the C-terminus is amidated
3. Any peptide of claim 1 wherein the dibasic Lys-Lys motif is modified to resist trypsin-like proteases while preserving the ε-amine groups
4. Any pharmaceutical composition comprising a peptide of claims 1-3
5. Any method of use of the peptides of claims 1-3 for wound healing, anti-inflammation, tissue repair, hair follicle neogenesis, or cardiac repair
6. All obvious variants including different combinations of the described modifications

**All rights reserved. No license granted.**
