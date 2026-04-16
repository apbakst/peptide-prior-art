---
title: "Half-Life Extended DSIP (Delta Sleep-Inducing Peptide) Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: All Rights Reserved — Copyright 2026 Andrew Bakst
---

# DSIP (Delta Sleep-Inducing Peptide / Emideltide): Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**Delta Sleep-Inducing Peptide (DSIP)** is a nonapeptide originally isolated from rabbit brain during slow-wave sleep. Also known as **Emideltide**, it has been studied for its roles in sleep regulation, stress response, and neuromodulation.

- **Native Sequence:** `Trp-Ala-Gly-Gly-Asp-Ala-Ser-Gly-Glu`
- **Single-Letter Code:** `WAGGDASGE`
- **Molecular Weight:** ~849 Da
- **Known Stability Issues:** DSIP is notorious for its extremely short half-life in serum (approximately 2-7 minutes). The di-glycine motif (Gly³-Gly⁴) is a major vulnerability — glycine-rich sequences are highly flexible and accessible to endopeptidases. The Trp N-terminus is susceptible to aminopeptidases, and the Glu C-terminus to carboxypeptidases. Three glycine residues (positions 3, 4, 8) create a protease-susceptible backbone.

### 1.2 Therapeutic Relevance

DSIP has demonstrated:
- Induction of delta (slow-wave) sleep EEG patterns
- Normalization of disturbed sleep architecture
- Stress-protective and adaptogenic properties
- Analgesic effects
- Modulation of corticotropin and somatotropin release
- Anticonvulsant activity
- Antioxidant properties
- Opioid system modulation

### 1.3 Problem Statement

DSIP has one of the shortest half-lives of any therapeutic peptide. Its ~2-7 minute serum half-life makes systemic therapeutic use virtually impossible without stabilization. The di-glycine motif is the primary degradation hotspot, but the peptide is vulnerable at nearly every position.

## 2. Disclosed Modifications

### 2.1 Variant A — Aib Replacement of Glycines

**Modified Sequence:**
```
Ac-[D-Trp¹]-Ala²-[Aib³]-[Aib⁴]-Asp⁵-Ala⁶-Ser⁷-[D-Gly⁸]-Glu⁹-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| N-terminus | Free amine | Acetyl cap | Blocks aminopeptidase; Trp is particularly susceptible |
| 1 | Trp | D-Trp | D-configuration resists aminopeptidases while fully preserving the indole pharmacophore. D-Trp substitution is well-precedented in peptide drug design (e.g., D-Trp in octreotide/somatostatin analogs) |
| 3 | Gly | Aib | **Critical modification.** The Gly³-Gly⁴ di-glycine motif is the primary protease target. Aib (α-aminoisobutyric acid) is the α,α-dimethylglycine — it maintains the lack of a functional side chain while the gem-dimethyl group provides complete steric shielding of the backbone |
| 4 | Gly | Aib | Same rationale as position 3. The di-Aib motif strongly induces 3₁₀ helical structure, which itself provides additional protease resistance |
| 8 | Gly | D-Gly | The third glycine position; D-Gly provides some protease resistance through altered backbone geometry |
| C-terminus | Free carboxyl | Amide (NH₂) | Blocks carboxypeptidase A (Glu is a carboxypeptidase A substrate) |

**Expected Impact:** 10-50× increase in serum half-life (from ~5 min to 50 min-4 hours). The di-Gly→di-Aib substitution alone is expected to account for the majority of the stabilization effect.

### 2.2 Variant B — Full Backbone Protection

**Modified Sequence:**
```
Ac-[D-Trp¹]-[NMe-Ala²]-[Aib³]-[Aib⁴]-[D-Asp⁵]-[NMe-Ala⁶]-Ser⁷-[Aib⁸]-Glu⁹-NH₂
```

**Additional Modifications Beyond Variant A:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 2 | Ala | NMe-Ala | N-methylation blocks protease access at the Trp¹-Ala² junction |
| 5 | Asp | D-Asp | Disrupts endopeptidase recognition at the Aib⁴-Asp⁵ junction |
| 6 | Ala | NMe-Ala | N-methylation of the second Ala; alternating NMe pattern maximizes backbone protection |
| 8 | Gly | Aib | All three glycine positions now replaced with Aib |

**Expected Impact:** 50-200× increase in serum half-life. This heavily modified variant may have altered pharmacology and requires activity validation.

### 2.3 Variant C — Retro-Inverso

**Modified Sequence:**
```
[D-Glu⁹]-[D-Gly⁸]-[D-Ser⁷]-[D-Ala⁶]-[D-Asp⁵]-[D-Gly⁴]-[D-Gly³]-[D-Ala²]-[D-Trp¹]
```

**Rationale:** Complete retro-inverso transformation. For a flexible nonapeptide like DSIP, where the bioactive conformation is not rigidly defined by intramolecular hydrogen bonds, retro-inverso analogs have a reasonable probability of retaining activity. The side chain presentation is topochemically equivalent to the native peptide.

**Expected Impact:** Complete protease resistance (>100× half-life increase). Activity must be empirically validated.

### 2.4 Variant D — Cyclic DSIP

**Modified Sequence:**
```
c[Trp¹-Ala²-Aib³-Aib⁴-Asp⁵-Ala⁶-Ser⁷-Aib⁸-Glu⁹]
```

Cyclization via side chain-to-side chain lactam bridge between Asp⁵ and an additional Lys/Dap residue, or head-to-tail macrolactamization. The cyclic constraint provides significant protease resistance and may improve receptor binding through conformational preorganization.

**Expected Impact:** 20-100× increase in serum half-life.

## 3. Synthesis Considerations

- Fmoc-D-Trp(Boc)-OH: commercially available; Boc protection of indole nitrogen prevents piperidine-mediated side reactions during Fmoc removal
- Di-Aib coupling: the Aib³-Aib⁴ sequential coupling is notoriously difficult. Recommended: microwave-assisted SPPS (75°C, 10 min coupling) with HATU/DIPEA, triple coupling. Alternatively, use Fmoc-Aib-Aib-OH dipeptide building block if available
- NMe-amino acids: coupling after NMe residues is slow; use HATU with 4 equiv, 2-hour coupling
- Retro-inverso: standard SPPS with all D-amino acids; no special difficulties
- Cyclic variant: requires orthogonal side chain protection strategy and on-resin or solution-phase cyclization

## 4. Disclosed Claims (Patent Rights Reserved)

The following claims are publicly disclosed to establish a date of invention. All patent rights are reserved by the author under the 1-year grace period of 35 U.S.C. § 102(b)(1)(A):

1. Any peptide comprising the sequence WAGGDASGE or a variant thereof, wherein the di-glycine motif (Gly³-Gly⁴) is replaced with α-aminoisobutyric acid (Aib), sarcosine, D-amino acids, β-amino acids, or other non-canonical amino acids
2. Any peptide of claim 1 wherein Trp¹ is in the D-configuration
3. Any peptide of claim 1 wherein one or more Ala residues are N-methylated
4. Any retro-inverso variant of the sequence WAGGDASGE
5. Any cyclic variant of DSIP, whether cyclized head-to-tail, side chain-to-side chain, or by other macrocyclization strategies
6. Any peptide of claims 1-5 with terminal capping modifications
7. Pharmaceutical compositions and methods of use for sleep induction, sleep architecture normalization, stress protection, analgesia, or neuromodulation
8. All obvious variants and combinations of the described modifications

**All rights reserved. No license granted.**
