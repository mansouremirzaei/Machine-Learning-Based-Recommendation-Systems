#  Content-Based Car Recommendation System using K-Nearest Neighbors

This project is a simple content-based recommender system that suggests cars to a customer based on their preferences for features like mileage (mpg), displacement, horsepower, and weight.

## 🔍 Goal

To recommend cars that are **most similar** to a given car using the **K-Nearest Neighbors algorithm**.

## 📊 Dataset

The dataset used is [`mtcars.csv`](https://www.rdocumentation.org/packages/datasets/versions/3.6.2/topics/mtcars), which contains specifications of various car models.

## 🛠 Features Used

- Miles per Gallon (mpg)
- Displacement
- Horsepower
- Weight

## 🤖 Algorithm

- `NearestNeighbors` from `scikit-learn`
- Finds the most similar cars using Euclidean distance between feature vectors.

## 📚 Reference

This project is based on the following course:
[LinkedIn Learning - Building a Recommendation System with Python Machine Learning and AI](https://www.linkedin.com/learning/building-a-recommendation-system-with-python-machine-learning-and-ai)

## ✅ Output

The notebook predicts cars similar to a given input and prints the top 3 most similar cars as recommendations.

---

Feel free to explore and improve!

