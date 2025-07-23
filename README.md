# 📄 Document Image Segmentation using CNN

This project involves segmenting document images into meaningful regions such as headers, paragraphs, tables, etc., using deep learning (U-Net CNN). The model learns from document images and their corresponding mask labels to perform pixel-wise classification.

## 🔧 Tools & Technologies
- Python 🐍
- Google Colab 📓
- OpenCV 🖼️
- TensorFlow / Keras 🤖
- NumPy, Matplotlib 📊
- Document & mask images (.png)

## 📁 Dataset Structure
project_folder/
│
├── images/ # Folder containing document images
├── masks/ # Folder containing corresponding masks
└── notebook.ipynb # Google Colab notebook

markdown
Copy
Edit

## 🚀 Steps Performed
1. **Data Loading** – Loaded `.png` images and their corresponding masks using `glob`.
2. **Preprocessing** – Resized, normalized images and masks using OpenCV and NumPy.
3. **Model Building** – Implemented U-Net architecture with Keras for segmentation.
4. **Training** – Trained the model using `fit()` on image-mask pairs.
5. **Evaluation** – Compared predictions with actual masks visually using Matplotlib.

## 📌 Output
- Visual comparisons between actual and predicted masks.
- Accuracy and loss graph during training.

## 🧠 Learning Outcome
- Gained understanding of image segmentation and document structure analysis.
- Hands-on experience with convolutional architectures (U-Net) and preprocessing image data.

## 💡 Future Work
- Improve model performance with augmentation.
- Try different architectures like DeepLab or SegNet.
- Extend segmentation to multi-class document elements.
