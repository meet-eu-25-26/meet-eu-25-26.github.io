# meet-eu-25-26.github.io

# 🧬 Computational Biology Project – Identification of Inhibitors of SLC6A20 (SIT1)

## 🎯 Course Overview
This course challenges students to **develop a complete computational biology project**, addressing an **open and ambitious biological question**.  
The central theme this year is:

> **Identification of putative inhibitors for the SLC6A20 transporter (SIT1) and characterization of the molecular determinants of its specificity.**

Students will integrate **structural bioinformatics, data analysis, and automation** to discover small molecules that selectively inhibit SLC6A20.

---

## 🧠 Biological Context

### The Biological Problem
**SLC6A20 (SIT1)** is a membrane transporter that moves **glycine and proline** across cell membranes.  
It belongs to the **SLC6 family**, which includes neurotransmitter transporters (GAT, SERT, DAT, etc.) and amino acid transporters.  

SLC6A20 is clinically relevant because:
- It is a **therapeutic target for diabetes**  
- It is an **emerging target in COVID-19 research**

Understanding how it recognizes its substrates and how its function can be inhibited has important biomedical implications.

---

## 🧩 The SLC6 Family and LeuT Fold

SLC6 transporters adopt the **LeuT fold**, with 12 transmembrane helices organized into:
- **Static domain**  
- **Mobile domain** enabling transport through conformational changes  

During the transport cycle, the protein alternates between:
- **Outward-open**  
- **Occluded**  
- **Inward-open**  

Several **3D structures of SLC6A20 and its homolog SLC6A19** are available and will guide your analysis.

---

## 🧬 SLC6A20 (SIT1) – Key Information

| Conformation | Ligand | PDB | Description |
|--------------|---------|-----|------------|
| Occluded | Proline (substrate) | 8I91 | SLC6A20 bound to its natural substrate |
| Inward-Open | Tiagabine (inhibitor) | 8WM3 | SLC6A20 bound to a known inhibitor |
| Outward-Open | Model | SIT1_Model_OO | Homology model based on SLC6A19 |

---

## 🧪 Course Objectives

Design and implement a **pipeline** that:

1. Analyzes the **sequence and/or structure** of SLC6A20 and homologs.  
2. Identifies and characterizes **binding sites** (orthosteric and/or allosteric).  
3. Evaluates **residue specificity** among SLC6 homologs.  
4. Screens a set of **small molecules** to identify potential inhibitors.  
5. Produces a **ranked list of inhibitors** based on interaction and specificity scores.  

> The entire process must be **automated, reproducible, and well-documented**.

---

## 🧰 Available Resources

**Data/**
- `SLC6A19-20.pse` – PyMOL session with annotated protein-ligand complexes  

**Docs/**


---

## 📋 Deliverables

Each group must provide:

1. 🧾 **Fully automated program or pipeline**  
   - Accepts example inputs and produces results without manual intervention  

2. 📈 **Clear documentation**
   - Instructions for installation and execution  
   - Description of inputs, outputs, and pipeline logic  

3. 📊 **Results**
   - List of binding site residues with specificity scores  
   - Ranked top 10 predicted inhibitors  
   - Optional: confidence or interaction scores  

4. 💬 **Report or presentation**
   - Explaining scientific rationale, methodology, and results  

---

## 🧪 Optional Auxiliary Tasks

### 1. Small Molecule Dataset
- Retrieve analogs from **ChemBL**  
- Repurpose ligands from **DrugBank**  
- Apply **Deep Docking (DD_protocol)** for large-scale screening  

### 2. Conformational Sampling
- Use the **outward-open homology model**  
- Generate alternative conformations with **BioEmu**  
- Consider different **isoforms of SLC6A20 (V1 and V2)**

---

## 🎓 Expected Outcomes / Learning Goals

By completing this course, students will be able to:
- Integrate **biological and computational reasoning**  
- Manipulate **sequence and structure data**  
- Build **reproducible computational pipelines**  
- Apply **molecular docking or deep learning approaches**  
- Interpret and communicate complex bioinformatics results  

---

## 🧭 Suggested Workflow

```text
1. Understand the target and gather structural data
2. Define binding pockets and specificity
3. Build or retrieve compound datasets
4. Implement and automate the pipeline
5. Test, validate, and document
6. Present results
