Unsupervised learning

## Project Overview

This project demonstrates how Deep Learning can be used to automatically classify fashion product images into different categories.

The project is designed around a business scenario where an e-commerce company receives thousands of product images and wants to reduce the need for manual product categorization.

## Objective

The main objectives of this project are:

* Understand how images are used as input for Deep Learning.
* Build a simple Artificial Neural Network (ANN).
* Understand input, hidden, and output layers.
* Train a Deep Learning model.
* Evaluate model accuracy.
* Predict the category of fashion images.
* Understand how Deep Learning can solve real business problems.

## Dataset

The project uses the **Fashion MNIST** dataset.

It contains images belonging to 10 fashion categories:

1. T-shirt/Top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

Each image is **28 × 28 pixels** and is represented in grayscale.

The pixel values are normalized from 0–255 to 0–1 before training.

## Model Architecture

The project uses a simple Artificial Neural Network:

**Input Image → Flatten Layer → Dense Hidden Layer → Output Layer**

* **Flatten Layer:** Converts the 28 × 28 image into a one-dimensional array.
* **Hidden Layer:** Contains 64 neurons and uses the ReLU activation function.
* **Output Layer:** Contains 10 neurons, one for each fashion category, and uses Softmax activation.

The model is trained using the Adam optimizer and sparse categorical crossentropy loss.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Fashion MNIST Dataset

## Project Workflow

1. Import the required libraries.
2. Load the Fashion MNIST dataset.
3. Normalize the image pixel values.
4. Build the neural network model.
5. Compile the model.
6. Train the model for 3 epochs.
7. Evaluate the model using test data.
8. Predict the category of fashion images.
9. Compare predicted and actual categories.

## Business Application

In a traditional e-commerce process, employees manually identify the category of each product image.

With an AI-assisted system:

**Product Image Uploaded → Deep Learning Model Analyzes Image → Category Predicted → Employee Reviews if Required → Product Added**

This can help businesses:

* Speed up product listing.
* Reduce repetitive manual work.
* Maintain consistent product categorization.
* Improve product search and organization.
* Process a larger number of product images.

## Model Evaluation

The model is evaluated using test data and accuracy is calculated.

The notebook gives **87% as an example accuracy**, while the actual accuracy may vary depending on the training run.

## Limitations

* The model is trained on Fashion MNIST, which contains simple 28 × 28 grayscale images.
* Real-world fashion images can be more complex.
* The model may make incorrect predictions.
* Human review may still be required for uncertain predictions.

## Human Role

AI can automate image classification, but human oversight can still be useful for checking incorrect or uncertain predictions.

## Future Scope

The system could be improved by:

* Using larger and more realistic fashion datasets.
* Using Convolutional Neural Networks (CNNs).
* Improving image quality and classification accuracy.
* Integrating the model with an e-commerce product listing system.
* Adding human-in-the-loop verification.

## Project Structure

```text
Deep_Learning_Fashion_Classification/
│
├── Deep_Learning_Fashion_Classification_Kamya.ipynb
├── README.md
└── Screenshot/
    └── prediction_screenshot.png
```

## Submission

The notebook should be renamed according to the required format and submitted along with a screenshot showing the product image, predicted category, and actual category. The files are uploaded to the course GitHub repository under:

```text
part-a/deep-learning/
```

## Conclusion

This project demonstrates how a simple Deep Learning model can classify fashion images and shows how AI can be applied to solve a practical business problem in the e-commerce industry.

## Author
arushi

BBA FinTech + AI
