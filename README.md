# 🌳 Tree Species Classification

This project is a deep learning-based classification system that identifies different tree species using image data. The model is built using Convolutional Neural Networks (CNN) and trained on a dataset of tree images. The final trained model is saved as `tree_species_model.h5`.

## 📌 Project Highlights

- Built using Python and TensorFlow/Keras
- Uses CNN for feature extraction and classification
- Pre-trained model (`tree_species_model.h5`) included
- Easily deployable for inference or retraining

## 🧪 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## 📊 Dataset

The dataset contains labeled images of various tree species. Each image is preprocessed (resized, normalized) and used to train and validate the CNN model.

## 📂 Files

- `Tree_Species_Classification.ipynb` – Jupyter Notebook with all code and outputs
- `tree_species_model.h5` – Trained model weights

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tree-species-classification.git
   cd tree-species-classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Tree_Species_Classification.ipynb
   ```

4. Use the saved model:
   ```python
   from tensorflow.keras.models import load_model
   model = load_model('tree_species_model.h5')
   ```

## ✅ Results

The model achieves good accuracy in classifying tree species. Evaluation metrics and sample predictions are shown in the notebook.

## 📸 Sample Output
<img width="984" height="606" alt="image" src="https://github.com/user-attachments/assets/2c4e92ef-528a-4272-a682-bc7d5aefd4d4" />
<img width="983" height="612" alt="Screenshot 2025-08-03 180725" src="https://github.com/user-attachments/assets/c918a2cf-c12f-4a3c-b9ea-449f0a9b3306" />
<img width="984" height="606" alt="Screenshot 2025-08-03 180744" src="https://github.com/user-attachments/assets/6b563053-e74f-423f-ae5c-6a426edab5a6" />



## 👨‍💻 Author

**Ravishankar Kumar**  
• GitHub : https://github.com/Ravishankar119
• LinkedIn : https://www.linkedin.com/in/ravishankar-kumar-119r/

## 📃 License

This project is open-source and available under the MIT License.
