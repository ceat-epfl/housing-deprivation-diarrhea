[![GitHub license](https://img.shields.io/github/license/ceat-epfl/sanitation-informal-settlements.svg)](https://github.com/ceat-epfl/sanitation-informal-settlements/blob/main/LICENSE)

# Housing deprivation and diarrhea in informal settlements in Abidjan.

A replicable computational workflow to assess the association between housing deprivation features and the odds of diarrhea, based on cross-sectional household surveys.

**Citation:** Pessoa Colombo V, Chenal J, Koné B, Koffi JA, Utzinger J. Spatial distributions of diarrheal cases in relation to housing conditions in informal settlements: a cross-sectional study in Abidjan, Côte d'Ivoire. Int J Urban Health. 2023. https://doi.org/10.1007/s11524-023-00786-z.

## Instructions to reproduce the analysis

### 1. Install conda

https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html

### 2. Create and activate environment

From the repository root, run:

```bash
conda env create -f environment.yml
conda activate diarrhea-informal-settlements
```

### 3. Input data

The input datasets are available in the 'data' folder.

### 4. Run the notebooks

Follow the order indicated in the names of the notebooks (order given by number in each notebook's prefix).
