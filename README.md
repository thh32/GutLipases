# GutLipases

**Uncovering the repertoire of bacterial lipolytic enzymes within the mammalian gut**

This repository accompanies the preprint *Ecology and Function of Bacterial Lipases within the Gut Microbiome* (Hitch, Masson *et al.*, bioRxiv 2020; [doi:10.1101/2020.09.08.287425](https://doi.org/10.1101/2020.09.08.287425)). It contains the data from our survey of bacterial encoded lipolytic enzymes in the gut of humans, mice and pigs.

---

## Background: what are bacterial lipolytic enzymes?

Lipases (EC 3.1.1.3) are enzymes that hydrolyse triglycerides into glycerol and free fatty acids. Triglycerides are a major component of the human diet, and excessive intake is linked to many health conditions. The role of host lipases in fat digestion and absorption is well documented, but the contribution of gut bacteria to this process has been largely ignored.

"Lipolytic enzyme" is a broad term. It covers true lipases as well as related α/β-hydrolases such as esterases, carboxylesterases and phospholipases. Most contain a conserved catalytic serine within a **GxSxG** motif. Bacterial lipolytic enzymes are grouped into families based on sequence and function ([Hitch and Clavel, 2019](https://peerj.com/articles/7249/); see also the [Lipase_reclassification](https://github.com/thh32/Lipase_reclassification) repository).


---

## Sources of the lipolytic enzymes

 **Metagenomic protein catalogues.** Candidate lipolytic enzymes were retrieved from gut metagenomic catalogues of **humans, mice and pigs**. Candidates were identified through annotation against multiple lipase-related databases (including EggNOG, UniProt EC 3.1.1.3 and the Lipase Engineering Database). Proteins were then filtered for the conserved GxSxG catalytic motif to limit false positives.

---

## Summary of findings

- **373 bacterial lipolytic enzymes** were identified across the human, mouse and pig gut.
- The sequences fall into **two major clusters**, which share highly conserved sequence motifs.
- **Lipase-positive bacteria are taxonomically diverse.** They occur in **seven phyla** and make up **9.1% ± 4.6%** of the human gut community.
- **Glycerol metabolism is more common than fatty acid utilisation** in lipase-positive species. Few encode complete fatty acid degradation pathways.
- **Stable-isotope experiments** with ¹³C-labelled glycerol showed that human gut bacteria can assimilate glycerol-derived carbon. This supports the hypothesis that glycerol released by lipolysis could serve as a bacterial nutrient.
- **In vitro characterisation** of the *Clostridium symbiosum* lipase confirmed lipolytic activity on a range of substrates.

Together, these results suggest that bacterial lipolytic activity contributes to triglyceride metabolism in the gut. They also provide a functional annotation resource for the many lipases that were previously unannotated.

---

## Repository contents

| File / folder | Description |
|---|---|
| `Lipases/` | Sequences and annotations of the microbial lipases identified in this study |
| `Taxonomic_assignment.ods` | Taxonomic assignment of lipase-positive bacteria/genomes |
| `README.md` | This file |

---

## Citation

If you use this resource, please cite:

> Hitch TCA, Masson JM, Streidl T, Fischöder T, Hobbs-Grimmer D, Ghosh D, Elling L, Jehmlich N, von Bergen M, Hoyles L, Clavel T. *Ecology and Function of Bacterial Lipases within the Gut Microbiome.* bioRxiv (2020). https://doi.org/10.1101/2020.09.08.287425


## Related resources

- [Lipase_reclassification](https://github.com/thh32/Lipase_reclassification): proposed classification system for bacterial lipolytic enzymes

## Contact

Thomas C. A. Hitch: [@thh32](https://github.com/thh32)
