# RECOMMENDATION-SYSTEM

**COMPANY** : CODTECH IT SOLUTIONS

**NAME** : GAURAV RAMASUBRAMANIAM

**INTERN ID** : CT08JUR

**DOMAIN** : MACHINE LEARNING

**DURATION** : 4 WEEKS

**MENTOR** : NEELA SANTOSH

# DESCRIPTION

# Anime Recommendation System

## 🚀 **Project Overview**

This project aims to build a personalized anime recommendation system using the **Collaborative Filtering** technique, specifically leveraging **Matrix Factorization** through the **SVD (Singular Value Decomposition)** model from the **Surprise** library.

The system recommends top anime titles for users based on their past ratings. The model is evaluated using accuracy metrics and provides top N recommendations for each user, enabling personalized anime suggestions.

---

## 🛠️ **Requirements**

To run this project, ensure you have the following libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-surprise`
- `collections`

You can install the required libraries using `pip`:

**`pip install pandas numpy matplotlib scikit-surprise`**

---

💻 **How to Use**

1. **Load the Data**  
   The dataset `anime.csv` contains the anime details and user ratings. It includes columns such as `anime_id`, `name`, `rating`, `user_id`, etc.

2. **Step-by-Step Execution**  
   Execute the script `recommendation_system.py`. The script follows these key steps:
   
   - **Step 1**: Load and preprocess the data.
   - **Step 2**: Prepare the data in the format required by the Surprise library.
   - **Step 3**: Split the dataset into training and testing sets.
   - **Step 4**: Train the model using **SVD (Singular Value Decomposition)**.
   - **Step 5**: Make predictions and evaluate model performance using accuracy metrics.
   - **Step 6**: Generate the top 10 anime recommendations for each user.
   - **Step 7**: Display the recommendations and visualize the results in a plot.

3. **View the Recommendations**  
   After running the script, you will get a list of top 10 anime recommendations for each user, along with their predicted ratings.

---

📈 **Evaluation Metrics**

- **RMSE (Root Mean Squared Error)**: Used to evaluate the accuracy of the predictions. The lower the RMSE, the better the model.
- **MAE (Mean Absolute Error)**: Measures the average magnitude of errors in predictions. A lower MAE signifies better accuracy.

---

📊 **Visualizing Recommendations**

- The script generates a bar plot visualizing the top anime recommendations based on predicted ratings.
- The plot displays the anime names and their estimated ratings, making it easy to assess the most recommended anime for each user.

---

🔧 **Technical Details**

- **Model Used**: Singular Value Decomposition (SVD) from the Surprise library.
- **Collaborative Filtering Approach**: The system uses collaborative filtering to recommend anime based on user-item interactions, without the need for content-based information.
- **Data**: The system uses a dataset containing anime information and user ratings. It processes this data to predict the rating a user would give to an anime they haven't rated yet.

---

📍 **Future Improvements**

- **Hybrid Models**: Incorporating content-based filtering along with collaborative filtering to improve recommendations.
- **User Interface**: Building a front-end interface to display recommendations interactively.
- **Advanced Algorithms**: Experimenting with more advanced recommendation algorithms like **KNN** or **Matrix Factorization** (non-SVD).

---

📝 **License**

This project is open-source and available under the [MIT License](LICENSE).

# OUTPUT

![Image](https://github.com/user-attachments/assets/0e376bf6-eabd-4ccd-9c4b-b1f14d9213d0)




