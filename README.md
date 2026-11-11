# Elevate-Labs-Task-5-Decision-Trees-and-Random-Forests

# Task 5: Decision Trees and Random Forests

## Objective
The objective of this task is to understand tree-based machine learning models for classification and regression, study overfitting, compare Decision Tree and Random Forest models, and analyze feature importance.

## Datasets Used

**1. Wine Recognition Dataset – Classification**

- 178 samples
- 13 numerical features
- 3 target classes

Dataset: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html

**2. Diabetes Dataset – Regression**

- 442 samples
- 10 numerical features

Dataset: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html

Both datasets are available directly through Scikit-learn.

## Tools & Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn
- Graphviz DOT format

## Tasks Performed

1. Loaded and explored the datasets.
2. Divided the data into training and testing sets.
3. Trained Decision Tree models for classification.
4. Studied overfitting by comparing unrestricted and depth-limited trees.
5. Visualized the Decision Tree and exported its structure in DOT format.
6. Trained a Random Forest Classifier and compared its performance with the Decision Tree.
7. Analyzed feature importance.
8. Evaluated classification models using 5-fold cross-validation.
9. Implemented Decision Tree and Random Forest models for regression.
10. Compared regression performance using MAE, RMSE, and R² score.

## Classification Results

| Model | Test Accuracy | 5-Fold CV Accuracy |
|---|---:|---:|
| Decision Tree | 94.44% | 89.51% |
| Random Forest | 100.00% | 97.91% |

## Regression Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Decision Tree Regressor | 47.05 | 59.74 | 0.3264 |
| Random Forest Regressor | 44.28 | 54.46 | 0.4402 |

## Files Included

- `TASK_5_Decision_Trees_and_Random_Forests.py` – Python implementation.
- `TASK_5_Decision_Trees_and_Random_Forests.ipynb` – Google Colab notebook with executed outputs.
- `Task_5_Output_Screenshots.pdf` – Important output screenshots and visualizations.
- `decision_tree.dot` – Exported Decision Tree structure.
- `output_screenshots/` – Generated graphs and visualizations.
- `README.md` – Project documentation.

## Learning Outcomes

Through this task, I gained practical experience in building Decision Tree and Random Forest models, understanding overfitting, controlling tree depth, interpreting feature importance, and evaluating models using cross-validation. I also learned how these algorithms can be applied to both classification and regression problems.

## Conclusion

Successfully implemented and compared Decision Tree and Random Forest models for classification and regression. The results showed that the Random Forest performed better than the selected Decision Tree models on the datasets used in this task. Overall, this task helped strengthen my understanding of tree-based learning, ensemble methods, model evaluation, and feature importance.

*Note: The reported results are based on the selected datasets and experimental settings. They may vary with different data splits or model parameters.*
