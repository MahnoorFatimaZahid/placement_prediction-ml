# Machine Learning Project – Linear Regression (Google Colab)

## Project Overview
This project demonstrates the basics of **Machine Learning** using **Linear Regression**.  
It shows how we can use data, train a model, and predict outputs using Python libraries like **NumPy**, **Pandas**, **Matplotlib**, and **Scikit-learn**.

### Goals of this project:
- Understand how data is handled in ML  
- Learn how to train a regression model  
- Test predictions on unseen data  
- Visualize results with graphs  

---

## Technologies Used
- Python 3  
- Google Colab (for writing & running code)  
- NumPy (math operations)  
- Pandas (data handling)  
- Matplotlib (graph/plots)  
- Scikit-learn (ML model)  

---

## Steps in the Code
1. **Import Libraries**  
   Load all the required Python libraries (NumPy, Pandas, Matplotlib, sklearn).  

2. **Load Dataset**  
   Use a sample dataset (either inbuilt or uploaded in Colab).  

3. **Data Preprocessing**  
   - Handle missing values (if any)  
   - Select features (X) and target (y)  

4. **Train-Test Split**  
   Divide the dataset into training data (to learn) and testing data (to check accuracy).  

5. **Build Linear Regression Model**  
   Use `LinearRegression()` from sklearn to train the model.  

6. **Make Predictions**  
   Test the model with test data.  

7. **Visualize Results**  
   Plot graphs to see how the model fits the data.  

---

## How to Run
1. Open [Google Colab](https://colab.research.google.com)  
2. Upload the notebook file (`.ipynb`)  
3. Run each cell step by step  
4. Change the dataset if you want to test with your own data  

---

## Example Output
- Model predictions on test data  
- A regression line on a scatter plot  
- Accuracy score of the model  

---

## Important Questions & Answers (About the Code)

**1. What is Linear Regression?**  
Linear regression is a machine learning algorithm that finds the relationship between input (X) and output (y) by fitting a straight line to the data.  

**2. Why do we split data into training and testing sets?**  
- Training data teaches the model.  
- Testing data checks if the model works well on unseen data.  
This prevents overfitting.  

**3. What does `.fit()` do in Linear Regression?**  
`.fit()` trains the model by finding the best line (best coefficients and intercept) for the dataset.  

**4. What does `.predict()` do?**  
`.predict()` uses the trained model to give output (y values) for new input data (X values).  

**5. What libraries are important in this project and why?**  
- Pandas → handle data  
- NumPy → mathematical operations  
- Matplotlib → visualization  
- Scikit-learn → building ML models  

**6. How do we measure accuracy of Linear Regression?**  
We can use:  
- R² Score (coefficient of determination) → how well data fits the model  
- Mean Squared Error (MSE) → average error in predictions  

**7. What is Overfitting in ML?**  
Overfitting happens when the model learns too much from training data (even noise), so it performs badly on new/unseen data.  

**8. Why do we visualize results with graphs?**  
Graphs help us see:  
- If the regression line fits the data properly  
- How predictions compare to real values  

---

## Key Takeaways
- Learned the complete ML workflow in Colab.  
- Understood how Linear Regression works.  
- Practiced model training, prediction, and evaluation.  
- Built a foundation for more advanced ML algorithms.  
