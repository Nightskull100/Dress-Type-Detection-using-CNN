
# Fashion MNIST Classifier

This repository contains a PyTorch implementation of a neural network designed to classify images from the Fashion MNIST dataset. The dataset consists of grayscale images of various clothing items, with each image being 28x28 pixels.

## Project Overview

The project includes the following key components:

- **Data Loading and Preprocessing**: The Fashion MNIST dataset is loaded and split into training, validation, and test sets. The images are normalized and transformed into tensors for processing by the neural network.
  
- **Model Architecture**: A simple neural network is built using PyTorch's `nn.Sequential` with layers including fully connected (linear) layers, ReLU activations, and dropout for regularization. The model outputs class probabilities using `LogSoftmax`.

- **Training and Validation**: The model is trained using the Adam optimizer and negative log likelihood loss (`NLLLoss`). The training and validation losses, as well as validation accuracy, are tracked and printed for each epoch.

- **Visualization**: The training and validation losses are plotted to observe the model's performance over time. Additionally, the model's predictions on sample images are visualized alongside the predicted class probabilities.

- **Image Prediction**: Two utility functions are provided to preprocess images from either a URL or a local file, allowing for prediction using the trained model. The predictions are then visualized along with the input image.

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

### 2. Predicting from a URL
To predict the class of an image from a URL, use the following command:

```bash
python predict_url.py --image_url "http://example.com/image.jpg"
```

### 3. Predicting from a Local File
To predict the class of an image from a local file, use the following command:

```bash
python predict_file.py --image_path "path/to/image.jpg"
```

## Results

The model achieves a validation accuracy of approximately 88% after 25 epochs of training. The trained model can accurately predict the class of various clothing items in the Fashion MNIST dataset.

## Examples

### Training and Validation Losses

![Training and Validation Losses](https://github.com/Nightskull100/Dress-Type-Detection-using-CNN/blob/3f8e12947ad1c26805abd6e117f7d0d43de8c417/Training%20and%20Validation%20Losses.png)

### Sample Prediction

Given an image of an **Ankle Boot**, the model predicts the class with a high probability.

![Sample Prediction](path/to/sample_prediction.png)

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# 💫 About Me:
🔭 A Simple guy who does coding for fun<br>👯 Willing to collaborate in all types of Projects<br>🤝 I’m looking for help with Neural Networking<br>🌱 I’m currently learning ML and Deep Learning, FIGMA(In near future) <br>


## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/cr7._.haseeb) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haseeb-ahsan-2b32a7293) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) 
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) 
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)


###  
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
[![](https://visitcount.itsvg.in/api?id=Nightskull100&icon=1&color=5)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
