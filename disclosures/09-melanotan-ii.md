---
title: "Half-Life Extended Melanotan II Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: All Rights Reserved — Copyright 2026 Andrew Bakst
---

# Melanotan II: Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**Melanotan II (MT-II)** is a synthetic cyclic heptapeptide analog of α-melanocyte-stimulating hormone (α-MSH). It is a non-selective agonist of melanocortin receptors (MC1R through MC5R) with particular activity at MC1R (pigmentation), MC3R (energy homeostasis), and MC4R (sexual function, appetite).

- **Native Sequence:** `Ac-Nle-c[Asp-His-D-Phe-Arg-Trp-Lys]-NH₂`
- **Molecular Weight:** ~1,024 Da
- **Existing ncAA Modifications:** MT-II already contains two non-canonical features:
  - **Norleucine (Nle)** at position 1 (replacing Met⁴ of α-MSH to prevent oxidation)
  - **D-Phenylalanine (D-Phe)** at position 4 of the cycle (replacing L-Phe⁷ of α-MSH to increase MC receptor binding and metabolic stability)
- **Cyclization:** Lactam bridge between Asp side chain and Lys side chain
- **Known Stability Issues:** Despite cyclization and existing ncAA modifications, MT-II is still susceptible to some endopeptidases, particularly at the His-D-Phe and Arg-Trp junctions. The His imidazole is susceptible to oxidation.

### 1.2 Therapeutic Relevance

Melanotan II has demonstrated:
- Induction of skin pigmentation (melanogenesis) via MC1R activation
- Pro-erectile effects via MC4R activation
- Appetite suppression via MC4R activation
- Potential photoprotection through increased melanin production
- Lipolytic effects via MC3R/MC5R

### 1.3 Problem Statement

MT-II is already substantially optimized with cyclization, D-Phe, and Nle. However, incremental half-life improvements are still valuable, particularly for reducing dosing frequency. The remaining vulnerabilities are at the His and Arg-Trp positions.

## 2. Disclosed Modifications

### 2.1 Variant A — NMe-His, Halogenated Trp

**Modified Sequence:**
```
Ac-Nle-c[Asp-[NMe-His]-D-Phe-Arg-[5-Br-Trp]-Lys]-NH₂
```

**Modifications:**
| Position | Native MT-II | Modified | Rationale |
|----------|-------------|----------|-----------|
| His | His | NMe-His | N-methylation of the backbone amide nitrogen at His. Within the cyclic constraint, this eliminates one protease-accessible NH while potentially improving the conformational rigidity. The imidazole side chain is preserved for MC receptor interactions |
| Trp | Trp | 5-Bromo-Trp (5-Br-Trp) | Halogenation at the 5-position of the indole ring increases metabolic stability by blocking CYP450-mediated oxidation at this position. The bromine atom also increases lipophilicity, which may improve tissue distribution. 5-Br-Trp has been used in melanocortin peptide SAR studies and can maintain or enhance receptor affinity |

**Expected Impact:** 1.5-3× increase in serum half-life. MT-II is already well-stabilized; these are incremental improvements.

### 2.2 Variant B — Additional D-Amino Acids and NMe

**Modified Sequence:**
```
Ac-Nle-c[Asp-[NMe-His]-D-Phe-[D-Arg]-[5-Br-Trp]-Lys]-NH₂
```

**Additional Modification:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| Arg | Arg | D-Arg | D-configuration at Arg disrupts trypsin-like protease recognition at the Arg-Trp junction. Within the cyclic scaffold, D-Arg may alter the pharmacophore presentation — activity must be validated. The guanidinium group, which is critical for MC4R electrostatic interactions, is preserved |

**Expected Impact:** 2-4× increase, with risk of reduced MC4R affinity due to altered ring conformation.

### 2.3 Variant C — β-Amino Acid Hybrid

**Modified Sequence:**
```
Ac-Nle-c[Asp-His-D-Phe-[β³-hArg]-Trp-Lys]-NH₂
```

**Modification:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| Arg | Arg | β³-homoArginine (β³-hArg) | Insertion of an additional backbone methylene at the Arg position. This expands the macrocycle ring size by one atom, which may be accommodated within the existing conformational space. β³-hArg is invisible to trypsin-family proteases while preserving the guanidinium side chain |

**Expected Impact:** 2-5× increase. The ring expansion is the main risk — larger ring may have altered conformational preferences.

### 2.4 Variant D — 2-Naphthylalanine Substitution

**Modified Sequence:**
```
Ac-Nle-c[Asp-His-D-2-Nal-Arg-Trp-Lys]-NH₂
```

**Modification:** D-Phe replaced with D-2-Naphthylalanine (D-2-Nal). The naphthyl ring system provides enhanced hydrophobic contacts with the MC receptor binding pocket and is more metabolically stable than phenyl due to the fused ring system being a poorer CYP450 substrate.

**Expected Impact:** 1.5-2× metabolic stability improvement with potentially enhanced receptor affinity.

## 3. Synthesis Considerations

- Standard Fmoc SPPS on Rink amide resin
- Linear assembly: Fmoc-Lys(Mtt)-OH ... Fmoc-Asp(OPp)-OH with orthogonal side chain protection for cyclization
- On-resin cyclization: remove Mtt and OPp with 2% TFA/DCM, cyclize with PyBOP/DIPEA
- Fmoc-NMe-His(Trt)-OH: available from specialty suppliers; double coupling
- Fmoc-5-Br-Trp(Boc)-OH: commercially available (e.g., Chem-Impex)
- Fmoc-β³-hArg(Pbf)-OH: available from Bachem/Iris Biotech
- Fmoc-D-2-Nal-OH: commercially available
- N-terminal Nle: Fmoc-Nle-OH, standard coupling, then Ac₂O capping

## 4. Disclosed Claims (Patent Rights Reserved)

The following claims are publicly disclosed to establish a date of invention. All patent rights are reserved by the author under the 1-year grace period of 35 U.S.C. § 102(b)(1)(A):

1. Any cyclic melanocortin receptor agonist peptide based on the MT-II scaffold (Ac-Nle-c[Asp-His-D-Phe-Arg-Trp-Lys]-NH₂) wherein one or more residues within or outside the cycle are substituted with non-canonical amino acids
2. Any peptide of claim 1 wherein His is N-methylated
3. Any peptide of claim 1 wherein Trp is halogenated (5-Br, 5-Cl, 5-F, 6-Br, 6-Cl, 6-F, or other halogen positions)
4. Any peptide of claim 1 wherein Arg is in D-configuration or replaced with β³-homoarginine
5. Any peptide of claim 1 wherein D-Phe is replaced with D-2-naphthylalanine, D-4-fluorophenylalanine, D-4-chlorophenylalanine, or other halogenated/extended aromatic D-amino acids
6. Any combination of modifications from claims 2-5
7. Pharmaceutical compositions and methods of use for pigmentation, sexual dysfunction, appetite regulation, photoprotection, or lipolysis
8. All obvious variants and combinations

**All rights reserved. No license granted.**
