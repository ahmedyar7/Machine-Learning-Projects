# 🐱🐶 Cat vs Dog Image Classifier

This project is a convolutional neural network (CNN) model designed to classify images as either a cat 🐱 or a dog 🐶. The model is trained using data augmentation techniques and is made interactive through the use of `ipywidgets` to allow users to upload and classify their own images.

## ✨ Features

- **🧠 Convolutional Neural Network (CNN):** The core model used for image classification.
- **🔄 Data Augmentation:** Enhances the training dataset by applying random transformations such as rotations, flips, and zooms.
- **🎛️ Interactive Interface:** Built using `ipywidgets`, allowing users to upload images and see predictions in real-time.

## 🛠️ Dependencies

1. **Python**
2. **Jupyter Notebook**

3. **Packages**
   ```bash
   pip install matplotlib keras tensorflow numpy ipywidgets
   ```

<div align="center">
  <span>
    <img src="https://skillicons.dev/icons?i=py" height="40" alt="python logo" style="margin: 0 10px;" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="40" alt="jupyter logo" style="margin: 0 10px;" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="40" alt="numpy logo" style="margin: 0 10px;" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" height="40" alt="matplotlib logo" style="margin: 0 10px;" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tensorflow/tensorflow-original.svg" height="40" alt="tensorflow logo" style="margin: 0 10px;" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/keras/keras-original.svg" height="40" alt="keras logo" style="margin: 0 10px;" />
  </span>
</div>

## 🚀 Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ahmedyar7/Machine-Learning-Projects.git
   cd Machine-Learning-Projects/Cat-vs-Dog-Classifier
   ```

2. **Download the Repository and navigate to the project**

## 💻 Usage

- **Training the Model:**

  - The model is trained using a dataset of labeled cat and dog images.
  - Data augmentation is applied to increase the diversity of the training set.
  - The training process includes visualizing training and validation accuracy and loss.

- **Classifying Images:**
  - Users can upload their own images of cats or dogs using the provided `ipywidgets` interface.
  - The model will output a prediction, indicating whether the image is of a cat 🐱 or a dog 🐶.

## 📊 Results

- **Model Performance:**
  - The trained CNN model achieves a certain level of accuracy on the test set (e.g., 77% accuracy).

## 💬 Acknowledgments

- **Dataset:** The dataset used for this project is publicly available and consists of labeled images of cats and dogs.
- **Libraries:** The project leverages powerful Python libraries such as TensorFlow, Keras, and `ipywidgets`.

## 🤝 Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
