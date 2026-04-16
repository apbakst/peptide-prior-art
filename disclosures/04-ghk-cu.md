---
title: "Half-Life Extended GHK-Cu Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: Public Domain (CC0 1.0)
---

# GHK-Cu: Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**GHK-Cu** (glycyl-L-histidyl-L-lysine:copper(II)) is a naturally occurring copper-binding tripeptide found in human plasma, saliva, and urine. It serves as a copper transport molecule and has potent wound healing, anti-inflammatory, and tissue remodeling properties.

- **Native Sequence:** `Gly-His-Lys` complexed with Cu²⁺
- **Single-Letter Code:** `GHK`
- **Molecular Weight:** ~403 Da (peptide alone), ~466 Da (with Cu²⁺)
- **Cu²⁺ Coordination:** The copper ion is coordinated by the Gly α-amino group, the Gly-His amide nitrogen, the His imidazole Nπ, and the Lys ε-amino group in a square-planar geometry
- **Known Stability Issues:** Extremely small peptide; susceptible to aminopeptidases, carboxypeptidases, and dipeptidyl peptidases. The His-Lys bond is susceptible to trypsin-like proteases. Rapid renal clearance due to small size.

### 1.2 Therapeutic Relevance

GHK-Cu has demonstrated:
- Stimulation of collagen and glycosaminoglycan synthesis
- Promotion of wound healing and tissue repair
- Hair follicle enlargement and stimulation of hair growth
- Anti-inflammatory effects (suppression of TNF-α, IL-6)
- Antioxidant properties via superoxide dismutase activation
- Skin remodeling and anti-aging effects
- Attraction of immune and endothelial cells to injury sites

### 1.3 Problem Statement

GHK-Cu's therapeutic utility is severely limited by its very short half-life (minutes). The critical challenge is that the Cu²⁺ coordination sphere involves atoms from all three residues — the Gly N-terminus, the backbone amide, the His imidazole, and the Lys side chain. Any modification must preserve this coordination geometry or the copper complex will not form, eliminating the peptide's activity.

## 2. Disclosed Modifications

### 2.1 Variant A — β-Ala / D-Lys (Preserve Cu²⁺ Binding)

**Modified Sequence:**
```
[β-Ala¹]-His²-[D-Lys³]-NH₂ · Cu²⁺
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 1 | Gly | β-Alanine (β-Ala) | β-Ala provides an extra methylene in the backbone, resisting aminopeptidases. Critically, the free N-terminal amine is preserved for Cu²⁺ coordination. The additional CH₂ may slightly alter the coordination geometry but the amine→Cu²⁺ bond should remain intact. β-Ala is the closest ncAA to Gly (both lack a side chain) |
| 2 | His | His (unmodified) | The imidazole ring is absolutely essential for Cu²⁺ coordination. This residue cannot be modified at the side chain |
| 3 | Lys | D-Lys + C-term amide | D-configuration resists trypsin-like cleavage at the His-Lys bond. The ε-amine group is preserved in the D-configuration for Cu²⁺ coordination. Amidation of the C-terminus provides carboxypeptidase resistance |

**Expected Impact:** 5-15× increase in serum half-life. Cu²⁺ binding affinity should be verified by ITC or UV-Vis spectroscopy (d-d transition at ~600 nm).

### 2.2 Variant B — NMe-His (Backbone-Protected)

**Modified Sequence:**
```
Ac-Gly¹-[NMe-His²]-Lys³-NH₂ · Cu²⁺
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| N-terminus | Free amine | Acetyl cap | **Important caveat:** This caps the N-terminal amine, which participates in Cu²⁺ coordination. The Ac group carbonyl oxygen can serve as a weaker Cu²⁺ ligand, or the coordination may shift to a different geometry. This variant trades some Cu²⁺ affinity for aminopeptidase resistance |
| 2 | His | NMe-His | N-methylation of the backbone amide nitrogen at His². The amide N between Gly¹ and His² is a Cu²⁺ ligand (deprotonated amide nitrogen coordination). NMe substitution will eliminate this coordination site. However, Cu²⁺ can adopt alternative 3-coordinate or use water as the fourth ligand. The His imidazole Nπ remains available |
| C-terminus | Free carboxyl | Amide | Carboxypeptidase resistance |

**Expected Impact:** 3-5× increase in half-life, but with potentially reduced Cu²⁺ affinity. This variant may be more suitable as a copper-free peptide (apo-GHK analog) if copper coordination is not the primary mechanism for a given application.

### 2.3 Variant C — Cyclized GHK

**Modified Sequence:**
```
c[Gly¹-His²-Lys³-Glu⁴] · Cu²⁺
```

**Modifications:** Head-to-tail cyclization via addition of a Glu residue that bridges the N-terminus of Gly and C-terminus of Lys through amide bonds, forming a 12-membered macrocycle. The Gly α-amino group participates in the macrolactam and is no longer available for Cu²⁺ coordination in the same geometry, but the His imidazole and Lys ε-amine remain free. The Glu carboxyl side chain can serve as an additional Cu²⁺ ligand.

**Expected Impact:** 10-30× increase in half-life due to cyclization-mediated protease resistance. Cu²⁺ coordination chemistry will differ from native GHK-Cu and requires empirical characterization.

## 3. Synthesis Considerations

### Variant A
- Linear SPPS on Rink amide resin: Fmoc-D-Lys(Boc)-OH → Fmoc-His(Trt)-OH → Fmoc-β-Ala-OH
- Cu²⁺ loading post-cleavage: dissolve peptide in water, add 1 equiv CuSO₄ or Cu(OAc)₂, adjust pH to 7.4

### Variant B
- Fmoc-NMe-His(Trt)-OH requires custom synthesis or is available from specialty vendors
- Standard SPPS otherwise; N-terminal Ac capping before cleavage

### Variant C
- Linear synthesis of GHKE on 2-chlorotrityl resin (cleave with mild acid to preserve side chains)
- Head-to-tail cyclization in solution at high dilution (0.5 mM) with PyBOP/DIPEA
- Side chain deprotection with TFA cocktail
- Cu²⁺ loading post-cyclization

## 4. Claims Dedicated to Public Domain

1. Any copper-binding peptide comprising the sequence GHK or a variant thereof, wherein one or more amino acid residues are replaced with non-canonical amino acids while preserving at least two of the three Cu²⁺ coordination sites (terminal amine, imidazole N, ε-amine)
2. Any peptide of claim 1 wherein Gly is replaced with β-alanine
3. Any peptide of claim 1 wherein Lys is in the D-configuration
4. Any cyclic variant of GHK or GHK-Cu with or without additional residues to enable cyclization
5. Any pharmaceutical composition comprising the peptides of claims 1-4 with or without copper
6. Any method of use for wound healing, hair growth, skin remodeling, anti-inflammation, or anti-aging
7. All obvious variants and combinations
