---
layout: page
title: Keynotes
---

{%- assign sp1_path = "/images/speakers/camille.jpeg" | relative_url -%}
{%- assign sp2_path = "/images/speakers/manolis.jpg" | relative_url -%}
{%- assign sp1_name = "Camille Marchet" -%}
{%- assign sp2_name = "Manolis Kellis" -%}
{%- assign sp1_inst = "CNRS" -%}
{%- assign sp2_inst = "MIT" -%}

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
  </tr>
</table>

---

### {{ sp1_name }}
*{{ sp1_inst }}*

**"Beyond reference sequences: algorithms for the next generation of sequence collections"**

Camille Marchet is a computational bioinformatics researcher and CNRS research associate in the BONSAI team at the CRIStAL lab, Université de Lille, France. She develops scalable algorithms and data structures for sequence analysis, with a focus on indexing and querying large collections of sequencing data and methods tailored to RNA-seq and other next-generation sequencing applications. Marchet received her BSc degree in Bioinformatics from INSA Lyon, a MSc in Ecology and Evolution from Université Claude Bernard Lyon 1, and completed her PhD in Computer Science at the University of Rennes in 2018, where she worked on de novo transcriptome analysis methods. After postdoctoral work in the BONSAI team, she joined CNRS as a research associate, contributing to projects on transcriptome encyclopedias and large-scale sequence indexing. Her research spans foundational data structures for k-mer sets, scalable sequence search, and efficient representation of sequencing datasets, and continues to drive methodological advances in computational genomics.

---

### {{ sp2_name }}
*{{ sp2_inst }} — Computer Science and Artificial Intelligence Laboratory*

**"The Geometry of Meaning: Representation Learning for Personalized Medicine"**

Manolis Kellis is a Professor of Computer Science at MIT and a member of the Broad Institute of MIT and Harvard. His research sits at the intersection of machine learning, genomics, and medicine, with a focus on understanding how the genome encodes biological function and how variation in regulatory elements contributes to disease. Kellis has pioneered computational methods for comparative and functional genomics, epigenomics, and single-cell biology, and his group applies these tools to unravel the genetic basis of complex traits including neurodegeneration, psychiatric disorders, and metabolic disease. He leads the MIT Computational Biology group and has contributed to major international consortia including ENCODE and Roadmap Epigenomics.