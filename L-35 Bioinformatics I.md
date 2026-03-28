This document, titled **"Bioinformatics-I"** (Lecture 35 of the course *Bioengineering: An Interface with Biology and Medicine*), introduces the practical application of bioinformatics tools for studying genes and proteins. Its primary purpose is to demonstrate how researchers can use publicly available databases and open-access software to retrieve biological information, compare sequences, and study evolutionary relationships without needing a wet-laboratory setup.

### Introduction to Bioinformatics Tools

Bioinformatics provides an interface where engineering disciplines and computational tools can assist medical scientists and biologists in solving complex physiological problems.

  * **Data Accessibility**: Large amounts of biological data are stored in public repositories and databases.
  * **Software**: Open-access software allows users to download and analyze this data from their own computers.
  * **Key Applications**: These tools are used to target specific genes, look at sequences for technologies like **PCR** (Polymerase Chain Reaction, a method to amplify DNA), and identify proteins with similar functions.

### National Centre for Biotechnology Information (NCBI)

NCBI is a major resource providing a variety of free computational tools and databases for the research community.

  * **PubMed**: A widely used database for literature searches and obtaining the full text of biomedical articles.
  * **Accession Numbers**: These are unique identifiers (e.g., 3040) assigned to specific DNA or protein sequences to facilitate retrieval from databases.
  * **Gene Retrieval**: By searching a **Gene ID** or symbol, users can find comprehensive details, including:
      * **Official Full Name and Symbol**: (e.g., Hemoglobin subunit alpha 2, symbol **HBA2**).
      * **Gene Type**: For example, identifying if a gene is **protein-coding**.
      * **Genomic Context**: Describes the exact physical location of a gene, such as its chromosome, arm, and region (e.g., 16p13.3).
      * **Functional Summary**: Information about what the gene does, such as encoding a subunit of hemoglobin that carries oxygen in red blood cells.
      * **Variations**: Tools like the **Variation Viewer** show genetic variations; darker colors often represent more "deadly" or clinically significant variations.

### Sequence Formats and Search Tools

The document explains how to obtain and use standardized sequence formats for analysis.

  * **FASTA Sequence**: A text-based format for representing either nucleotide (DNA/RNA) or peptide (protein) sequences using single-letter codes.
  * **BLAST (Basic Local Alignment Search Tool)**: A popular feature of NCBI that allows users to compare an input "query" sequence against a massive database.
      * **Purpose**: It helps study unknown sequences, find regions of similarity, and identify similar sequences already found by other researchers.
      * **Statistical Significance**: Results include a **Query Cover** (percentage match) and an **E value** (Expectation value).
      * **E Value**: A measure of how likely a match could occur by chance; a lower E value indicates a more statistically significant and better result.
  * **PDB ID**: A unique identifier for the **Protein Data Bank**, which contains 3D structural data for large biological molecules.

### Multiple Sequence Alignment (MSA) and Evolutionary Studies

Comparing sequences across different organisms provides biologically relevant information and clues about the process of evolution.

  * **Multiple Sequence Alignment (MSA)**: An analysis used to compare three or more biological sequences (protein or DNA) to identify similarities and differences.
  * **Clustal Omega**: An open-access MSA program that aligns divergent sequences to visualize variations and gaps.
  * **Phylogenetic Analysis**: Evolutionary relationships are visualized through diagrams:
      * **Cladogram**: A branching diagram showing the relationship between a number of species based on their shared characteristics.
      * **Phylogram**: A phylogenetic tree that has branch lengths proportional to the amount of character change.
  * **Neighbor-Joining Tree**: A specific type of "bottom-up" clustering method used for the creation of phylogenetic trees.

The lecture concludes by noting that future sessions will cover protein structure visualization, pathway analysis, molecular simulations, and **docking experiments** to study how drugs interact with proteins.
