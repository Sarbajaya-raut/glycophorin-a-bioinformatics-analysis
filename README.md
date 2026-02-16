
# Glycophorin A – Structural and Functional Analysis

## Objective
To perform a comprehensive bioinformatics analysis of human Glycophorin A (UniProt ID: P02724), including sequence retrieval, similarity search, multiple sequence alignment, phylogenetic analysis, and structural alignment.

## Methodology
- **Data Retrieval**: UniProt, Pfam, InterPro
- **Similarity Search**: BLASTp against PDB and RefSeq databases (NCBI)
- **Multiple Sequence Alignment**: MultAlin
- **Phylogenetic Analysis**: MUSCLE (via EBI) and ClustalW
- **Structural Alignment**: PyMOL (PDB IDs: 2KPE and 2KPF)
- **Visualization**: PyMOL, online tree viewers

## Results

### 1. Protein Information
- **Protein**: Glycophorin A (*Homo sapiens*)
- **Accession**: P02724
- **Length**: 150 amino acids
- **Subcellular Location**: RBC membrane (type I membrane protein)
- **Key Functions**: Membrane stability, pathogen receptor, blood group antigen

### 2. BLAST Search
![BLAST against PDB](results/blast_pdb.png)
*Figure 1: BLAST results against PDB database – top hits with known structures.*

![BLAST against RefSeq](results/blast_refseq.png)
*Figure 2: BLAST results against RefSeq database – orthologs in other species.*

### 3. Multiple Sequence Alignment
![MSA from MultAlin](results/msa_alignment.png)
*Figure 3: Multiple sequence alignment showing conserved and variable regions.*

### 4. Phylogenetic Tree
![Phylogenetic tree – species](results/phylo_species.png)
*Figure 4: Phylogenetic tree of Glycophorin A across different species.*

![Phylogenetic tree – variants](results/phylo_variants.png)
*Figure 5: Phylogenetic tree of human Glycophorin A variants.*

### 5. Structural Alignment
![Structural alignment in PyMOL](results/structural_alignment.png)
*Figure 6: Superimposition of NMR structures 2KPE and 2KPF. RMSD = 0.737 Å (high similarity).*

### 6. Post-Translational Modifications
- Heavily O-glycosylated with sialic acid residues; critical for pathogen binding (e.g., *Plasmodium falciparum*).

## Repository Structure
