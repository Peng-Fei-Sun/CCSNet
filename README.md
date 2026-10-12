# CCSNet: Connectivity-Based Curvature Spectrum

Official implementation of CCSNet: Connectivity-Based Curvature Spectrum for Protein–Ligand Binding Affinity Prediction.

## Supplementary Material

The supplementary material for this paper is available at:

[https://github.com/Peng-Fei-Sun/CCSNet-Supplementary](https://github.com/Peng-Fei-Sun/CCSNet-Supplementary)

---

## Setup Environment

Create the conda environment using:

```bash
conda env create -f environment.yml
conda activate CCSNet
```

---

## Step1: Preprocess Raw Data

The PDBbind dataset can be downloaded from: [PDBbind+](https://www.pdbbind-plus.org.cn/). 
Place the raw pdb files in: `./data`

Preprocess the raw protein-ligand complex data:

```bash
python preprocess.py
```

---

## Step2: Construct Graph Data

Construct graph-based representations for model training:

```bash
python processdata.py
```

---

## Step3: Train and Evaluate the Model

Train and evaluate the CCSNet model:

```bash
python train.py
```

---

## Contact

For questions regarding this work, please contact:

**Peng-Fei Sun**  
sunpf6@mail.sysu.edu.cn

---

## Citation

```bibtex
@ARTICLE{CCSNet2026,
  author={Sun, Peng-Fei and Ren, Chuan-Xian and Yan, Hong},
  journal={IEEE Journal of Biomedical and Health Informatics},
  title={Connectivity-Based Curvature Spectrum for Protein–Ligand Binding Affinity Prediction},
  year={2026},
  doi={10.1109/JBHI.2026.3735035}
}


