# Fashion Product Classification using Multimodal Deep Learning

This project implements a high-performance fashion product classification system using Deep Learning. It utilizes a multimodal dataset consisting of images and textual metadata to categorize products into diverse classes. The training was optimized using **Kaggle TPU v3-8** to handle large-scale computations efficiently.

## 🚀 Key Features
- **Multimodal Data Integration:** Combined image data with product attributes (textual metadata) for better feature extraction.
- **TPU Acceleration:** Utilized **Tensor Processing Unit (TPU)** to accelerate the training process of heavy CNN architectures.
- **Comparative Analysis:** Evaluated the performance of six different state-of-the-art deep learning models.
- **Scalability:** Successfully processed and trained on a dataset of **44,424 images**.

## 📊 Dataset Description
The dataset contains fashion product images along with a CSV file containing metadata such as gender, category, sub-category, and article type. 

- **Total Samples:** 44,424
- **Input Types:** Images (Resized & Normalized) + Categorical Metadata.
- **Source:** [Kaggle - Fashion Product Images Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)

## 🏗️ Models Implemented
To find the most accurate classifier, the following **6 CNN architectures** were implemented and evaluated:
1. **DenseNet201**
2. **Xception**
3. **InceptionV3**
4. **EfficientNetV2M**
5. **NASNetLarge**
6. **ResNet50**

## 📈 Performance & Results
- **Best Performing Models:** Both **DenseNet201** and **Xception** achieved a peak **Validation Accuracy of 95.3%**.
- **InceptionV3** followed closely with **94.8%** accuracy.
- The models demonstrated robust generalization even when tested against new, external e-commerce images.

## 🛠️ Installation & Setup
To run this project locally or on Kaggle/Colab, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SakibJahid/Fashion-Product-Classification.git
   ```
   ```bash
   cd Fashion-Product-Classification
   ```

2. **Install dependencies:**
   ```bash
   pip install tensorflow pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Dataset Setup:**
   Download the dataset from [Kaggle](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset) and ensure the file paths match the notebook configuration.

4. **Run the Notebook:**
   Open `Fashion Product Classification with Multimodal.ipynb` in Jupyter Notebook or upload it to Kaggle/Colab to start training. 

## 🤝 Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## 📂 Repository Contents
- **Fashion Product Classification with Multimodal.ipynb:** The complete notebook containing data preprocessing, model building, and evaluation.
- **FashionProductClassification_Report.pdf:** A detailed research report covering the methodology and analysis.
