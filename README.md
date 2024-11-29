<h1 align="center">
  DermaScan: ML Repository
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

* Dataset
  * [Skin Dataset With Augmentation](https://www.kaggle.com/datasets/akbariffianto/final-skin-disease)

## Prerequisites
1. [Jupyter Notebook](https://test-jupyter.readthedocs.io/en/latest/install.html) or [Google Colab](https://colab.research.google.com/)
2. Kaggle API Token → [Generate](https://github.com/Kaggle/kaggle-api#api-credentials)
3. [Python](https://www.python.org/downloads/) version 3.6 or above
4. Latest version of Tensorflow 2.5 (or you can update again by rerunning .ipynb and updating models)
