### Compararison of orthologous gene groups with pangenomemtx_to_Venn
---

This repository contains the <a href="https://github.com/MarDZiuba/pangenomemtx_to_Venn/blob/9d15e168dad0cd0cf928538c10e5f93fc4e0b5de/pangenomemtx_to_Venn.ipynb" title="pangenomemtx_to_Venn">jupyter notebook</a> with the code used for interrogating the pangenome matrix and demonstrating the result of it as Venn diagrams in the following paper:

Dziuba M.V., Müller F.D., Posfai M., Schüler D. (2023) **Exploring the host range for genetic transfer of magnetic organelle biosynthesis.** *In preparation.*

The script accepts the pangenome matrix produced by <a href="https://github.com/eead-csic-compbio/get_homologues" title="get_homologues">get_homologues</a> software as input and retrieves the orthologues sets shared by a specified organism or a group of organisms in comparison to the other groups. Besides the lists of such genes, it produces Venn diagrams for the result visualization.

---

### Problem statement
Magnetosomes produced by magnetotactic bacteria have great potential for application in biotechnology and medicine due to their unique physicochemical properties and high biocompatibility. Recent studies uncovered the genetic determinants for magnetosome formation and inspired ideas to transfer the pathway into hitherto non-magnetic organisms. However, previous efforts to genetically magnetize other species have been successful in only a few bacterial recipients, revealing significant challenges in this strategy. Here, by systematic examination of 25 proteobacterial hosts, we generated 7 novel magnetosome-producing strains. To find out, which accessory genes might support magnetosome formation, we compared the orthologues genes found on the genomes of all the "magnetized" strains vs. the strains failed to produce magnetosomes in our experiments. 

---

### Data set

The pangenome matrix produced by get_homologues with the following parameters for defining clusters of orthologous proteins: OrthoMCL clustering algorithm, the cut-off threshold for pairwise blastp alignments E value < 10e-5 and a minimal protein coverage of 50%.

* <a href="https://github.com/MarDZiuba/pangenomemtx_to_Venn/blob/9d15e168dad0cd0cf928538c10e5f93fc4e0b5de/pangenome_matrix_t0.tr.tab" title="pangenome_matrix_t0.tr.tab">pangenome matrix</a>
