# 🐱🐶 Cat vs Dog Image Classifier

A deep learning project developed for the **ENCIDE ML Challenge** to classify images as either **cat** or **dog** using a Convolutional Neural Network (CNN).

---

## 📂 Dataset

The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/aleemaparakatta/cats-and-dogs-mini-dataset):

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
1.jpg => dog
10.jpg => cat
11.jpg => cat
12.jpg => dog
13.jpg => dog
14.jpg => cat
15.jpg => dog
16.jpg => cat
17.jpg => dog
18.jpg => cat
19.jpg => dog
2.jpg => dog
20.jpg => dog
3.jpg => cat
4.jpg => dog
5.jpg => cat
6.jpg => dog
7.jpg => cat
8.jpg => cat
9.jpg => cat

   
## 📊 Model Performance

The model was trained with early stopping and image augmentation. 

**Final Metrics:**

-✅ Final Training Accuracy: 88.86%

-✅Final Validation Accuracy: 79.17%

📈 Accuracy Curves:

![image](https://github.com/user-attachments/assets/f41c21a2-3a5a-44c0-aa4d-ad768b0af140)



---

## 🛠️ Tech Stack

- **Language**: Python
- **Platform**: Google Colab
- **Libraries**: TensorFlow, Keras, Matplotlib, PIL

## 📁 Repo Structure

📦 Project Root
├── cat_vs_dog_classifier.ipynb # Main notebook
├── submission.csv # Final predictions
└── README.md # Project guide


---

>🔬 Developed as part of the ENCIDE ML Challenge by [Samuel M Dileep]

