---
title: "Half-Life Extended Cathelicidin LL-37 Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: All Rights Reserved — Copyright 2026 Andrew Bakst
---

# Cathelicidin LL-37: Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**LL-37** is the sole human cathelicidin antimicrobial peptide, produced by cleavage of the precursor protein hCAP-18. It is a 37-residue, amphipathic, α-helical peptide with broad-spectrum antimicrobial activity and immunomodulatory functions.

- **Native Sequence:** `Leu-Leu-Gly-Asp-Phe-Phe-Arg-Lys-Ser-Lys-Glu-Lys-Ile-Gly-Lys-Glu-Phe-Lys-Arg-Ile-Val-Gln-Arg-Ile-Lys-Asp-Phe-Leu-Arg-Asn-Leu-Val-Pro-Arg-Thr-Glu-Ser`
- **Single-Letter Code:** `LLGDFFRKSKEKIGKEFKRIVQRIKDFLRNLVPRTES`
- **Molecular Weight:** ~4,493 Da
- **Structure:** Amphipathic α-helix in membrane-like environments; disordered in aqueous solution
- **Known Stability Issues:** Multiple trypsin sites (after 8 Arg/Lys residues); chymotrypsin sites (after Phe⁵, Phe⁶, Phe¹⁷, Phe²⁷, Leu²⁸); susceptible to both aminopeptidases and carboxypeptidases. The high density of basic residues (5 Arg + 6 Lys = 11 basic residues in 37 positions) makes LL-37 exceptionally trypsin-susceptible.

### 1.2 Therapeutic Relevance

LL-37 has demonstrated:
- Broad-spectrum antimicrobial activity against Gram-positive and Gram-negative bacteria, fungi, and enveloped viruses
- Mechanism of action via membrane disruption (carpet model and toroidal pore formation)
- Immunomodulatory functions: chemotaxis of immune cells, modulation of TLR signaling, wound healing promotion
- Anti-biofilm activity
- LPS neutralization (anti-endotoxin)
- Promotion of angiogenesis and wound healing
- Potential anti-cancer activity

### 1.3 Problem Statement

LL-37 presents a unique challenge: its antimicrobial activity depends on its amphipathic helical structure and the cationic charge from Arg/Lys residues — yet these same basic residues are the primary protease targets. Full D-amino acid substitution would eliminate antimicrobial activity because the peptide-membrane interaction involves chiral recognition of phospholipid headgroups. The strategy must selectively protect protease-susceptible sites while preserving the amphipathic helix and cationic charge.

## 2. Disclosed Modifications

### 2.1 Variant A — Selective NMe/D-Amino Acid Substitution

**Modified Sequence:**
```
Ac-[D-Leu¹]-Leu²-Gly³-Asp⁴-Phe⁵-Phe⁶-Arg⁷-Lys⁸-Ser⁹-[NMe-Lys¹⁰]-Glu¹¹-Lys¹²-Ile¹³-Gly¹⁴-Lys¹⁵-Glu¹⁶-Phe¹⁷-Lys¹⁸-Arg¹⁹-Ile²⁰-Val²¹-Gln²²-Arg²³-Ile²⁴-[NMe-Lys²⁵]-Asp²⁶-Phe²⁷-Leu²⁸-Arg²⁹-Asn³⁰-Leu³¹-Val³²-Pro³³-Arg³⁴-Thr³⁵-[Aib³⁶]-Ser³⁷-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| N-terminus | Free amine | Ac + D-Leu¹ | Combined N-terminal protection; D-Leu resists leucine aminopeptidase |
| 10 | Lys | NMe-Lys | N-methylation at an internal Lys protects the Ser⁹-Lys¹⁰ trypsin site. The ε-amine is preserved for cationic charge |
| 25 | Lys | NMe-Lys | Protects the Ile²⁴-Lys²⁵ trypsin site. Strategic placement in the middle of the C-terminal helical segment |
| 36 | Glu | Aib | Replaces Glu near the C-terminus with a helix-stabilizing α,α-disubstituted amino acid; protects the C-terminal region |
| C-terminus | Free carboxyl | Amide (NH₂) | Carboxypeptidase resistance |

**Design Philosophy:** Only 4 modifications out of 37 residues (~11%). This conservative approach prioritizes activity preservation. The two NMe-Lys substitutions are placed at non-adjacent trypsin sites to disrupt protease processivity — once a protease encounters an NMe site and stalls, the fragment released from the other end is still too large to be rapidly degraded further.

**Expected Impact:** 3-5× increase in serum half-life. The amphipathic helix and membrane-active properties should be well-preserved.

### 2.2 Variant B — Hydrocarbon Stapled LL-37

**Modified Sequence (Staple 1, positions 6 and 10):**
```
Leu¹-Leu²-Gly³-Asp⁴-Phe⁵-[S₅⁶]-Arg⁷-Lys⁸-Ser⁹-[S₅¹⁰]-Glu¹¹-Lys¹²-Ile¹³-Gly¹⁴-Lys¹⁵-Glu¹⁶-Phe¹⁷-Lys¹⁸-Arg¹⁹-Ile²⁰-Val²¹-Gln²²-Arg²³-Ile²⁴-Lys²⁵-Asp²⁶-Phe²⁷-Leu²⁸-Arg²⁹-Asn³⁰-Leu³¹-Val³²-Pro³³-Arg³⁴-Thr³⁵-Glu³⁶-Ser³⁷
```

Where S₅ = (S)-2-(4'-pentenyl)alanine. After ring-closing metathesis, positions 6 and 10 are connected by an all-hydrocarbon i, i+4 staple.

**Modified Sequence (Staple 2, positions 18 and 22):**
```
Leu¹-Leu²-Gly³-Asp⁴-Phe⁵-Phe⁶-Arg⁷-Lys⁸-Ser⁹-Lys¹⁰-Glu¹¹-Lys¹²-Ile¹³-Gly¹⁴-Lys¹⁵-Glu¹⁶-Phe¹⁷-[S₅¹⁸]-Arg¹⁹-Ile²⁰-Val²¹-[S₅²²]-Arg²³-Ile²⁴-Lys²⁵-Asp²⁶-Phe²⁷-Leu²⁸-Arg²⁹-Asn³⁰-Leu³¹-Val³²-Pro³³-Arg³⁴-Thr³⁵-Glu³⁶-Ser³⁷
```

**Double-Stapled Variant (both staples):**
```
Leu¹-Leu²-Gly³-Asp⁴-Phe⁵-[S₅⁶]-Arg⁷-Lys⁸-Ser⁹-[S₅¹⁰]-Glu¹¹-Lys¹²-Ile¹³-Gly¹⁴-Lys¹⁵-Glu¹⁶-Phe¹⁷-[S₅¹⁸]-Arg¹⁹-Ile²⁰-Val²¹-[S₅²²]-Arg²³-Ile²⁴-Lys²⁵-Asp²⁶-Phe²⁷-Leu²⁸-Arg²⁹-Asn³⁰-Leu³¹-Val³²-Pro³³-Arg³⁴-Thr³⁵-Glu³⁶-Ser³⁷
```

**Rationale:** Hydrocarbon staples:
1. Lock the α-helical conformation, which is the bioactive state for membrane interaction
2. Dramatically increase protease resistance across the stapled region (the hydrocarbon bridge physically blocks protease access)
3. Enhance cell/membrane permeability (the hydrocarbon staple increases the peptide's amphipathic character)
4. The staple positions are chosen on the hydrophobic face of the amphipathic helix (based on helical wheel projection) to avoid disrupting the cationic face

**Expected Impact:** 5-15× increase in serum half-life with potentially enhanced antimicrobial potency due to pre-organized helical structure.

### 2.3 Variant C — Truncated Stabilized Core (LL-37 fragment)

The minimal antimicrobial core of LL-37 is approximately residues 17-29 (FK-13: FKRIVQRIKDFLR). A stabilized version of this fragment:

**Modified Sequence:**
```
Ac-[D-Phe¹⁷]-Lys¹⁸-Arg¹⁹-Ile²⁰-Val²¹-Gln²²-Arg²³-Ile²⁴-[NMe-Lys²⁵]-Asp²⁶-Phe²⁷-Leu²⁸-[D-Arg²⁹]-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 17 | Phe | D-Phe + Ac | N-terminal protection of the truncated fragment |
| 25 | Lys | NMe-Lys | Internal trypsin site protection |
| 29 | Arg | D-Arg + NH₂ | C-terminal protection |

**Expected Impact:** 5-10× increase for the minimal active fragment. Shorter peptide is cheaper to synthesize and the ncAA modifications have higher impact per residue.

### 2.4 Variant D — Selective Lys→Orn/Dab Substitution

**Modified Sequence:** Replace select Lys residues with **ornithine (Orn)** or **2,4-diaminobutyric acid (Dab)**:
```
Leu¹-Leu²-Gly³-Asp⁴-Phe⁵-Phe⁶-Arg⁷-[Orn⁸]-Ser⁹-[Orn¹⁰]-Glu¹¹-Lys¹²-Ile¹³-Gly¹⁴-Lys¹⁵-Glu¹⁶-Phe¹⁷-[Orn¹⁸]-Arg¹⁹-Ile²⁰-Val²¹-Gln²²-Arg²³-Ile²⁴-[Orn²⁵]-Asp²⁶-Phe²⁷-Leu²⁸-Arg²⁹-Asn³⁰-Leu³¹-Val³²-Pro³³-Arg³⁴-Thr³⁵-Glu³⁶-Ser³⁷-NH₂
```

**Rationale:** Ornithine (Orn) is a non-proteinogenic amino acid with a 4-carbon side chain amine (vs. Lys's 5-carbon). Trypsin recognizes Lys via the ε-amine at a specific distance from the backbone; shortening the side chain by one methylene reduces trypsin recognition while preserving the cationic charge at physiological pH. Dab (3-carbon amine) provides even greater trypsin resistance but with pKa shift (~8.5 vs ~10.5) that may reduce the effective charge at physiological pH.

Positions 8, 10, 18, 25 are selected for Orn substitution — these are internal Lys residues where trypsin cleavage would generate the most damaging fragments. Positions 12 and 15 are left as native Lys to maintain the cationic density on the polar face of the helix.

**Expected Impact:** 3-8× increase in serum half-life with preservation of antimicrobial activity.

## 3. Synthesis Considerations

### General
- 37-residue peptides are at the upper limit of practical SPPS; pseudoproline dipeptide building blocks recommended at Ser and Thr positions to prevent aggregation
- Microwave-assisted SPPS strongly recommended
- Double coupling at all positions after Aib, NMe, and at difficult sequences

### Stapled Variants
- S₅ amino acids: Fmoc-(S)-2-(4'-pentenyl)Ala-OH (commercially available from Aileron/custom synthesis)
- On-resin ring-closing metathesis: Grubbs 1st generation catalyst (10 mol%), DCE, 50°C, 2h. Repeat 2× for complete conversion
- Double-stapled variant: sequential metathesis (first staple, then extend chain, then second staple) or simultaneous metathesis of both pairs after full chain assembly

### Orn/Dab Variants
- Fmoc-Orn(Boc)-OH and Fmoc-Dab(Boc)-OH: commercially available, standard coupling

## 4. Disclosed Claims (Patent Rights Reserved)

The following claims are publicly disclosed to establish a date of invention. All patent rights are reserved by the author under the 1-year grace period of 35 U.S.C. § 102(b)(1)(A):

1. Any peptide comprising the full-length LL-37 sequence (LLGDFFRKSKEKIGKEFKRIVQRIKDFLRNLVPRTES) or any fragment thereof (including FK-13, KR-12, GF-17, or other known active fragments), wherein one or more amino acid residues are substituted with non-canonical amino acids
2. Any peptide of claim 1 wherein one or more Lys residues are replaced with ornithine (Orn), 2,4-diaminobutyric acid (Dab), 2,3-diaminopropionic acid (Dap), or N-methylated Lys
3. Any peptide of claim 1 wherein one or more positions are replaced with (S)-2-(4'-pentenyl)alanine or (R)-2-(7'-octenyl)alanine or other olefin-bearing amino acids for hydrocarbon stapling at any i, i+3; i, i+4; or i, i+7 spacing
4. Any single-stapled, double-stapled, or triple-stapled variant of LL-37 or fragments thereof
5. Any peptide of claim 1 wherein terminal residues are in D-configuration and/or the peptide bears N-terminal and/or C-terminal capping groups
6. Any combination of modifications from claims 1-5
7. Pharmaceutical compositions for topical, injectable, inhaled, or oral administration
8. Methods of use for antimicrobial therapy, anti-biofilm therapy, wound healing, immunomodulation, LPS neutralization, or anti-cancer applications
9. All obvious variants and combinations including different staple positions, different ncAA combinations, and different fragment lengths

**All rights reserved. No license granted.**
