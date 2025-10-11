# BD Sports-10 Dataset: Supporting Code, Notebooks & Sample data.

## This repository provides **Jupyter Notebooks** for preprocessing, video resizing, and automated face blurring for the **BD Sports-10 dataset**, a collection of Bangladeshi Sports videos.

---

## 📂 Repository Contents
- `data_preprocessing_trimming_and_export_figures`  → Contains the data preprocessing, standardization, trimming, and export figures. These images illustrate the workflow followed during dataset preparation using Adobe Premiere Pro and Media Encoder.  
   - `Figure_01.jpg`
   - `Figure_02.jpg`
   - `Figure_03.jpg`
   - .
   - .
   - .
   - `Figure_17.jpg`

- `data_sample/` → Small sample videos for demonstration:
  - `resized_224x224/` → 3 sample videos in 224×224 resolution
  - `original_1920x1080/` → 3 sample videos in 1920×1080 resolution
    
- `notebooks/` → Jupyter notebooks with instructions:
  - `automated-face-blurring-using.ipynb`    → Contains dataset face blurring code with description.
  - `dataset-preparation-and-preprocessing-for-bd-sport.ipynb`   → Contain Dataset preparation and preprocessing, and ready to implement in DL model code with description 
  - `video-resizing-script-for-bd-sports-10-datasets.ipynb`    → Contain the Video resizing code with a description.
  - `bd-sports-10-dataset-download-from-pypi.ipynb`    → Contain the BD Sports-10 dataset using the PyPi module with description.
    
- `sample_gifs_for_github/` → Contains 2 sample GIFs for preview on GitHub: Hari_Vanga_025_resized_sample.gif and Joldanga_005_original_sample.gif.
- `README.md` → Documentation and instructions
- `LICENSE` → MIT License (for code)
- `CITATION.cff` → Citation metadata

---

## 📂 Repository Structure

```plaintext
📂 BD-Sports-10/
│
├── data_preprocessing_trimming_and_export_figures/
│   ├── Figure_01.jpg
│   ├── Figure_02.jpg
│   ├── Figure_03.jpg
│   ├── . 
│   ├── .
│   ├── .
│   └── Figure_17.jpg
│
│
├── data_sample/
│   ├── resized_224x224/
│   │   ├── Hari_Vanga_025.mp4
│   │   ├── Joldanga_010.mp4
│   │   └── Lathim_105.mp4
│   │
│   └── original_1920x1080/
│       ├── Joldanga_005.mp4
│       ├── Kanamachi_127.mp4
│       └── Kolagach_299.mp4
│
├── notebooks/
│   ├── automated-face-blurring-using.ipynb
│   ├── dataset-preparation-and-preprocessing-for-bd-sport.ipynb
│   ├── video-resizing-script-for-bd-sports-10-datasets.ipynb
|   └── video-resizing-script-for-bd-sports-10-datasets.ipynb
│
├── sample_gifs_for_github/
│   ├── Hari_Vanga_025_resized_sample.gif
│   └── Joldanga_005_original_sample.gif
│
├── CITATION.cff
├── LICENSE
└── README.md

```


## 🎥 Sample Video Preview
Here are short preview clips from the BD Sports-10 dataset:

**Resized (224×224 pixels) sample:**  
![Resized Sample](sample_gifs_for_github/Hari_Vanga_025_resized_sample.gif)

**Original (1920×1080 pixels) sample:**  
![Original Sample](sample_gifs_for_github/Joldanga_005_original_sample.gif)

> ⚠️ These are only sample videos. The full dataset must be downloaded from the official sources below.

---
## 📊 Dataset Access via PyPI

You can easily download and use the **BD Sports-10 Dataset** directly in your Python environment or notebooks (Kaggle, Colab, etc.) using `pip`. Both the **resized** and **original** versions are available as PyPI packages.

### 🚀 Install the Resized Version (224×224 pixels)
Optimized for **machine learning** and **deep learning** tasks:

```bash
!pip install bd-sports-10-resized==0.4.0
```
---
### 📦 Install the Original Version (Full HD 1920×1080 pixels)

```bash
!pip install bd-sports-10-original==0.2.0
```
---

## 📊 Dataset Access
The full dataset can be downloaded from:

- **Resized Version (224×224 pixels):** [Mendeley Data](https://data.mendeley.com/datasets/rnh3x48nfb/1)
- [![BD Sports-10 Dataset (224×224 Pixels, Resized Version)](https://img.shields.io/badge/BD_Sports_10_Resized_Version-224x224-blue)](https://data.mendeley.com/datasets/rnh3x48nfb/1)  
  
- **Original Version (1920×1080 pixels):** [Science Data Bank](https://doi.org/10.57760/sciencedb.24216)
- [![BD Sports-10 Dataset (1920×1080 Pixels, Original Version)](https://img.shields.io/badge/BD_Sports_10_Original_Version-1920x1080-green)](https://doi.org/10.57760/sciencedb.24216)


The dataset is **licensed under Creative Commons Attribution 4.0 International (CC BY 4.0)**.


## 📜 Citation: BD Sports-10 Dataset (224×224 Pixels, Resized Version)
### Please cite the dataset if used:

- Tanzim, Wazih Ullah; Minhaz Hossain, Syed Md.; Supta, Niloy Barua; Shifa, Shifatun Nur (2025). **“BD Sports-10 Dataset (224×224 Pixels, Resized Version)”**, Mendeley Data, V1, DOI: [10.17632/rnh3x48nfb.1](https://doi.org/10.17632/rnh3x48nfb.1)  

---
## 📚 BibTex Citation (Resized Dataset):
```bibtex
@misc{tanzim2025_bdsports10_resized,
  author       = {Tanzim, Wazih Ullah and Minhaz Hossain, Syed Md. and Supta, Niloy Barua and Shifa, Shifatun Nur},
  title        = {{BD Sports-10 Dataset (224×224 Pixels, Resized Version)}},
  year         = {2025},
  publisher    = {Mendeley Data},
  version      = {V1},
  doi          = {10.17632/rnh3x48nfb.1},
  url          = {https://data.mendeley.com/datasets/rnh3x48nfb/1}
}
```

## 📜 Citation: BD Sports-10 Dataset (Original Dataset)
### Please cite the dataset if used:

- Wazih Ullah Tanzim, Syed Md. Minhaz Hossain, Niloy Barua Supta, et al. (2025). **“BD Sports-10 Dataset”**, V4. Science Data Bank. DOI: [10.57760/sciencedb.24216](https://doi.org/10.57760/sciencedb.24216)  

---

## 🔖 APA Citation (Original Dataset):
- Tanzim, W. U., Hossain, S. M. M., Supta, N. B., & Shifatun Nur, S. (2025, October). BD Sports-10 Dataset (Version V4) [Data set]. Science Data Bank. https://doi.org/10.57760/sciencedb.24216

---

## 📚 BibTex Citation (Original Dataset):

```bibtex
@misc{tanzim2025_bdsports10_original,
  author       = {Wazih Ullah Tanzim and Syed Md. Minhaz Hossain and Niloy Barua Supta and Shifatun Nur Shifa},
  title        = {{BD Sports-10 Dataset}},
  year         = {2025},
  month        = {October},
  publisher    = {Science Data Bank},
  version      = {V4},
  doi          = {10.57760/sciencedb.24216},
  url          = {https://doi.org/10.57760/sciencedb.24216}
}
```



## 📄 License

- **Code in this repository** → MIT License (permissive, see LICENSE file)  
- **Dataset** → CC BY 4.0 (download separately, attribution required)
