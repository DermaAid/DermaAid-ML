<h1 align="center">
  DermaScan: ML Repository
</h1>

<div align="center">
[![ML Contributors](https://img.shields.io/github/contributors/Bangkit-Capstone-Project/ML_Structuring_Model?color=red)](#mlcontributors)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Bangkit-Capstone-Project/ML_Structuring_Model)
![GitHub last commit](https://img.shields.io/github/last-commit/Bangkit-Capstone-Project/ML_Structuring_Model)
[![GitHub forks](https://img.shields.io/github/forks/Bangkit-Capstone-Project/ML_Structuring_Model)](https://github.com/Bangkit-Capstone-Project/ML_Structuring_Model)
</div>

# Team Profile

### Team ID		: C242-PS440 

### Team Member	: 
(ML) M297B4KY0278 – Akbar Ariffianto – Universitas Pembangunan Nasional Veteran Yogyakarta - Active
(ML) M297B4KY2559 – Mohamad Risqi Aditiya – Universitas Pembangunan Nasional Veteran Yogyakarta - Active 
(ML) M302B4KY2233 – Kristian Suriyadharma – Universitas Pertamina - Active
(CC) C282B4KY1152 – Dimaz Ardawan – Universitas Negeri Padang - Active
(CC) C282B4KY4456 – Wahyu Isnan – Universitas Negeri Padang- Active
(MD) A282B4KY1033 - Delano Yusuf Habibie – Universitas Negeri Padang - Active
(MD) A282B4KY4523 – Yazid Aqil Assalam – Universitas Negeri Padang - Active

**Project Background:**

As a tropical country, Indonesian citizens have a very high risk of skin diseases. Based on the World Health Organization (WHO) report, the prevalence of infectious skin diseases worldwide reaches around 300 million cases per year. In Indonesia itself, the prevalence of skin diseases reaches 4.60% - 12.95% and ranks third out of 10 most common diseases (Desmawati, 2020).
Even though the numbers are high, access to specialist dermatologists is still limited, especially in remote areas where there is a lack of medical personnel with specialized skills. This slows down diagnosis and proper treatment for people with skin diseases, so their condition often worsens. In addition, there are concerns regarding violations of medical SOPs, especially in privacy examination situations where patients may feel uncomfortable or vulnerable to harassment if the examination is not accompanied by similar medical personnel.
From all these challenges, the question arises as a solution, namely "How can we help reduce the rate of skin disease sufferers more quickly and safely?" to address this question. We will develop an AI-based  application that allows users to detect skin diseases through the photos they upload. The app is designed to provide early diagnosis and treatment recommendations, so patients can take further steps more quickly and privately.


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
