# Dubai Property Nearest Metro Prediction  
> A predictive analysis project aimed at determining the nearest metro station for various properties across Dubai, developed as part of a Data Science project at the University of Wollongong in Dubai.

> The project utilizes advanced machine learning techniques to predict the closest metro station for a given property based on its geographical coordinates and other relevant features.

> The analysis began with the implementation of weak learning classifiers, specifically Decision Trees, Logistic Regression, and K-Nearest Neighbors (KNN). These models were then enhanced using an ensemble learning technique—Bagging—that was implemented from scratch. The performance of these models was thoroughly evaluated using 10-fold cross-validation, achieving a highly accurate prediction rate of 99.9%.

> Extensive Exploratory Data Analysis (EDA) was conducted to explore and visualize the dataset, unveiling key insights and trends related to property locations and metro stations.

> Data preprocessing steps were rigorously executed to prepare the dataset for accurate prediction, including feature engineering and data normalization.

> The project also incorporates a comprehensive evaluation of the prediction models using various performance metrics and validation techniques.

> The final predictions offer valuable insights for real estate stakeholders, providing a practical tool for estimating proximity to metro stations.

## Design Process and Methods  
> **Exploratory Data Analysis (EDA):**  
> - Detailed examination of the dataset to understand its spatial distribution and key attributes.  
> - Geospatial visualization techniques, including heatmaps and scatter plots, were used to analyze the relationship between property locations and metro stations.  
> - Statistical analysis provided insights into the distribution of distances between properties and their nearest metro stations.

> **Preprocessing:**  
> - Data cleaning involved handling missing values, removing unwanted columns(columns repeated in arabic), correcting inaccuracies in property coordinates, and filtering out irrelevant entries.  
> - Feature engineering included the creation of new variables such as distance to the nearest metro line, and categorization of properties based on type and area.  
> - Normalization and scaling of features were performed to ensure that the prediction models could accurately assess distances and spatial relationships.

> **Prediction Techniques:**  
> - **Weak Learning Classifiers:**  
>   - **Decision Trees:** Applied to capture non-linear relationships between property features and their nearest metro stations.  
>   - **Logistic Regression:** Used to predict binary outcomes in cases where properties were within a certain distance from metro stations.  
>   - **K-Nearest Neighbors (KNN):** Implemented to predict the nearest metro station based on the proximity of similar properties.  
> - **Ensemble Learning - Bagging:**  
>   - Bagging was implemented from scratch to aggregate the predictions of the weak learners, improving overall model stability and accuracy.  
>   - The ensemble method was tested on all three models, and its performance was evaluated through 10-fold cross-validation, resulting in a prediction accuracy of 99.9%.

> **Evaluation:**  
> - Model performance was assessed using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).  
> - Validation was performed using a train-test split approach as well as k-fold cross-validation to ensure the robustness of the predictive models.  
> - Visual inspection of prediction results, including maps plotting predicted versus actual nearest metro stations, was used to interpret the effectiveness of the models.  
