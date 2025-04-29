<h1>Bulldozer Price Prediction Using Machine Learning</h1>

<h2>📌 Objective</h2>
<p>To build a machine learning model capable of predicting the sale price of used bulldozers based on historical equipment sales data.</p>

<hr>

<h2>🛑 Problem Statement</h2>
<p>Accurate price prediction for used heavy equipment is crucial for sellers, buyers, and auction platforms. This project leverages historical auction data to train a regression model that estimates bulldozer sale prices, helping stakeholders make informed decisions.</p>

<hr>

<h2>📊 Dataset</h2>
<ul>
  <li><b>Source:</b> <a href="https://www.kaggle.com/c/bluebook-for-bulldozers" target="_blank">Kaggle - Blue Book for Bulldozers</a></li>
  <li><b>Features:</b>
    <ul>
      <li>Model ID, Year Made, Usage Hours</li>
      <li>Product Group & Type</li>
      <li>Machine Specifications</li>
      <li>Sale Date and Location</li>
      <li><b>Target:</b> SalePrice</li>
    </ul>
  </li>
</ul>

<hr>

<h2>⚙️ Methodology</h2>

<h3>1. Data Preprocessing</h3>
<ul>
  <li>Parse and convert date columns</li>
  <li>Handle missing values and invalid years</li>
  <li>Convert categorical variables using encoding</li>
  <li>Feature engineering (e.g., age of equipment)</li>
</ul>

<h3>2. Exploratory Data Analysis (EDA)</h3>
<ul>
  <li>Analyze sale price distribution</li>
  <li>Visualize trends over time</li>
  <li>Understand correlations between features</li>
</ul>

<h3>3. Model Building</h3>
<ul>
  <li>Use Random Forest Regressor as baseline</li>
  <li>Experiment with other models: XGBoost, LightGBM</li>
  <li>Cross-validation for reliable performance estimates</li>
</ul>

<h3>4. Evaluation Metrics</h3>
<ul>
  <li>Root Mean Squared Log Error (RMSLE)</li>
  <li>R² Score</li>
  <li>Mean Absolute Error (MAE)</li>
</ul>

<h3>5. Model Tuning</h3>
<ul>
  <li>Grid Search / Randomized Search for hyperparameter tuning</li>
  <li>Feature importance analysis</li>
</ul>

<h3>6. Deployment (optional)</h3>
<ul>
  <li>Build a simple Streamlit or Flask web app</li>
  <li>Allow users to input features and get real-time price predictions</li>
</ul>

<hr>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>Pandas, NumPy</li>
  <li>Matplotlib, Seaborn</li>
  <li>Scikit-learn</li>
  <li>XGBoost / LightGBM (optional)</li>
  <li>(Optional) Streamlit or Flask for deployment</li>
</ul>

<hr>

<h2>✅ Results</h2>
<ul>
  <li>Achieved strong predictive performance using Random Forest</li>
  <li>RMSLE below 0.25 on validation data</li>
  <li>Model generalizes well across different equipment years and types</li>
</ul>

<hr>

<h2>📝 Conclusion</h2>
<p>This project demonstrates how machine learning can effectively predict prices in the used heavy equipment market. With further enhancements and real-time deployment, the model can assist auctioneers, dealers, and buyers in decision-making.</p>

<hr>

<h2>🔮 Future Work</h2>
<ul>
  <li>Integrate external economic indicators (e.g., fuel prices, demand index)</li>
  <li>Build a user-friendly web application</li>
  <li>Explore deep learning models for tabular data</li>
</ul>
