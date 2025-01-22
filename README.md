# Leaf Disease Detection with GLCM for Feature Extraction

## 📌 Overview
This project focuses on detecting leaf diseases using **Gray-Level Co-occurrence Matrix (GLCM)** for feature extraction. GLCM helps in analyzing texture features from leaf images, which are then used for classification. The goal is to develop an automated system that assists farmers and agriculturists in identifying plant diseases efficiently.

## 📂 Dataset
- The dataset consists of healthy and diseased leaf images.
- Preprocessed using image resizing, noise reduction, and enhancement techniques.

## 🛠️ Technologies Used
- **Python**
- **OpenCV** for image processing
- **GLCM (Gray-Level Co-occurrence Matrix)** for feature extraction
- **Machine Learning (SVM, Random Forest, etc.)** for classification
- **Matplotlib & Seaborn** for visualization

## 🔬 Methodology
1. **Data Preprocessing**
   - Image resizing, denoising, and contrast enhancement.
2. **Feature Extraction using GLCM**
   - Extracts texture features such as contrast, correlation, energy, and homogeneity.
3. **Model Training**
   - Uses classifiers like **SVM, Random Forest, or CNN** for disease classification.
4. **Evaluation**
   - Accuracy, precision, recall, and F1-score are used to assess performance.

## 🚀 Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/leaf-disease-detection.git
   cd leaf-disease-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the model:
   ```sh
   python main.py
   ```
4. Upload leaf images for testing:
   ```sh
   python test.py --image path/to/image.jpg
   ```

## 📊 Results
- Achieved **X% accuracy** on the test dataset.
- Visualized feature maps using **GLCM-based texture analysis**.
- Classified leaf diseases into categories like **healthy, bacterial spot, mildew, etc.**

## 📜 Future Enhancements
- Integration with **deep learning models (CNN, ResNet, etc.)** for improved accuracy.
- Developing a **web application** for user-friendly disease detection.
- Expanding the dataset for better generalization.

## 🤝 Contribution
Feel free to fork this repository, raise issues, or contribute by submitting pull requests.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

