# 🧠 MNIST Digit Predictor using CNN

This project demonstrates how to use a trained Convolutional Neural Network (CNN) model to predict handwritten digits from custom images. It uses the MNIST dataset model and processes user-provided images for prediction.

---

## 🚀 Features

* Load pre-trained CNN model (`.h5`)
* Preprocess custom images using OpenCV
* Predict handwritten digits (0–9)
* Display prediction with image visualization

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

---

## 📂 Project Structure

```
mnist-digit-predictor-cnn/
│
├── mnist_cnn_model.h5       # Trained CNN model
├── predict.py              # Prediction script
├── sample_images/          # Folder for test images
└── README.md               # Project documentation
```

---

## ⚙️ How It Works

1. Load the trained CNN model
2. Read a custom image using OpenCV
3. Convert image to grayscale
4. Resize to 28x28 pixels
5. Invert colors (if needed)
6. Normalize pixel values
7. Predict digit using the model

---

## ▶️ Usage

1. Clone the repository:

```
git clone https://github.com/your-username/mnist-digit-predictor-cnn.git
cd mnist-digit-predictor-cnn
```

2. Install dependencies:

```
pip install numpy opencv-python tensorflow matplotlib
```

3. Run the prediction script:

```
python predict.py
```

---

## 🖼️ Input Image Requirements

* Image should contain a single digit (0–9)
* Preferably centered
* White digit on dark background (or inversion applied)

---

## 📌 Example Output

```
Model loaded successfully
Predicted Digit: 5
```

---

## 💡 Future Improvements

* Add GUI for drawing digits
* Support real-time webcam input
* Improve accuracy with data augmentation
* Deploy as a web app

---

## 🤝 Contributing

Feel free to fork this repository and improve it. Pull requests are welcome!

---

## 📜 License

This project is open-source and available under the MIT License.
