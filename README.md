<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>

<h1>Diabetes Prediction Model</h1>

<p>This project involves the development of a machine learning model to predict diabetes outcomes based on various medical features. The goal is to create an accurate and reliable tool that can assist healthcare professionals in identifying individuals at risk of developing diabetes.</p>



<h2 id="installation">Installation</h2>
<p>To run this project, clone the repository and install the required libraries:</p>
<pre><code>git clone https://github.com/aqib11234/diabetes-prediction-model.git
cd diabetes-prediction-model
pip install -r requirements.txt</code></pre>



<h2 id="data">Data</h2>
<p>The dataset used for this project is the diabetes dataset, which includes various medical features to predict diabetes outcomes. Key features include:</p>
<ul>
    <li><strong>Glucose:</strong> The most influential feature affecting diabetes outcomes.</li>
    <li><strong>Blood Pressure:</strong> Diastolic blood pressure (mm Hg).</li>
    <li><strong>Skin Thickness:</strong> Triceps skin fold thickness (mm).</li>
    <li><strong>Insulin:</strong> 2-Hour serum insulin (mu U/ml).</li>
    <li><strong>BMI:</strong> Body mass index (weight in kg/(height in m)^2).</li>
    <li><strong>Age:</strong> Age of the patient.</li>
    <li><strong>Outcome:</strong> Indicates whether the patient has diabetes (1) or not (0).</li>
</ul>

<h2 id="model-development">Model Development</h2>
<p>The model was developed using the following steps:</p>
<ul>
    <li><strong>Data Preprocessing:</strong> Handled missing values and normalized the features using StandardScaler.</li>
    <li><strong>Data Splitting:</strong> Separated the data into training (80%) and testing (20%) sets.</li>
    <li><strong>Model Selection:</strong> Utilized a Random Forest Classifier for its robustness and effectiveness in handling medical data.</li>
    <li><strong>Evaluation Metrics:</strong> Assessed the model using accuracy, precision, recall, and F1-score.</li>
</ul>

<h2 id="results">Results</h2>
<p>The model achieved satisfactory performance, with key findings including:</p>
<ul>
    <li>Accuracy: The overall prediction accuracy of the model.</li>
    <li>Precision: The accuracy of positive predictions, indicating how many of the predicted diabetes cases were actually true cases.</li>
    <li>Recall: The ability of the model to identify all actual diabetes cases.</li>
    <li>F1-score: The harmonic mean of precision and recall, providing a balance between the two metrics.</li>
</ul>
<p>The confusion matrix visualization provides insights into true positives, false positives, true negatives, and false negatives, helping to understand the model's strengths and weaknesses.</p>

<h2 id="conclusion">Conclusion</h2>
<p>This project highlights the importance of data preprocessing, feature scaling, and comprehensive evaluation metrics in building an effective diabetes prediction model. By focusing on the most significant features, particularly Glucose, the model can assist healthcare professionals in identifying individuals at risk of diabetes, ultimately contributing to better patient care and prevention strategies.</p>



</body>
</html>
