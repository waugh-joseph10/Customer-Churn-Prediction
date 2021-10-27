<h1>Deep Neural Network - Customer Account Churn Prediction</h1>
<h2>Author: Joseph Waugh</h2>

This workbook takes a <a href="https://www.kaggle.com/blastchar/telco-customer-churn">data source</a> from Kaggle regarding Telco customers, a Global telecommunications provider, and provides various attributes related to customer churn. 
Customer churn is a very important KPI in the telecommunications industry, with the average churn rate being approximately 1.9% per month across the 4 major carriers, but even as high as 67% for prepaid customers (<a href="https://www.omnisci.com/blog/strategies-for-reducing-churn-rate-in-the-telecom-industry#:~:text=The%20average%20churn%20rate%20in,fostering%20customer%20loyalty%20is%20key.">source</a>).
<br>
<br>
This Jupyter notebook explores Telco churn rates and trends among the customer demogaphics, with the final output being a Tensorflow deep learning neural network. The neural network contains a standardization layer, two dense ReLU activation layers, and a final dense output layer to produce the output predictions. The model achieves a 73% accuracy based on RMSE, with the dense layers utilizing a <a href="https://keras.io/api/layers/activations/">ReLU</a> mean squared loss minimization function.
