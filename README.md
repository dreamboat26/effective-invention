# Effect of Screen Time on Glaucoma

This repository contains the supplementary materials, implementation details, and data associated with the paper **"Effect of Screen Time on Glaucoma"** by **Mahule Roy**.

---

## Abstract

Glaucoma, a group of eye conditions characterized by elevated intraocular pressure (IOP) and optic nerve damage, is significantly influenced by environmental, biological, and lifestyle factors. This study explores the impact of prolonged screen time on IOP levels, incorporating machine learning models for glaucoma detection and proposing a digital wellness application for patient management. The findings highlight the relationship between screen time, stress, and glaucoma progression, emphasizing the potential of lifestyle interventions like yoga to mitigate these risks.

---

## Repository Contents

### 1. **Paper**
- A PDF copy of the full research paper is available in the `docs/` folder.

### 2. **Code**
- Python scripts for:
  - Preprocessing the Kaggle dataset: EyePACS-AIROGS-light-V2.
  - Training and testing glaucoma detection models, including U-Net, MobileNetV3, ConvNeXtTiny, Xception etc.
  - Data augmentation using Generative Adversarial Networks (GANs).
- Code is located in the `scripts/` folder with a `requirements.txt` file for dependencies.

### 3. **Data**
- This repository references the publicly available Kaggle dataset [EyePACS-AIROGS-light-V2](https://www.kaggle.com/datasets/deathtrooper/glaucoma-dataset-eyepacs-airogs-light-v2). 
- Please download the dataset from Kaggle and place it in the dataset zip file.

### 4. **Models**
  - U-Net (optimized for glaucoma detection).
  - Xception, MobileNetV3 and ConvNeXtTiny architectures.

### 5. **Results**
- Visualization of training and testing losses, accuracy, AUC-ROC curves, and other metrics can be found in the respective .ipynb files.

### 6. **Digital Wellness App**
- A conceptual design and implementation plan for the proposed mobile app aimed at managing screen time and IOP for glaucoma patients.
  
---

## Key Findings

- **Screen Time Impact**: Prolonged exposure to screens leads to significant increases in IOP, especially under specific conditions such as neck flexion.
- **Machine Learning Role**: U-Net models demonstrated the highest efficacy in glaucoma detection, with metrics like AUC-ROC and F1 Score surpassing other architectures.
- **Lifestyle Interventions**: Incorporating yoga, reducing screen time, and monitoring digital habits can alleviate IOP and promote eye health.

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/dreamboat26/effective-innovation.git
   cd effective-innovation
   ```
2. Install dependencies:
    ```bash
   pip install -r requirements.txt
    ```
3. Run training scripts
4. Visualize results

## Citation

If you use this repository, please cite my work:

```bibtex
@inproceedings{mahule2024effect,
  title={Effect of Screen Time on Glaucoma},
  author={Mahule, Roy},
  conference={Proceedings of the International Conference on Advances and Challenges in Medical Technology Translation (ICACMTT)},
  year={2024},
  publisher={TransMedTech},
  doi={10.13140/RG.2.2.20463.75685},
  url={https://paperswithcode.com/paper/effect-of-screen-time-on-glaucoma}
}
```

## Acknowledgments

This research was conducted under the guidance of Dr. Jabia Chowdhury, Department of Biomedicine and Pharmaceutics, Texas A&M University. I thank Kaggle for the dataset and all reviewers for their valuable insights.
