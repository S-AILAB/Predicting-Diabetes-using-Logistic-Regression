
<h1>🧠 Diabetes Prediction using Logistic Regression</h1>

<p>This project demonstrates a complete machine learning workflow for predicting diabetes using <strong>Logistic Regression</strong>, based on clinical features. It includes data cleaning, exploratory data analysis (EDA), model training, evaluation, and visualization.</p>

<h2>📁 Dataset</h2>
<p>The dataset used is <code>Diabetes.csv</code> and includes attributes like:</p>
<ul>
    <li>Pregnancies</li>
    <li>Glucose</li>
    <li>Blood Pressure</li>
    <li>Skin Thickness</li>
    <li>Insulin</li>
    <li>BMI</li>
    <li>Diabetes Pedigree Function</li>
    <li>Age</li>
    <li>Outcome (Target)</li>
</ul>
<p><strong>Note:</strong> Outcome is a binary variable: <code>YES</code> (diabetic) and <code>NO</code> (non-diabetic), encoded as 1 and 0 respectively.</p>

<h2>📌 Project Workflow</h2>

<h3>🔹 1. Data Preprocessing</h3>
<ul>
    <li>Renamed columns for clarity</li>
    <li>Checked for missing values and duplicates</li>
    <li>Encoded the target variable (Outcome)</li>
    <li>Applied IQR-based outlier treatment</li>
</ul>

<h3>🔹 2. Exploratory Data Analysis (EDA)</h3>
<ul>
    <li>Univariate analysis: histograms, countplots</li>
    <li>Bivariate analysis: boxplots, scatterplots</li>
    <li>Correlation heatmap and pairplots</li>
</ul>

<h3>🔹 3. Model Building</h3>
<ul>
    <li>Data split: 75% training, 25% testing</li>
    <li>Trained a Logistic Regression model using scikit-learn</li>
</ul>

<h3>🔹 4. Model Evaluation</h3>
<ul>
    <li>Metrics: Accuracy, Precision, Recall</li>
    <li>Confusion Matrix Heatmap</li>
    <li>ROC Curve and AUC Score</li>
</ul>

<h2>📈 Results</h2>
<ul>
    <li><strong>Accuracy:</strong> High predictive performance on test data</li>
    <li><strong>AUC Score:</strong> ~0.84 — strong class separation</li>
    <li>Good balance between false positives and negatives</li>
</ul>

<h2>🛠️ Tech Stack</h2>
<ul>
    <li>Python 3.x</li>
    <li>Pandas, NumPy</li>
    <li>Seaborn, Matplotlib</li>
    <li>Scikit-learn</li>
</ul>

<h2>❓ Making a Comparative study between Decision Tree v/s Logistics Regression</h2>
<ul>
    <li>Comparing the evaluation between the two models to select which one is better.</li>
    <li>Comparison parameters are Accuracy, Precision, Recall</li>
    <li>File Name: Model Evaluation DT & LogiR.ipynb </li>
</ul>


</body>
</html>
