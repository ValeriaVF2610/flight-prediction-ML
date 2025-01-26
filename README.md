# Flight Delay/Cancellation Prediction ML  

## Project Objective  
This project focuses on analyzing and predicting airline flight delays and cancellations in the United States during 2022–2023. By leveraging historical flight data, we aim to uncover key insights through Exploratory Data Analysis (EDA) and use Machine Learning models to predict delays based on flight-specific features.  

---

## Dataset Description  
The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018/data) and contains flight records spanning 2009 to 2018. For this project, data was filtered to include flights in the United States from 2022 to 2023.
The dataset provides extensive details, enabling a robust analysis and predictive modeling framework.  

---

## Machine Learning Techniques  
We utilized supervised learning techniques for regression tasks to predict departure delays. The models implemented include:  
1. **Bagging**: A powerful ensemble method combining multiple predictors to improve accuracy.  
2. **Random Forest**: An ensemble model leveraging bagging with decision trees for better generalization.  
3. **Gradient Boosting**: Focused on minimizing prediction error through sequential improvements.  

Random Forest proved to be the most effective for this project, showcasing strong predictive capabilities.  

---

## Libraries and Dependencies  
The project leverages the following Python libraries:  
- **pandas**: For data manipulation and preprocessing.  
- **scikit-learn**: For model development and evaluation.  
- **matplotlib**/**seaborn**: For visualizing trends and patterns.  

---

## Future Work  
1. **Training on Additional Data**: Expanding the dataset to include more recent years or larger datasets for better generalization.  
2. **Enhanced Precision**: Exploring more advanced algorithms and hyperparameter tuning to improve prediction accuracy.  
3. **Feature Engineering**: Identifying and integrating additional features, such as weather or air traffic conditions, to refine the model.  

---

## Presentation  
You can view the project’s presentation on Canva: [Flight Delay ML Presentation](https://www.canva.com/design/DAGb4mSxxGE/dmS01-aFqmIBn7YAvwSnZg/view?utm_content=DAGb4mSxxGE&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hf6fb4de9ce).  

---

## Conclusion  
This project serves as a foundation for predicting flight delays using machine learning. By combining exploratory data analysis with advanced predictive models, it demonstrates the potential to minimize the inconvenience caused by flight delays. Further improvements will focus on leveraging additional data and fine-tuning model performance.  


