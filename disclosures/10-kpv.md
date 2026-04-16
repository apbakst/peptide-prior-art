---
title: "Half-Life Extended KPV Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: All Rights Reserved — Copyright 2026 Andrew Bakst
---

# KPV: Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**KPV** is the C-terminal tripeptide fragment of α-melanocyte-stimulating hormone (α-MSH), corresponding to residues 11-13. Despite lacking the core melanocortin pharmacophore (His-Phe-Arg-Trp), KPV retains potent anti-inflammatory activity through a melanocortin receptor-independent mechanism involving NF-κB inhibition.

- **Native Sequence:** `Lys-Pro-Val`
- **Single-Letter Code:** `KPV`
- **Molecular Weight:** ~342 Da
- **Known Stability Issues:** As a tripeptide, KPV is extremely susceptible to exopeptidases. The N-terminal Lys is a target for aminopeptidases and trypsin-like proteases. The C-terminal Val is targeted by carboxypeptidases. Estimated in vivo half-life: minutes.

### 1.2 Therapeutic Relevance

KPV has demonstrated:
- Potent anti-inflammatory effects via NF-κB pathway inhibition
- Suppression of pro-inflammatory cytokines (IL-1β, IL-6, TNF-α)
- Efficacy in colitis models (oral and rectal administration)
- Antimicrobial activity against Staphylococcus aureus and Candida albicans
- Wound healing promotion
- Anti-pyretic effects
- Potential for inflammatory bowel disease treatment
- Intestinal epithelial cell protection

### 1.3 Problem Statement

KPV is an extremely short peptide with rapid degradation in vivo. The central Pro provides some inherent protease resistance (as an imino acid), but the flanking Lys and Val are highly vulnerable. Stabilization of both termini is essential.

## 2. Disclosed Modifications

### 2.1 Variant A — D-Lys / Aib

**Modified Sequence:**
```
Ac-[D-Lys¹]-Pro²-[Aib³]-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| N-terminus | Free amine | Acetyl cap | Aminopeptidase resistance |
| 1 | Lys | D-Lys | D-configuration resists aminopeptidases and trypsin-like proteases. The ε-amine side chain is preserved in the same spatial orientation for any electrostatic interactions involved in NF-κB inhibition |
| 2 | Pro | Pro (unchanged) | Pro is intrinsically protease-resistant; no modification needed |
| 3 | Val | Aib + C-term amide | Aib (α-aminoisobutyric acid) is an α,α-disubstituted amino acid. While it replaces Val's isopropyl side chain with two methyl groups (changing hydrophobic character), the gem-dimethyl substitution provides excellent carboxypeptidase resistance. Amidation further blocks carboxypeptidases |

**Expected Impact:** 5-15× increase in serum half-life.

### 2.2 Variant B — NMe-Lys / D-Val (Preserve All Side Chains)

**Modified Sequence:**
```
Ac-[NMe-Lys¹]-Pro²-[D-Val³]-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 1 | Lys | NMe-Lys + Ac | N-methylation blocks aminopeptidase access. Combined with N-terminal acetylation, provides robust N-terminal protection. The Lys side chain is fully preserved |
| 3 | Val | D-Val + NH₂ | D-Val resists carboxypeptidases while perfectly preserving the isopropyl side chain. Amidation adds further protection |

**Expected Impact:** 5-10× increase with maximal preservation of native side chains.

### 2.3 Variant C — β-Amino Acid Hybrid

**Modified Sequence:**
```
Ac-[β³-hLys¹]-Pro²-[β³-hVal³]-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 1 | Lys | β³-homoLysine | Additional backbone methylene makes this invisible to all standard proteases while preserving the full Lys side chain |
| 3 | Val | β³-homoValine | Same rationale; preserves isopropyl side chain |

**Expected Impact:** 15-30× increase. The backbone extension at both flanking positions significantly alters the overall peptide geometry — this is the most aggressive variant and activity must be confirmed.

### 2.4 Variant D — Retro-Inverso

**Modified Sequence:**
```
[D-Val]-[D-Pro]-[D-Lys]
```

**Rationale:** Complete retro-inverso transformation. For a tripeptide, the retro-inverso approach is particularly attractive because the short chain has minimal defined secondary structure, and the side chain spatial presentation is a close topochemical mimic of the native peptide.

**Expected Impact:** Complete protease resistance (>50× half-life increase). Activity validation required.

## 3. Synthesis Considerations

- All variants are trivial to synthesize by SPPS or solution-phase peptide synthesis
- D-amino acids: all commercially available
- NMe-Lys: Fmoc-NMe-Lys(Boc)-OH available; coupling after NMe residues requires extended times
- β³-amino acids: Fmoc-β³-hLys(Boc)-OH and Fmoc-β³-hVal-OH available from Bachem
- Retro-inverso: Fmoc-D-Val-OH, Fmoc-D-Pro-OH, Fmoc-D-Lys(Boc)-OH — all standard
- Scale: tripeptides can be economically produced at gram-kilogram scale by solution-phase synthesis

## 4. Disclosed Claims (Patent Rights Reserved)

The following claims are publicly disclosed to establish a date of invention. All patent rights are reserved by the author under the 1-year grace period of 35 U.S.C. § 102(b)(1)(A):

1. Any peptide comprising the sequence KPV or a variant thereof, wherein one or more amino acid residues are replaced with their D-enantiomer, N-methylated form, α,α-disubstituted analog, or β-amino acid analog
2. Any retro-inverso variant of KPV
3. Any peptide of claims 1-2 with terminal capping modifications (acetyl, amide, or other)
4. Pharmaceutical compositions and methods of use for anti-inflammation, NF-κB inhibition, inflammatory bowel disease, colitis, antimicrobial applications, or wound healing
5. All obvious variants and combinations including different non-canonical amino acid types at each position

**All rights reserved. No license granted.**
