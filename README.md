# Asteroid Trajectory Prediction

This project focuses on analyzing and predicting asteroid trajectories and related properties using data from NASA and Kaggle. It includes exploratory data analysis, preprocessing, machine learning modeling, and visualization of asteroid motion.

## Objectives

- Understand and explore the key features of asteroid data.
- Perform preprocessing and feature engineering to prepare data for modeling.
- Train both regression and classification models to predict important parameters such as asteroid diameter, orbit period, and whether an asteroid is potentially hazardous.
- Visualize results through informative plots and an interactive simulation GUI.
- Export models for deployment or dashboard use.

## Dataset

The primary dataset used for this project was sourced from [Kaggle](https://www.kaggle.com/) and contains near-Earth object (NEO) data including information on orbital elements, estimated diameter, absolute magnitude, and hazard potential.

## Workflow Summary

1. **Data Exploration**: Understand distributions, missing values, outliers.
2. **Preprocessing**: Clean and transform data, handle encoding and missing values.
3. **Feature Engineering**: Create and refine features to improve model performance.
4. **Modeling**: 
   - **Regression**: Predict numeric attributes like diameter or period.
   - **Classification**: Predict if an object is a Potentially Hazardous Asteroid (PHA).
5. **Evaluation**: Assess model performance using metrics and visual diagnostics.
6. **Interpretability**: Use SHAP and LIME for model explainability.
7. **Simulation**: Visualize orbital paths through a GUI.
8. **Deployment**: Prepare final model for use in dashboards or applications.

## Technologies Used

- Python 3.12
- Jupyter Notebooks
- Scikit-learn
- Pandas & NumPy
- Seaborn & Matplotlib
- SHAP, LIME
- Tkinter (for GUI simulation)

## Author

Jobet P. Casquejo

## License

This project is licensed under the MIT License.
