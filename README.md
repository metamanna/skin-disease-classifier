# skin-disease-classifier
Deep learning image classification model for detecting and classifying skin diseases from dermatology images using TensorFlow and Keras.

# Skin Disease Classifier

A deep learning image classification model for detecting and classifying skin diseases from dermatology images using **TensorFlow** and **Keras**.

## 📌 Project Overview
This project uses a Convolutional Neural Network (CNN) to classify skin disease images into multiple categories.  
The dataset consists of labeled dermatology images, and the model is trained to recognize patterns associated with different skin conditions.


## 📊 Dataset
The dataset used is **Skin Disease Classification Dataset**.  
Due to size limits, it is not included in the repository.

**Download link:** https://universe.roboflow.com/skincare-gxqjb/skincare-8dmzr/dataset/5

Once downloaded, place the extracted dataset in the `data/` folder.

## 🛠 Installation & Setup
1.  git clone https://github.com/metamanna/skin-disease-classifier.git
   cd skin-disease-classifier

2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook or training script:
jupyter notebook notebooks/skin_disease_classifier.ipynb
or
python src/train.py

🧠 Model Architecture
The model is a CNN built with TensorFlow and Keras, including:

Convolutional layers

MaxPooling layers

Dropout layers for regularization

Dense layers for classification

📈 Results
Achieved X% accuracy on the test dataset.

Model performs well in differentiating between the given skin disease classes.

🚀 Future Improvements
Add data augmentation for better generalization.

Experiment with transfer learning using pre-trained models.

Deploy as a web app for real-time predictions.

📜 License
This project is licensed under the MIT License.
