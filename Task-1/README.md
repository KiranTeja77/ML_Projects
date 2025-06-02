#  Task 1: Decision Tree Classification

##  Objective

This task focuses on applying the Decision Tree algorithm to a classic supervised learning problem using the Iris dataset. The main goal is to train a model that can accurately classify iris flowers into three species — Setosa, Versicolor, and Virginica — based on the measurements of their petal and sepal dimensions. Decision Trees are intuitive, visual, and easy-to-interpret models that can handle both classification and regression tasks. In this project, the Decision Tree is used specifically for multi-class classification.

##  Dataset

- **File**: `iris.csv`
- **Source**: Built-in dataset in `scikit-learn`, also available via UCI Machine Learning Repository
- **Features**:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Target**: `species` (Setosa, Versicolor, Virginica)

The dataset consists of 150 samples, with 50 examples for each class. It is perfectly balanced and ideal for demonstrating classification techniques.

##  Technologies Used

- **Python** – Primary programming language
- **Jupyter Notebook** – Interactive development environment
- **Pandas** – For data manipulation and exploration
- **Scikit-learn (sklearn)** – For model training, evaluation, and visualization
- **Matplotlib** – For visualizing the Decision Tree

##  Steps Performed

1. **Data Loading**: The Iris dataset is loaded either from a CSV file (`iris.csv`) or directly using `sklearn.datasets.load_iris()`. It is then converted into a Pandas DataFrame for easy manipulation.

2. **Data Preprocessing**: Basic inspection is done to ensure there are no missing values. The features and target variables are separated.

3. **Train-Test Split**: The dataset is split into training and testing subsets using an 80/20 ratio to evaluate the generalization performance of the model.

4. **Model Training**: A `DecisionTreeClassifier` from `scikit-learn` is instantiated and trained using the training data.

5. **Prediction & Evaluation**: The model is used to make predictions on the test set. Accuracy score and a detailed classification report (precision, recall, F1-score) are generated to assess the model's performance.

6. **Visualization**: The trained decision tree is visualized using `plot_tree()`, making it easier to interpret how decisions are made based on feature thresholds.

##  How to Run

1. Make sure you have Python and the necessary libraries installed:
   ```bash
   pip install pandas scikit-learn matplotlib
   ```

2. Place `iris.csv` in the same directory as the notebook (if using CSV).

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook decision_tree.ipynb
   ```

4. Run all cells to see the results and visualization.

##  Output

- **Accuracy Score**: Provides a quick performance overview on unseen test data.
- **Classification Report**: Offers metrics like precision, recall, and F1-score for each class.
- **Tree Visualization**: A graphical representation of the decision-making process based on feature splits.
- 

## 📌 Summary

This task demonstrates the power and simplicity of Decision Trees for solving a classic classification problem. By using a structured dataset like Iris, we can understand how features influence predictions and visualize the decision process. This forms a foundation for more advanced ensemble techniques like Random Forests and Gradient Boosted Trees in future tasks.
