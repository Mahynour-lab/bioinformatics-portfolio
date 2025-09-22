# Project 1: Sequence Analysis

## 🎯 Objective
Analyze a DNA sequence from NCBI and calculate:
- Sequence length  
- GC content  
- Base composition  

This project demonstrates beginner-level sequence analysis using R and the **Biostrings** package.

---

## 📂 Data
- Source: NCBI GenBank  
- Example Accession Number: **U14680.1**  
- File: [sequence.fasta](./data/sequence.fasta)  

---

## 🛠 Tools
- R programming language  
- Bioconductor package: `Biostrings`

---

## 📜 Steps
1. Download a DNA FASTA sequence from NCBI.  
2. Place the file in the `data/` folder.  
3. Run the R script in `scripts/analysis.R`.  
4. The script will compute:  
   - Sequence length  
   - GC content (%)  
   - Base frequencies (A, T, G, C)  
5. Results and plots will be saved in the `results/` folder.  

---

## 📊 Example Results
- Sequence length: `699 bp`  
- GC content: `42.48927  %`  
- Base composition:  
  - A: 2.19 %  
  - T: 1.83 %  
  - G: 1.46 %  
  - C: 1.51 %  

Plots are available in the [results](./results/) folder.
