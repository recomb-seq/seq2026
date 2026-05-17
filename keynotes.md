---
layout: page
title: Keynotes
---

{%- assign sp1_path = "/images/speakers/camille.jpeg" | relative_url -%}
{%- assign sp2_path = "/images/speakers/richard.png" | relative_url -%}
{%- assign sp3_path = "/images/speakers/manolis.jpg" | relative_url -%}
{%- assign sp1_name = "Camille Marchet" -%}
{%- assign sp2_name = "Richard Durbin" -%}
{%- assign sp3_name = "Manolis Kellis" -%}
{%- assign sp1_inst = "CNRS" -%}
{%- assign sp2_inst = "University of Cambridge" -%}
{%- assign sp3_inst = "MIT" -%}

<!-- #### Join us as two distinguished scientists from diverse fields share their groundbreaking research throughout the conference. -->

<table style="border: none;">
  <tr>
    <td style="text-align: center; border: none;">
      <img src="{{ sp1_path }}" alt="{{ sp1_name }}" class="speaker-photo" style="max-width: 200px;"><br>
      <b>{{ sp1_name }}</b><br>
      {{ sp1_inst }}
    </td>
    <td style="text-align: center; border: none;">
      <img src="{{ sp2_path }}" alt="{{ sp2_name }}" class="speaker-photo" style="max-width: 200px;"><br>
      <b>{{ sp2_name }}</b><br>
      {{ sp2_inst }}
    </td>
    <td style="text-align: center; border: none;">
      <img src="{{ sp3_path }}" alt="{{ sp3_name }}" class="speaker-photo" style="max-width: 200px;"><br>
      <b>{{ sp3_name }}</b><br>
      {{ sp3_inst }}
    </td>
  </tr>
</table>

---

### {{ sp1_name }}
*{{ sp1_inst }}*

**"Beyond reference sequences: algorithms for the next generation of sequence collections"**

Camille Marchet is a computational bioinformatics researcher and CNRS research associate in the BONSAI team at the CRIStAL lab, Université de Lille, France. She develops scalable algorithms and data structures for sequence analysis, with a focus on indexing and querying large collections of sequencing data and methods tailored to RNA-seq and other next-generation sequencing applications. Marchet received her BSc degree in Bioinformatics from INSA Lyon, a MSc in Ecology and Evolution from Université Claude Bernard Lyon 1, and completed her PhD in Computer Science at the University of Rennes in 2018, where she worked on de novo transcriptome analysis methods. After postdoctoral work in the BONSAI team, she joined CNRS as a research associate, contributing to projects on transcriptome encyclopedias and large-scale sequence indexing. Her research spans foundational data structures for k-mer sets, scalable sequence search, and efficient representation of sequencing datasets, and continues to drive methodological advances in computational genomics.

---

### {{ sp2_name }}
*{{ sp2_inst }}*

**"New scalable approaches to pangenome construction and repeat analysis in the era of diversity genomics"**

Richard Durbin is Professor of Computational Genomics in the Department of Genetics at the University of Cambridge and an associate faculty member of the Wellcome Sanger Institute, where he previously led the Informatics division for nearly two decades. His research spans algorithms for biological sequence analysis, population and statistical genetics, and pangenomics. He has played a leading role in many of the field's defining projects: he was a principal investigator of the 1000 Genomes Project, contributed to the Human Genome Project, and co-founded the Ensembl genome browser, the Pfam protein families database, the TreeFam database of animal gene families, and the ACeDB database for C. elegans. His algorithmic contributions include the positional Burrows–Wheeler Transform (PBWT) for haplotype data and, more recently, GBWT-based data structures for scalable pangenome representation. He is co-author of "Biological Sequence Analysis: Probabilistic Models of Proteins and Nucleic Acids" (Cambridge University Press, 1998), the standard graduate text in the field, which has shaped the training of generations of computational biologists. He was elected a Fellow of the Royal Society in 2004 and is a member of EMBO, and has received the ISCB Accomplishment by a Senior Scientist Award among other recognitions. His former students and postdocs hold faculty and leadership positions at institutions including the Wellcome Sanger Institute, EMBL-EBI, Oxford, Stanford, and others. He completed his PhD at the MRC Laboratory of Molecular Biology in Cambridge with Sydney Brenner, working on the reconstruction of the C. elegans nervous system. 

---

### {{ sp3_name }}
*{{ sp3_inst }}*

**"From Genomics to Therapeutics: Single-cell Circuitry and Rewiring in Alzheimer's, Schizophrenia, Obesity, Cancer."**
<!-- **"The Geometry of Meaning: Representation Learning for Personalized Medicine"** -->

<!-- *Current AI systems in biomedicine are powerful and opaque in equal measure, compressing biological
knowledge into flat text exchanges, hiding the structure of the data they reason over, and excluding humans
from what they do better than any machine: seeing patterns, relationships, and anomalies at a glance. The
next frontier is not faster automation but elevating human understanding by revealing structure that was
always in the data but invisible to us. In this talk, I will focus on the geometric foundations of representation
learning across genes, drugs, proteins, cells, and patients. Each of these inhabits a semantic space whose
geometric structure determines how its elements relate, how they transform, and what is therapeutically
possible, and joint multimodal representation learning provides the instruments to measure that geometry
directly. I will show how joint representation learning enables personalized medicine through self-supervised and
contrastive objectives over graph neural networks of atoms, amino acids, and regulatory sequence. For
target identification, we leverage single-cell atlases of Alzheimer's disease, ALS, schizophrenia, and
bipolar disorder spanning hundreds of donors, and aggregate gene-level embeddings into cell-level vectors
to replace binary case/control phenotyping with continuous, cell-resolved disease scores — revealing that
within a single donor microglia and oligodendrocytes can sit in opposite regions of the disease
manifold, and recovering hundreds of metabolic biomarkers invisible under conventional differential
analysis. I will then present an interactive platform for navigating the resulting latent manifolds — the 20,000-
dimensional human gene space, the 121-million-compound chemical universe, and the space of protein
structures — through navigable, searchable, and composable operations. I will also describe our work on
joint protein–chemistry embeddings, which screen millions of compounds in seconds at nanomolar
resolution, including for disordered proteins on which traditional docking fails because stable structures
cannot be resolved. Lastly, I will describe our work on using agentic workflows to reason over these geometric
landscapes, predict new drugs, targets, and their interactions, and reframing personalized medicine as a
consequence of the joint geometry of patients, cells, genes, drugs, functions, and phenotypes.* -->

Manolis Kellis is a professor of computer science at MIT, a member of the Broad Institute of MIT and Harvard, a principal investigator of the Computer Science and Artificial Intelligence Lab at MIT, and head of the MIT Computational Biology Group (compbio.mit.edu). His research includes disease circuitry, genetics, genomics, epigenomics, coding genes, non-coding RNAs, regulatory genomics, and comparative genomics, applied to Alzheimer's Disease, Obesity, Schizophrenia, Cardiac Disorders, Cancer, and Immune Disorders, and multiple other disorders. He has led several large-scale genomics projects, including the Roadmap Epigenomics project, the ENCODE project, the Genotype Tissue-Expression (GTEx) project, and comparative genomics projects in mammals, flies, and yeasts. He received the US Presidential Early Career Award in Science and Engineering (PECASE) by US President Barack Obama, the Mendel Medal for Outstanding Achievements in Science, the NIH Director’s Transformative Research Award, the Boston Patent Law Association award, the NSF CAREER award, the Alfred P. Sloan Fellowship, the Technology Review TR35 recognition, the AIT Niki Award, and the Sprowls award for the best Ph.D. thesis in computer science at MIT. He has authored over 325 journal publications cited 200,000 times. He has obtained more than 20 multi-year grants from the NIH, and his trainees hold faculty positions at Stanford, Harvard, CMU, McGill, Johns Hopkins, UCLA, and other top universities. He lived in Greece and France before moving to the US, and he studied and conducted research at MIT, the Xerox Palo Alto Research Center, and the Cold Spring Harbor Lab. For more info, see: compbio.mit.edu 
