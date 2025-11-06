# Triplet-Neural-Net-for-signatures-classification-learning

## 1. Project Overview
Signature Verification using Triplet Network Architecture. This project implements a triplet loss neural network for distinguishing between genuine and forged signatures. The dataset includes 24 authentic and 30 counterfeit signatures per subject, focusing on robust biometric authentication.

## 2. Problem Statement
The project addresses the challenge of automated signature verification, which is crucial for:
- Document authentication
- Financial transaction security
- Identity verification systems
- Fraud prevention

Traditional classification methods struggle with signature verification due to high intra-class variance and low inter-class variance. Triplet networks learn a feature embedding where genuine signatures are clustered together and separated from forgeries.

## 3. Dataset
**Source:** [Kaggle - Handwritten Signature Datasets](https://www.kaggle.com/datasets/ishanikathuria/handwritten-signature-datasets)

**Structure:**
DATASET
|---1
|---|---images
|---2
|---|---images
.
.
.



**Dataset Characteristics:**
- Multiple subjects with unique signature sets
- 24 genuine signatures per subject
- 30 forged signatures per subject
- Image-based format requiring preprocessing

## 4. Methodology

### Architecture Choice
Triplet Network was selected because:
- Learns relative similarity between samples
- Effective for verification tasks with limited data
- Creates meaningful embedding space for signatures
- Handles intra-class variation better than traditional classification

### Model Architecture
- **Base Network:** CNN feature extractor
- **Loss Function:** Triplet Loss
- **Distance Metric:** Euclidean distance in embedding space

### Evaluation Metrics
- Accuracy
- Precision
- Recall

## 5. Installation & Usage

### Requirements
```bash
!pip install kagglehub pandas matplotlib numpy pillow tensorflow seaborn scikit-learn
```


## Results 
<img width="1111" height="547" alt="{4F3AFC1D-24AE-4089-9782-C7C1FF7D5AAF}" src="https://github.com/user-attachments/assets/6ee98bfa-e474-421c-8411-f3f903db23d4" />

<img width="1136" height="757" alt="{5D2A9A78-49FA-460C-B53A-FB15C525F73B}" src="https://github.com/user-attachments/assets/973b3a13-386c-402f-bde5-1062f8bbbd82" />

