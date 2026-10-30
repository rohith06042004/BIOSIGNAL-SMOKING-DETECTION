BIOSIGNAL SMOKING DETECTION OF X-RAY IMAGES
Project Overview
This project uses deep learning and transfer learning with EfficientNetB0 to classify chest X-ray images into two categories:
* Pneumonia
* Emphysema
The model is trained using TensorFlow and Keras.
Technologies Used
* Python
* TensorFlow
* Keras
* EfficientNetB0
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
Project Workflow
1. Load and prepare the chest X-ray dataset.
2. Resize images to 224 × 224 pixels.
3. Split the dataset into training, validation, and testing sets.
4. Build an EfficientNetB0-based classification model.
5. Train the model using binary cross-entropy and the Adam optimizer.
6. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
7. Generate Grad-CAM visual explanations.
Model Performance
* Test accuracy: approximately 99.22%.
* The evaluation results and confusion matrix are available in the results folder.
Note: This result is from the selected dataset and test split. It does not establish clinical performance or prove that emphysema was caused by smoking.
Project Structure
BIOSIGNAL-SMOKING-DETECTION/
├── BIOSIGNAL_SMOKING_DETECTION.ipynb
├── README.md
├── models/
│   └── lung_model.keras
├── results/
│   ├── training_history.json
│   ├── evaluation_results.json
│   ├── clean_evaluation_results.json
│   ├── prediction_result.json
│   ├── training_graphs.png
│   └── gradcam_result.png
└── requirements.txt
Disclaimer
This project is for educational and research purposes only. It is not intended for medical diagnosis.