
---

# FashionNet: Simple Apparel Classifier with PyTorch

This repository contains a PyTorch implementation of a neural network designed to classify images from the Fashion MNIST dataset. The dataset consists of grayscale images of various clothing items, with each image being 28x28 pixels.

## Project Overview

The project includes the following key components:

- **Data Loading and Preprocessing**: The Fashion MNIST dataset is loaded and split into training, validation, and test sets. The images are normalized and transformed into tensors for processing by the neural network.
  
- **Model Architecture**: A simple neural network is built using PyTorch's `nn.Sequential` with layers including fully connected (linear) layers, ReLU activations, and dropout for regularization. The model outputs class probabilities using `LogSoftmax`.

- **Training and Validation**: The model is trained using the Adam optimizer and negative log likelihood loss (`NLLLoss`). The training and validation losses, as well as validation accuracy, are tracked and printed for each epoch.

- **Visualization**: The training and validation losses are plotted to observe the model's performance over time. Additionally, the model's predictions on sample images are visualized alongside the predicted class probabilities.

- **Image Prediction**: Three options are provided to predict images:
  1. **Random Image from Dataset**: Use a random image from the Fashion MNIST dataset to predict the class.
  2. **Image from URL**: Preprocess and predict the class of an image from a given URL.
  3. **Image from Local File**: Upload a local file to predict the class using the trained model. The predictions are then visualized along with the input image.

## Dependencies

- Python 3.x
- PyTorch
- torchvision
- matplotlib
- numpy
- requests
- PIL (Pillow)

You can install the required packages using:

```bash
pip install torch torchvision matplotlib numpy requests pillow
```

## Usage

### 1. Training the Model
To train the model, simply run the main script. The model will train for 25 epochs, and the training and validation losses will be displayed.

```bash
python train.py
```

### 2. Predicting from a Random Dataset Image
To predict the class of a random image from the Fashion MNIST dataset, use the following command:

```bash
python predict_random.py
```

### 3. Predicting from a URL
To predict the class of an image from a URL, use the following command:

```bash
python predict_url.py --image_url "http://example.com/image.jpg"
```

### 4. Predicting from a Local File
To predict the class of an image from a local file, use the following command:

```bash
python predict_file.py --image_path "path/to/image.jpg"
```

## Results

The model achieves a validation accuracy of approximately 88% after 25 epochs of training. The trained model can accurately predict the class of various clothing items in the Fashion MNIST dataset.

## Examples

### Training and Validation Losses

![Training and Validation Losses](https://github.com/Nightskull100/Dress-Type-Detection-using-CNN/blob/e09a0aced7fd61d2728f3875e930a70cb24d260d/Images/Training%20and%20Validation%20Losses.png)



## Sample Prediction

Given an image of an **Tshirt**, the model predicts the class with a high probability.

<img src="https://github.com/Nightskull100/Dress-Type-Detection-using-CNN/blob/f432f729aec9750d4bbe6ddd7f1e07586a50629f/Images/Image%20from%20Online.png" alt="Description" width="500" height="500">

![Sample Prediction](https://github.com/Nightskull100/Dress-Type-Detection-using-CNN/blob/e09a0aced7fd61d2728f3875e930a70cb24d260d/Images/Result%20online.png)


## Contributing
This project was done in collaboration with **Mr.Prajan Kannan**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prajan-kannan/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

# 💫 About Me:
🔭 A Simple guy who does coding for fun<br>👯 Willing to collaborate in all types of Projects<br>🤝 I’m looking for help with Neural Networking<br>🌱 I’m currently learning ML and Deep Learning, FIGMA (In near future)<br>

## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/cr7._.haseeb) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haseeb-ahsan-2b32a7293)

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) 
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) 
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)


###  
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
[![](https://visitcount.itsvg.in/api?id=Nightskull100&icon=1&color=5)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

---

This update includes the information on the notebook's ability to use a random image from the dataset, a URL, or an uploaded image for predictions.
