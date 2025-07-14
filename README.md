
# Pet Classifier 🐶🐱  
A deep learning project by [Anurag637](https://github.com/Anurag637)

## 📌 Overview

**Pet Classifier** is a convolutional neural network (CNN)-based image classification project that identifies whether a given image is of a **cat** or a **dog**. This project demonstrates the use of TensorFlow and Keras for building and training a simple yet effective CNN model for binary image classification.

---

## 🧠 Model Highlights

- Built using TensorFlow and Keras.
- Uses `ImageDataGenerator` for data preprocessing and augmentation.
- Trained on a structured directory of pet images (dogs and cats).
- Applies binary cross-entropy loss and Adam optimizer.
- Evaluates model accuracy on validation data.

---

## 🗂️ Project Structure

```
Pet_Classifier/
│
├── Pet_Classifier.ipynb      # Jupyter notebook containing the full model pipeline
├── data/
│   ├── train/
│   │   ├── cats/
│   │   └── dogs/
│   └── validation/
│       ├── cats/
│       └── dogs/
```

> 📌 Note: You’ll need to prepare your dataset following this structure before running the notebook.

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/Anurag637/Pet_Classifier.git
   cd Pet_Classifier
   ```

2. **Install the requirements**
   ```bash
   pip install -r requirements.txt
   ```

3. **Add your dataset**  
   Organize your training and validation images in the specified folder structure inside a `data/` directory.

4. **Run the notebook**  
   Open `Pet_Classifier.ipynb` in Jupyter Notebook or any other supported IDE and execute all the cells.

---

## 📊 Results

The model achieves promising accuracy on validation data and can generalize well to unseen pet images. Final model accuracy and loss plots are included in the notebook.

---

## 🛠️ Requirements

- Python 3.7+
- TensorFlow 2.x
- NumPy
- Matplotlib
- Jupyter Notebook

Install dependencies using:

```bash
pip install tensorflow numpy matplotlib notebook
```

---

## ✍️ Author

**Anurag Singh**  
[GitHub Profile](https://github.com/Anurag637)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
