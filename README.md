<h1>Breast Cancer Prediction Using scikit-learn Dataset</h1>
<h3>Overview</h3>
<p>This project aims to predict breast cancer using the Breast Cancer Wisconsin (Diagnostic) Dataset available from scikit-learn.
  By applying various Machine Learning (ML) techniques, we aim to build a reliable and accurate model for breast cancer diagnosis based on diagnostic features.</p>

<h3>Table of Contents</h3>
<ol type = "1">
<li>Installation</li>
<li>Dataset</li>

<li>Usage</li>
<li>Models Implemented</li>
<li>Evaluation Metrics</li>

<li>Contributing</li>
</ol>
<h3>Installation</h3>
<b>Prerequisites</b>
<p>Ensure you have Python 3.7 or above installed. The required libraries can be installed using the following command:</p>

<ul>pip install -r requirements.txt</ul>
<b>Required Libraries</b>
<ol type = "1">
<li>numpy</li>
<li>pandas</li>
<li>scikit-learn</li>
<li>matplotlib</li>
<li>seaborn</li>
</ol>
<h2>Dataset</h2>
<p>The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) Dataset available in scikit-learn. 
  It includes 30 features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, describing characteristics of the cell nuclei present in the image.</p>

<b>Loading the Dataset</b>
<ul>The dataset can be loaded directly from scikit-learn:</ul>

<ul>from sklearn.datasets import load_breast_cancer</ul>
<ul>data = load_breast_cancer()</ul>
</ol>
<h2>Usage</h2>

<li><b><i>Data Preprocessing</i></b></li>
<ul>Run the data preprocessing script to clean and prepare the dataset.</ul>

<ul>python src/data_preprocessing.py</ul>
<li><b><i>Training Models</i></b></li>
<ul>Train the Machine Learning models:</ul>

<ul>python src/ml_models.py</ul>
<li><b><i>Evaluation</i></b></li>
<ul>Evaluate the performance of the models:</ul>

<ul>python src/evaluation.py</ul>

<h2>Models Implemented</h2>
<li><b>Machine Learning Models</b></li>
<ol type = "1">
<li>Logistic Regression</li>
<li>Decision Tree Classifier</li>
<li>Random Forest Classifier</li>
<li>Support Vector Machine (SVM)</li>
<li>K-Nearest Neighbors (KNN)</li>
</ol>
<h2>Evaluation Metrics</h2>
<ol type = "1">
  
</ol>
<li>Accuracy</li>
<li>Precision</li>
<li>Recall</li>
<li>F1 Score</li>
<li>ROC-AUC Score</li>



<h2>Contributing</h2>
<ul>Please follow these steps:</ul> 
<ol type = "1">
<li>Fork the repository.</li>
<li>Create a new branch (git checkout -b feature-branch).</li>
<li>Commit your changes (git commit -m 'Add new feature').</li>
<li>Push to the branch (git push origin feature-branch).</li>
<li>Open a Pull Request.</li>
</br>
<b>By following this README, you should be able to set up, run, and understand the breast cancer
  prediction project using the scikit-learn dataset and Machine Learning techniques. Let's work together to enhance early detection and diagnosis of breast cancer!</b>






