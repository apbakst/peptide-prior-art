---
title: "Half-Life Extended Semax Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: Public Domain (CC0 1.0)
---

# Semax: Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**Semax** is a synthetic heptapeptide derived from the ACTH(4-10) fragment (Met-Glu-His-Phe-Pro-Gly-Pro), which is the minimal fragment of adrenocorticotropic hormone (ACTH) retaining nootropic and neuroprotective activity without hormonal (corticosteroid-stimulating) effects.

- **Native Sequence:** `Met-Glu-His-Phe-Pro-Gly-Pro`
- **Single-Letter Code:** `MEHFPGP`
- **Molecular Weight:** ~813 Da
- **Known Stability Issues:** Met¹ is highly susceptible to oxidation (forming Met sulfoxide, which reduces activity). The His³-Phe⁴ bond is susceptible to chymotrypsin. The Gly⁶ position is a flexible protease target. Exopeptidases attack both termini. Estimated half-life: minutes to tens of minutes intranasally.

### 1.2 Therapeutic Relevance

Semax has demonstrated:
- Nootropic effects (enhancement of memory and learning)
- Neuroprotective activity in ischemic stroke models
- Neurotrophic effects (upregulation of BDNF, NGF)
- Anxiolytic properties
- Attention and cognitive performance enhancement
- Approved in Russia as a prescription nootropic (intranasal)
- Anti-inflammatory effects in the CNS

### 1.3 Problem Statement

Semax's utility is limited by methionine oxidation (both during storage and in vivo) and rapid proteolytic degradation. The existing clinical formulation requires intranasal administration with frequent dosing. A stabilized analog could improve both shelf life and pharmacokinetics.

## 2. Disclosed Modifications

### 2.1 Variant A — Nle/D-Phe/Aib

**Modified Sequence:**
```
Ac-[Nle¹]-Glu²-His³-[D-Phe⁴]-Pro⁵-[Aib⁶]-Pro⁷-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| N-terminus | Free amine | Acetyl cap | Aminopeptidase resistance |
| 1 | Met | Norleucine (Nle) | **Most critical modification.** Nle is the standard isosteric replacement for Met — identical chain length and hydrophobicity, but the thioether sulfur is replaced with a methylene group, completely eliminating oxidation. This addresses both the in vivo degradation and storage stability issues simultaneously |
| 4 | Phe | D-Phe | D-configuration disrupts chymotrypsin recognition at the His³-Phe⁴ junction. D-Phe preserves the aromatic pharmacophore. This substitution has strong precedent in ACTH/melanocortin peptide design (cf. MT-II, which uses D-Phe at the equivalent position) |
| 6 | Gly | Aib | Aib replaces the flexible, protease-susceptible Gly⁶ with an α,α-disubstituted amino acid. The gem-dimethyl group provides steric protection while Aib's helix-inducing property may improve the presentation of the pharmacophore |
| C-terminus | Free carboxyl | Amide (NH₂) | Blocks carboxypeptidase access to the C-terminal Pro |

**Expected Impact:** 5-10× increase in serum half-life, with elimination of oxidative degradation.

### 2.2 Variant B — NMe Backbone Protection

**Modified Sequence:**
```
Ac-[Nle¹]-[NMe-Glu²]-His³-[D-Phe⁴]-Pro⁵-[Aib⁶]-Pro⁷-NH₂
```

**Additional Modification:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 2 | Glu | NMe-Glu | N-methylation of the Nle¹-Glu² amide bond blocks endopeptidase access in the N-terminal region. The Glu side chain carboxyl is preserved |

**Expected Impact:** 8-15× increase. The additional NMe provides a second line of defense in the N-terminal half of the peptide.

### 2.3 Variant C — Extended Semax with Stabilization

The clinical form of Semax sometimes includes a C-terminal Pro-Gly-Pro extension (making it a decapeptide: MEHFPGP-PGP, known as "Semax extended" or N-Acetyl Semax). This variant stabilizes the extended form:

**Modified Sequence:**
```
Ac-[Nle¹]-Glu²-His³-[D-Phe⁴]-Pro⁵-[Aib⁶]-Pro⁷-Pro⁸-[Aib⁹]-Pro¹⁰-NH₂
```

**Rationale:** The PGP extension is stabilized by replacing both Gly residues (6 and 9) with Aib. The Pro-Aib-Pro motif is extremely protease-resistant and enforces a rigid turn structure. All Pro residues are intrinsically resistant.

**Expected Impact:** 10-20× increase for the extended form.

### 2.4 Variant D — Retro-Inverso Core

**Modified Sequence:**
```
Ac-Nle¹-Glu²-[D-Phe⁴-D-His³]-Pro⁵-Aib⁶-Pro⁷-NH₂
```

A partial retro-inverso approach limited to the His³-Phe⁴ dipeptide segment (the primary chymotrypsin target). The retro-inverso dipeptide [D-Phe-D-His] replaces [His-Phe], presenting the same side chains in approximately the same spatial orientation while being invisible to chymotrypsin.

**Expected Impact:** 3-5× protection specifically at the chymotrypsin-susceptible junction, additive with other modifications.

## 3. Synthesis Considerations

- Fmoc-Nle-OH: commercially available, inexpensive, standard coupling
- Fmoc-D-Phe-OH: commercially available, standard coupling
- Fmoc-Aib-OH: double coupling with HATU required
- Fmoc-NMe-Glu(OtBu)-OH: available from specialty suppliers; coupling after NMe residues requires extended times
- Partial retro-inverso (Variant D): requires synthesis of Fmoc-D-Phe-D-His(Trt)-OH dipeptide building block in solution phase, then incorporation into SPPS
- All variants amenable to standard Rink amide resin SPPS

## 4. Claims Dedicated to Public Domain

1. Any peptide comprising the sequence MEHFPGP (Semax), MEHFPGP-PGP (extended Semax), or ACTH(4-10) or a variant thereof, wherein Met¹ is replaced with norleucine or other oxidation-resistant amino acid isosteres
2. Any peptide of claim 1 wherein Phe⁴ is in D-configuration
3. Any peptide of claim 1 wherein one or more Gly residues are replaced with Aib, sarcosine, or other non-canonical amino acids
4. Any peptide of claim 1 wherein one or more residues are N-methylated
5. Any partial or complete retro-inverso variant of Semax or extended Semax
6. Any combination of modifications from claims 1-5
7. Pharmaceutical compositions for intranasal, subcutaneous, oral, or other routes of administration
8. Methods of use for nootropic effects, neuroprotection, stroke recovery, BDNF modulation, cognitive enhancement, or anxiolytic applications
9. All obvious variants and combinations
