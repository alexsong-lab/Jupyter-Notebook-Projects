# Image Classification

> We want to develop a model to classify the class/type of flower shown in an image.

---

## Project Overview

We will take a predictive approach in this problem. We will train a classifier that can predict the type of flowers in an image from the following 5 categories: chamomile, tulip, rose, sunflower, dandelion.

- **Objective:** understand how the model is classifying the images.
- **Domain:** Immage Classification
- **Key Techniques:** Regression analysis, missing-data imputation, exploratory data analysis, visualization.
---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** Link to the data source(s) [Flowers Recognition](https://www.kaggle.com/datasets/alxmamaev/flowers-recognitionl)
- **Description:** This dataset contains 4242 images of flowers. The pictures are divided into five classes: chamomile, tulip, rose, sunflower, dandelion. For each class there are about 800 photos.
- **License:** Unknown.

---

## Analysis

- Train a model to classify images as five classes: chamomile, tulip, rose, sunflower, dandelion, starting from the resnet34 model that has already been trained to solve an image classification problem involing many types of images.
- Use fast.ai has a `ClassificationInterpretation` function to help analyze the performance of the model.
- Plot the confusion matrix, which shows the number of images in the validation set that were correctly and incorrectly classified by the model.
- Use the model to predict the flower type for an example image and plot the class probabilities.

---

## Results

The image cllasification model performs well on the test overall, and we have a decent grasp of its weak points. While our initial confidence is justified, achieving robust performance across diverse real-world scenarios may require enhancing the training data and conducting further evaluations.

---

## Authors

- [@Alex Song](https://github.com/alexsong-lab)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Python libraries: fastai, fastscoreseaborn, matplotlib.
- Codes are refrenced to the class examples provided by the instructor.
