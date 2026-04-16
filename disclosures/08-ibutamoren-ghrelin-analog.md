---
title: "Peptide-Based Ghrelin Mimetic with Non-Canonical Amino Acids as Alternative to Ibutamoren"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: All Rights Reserved — Copyright 2026 Andrew Bakst
---

# Ibutamoren (MK-677) Context & Peptide-Based Ghrelin Mimetic Alternatives

## 1. Background

### 1.1 Ibutamoren (MK-677)

**Ibutamoren mesylate (MK-677)** is a non-peptide, orally active growth hormone secretagogue that mimics the action of ghrelin at the GHS-R1a (growth hormone secretagogue receptor type 1a). It is a spiropiperidine small molecule, NOT a peptide.

- **Chemical Name:** 2-amino-2-methyl-N-[1-(1-methylsulfonylspiro[2H-indene-1,4'-piperidine]-6-yl)but-3-enyl]-propanamide methanesulfonate
- **Molecular Weight:** ~624 Da (mesylate salt)
- **Half-life:** ~24 hours (oral)
- **Bioavailability:** ~60% (oral)

Since MK-677 is a small molecule, non-canonical amino acid substitution is not applicable. However, the disclosure below covers **peptide-based ghrelin receptor agonists** incorporating ncAAs that could serve as alternatives.

### 1.2 Ghrelin and Peptide-Based GHS-R1a Agonists

**Native ghrelin** is a 28-amino acid peptide with an n-octanoyl modification on Ser³:
```
Gly-Ser-Ser(n-octanoyl)-Phe-Leu-Ser-Pro-Glu-His-Gln-Arg-Val-Gln-Gln-Arg-Lys-Glu-Ser-Lys-Lys-Pro-Pro-Ala-Lys-Leu-Gln-Pro-Arg
```

The **minimal active fragment** for GHS-R1a activation is ghrelin(1-5): `Gly-Ser-Ser(n-octanoyl)-Phe-Leu`, with the n-octanoyl group on Ser³ being essential for receptor binding.

### 1.3 Problem Statement

Peptide-based ghrelin agonists have poor half-life due to protease susceptibility and the lability of the octanoyl ester on Ser³ (hydrolysis to des-acyl ghrelin, which is inactive at GHS-R1a). A stabilized peptide ghrelin mimetic could offer the tissue selectivity and potency of peptide agonists with improved pharmacokinetics.

## 2. Disclosed Modifications

### 2.1 Variant A — Stabilized Ghrelin(1-8) Mimetic

**Modified Sequence:**
```
Ac-[Aib¹]-Ser²-[Dap³(n-octanoyl)]-Phe⁴-Leu⁵-[NMe-Ser⁶]-Pro⁷-Glu⁸-NH₂
```

**Modifications:**
| Position | Native Ghrelin | Modified | Rationale |
|----------|---------------|----------|-----------|
| N-terminus | Free Gly amine | Ac-Aib cap | Aib replaces Gly with aminopeptidase-resistant α,α-dimethylglycine; Ac cap adds further protection |
| 2 | Ser | Ser (unchanged) | Preserves structure around the critical acylation site |
| 3 | Ser(n-octanoyl) | Dap(n-octanoyl) | **Key modification.** 2,3-diaminopropionic acid (Dap) replaces Ser. The octanoyl group is attached via an amide bond to the β-amino group of Dap instead of an ester bond to the Ser hydroxyl. The amide bond is ~1000× more stable than the ester toward hydrolysis. The spatial position of the octanoyl chain is similar (one atom shorter to the branch point). This is the single most impactful modification for preventing loss of the essential acyl group |
| 6 | Ser | NMe-Ser | N-methylation at a non-pharmacophoric position to block endopeptidase access |
| 8 | Glu | Glu-NH₂ | C-terminal amidation |
| 1 | Gly | Aib | Protease resistance as described above |

**Expected Impact:** 10-30× increase in functional half-life, primarily due to the ester→amide switch at the acylation site preventing des-acylation.

### 2.2 Variant B — D-Amino Acid Stabilized

**Modified Sequence:**
```
Ac-[D-Ala¹]-Ser²-[Dap³(n-octanoyl)]-[D-Phe⁴]-Leu⁵-[D-Ser⁶]-Pro⁷-Glu⁸-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 1 | Gly | D-Ala + Ac | D-Ala provides a small methyl side chain + D-configuration for full aminopeptidase resistance |
| 3 | Ser(octanoyl) | Dap(octanoyl) | Ester-to-amide as in Variant A |
| 4 | Phe | D-Phe | Disrupts chymotrypsin recognition. D-Phe at position 4 in ghrelin analogs has been shown to retain GHS-R1a affinity in some contexts |
| 6 | Ser | D-Ser | Additional protease resistance in the mid-peptide region |

**Expected Impact:** 15-40× increase in functional half-life.

### 2.3 Variant C — Cyclic Ghrelin Mimetic

**Modified Sequence:**
```
c[Lys¹-Ser²-Dap³(n-octanoyl)-Phe⁴-Leu⁵-Glu⁶] (lactam via Lys¹ ε-amine to Glu⁶ γ-carboxyl)
```

**Rationale:** Cyclization via Lys-Glu side chain lactam constrains the pharmacophore, provides protease resistance, and may improve GHS-R1a binding selectivity. The octanoyl-Dap is positioned within the ring to present the acyl chain.

**Expected Impact:** 20-50× increase with enhanced receptor selectivity.

## 3. Synthesis Considerations

- **Dap(n-octanoyl):** Fmoc-Dap(Alloc)-OH is loaded during SPPS; after chain assembly, Alloc is removed with Pd(PPh₃)₄/PhSiH₃, and octanoic acid is coupled to the β-amine with HATU
- **Aib/NMe residues:** standard double-coupling protocols
- **Cyclic variant:** orthogonal protection (Alloc on Lys, 2-PhiPr on Glu side chains), selective deprotection and on-resin lactamization with PyBOP

## 4. Disclosed Claims (Patent Rights Reserved)

The following claims are publicly disclosed to establish a date of invention. All patent rights are reserved by the author under the 1-year grace period of 35 U.S.C. § 102(b)(1)(A):

1. Any peptide-based ghrelin receptor (GHS-R1a) agonist comprising a sequence derived from ghrelin(1-5) through ghrelin(1-28), wherein the Ser³ octanoyl ester is replaced with a 2,3-diaminopropionic acid (Dap) octanoyl amide or any other hydrolysis-resistant acyl linkage
2. Any peptide of claim 1 wherein one or more amino acid residues are replaced with D-amino acids, N-methylated amino acids, α-aminoisobutyric acid, or β-amino acids
3. Any cyclic variant of the peptides in claims 1-2
4. Any peptide of claims 1-3 with terminal capping modifications
5. Pharmaceutical compositions and methods of use for growth hormone secretion, appetite regulation, muscle wasting, osteoporosis, or metabolic disorders
6. All obvious variants including different acyl chain lengths (C6-C12) on the Dap/Dab residue
7. All obvious combinations of the described modifications

**All rights reserved. No license granted.**
