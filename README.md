"Project Overview"

This project involves building a predictive model to forecast sales based on TV Radio Newspaper cotypes. Using machine learning techniques, specifically linear regression, we train a model on historical data, test it, and evaluate its performance. The project uses Python libraries such as Pandas, NumPy, Scikit-Learn, and Plotly for data manipulation, model building, and visualization.

"Features"

Data Features:
Feature 1: TV 
Feature 2: Radio
Feature 3: Newspaper
Target Variable:
Target: total sales

"Data analysis"

Data analysis is the process of inspecting, cleaning, transforming, and modeling data to discover useful information, draw conclusions, and support decision-making. It enables organizations to identify patterns, trends, and relationships in their data, providing valuable insights for strategic planning and problem-solving. In today’s data-driven world, effective data analysis is essential for making informed decisions, optimizing processes, and improving efficiency across industries. By turning raw data into actionable insights, data analysis helps businesses stay competitive and respond quickly to changes in the market.

"Used tools"

1. Pandas
Purpose: Data manipulation and analysis.
2. NumPy
Purpose: Numerical computing and array manipulation.
3. Matplotlib
Purpose: Data visualization
4. Seaborn
Purpose: Statistical data visualization.
6. Scikit-Learn
Purpose: Machine learning and data mining

"Run project"

To run this project, you'll need Python 3.x installed on your system, along with the required libraries. If you don't have these installed, follow the instructions below.
Clone the repository by this code
git clone https://github.com/galstyan13/ml1.git
cd ml1
Create a virtual environment 
python -m venv venv
source venv/bin/activate

"Model Evaluation"

Model Used: Linear Regression was chosen for this problem because it is a simple yet powerful algorithm for predicting continuous numerical values. Given that we are trying to predict sales based on numerical features, linear regression is an ideal candidate.
Performance Metrics:
R-squared: The R-squared score measures how well the model’s predictions match the real data. A higher R-squared value indicates better accuracy.
Mean Squared Error (MSE): This metric helps evaluate the model's prediction accuracy by measuring the average squared difference between predicted and actual values.
The model’s accuracy is evaluated using the model.score() and model.predict() functions. You can test the model on different examples to predict sales for new data point

"Why Choose Linear Regression?"

Linear Regression is chosen for the following reasons:
Simplicity: It’s easy to implement and interpret.
Performance: It performs well when the relationship between the target variable (sales) and the input features (advertising budget, store traffic, etc.) is approximately linear.
Scalability: Linear regression works efficiently with large datasets and gives a good baseline model.

"Conclusion"

This project aims to predict sales based on three features using Linear Regression. We’ve visualized the data, split it into training and testing sets, trained the model, and evaluated it using standard metrics such as R-squared and Mean Squared Error.

