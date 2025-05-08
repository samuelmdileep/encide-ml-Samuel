Cat vs Dog Image Classifier

A deep learning project built for the ENCIDE ML Challenge to classify images as either **cat** or **dog** using a Convolutional Neural Network (CNN).

* Dataset

The dataset was sourced from Kaggle and includes:

- `cats_set`: 500 cat images
- `dogs_set`: 500 dog images

Images were organized into folders as follows:

/data
├── /cats
└── /dogs

How to Run

1. Open `cat_vs_dog_classifier.ipynb` in Google Colab.
2. Upload the dataset to your Colab environment in the structure above.
3. Run all cells in sequence to:
   - Preprocess and normalize the images
   - Train the CNN model
   - Evaluate model performance
   - Generate predictions on test images
4. A `submission.csv` file will be created with predictions in the required format:

filename,prediction
cat.jpg,cat
dog.JPG,dog

   
## 📊 Model Performance

The model was trained with early stopping and image augmentation. Accuracy curves for training and validation are plotted to visualize performance.
![download](https://github.com/user-attachments/assets/b8a0ee50-d65a-4d9a-abdb-c06ba5d9f028)(graph)

Final Training Accuracy: 86.26%
Final Validation Accuracy: 72.40%

## 🛠️ Tech Stack

- **Language**: Python
- **Platform**: Google Colab
- **Libraries**: TensorFlow, Keras, Matplotlib, PIL

## 📁 Repo Structure

- `cat_vs_dog_classifier.ipynb` – Complete Colab notebook
- `submission.csv` – Final predictions
- `README.md` – Project overview and instructions

---

> Developed as part of the ENCIDE ML Challenge by [Samuel M Dileep]

