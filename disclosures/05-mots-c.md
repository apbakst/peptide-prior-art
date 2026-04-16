---
title: "Half-Life Extended MOTS-c Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: All Rights Reserved — Copyright 2026 Andrew Bakst
---

# MOTS-c: Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**MOTS-c** (Mitochondrial Open Reading Frame of the Twelve S rRNA type-c) is a mitochondria-derived peptide encoded within the 12S rRNA gene of mitochondrial DNA. It functions as a mitochondrial-encoded signaling peptide that regulates metabolic homeostasis.

- **Native Sequence:** `Met-Arg-Trp-Gln-Glu-Met-Gly-Tyr-Ile-Phe-Tyr-Pro-Arg-Lys-Leu-Arg`
- **Single-Letter Code:** `MRWQEMGYIFYPRKLR`
- **Molecular Weight:** ~2,174 Da
- **Known Stability Issues:** Two methionine residues (Met¹, Met⁶) are highly susceptible to oxidation, forming methionine sulfoxide; multiple trypsin sites after Arg², Arg¹³, Lys¹⁴, Arg¹⁶; chymotrypsin sites after Trp³, Tyr⁸, Phe¹⁰, Tyr¹¹.

### 1.2 Therapeutic Relevance

MOTS-c has demonstrated:
- Regulation of insulin sensitivity and glucose metabolism
- Prevention of diet-induced and age-dependent obesity in mice
- Activation of AMPK signaling pathway
- Improvement of exercise capacity and endurance
- Skeletal muscle metabolic regulation
- Anti-inflammatory effects
- Potential geroprotective properties
- Translocation to the nucleus under metabolic stress to regulate gene expression

### 1.3 Problem Statement

MOTS-c has multiple vulnerability points: two oxidation-prone Met residues, numerous trypsin and chymotrypsin cleavage sites, and susceptibility to exopeptidases. The methionine oxidation issue is particularly problematic as it occurs both in vivo and during storage, degrading the peptide before it even reaches its target.

## 2. Disclosed Modifications

### 2.1 Variant A — Oxidation-Resistant, Trypsin-Protected

**Modified Sequence:**
```
Ac-[Nle¹]-Arg²-Trp³-[D-Gln⁴]-Glu⁵-[Nle⁶]-Gly⁷-Tyr⁸-Ile⁹-Phe¹⁰-Tyr¹¹-Pro¹²-Arg¹³-[NMe-Lys¹⁴]-Leu¹⁵-Arg¹⁶-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| N-terminus | Free amine | Acetyl cap | Aminopeptidase resistance |
| 1 | Met | Norleucine (Nle) | Isosteric replacement: Nle (2-aminohexanoic acid) has the same chain length and hydrophobicity as Met but replaces the thioether (-S-CH₃) with a methylene (-CH₂-CH₃), completely eliminating oxidation susceptibility |
| 4 | Gln | D-Gln | Disrupts the protease recognition motif at Trp³-Gln⁴-Glu⁵ (chymotrypsin/endopeptidase junction) |
| 6 | Met | Norleucine (Nle) | Same rationale as position 1; eliminates the second oxidation-susceptible site |
| 14 | Lys | NMe-Lys | N-methylation blocks trypsin recognition at Arg¹³-Lys¹⁴; the ε-amine side chain is unaffected |
| C-terminus | Free carboxyl | Amide (NH₂) | Blocks carboxypeptidase B (which preferentially cleaves basic C-terminal residues like Arg¹⁶) |

**Expected Impact:** 3-5× increase in serum half-life; complete elimination of methionine oxidation degradation pathway (which is the primary storage stability issue).

### 2.2 Variant B — Multi-Site Protected

**Modified Sequence:**
```
Ac-[Nle¹]-[D-Arg²]-Trp³-Gln⁴-Glu⁵-[Nle⁶]-[Aib⁷]-Tyr⁸-Ile⁹-[D-Phe¹⁰]-Tyr¹¹-Pro¹²-[NMe-Arg¹³]-[NMe-Lys¹⁴]-Leu¹⁵-[D-Arg¹⁶]-NH₂
```

**Additional Modifications Beyond Variant A:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 2 | Arg | D-Arg | Protects the N-terminal region from trypsin cleavage after Arg² |
| 7 | Gly | Aib | Helix-inducing α,α-disubstituted amino acid replaces flexible Gly; provides local steric protection |
| 10 | Phe | D-Phe | Disrupts chymotrypsin recognition at Phe¹⁰ while maintaining the aromatic side chain |
| 13 | Arg | NMe-Arg | N-methylation blocks trypsin access at the Arg¹³-Lys¹⁴ dibasic site |
| 16 | Arg | D-Arg + amide | Terminal D-Arg resists carboxypeptidase B; maintains the guanidinium group |

**Expected Impact:** 8-15× increase in serum half-life. More aggressive modification — activity must be confirmed empirically as the MOTS-c pharmacophore is not fully defined.

### 2.3 Variant C — Stapled Helical MOTS-c

**Modified Sequence:**
```
Ac-[Nle¹]-Arg²-Trp³-Gln⁴-[S₅⁵]-[Nle⁶]-Gly⁷-Tyr⁸-[S₅⁹]-Phe¹⁰-Tyr¹¹-Pro¹²-Arg¹³-Lys¹⁴-Leu¹⁵-Arg¹⁶-NH₂
```

Where S₅ = (S)-2-(4'-pentenyl)alanine. Positions 5 and 9 (i, i+4 spacing) are replaced with olefin-bearing α-methyl amino acids that undergo ring-closing metathesis (Grubbs catalyst) to form an all-hydrocarbon staple.

**Rationale:** If the region spanning residues 5-9 adopts helical structure, the staple will:
- Lock the helix, increasing protease resistance across the entire stapled region
- Increase cell permeability (stapled peptides are known to enhance cellular uptake)
- Provide metabolic stability without altering multiple side chains

**Expected Impact:** 5-10× increase in serum half-life with enhanced cellular uptake.

## 3. Synthesis Considerations

- Nle: Fmoc-Nle-OH is inexpensive and commercially available; direct replacement for Met in SPPS
- D-amino acids: all Fmoc-D-Xaa-OH building blocks commercially available
- NMe-amino acids: Fmoc-NMe-Arg(Pbf)-OH and Fmoc-NMe-Lys(Boc)-OH require double coupling
- Stapled variant: requires on-resin ring-closing metathesis with Grubbs 1st generation catalyst in DCE at 50°C after full chain assembly but before global deprotection/cleavage

## 4. Disclosed Claims (Patent Rights Reserved)

The following claims are publicly disclosed to establish a date of invention. All patent rights are reserved by the author under the 1-year grace period of 35 U.S.C. § 102(b)(1)(A):

1. Any peptide comprising the sequence MRWQEMGYIFYPRKLR or a variant thereof, wherein one or both methionine residues are replaced with norleucine or other oxidation-resistant isosteres
2. Any peptide of claim 1 wherein one or more Arg or Lys residues are modified with D-configuration or N-methylation to resist trypsin
3. Any peptide of claim 1 containing α,α-disubstituted amino acids (Aib or stapling amino acids) at one or more positions
4. Any hydrocarbon-stapled variant of MOTS-c at any i, i+3, i+4, or i+7 spacing
5. Any combination of modifications from claims 1-4 with terminal capping
6. Pharmaceutical compositions and methods of use for metabolic regulation, insulin sensitization, obesity, exercise enhancement, or geroprotection
7. All obvious variants and combinations

**All rights reserved. No license granted.**
