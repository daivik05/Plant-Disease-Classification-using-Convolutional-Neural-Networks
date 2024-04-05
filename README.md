# Plant-Disease-Classification-using-Convolutional-Neural-Networks

This repository contains a deep learning model for classifying plant diseases. The model is trained to identify various diseases that affect plants, aiding in early detection and prevention measures.

## Overview

Plant diseases can significantly impact crop yield and quality, leading to economic losses for farmers. Early detection and accurate identification of these diseases are crucial for effective management strategies. This project aims to provide a solution by leveraging machine learning techniques to classify plant diseases based on images of affected plants.

## Model Architecture

The classification model is built using a convolutional neural network (CNN) architecture. CNNs are well-suited for image classification tasks due to their ability to automatically learn relevant features from raw pixel data. The model architecture comprises multiple convolutional and pooling layers followed by fully connected layers for classification.
You can download the model present in the [model](https://github.com/daivik05/Plant-Disease-Classification-using-Convolutional-Neural-Networks/blob/master/model
) folder.

## Dataset

The model is trained on a dataset consisting of labeled images of various plant diseases. The dataset includes images of healthy plants as well to enable differentiation between healthy and diseased plants. It is important to ensure a diverse and representative dataset to improve the model's generalization ability.
The dataset was taken from [Kaggle.com](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)


## Requirements

Ensure you have the following dependencies installed:

- tensorflow==2.7.0
- numpy==1.19.5
- matplotlib==3.2.2
- seaborn==0.11.1
- scikit-learn==0.24.2
- pandas==1.1.5
- opencv-python==4.5.3.56
- Pillow==8.2.0
- tensorflow-hub==0.12.0

You can install the dependencies using `pip`:

```bash
pip install -r requirements.txt
```

## Future Improvements

- Fine-tuning the model architecture for better performance.
- Data augmentation techniques to increase the diversity of the training dataset.
- Implementing transfer learning using pre-trained models to improve efficiency and accuracy.

## Contribution

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---


