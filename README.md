# Histopathological-Cancer-Detection
In this machine learning project on histopathologic cancer detection, we utilized various classification models to predict the presence of cancerous cells in histopathology images. The models used in the project included Decision Tree, Random Forest, Logistic Regression, AdaBoost, XGBoost, LightGBM, and Convolutional Neural Network (CNN).

We evaluated the performance of these models using accuracy as the evaluation metric. The accuracies achieved by each model on the test set were as follows:
   * **Decision Tree Classifier: 65.44%**
   * **Random Forest Classifier: 77.60%**
   * **Logistic Regression: 59.03%**
   * **AdaBoost: 68.78%**
   * **XGBoost: 73.42%**
   * **LightGBM: 91.29%**
   * **CNN: 93.45%**

1. Based on the results, we saw that the CNN model was the most accurate, with a score of 93.45%. LightGBM was next, with a score of 91.29%. These models were better than the others at figuring out whether or not cells were dangerous.

2. The CNN model's high accuracy is due to the fact that it can use convolutional layers to learn complex features and patterns from the histopathology pictures. On the other hand, LightGBM, which is a gradient boosting framework, did very well because it could handle datasets that were not evenly distributed and record complex relationships between features.

3. Overall, the results show that machine learning models work well in histopathology to find cancer. The CNN and LightGBM models show promise for being able to correctly find cancerous cells, which could help find and treat cancer earlier.

4. We could make more improvements by looking into other deep learning architectures or ensemble methods, optimizing hyperparameters, and adding more preprocessing techniques or picture enhancement strategies.

In the end, this project shows how machine learning methods can be used to find cancer in histopathology and how important it is to use advanced models to make accurate and quick diagnoses in the field of medical imaging.
