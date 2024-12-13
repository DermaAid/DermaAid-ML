<h1 align="center">
  Derma.Aid: ML Repository
</h1>

# Team Profile

### Team ID		: C242-PS440 

### Team Member	: 
- (ML) M297B4KY0278 – Akbar Ariffianto – Universitas Pembangunan Nasional Veteran Yogyakarta - Active
- (ML) M297B4KY2559 – Mohamad Risqi Aditiya – Universitas Pembangunan Nasional Veteran Yogyakarta - Active 
- (ML) M302B4KY2233 – Kristian Suriyadharma – Universitas Pertamina - Active
- (CC) C282B4KY1152 – Dimaz Ardawan – Universitas Negeri Padang - Active
- (CC) C282B4KY4456 – Wahyu Isnan – Universitas Negeri Padang- Active
- (MD) A282B4KY1033 - Delano Yusuf Habibie – Universitas Negeri Padang - Active
- (MD) A282B4KY4523 – Yazid Aqil Assalam – Universitas Negeri Padang - Active

**Project Background:**

Indonesia, as a tropical country, faces a high prevalence of skin diseases, with rates reaching 4.60%–12.95%, ranking third among the nation's most common diseases (Desmawati, 2020). Despite the urgency, access to dermatologists remains limited, especially in remote areas, delaying diagnosis and treatment. Privacy concerns during examinations further complicate the situation. To address these challenges, we propose an AI-based application enabling users to detect skin diseases through uploaded photos. This app provides early diagnosis and treatment recommendations, ensuring quicker, safer, and more private healthcare access.

**Machine Learning:** 

Our machine learning approach for the capstone involves using transfer learning with a pre-trained Convolutional Neural Network (CNN) model. We will fine-tune the model on our skin disease dataset to enhance its accuracy in classifying skin conditions. TensorFlow will be used for model training and optimization. Use TensorFlow.lite to run ML models on mobile devices.

**Project Case :**

    -'Fungal infection': 'Fungal Infections (Tinea/Ringworm)',
    -'Eczema': 'Atopic Dermatitis (Eczema)',
    -'Viral infection': 'Viral Infections (Warts/Molluscum)',
    -'Benign tumors': 'Benign Tumors (Seborrheic Keratoses)',
    -'Skin cancer': 'Skin Cancer (Basal Cell Carcinoma)',
    -'eczema': 'Eczema (General)',
    -'Benign moles': 'Benign Moles (Melanocytic Nevi)',
    -'Benign lesions': 'Benign Lesions (Keratosis-like)',
    -'melanoma': 'Skin Cancer (Melanoma)',
    -'psoriasis': 'Chronic Skin Diseases (Psoriasis/Lichen)

**Our Dataset Link:**

* [Skin Dataset With Augmentation](https://www.kaggle.com/datasets/akbariffianto/final-skin-disease)

## Overview
DermaScan is a machine learning project designed to analyze dermatological data and assist in diagnosing skin conditions. The project leverages deep learning techniques to create a model that can classify images of skin lesions or related data. It aims to provide an efficient and accurate tool for dermatological analysis.

## Features
- **Dataset Management**: Import and preprocess datasets from Kaggle.
- **Model Development**: Build and train a deep learning model using TensorFlow and Keras.
- **Evaluation**: Evaluate the model using metrics like accuracy, precision, recall, and F1 score.
- **Model Saving**: Save the trained model for future use.

## Technologies Used
- **Programming Language**: Python
- **Frameworks and Libraries**:
  - TensorFlow and Keras (Deep Learning)
  - NumPy and Pandas (Data Manipulation)
  - Matplotlib and Seaborn (Data Visualization)
  - Scikit-learn (Model Evaluation)
- **Tools**:
  - Kaggle API for dataset import

## Getting Started

### Prerequisites
Make sure you have the following installed:
- Python 3.8+
- Pip (Python package manager)
- Kaggle API credentials (kaggle.json file)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dermascan.git
   cd dermascan
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up Kaggle API:
   ```bash
   mkdir ~/.kaggle
   cp kaggle.json ~/.kaggle/
   chmod 600 ~/.kaggle/kaggle.json
   ```

### Usage
1. Run the notebook to:
   - Import and preprocess the dataset.
   - Train the model.
   - Evaluate its performance.
2. Adjust the hyperparameters and model architecture as needed.

## Acknowledgments
- Kaggle for providing the datasets.
- TensorFlow and Keras for their comprehensive deep learning frameworks.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
