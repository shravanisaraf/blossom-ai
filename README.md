# BlossomAI 🌸
A **flower classification web app** that uses a Convolutional Neural Network (CNN) model to identify flower species from images. This project combines deep learning with a simple web interface built using Flask, allowing users to upload flower images and receive real-time predictions.

## Project Overview
BlossomAI is designed to:
- Predict the species of flowers from images using a pre-trained CNN model (VGG16).
- Provide an intuitive web interface for users to upload their own flower photos.
- Display predictions along with the model’s confidence scores.

This project is part of a machine learning portfolio to showcase deep learning skills and model deployment in a web application.

---

## Features
- 🌼 **Upload Flower Images**: Users can upload flower images to the web app for classification.
- 🌻 **Supports 102 Flower Categories**: The model is trained on the **102 Category Flower Dataset** from Oxford University.
- 🌸 **Interactive UI**: A simple, user-friendly interface built with HTML/CSS and Flask.
- 🌺 **Real-time Predictions**: Get instant feedback on the predicted flower species after image upload.

---

## Technologies Used
- **Backend**: Python, Flask
- **Machine Learning**: TensorFlow, Keras (VGG16 model for transfer learning)
- **Frontend**: HTML, CSS
- **Data Visualization**: Matplotlib, Plotly (for optional data insights)
- **Deployment**: Heroku (or your chosen platform)

---
```md
## How to Run the Project Locally

### 1. Clone the Repository
First, clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/BlossomAI.git
cd BlossomAI
```
### 2. Install Dependencies
Install all necessary dependencies from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```
### 3. Add the Pre-trained Model
Download the pre-trained VGG16 model (or the `model.h5` file) and place it inside the `model/` directory. If you don't have a model file, you can train your own using the code provided.

### 4. Run the App
Start the Flask app by running:

```bash
python app.py
```
---

## Model Training
The model was trained on the **102 Category Flower Dataset** using the following steps:

- **Model Architecture**: Used the pre-trained VGG16 model for feature extraction.
- **Custom Layers**: Added custom dense layers to classify 102 flower species.
- **Data Augmentation**: Applied augmentation techniques (rotation, zooming, flipping) to increase dataset variability.
- **Training**: Trained the model for 25-30 epochs with early stopping to avoid overfitting.

You can retrain the model by using the same dataset and following the steps in `train_model.py`.

---

## Deployment
This web app is deployed on **Heroku** (or whichever platform you choose). You can check the live version here:

**BlossomAI Web App**

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Future Enhancements
- 🧠 Improve the model's accuracy with more sophisticated architectures.
- 📊 Add an interactive data insights section with visualizations of flower classification results.
- 🌍 Expand the dataset to include more flower species from different regions.

---

## Credits
- **Dataset**: 102 Category Flower Dataset from Oxford University.
- **Pre-trained Model**: VGG16 model from Keras applications.
- **Inspiration**: This project was inspired by the need to showcase machine learning skills with a visually engaging and practical web application.

---

## Contact
If you have any questions or want to contribute, feel free to reach out or submit a pull request. 😊
```
