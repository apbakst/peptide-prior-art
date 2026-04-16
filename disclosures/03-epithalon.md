---
title: "Half-Life Extended Epithalon (AEDG) Analogs via Non-Canonical Amino Acid Substitution"
date: 2026-04-16
type: Defensive Publication / Prior Art Disclosure
author: Andrew Bakst (bakst@hairdao.xyz)
status: Public Domain (CC0 1.0)
---

# Epithalon (AEDG): Half-Life Extension via Non-Canonical Amino Acids

## 1. Background

### 1.1 Native Peptide

**Epithalon** (also Epitalon, Epithalone) is a synthetic tetrapeptide based on the natural peptide epithalamin, produced by the pineal gland. It is a telomerase activator that has been studied for anti-aging properties.

- **Native Sequence:** `Ala-Glu-Asp-Gly`
- **Single-Letter Code:** `AEDG`
- **Molecular Weight:** ~390 Da
- **Known Stability Issues:** Extremely short peptide with minimal secondary structure; susceptible to aminopeptidases (Ala N-terminal), carboxypeptidases (Gly C-terminal), and endopeptidases at the Glu-Asp junction. The C-terminal Gly provides no steric protection. Estimated half-life in serum: minutes.

### 1.2 Therapeutic Relevance

Epithalon has demonstrated:
- Activation of telomerase in human somatic cells
- Elongation of telomeres in cell culture studies
- Anti-aging effects in animal models (increased lifespan in rodents)
- Regulation of melatonin and cortisol circadian rhythms
- Antioxidant properties

### 1.3 Problem Statement

As a tetrapeptide, Epithalon is one of the smallest therapeutic peptides and is degraded almost immediately in serum. Every residue is accessible to proteases. A stabilization strategy must modify nearly every position while preserving the overall charge distribution and side chain functionality that mediate telomerase activation.

## 2. Disclosed Modifications

### 2.1 Variant A — Maximal Protection

**Modified Sequence:**
```
Ac-[Aib¹]-Glu²-[D-Asp³]-[β-Ala⁴]-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| N-terminus | Free amine | Acetyl cap | Aminopeptidase resistance |
| 1 | Ala | Aib (α-aminoisobutyric acid) | Aib is the α,α-dimethyl analog of Ala — preserves the methyl side chain character while adding a second methyl group that provides steric protection. This is the most conservative possible ncAA substitution for Ala |
| 2 | Glu | Glu (unmodified) | The acidic side chain of Glu is likely critical for activity; left unmodified to preserve the charge profile |
| 3 | Asp | D-Asp | Inverts stereochemistry to resist endopeptidases; the carboxyl side chain is preserved for charge interactions |
| 4 | Gly | β-Alanine (β-Ala) + amide | β-Ala provides an additional backbone methylene that eliminates protease recognition while preserving the flexible, small character of the C-terminal position. Amidation blocks carboxypeptidases |
| C-terminus | Free carboxyl | Amide (NH₂) | Blocks carboxypeptidase recognition |

**Expected Impact:** 10-20× increase in serum half-life. For a tetrapeptide, this represents a meaningful extension from minutes to potentially 30-60 minutes.

### 2.2 Variant B — All-D Retro-Inverso

**Modified Sequence:**
```
[D-Gly⁴]-[D-Asp³]-[D-Glu²]-[D-Ala¹]
```
(Sequence reversed and all residues in D-configuration)

**Rationale:** Retro-inverso peptides maintain the same side chain topology as the parent L-peptide while being completely resistant to proteases. The backbone amide bond directionality is reversed, and all chiral centers are inverted, resulting in a topochemical mimic of the native peptide. For a short, flexible tetrapeptide like Epithalon where the bioactive conformation is likely dictated by side chain interactions rather than backbone hydrogen bonding, the retro-inverso approach has a high probability of retaining activity.

**Expected Impact:** 50-100× increase in serum half-life (complete protease resistance); activity preservation is probable but must be empirically confirmed.

### 2.3 Variant C — NMe Backbone

**Modified Sequence:**
```
Ac-[NMe-Ala¹]-Glu²-[NMe-Asp³]-Gly⁴-NH₂
```

**Modifications:**
| Position | Native | Modified | Rationale |
|----------|--------|----------|-----------|
| 1 | Ala | NMe-Ala | N-methylation of alternating residues creates a "protease-invisible" backbone while preserving all side chains |
| 3 | Asp | NMe-Asp | Same rationale; the alternating pattern ensures no two adjacent backbone NH groups are available for protease binding |

**Expected Impact:** 5-10× increase in serum half-life with excellent side chain preservation.

## 3. Synthesis Considerations

- Tetrapeptide synthesis is straightforward on Rink amide resin
- Fmoc-Aib-OH: double coupling with HATU (standard)
- Fmoc-D-Asp(OtBu)-OH: commercially available
- Fmoc-β-Ala-OH: commercially available, standard coupling
- Retro-inverso variant: all Fmoc-D-Xaa-OH building blocks commercially available; sequence is loaded C→N as written (which is N→C in the retro orientation)
- NMe variants: Fmoc-NMe-Ala-OH and Fmoc-NMe-Asp(OtBu)-OH available; coupling after NMe residues requires HATU with extended reaction times

## 4. Claims Dedicated to Public Domain

1. Any peptide comprising the sequence AEDG or a variant thereof, wherein one or more amino acid residues are replaced with Aib, D-amino acids, β-amino acids, N-methylated amino acids, or any other non-canonical amino acid
2. Any retro-inverso variant of the sequence AEDG
3. Any peptide of claims 1-2 with terminal capping (acetyl, amide, or other protective groups)
4. Any pharmaceutical composition or method of use of the above for telomerase activation, anti-aging, telomere elongation, or melatonin regulation
5. All obvious variants and combinations of the described modifications
