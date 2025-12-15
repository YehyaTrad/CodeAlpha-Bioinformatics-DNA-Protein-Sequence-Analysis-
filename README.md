# Protein Sequence Analysis Using BLAST

## 📘 Project Overview
This project was completed as part of the **CodeAlpha Bioinformatics Internship**.  
The objective of this task is to perform protein sequence analysis using the **NCBI BLAST** tool in order to identify homologous proteins and analyze evolutionary and functional similarities.

---

## 🧬 Protein Information
- **Protein Name:** Hemoglobin Subunit Beta
- **Organism:** Homo sapiens
- **UniProt ID:** P68871
- **Sequence Format:** FASTA

---

## 🛠️ Tools & Databases Used
- **UniProt** – Protein sequence retrieval
- **NCBI BLAST (Protein BLAST)** – Sequence similarity analysis
- **Database:** Non-redundant protein sequences (nr)

---

## 🔬 Methodology
1. Retrieved the Hemoglobin beta protein sequence from UniProt in FASTA format.
2. Performed a Protein BLAST search using default parameters.
3. Identified the top 5 homologous protein sequences.
4. Analyzed sequence similarity using:
   - Percent Identity
   - Query Coverage
   - E-value
5. Examined conserved regions using sequence alignment.

---

## 📊 Results
- The top BLAST hits showed **high sequence identity and full query coverage**.
- Very low **E-values (e.g., 1e-97)** indicated statistically significant alignments.
- Conserved amino acid regions suggest strong evolutionary conservation.

---

## 📁 Repository Contents
- `BLAST_Report.pdf` – Detailed analysis report
- `hemoglobin_beta.fasta` – Protein sequence file
- `blast_top5_table.png` – BLAST results table screenshot
- `blast_alignment.png` – Alignment visualization

---

## 🧾 Conclusion
The BLAST analysis confirmed that Hemoglobin subunit beta is highly conserved across species, reflecting its critical biological function. This project demonstrates the effective use of BLAST for protein sequence analysis and comparative bioinformatics.

---

## 📌 Internship
**Program:** CodeAlpha Bioinformatics Internship  
**Task:** Task 1 – DNA/Protein Sequence Analysis
