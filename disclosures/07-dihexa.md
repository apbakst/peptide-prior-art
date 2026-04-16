---
title: "Half-Life Extended Dihexa Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: All Rights Reserved — Copyright 2026 Andrew Bakst
---

# Dihexa (N-hexanoyl-Tyr-Ile--(6) aminohexanoic amide): Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**Dihexa** (also known as N-hexanoic-Tyr-Ile-(6) aminohexanoic amide) is a synthetic hexapeptide analog derived from angiotensin IV. It was developed as a hepatocyte growth factor (HGF) mimetic and is one of the most potent procognitive agents ever described, with activity at picomolar concentrations.

- **Parent Sequence (Angiotensin IV):** `Val-Tyr-Ile-His-Pro-Phe`
- **Dihexa Structure:** `N-hexanoyl-Tyr-Ile-ψ[CH₂NH]-His-Pro-Phe` (contains a reduced amide bond ψ between Ile and His)
- **Molecular Weight:** ~771 Da
- **Key Structural Feature:** The reduced amide bond (ψ[CH₂NH]) between Ile and His is already a non-natural modification that confers resistance to peptidases at that specific junction
- **Known Stability Issues:** Despite the ψ bond, remaining peptide bonds are susceptible to chymotrypsin (after Tyr, Phe), and exopeptidases. The N-hexanoyl cap provides partial aminopeptidase protection but is itself susceptible to amidases.

### 1.2 Therapeutic Relevance

Dihexa has demonstrated:
- Potent procognitive effects at picomolar-nanomolar concentrations
- Enhancement of HGF/c-Met signaling
- Promotion of synaptogenesis and spinogenesis
- Reversal of cognitive deficits in scopolamine-treated rats
- Improvement of hippocampal-dependent learning and memory
- Potential applications in Alzheimer's disease and other dementias

### 1.3 Problem Statement

Dihexa already contains one non-canonical modification (the reduced peptide bond). However, the remaining conventional peptide bonds remain susceptible to proteolysis, particularly at the chymotrypsin-susceptible Tyr and Phe positions. Further stabilization could improve pharmacokinetics for systemic use.

## 2. Disclosed Modifications

### 2.1 Variant A — NMe/D-Amino Acid Enhancement

**Modified Sequence:**
```
N-hexanoyl-[NMe-Tyr¹]-Ile²-ψ[CH₂NH]-His³-Pro⁴-[D-Phe⁵]-NH₂
```

**Modifications:**
| Position | Native Dihexa | Modified | Rationale |
|----------|--------------|----------|-----------|
| 1 | Tyr | NMe-Tyr | N-methylation of the backbone nitrogen blocks chymotrypsin access to the Tyr position. The hydroxyphenyl side chain (critical for HGF/c-Met interaction) is fully preserved |
| 2-3 | Ile-ψ[CH₂NH]-His | Unchanged | The reduced amide bond already provides protease resistance at this junction |
| 4 | Pro | Pro (unchanged) | Pro is inherently protease-resistant (imino acid) |
| 5 | Phe | D-Phe + C-term amide | D-Phe resists chymotrypsin while maintaining the aromatic pharmacophore. The benzyl side chain in D-configuration may adopt a different rotamer but the aromatic character is preserved. Amidation of the C-terminus (if not already present in the 6-aminohexanoic acid amide moiety) provides carboxypeptidase resistance |

**Expected Impact:** 2-3× increase in serum half-life beyond native Dihexa. Dihexa is already partially stabilized, so the incremental gains are smaller.

### 2.2 Variant B — Aib Insertion

**Modified Sequence:**
```
N-hexanoyl-Tyr¹-[Aib]-Ile²-ψ[CH₂NH]-His³-Pro⁴-Phe⁵-NH₂
```

**Modification:** Insertion of Aib between the N-hexanoyl-Tyr and Ile residues. This does not replace any existing residue but adds an α,α-disubstituted spacer that disrupts the protease recognition motif at the Tyr¹-Ile² junction while maintaining all pharmacophoric elements.

**Expected Impact:** 2-4× increase with preservation of all original side chains.

### 2.3 Variant C — Full ncAA Suite

**Modified Sequence:**
```
N-hexanoyl-[NMe-Tyr¹]-[D-Ile²]-ψ[CH₂NH]-[NMe-His³]-Pro⁴-[D-Phe⁵]-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 1 | Tyr | NMe-Tyr | Backbone protection |
| 2 | Ile | D-Ile | The ψ bond already protects Ile²-His³, but D-Ile adds protection from the Tyr¹-Ile² side |
| 3 | His | NMe-His | Backbone N-methylation; the imidazole side chain is preserved. Note: NMe on the reduced amine (ψ bond) side may sterically interact with the methylene — must verify stability |
| 5 | Phe | D-Phe + amide | C-terminal protection |

**Expected Impact:** 3-5× increase. Aggressive modification warranting empirical activity confirmation.

## 3. Synthesis Considerations

- The ψ[CH₂NH] reduced bond requires reductive amination during SPPS or incorporation of a pre-formed Ile-ψ[CH₂NH]-His dipeptide building block
- NMe-Tyr: Fmoc-NMe-Tyr(tBu)-OH commercially available; double coupling after this residue
- D-Phe: Fmoc-D-Phe-OH, standard coupling
- D-Ile: Fmoc-D-Ile-OH, standard coupling
- N-hexanoyl cap: hexanoic acid activated with HATU, coupled to N-terminal amine

## 4. Disclosed Claims (Patent Rights Reserved)

The following claims are publicly disclosed to establish a date of invention. All patent rights are reserved by the author under the 1-year grace period of 35 U.S.C. § 102(b)(1)(A):

1. Any analog of Dihexa (N-hexanoyl-Tyr-Ile-ψ[CH₂NH]-His-Pro-Phe or a variant thereof) wherein one or more residues are substituted with N-methylated, D-configured, or α,α-disubstituted amino acids
2. Any peptide of claim 1 wherein the C-terminal Phe is in D-configuration
3. Any peptide of claim 1 wherein Tyr is N-methylated
4. Any peptide of claim 1 with additional non-canonical amino acid insertions between existing residues
5. Pharmaceutical compositions and methods of use for cognitive enhancement, synaptogenesis, HGF/c-Met pathway modulation, or neurodegenerative disease
6. All obvious variants and combinations

**All rights reserved. No license granted.**
