# mlops_specalization
 
<p>This repo has the Notes and Code with respective <b>Deeplearning.ai</b> course</p>

# Steps of an Ml Project :
<ol>
<li>Scoping</li>
<ul>
<li>Define the business problem or use case that the ML project is intended to solve. This involves identifying the key stakeholders, understanding their needs, and setting project goals and constraints.</li>
</ul>
<li>Data</li>
<ul>
<li>Define the data that will be used to train and test the model. This involves identifying the sources of data, understanding their format and quality, and establishing a baseline performance metric for the model.</li>
<li>Label and organize the data to make it ready for training. This involves identifying the target variable and ensuring that the data is properly formatted and annotated.</li>
</ul>
<li>Modeling</li>
<ul>
<li>Select an appropriate model and train it on the labeled data. This involves choosing a suitable algorithm and hyperparameters and evaluating the performance of the model using various metrics.</li>
<li>Conduct error analysis to identify the sources of errors and improve the model's performance. This involves analyzing the model's predictions and identifying the most common types of errors.</li>
</ul>
<li>Deployment</li>
<ul>
<li>Deploy the model in a production environment, making sure that it can handle incoming data and respond to requests in real-time.</li>
<li>Monitor and maintain the system to ensure that it continues to perform well over time. This involves monitoring key performance metrics and making updates to the model and infrastructure as necessary.</li>
</ul>
</ol>
These steps provide a high-level overview of the typical stages involved in an ML project, but the exact details may vary depending on the specific project and its requirements.

# Here's a more detailed breakdown of each step involved in an ML project:
<ol>
<h1><li>
 
 Deployment: 
 
 </li></h1>
 
<ul>
 <li>
  Deployment in an ML system refers to the process of making a trained machine learning model available for use in a production environment. This involves setting up the infrastructure and systems needed to run the model and respond to incoming data, such as databases, APIs, or web applications.
 </li>

<li>
 In deployment, the model is integrated into the existing production infrastructure, and it should be able to handle a high volume of requests and respond quickly to user inputs. Once deployed, the model's performance is monitored using various metrics, such as accuracy, latency, and throughput, to ensure that it continues to function optimally over time.
</li>
<li>
Deployment is a crucial stage in an ML project because it's the point where the model is actually put into use to solve real-world problems. A well-deployed and well-monitored ML model can provide a significant business value, improve efficiency, and save time and money.
</li>
</ul>
<h2>Key Challenges in deployment:</h2>
<ol>
<h3>
 <li>Conecept Drift & Data Drift</li>
 </h3>
 <h3>Concept drift</h3>
 <ul>
 <li>
 <p>
Concept drift refers to the phenomenon where the underlying relationship between the input variables and the target variable changes over time. This can happen in situations where the external environment or conditions change, causing the relationships between the variables to shift.

For example, let's say a company uses a machine learning model to predict the demand for a certain product based on historical sales data. The model is trained on data from the past few years and works well in predicting future demand. However, the company launches a new marketing campaign that significantly increases the product's visibility and popularity. This change in external conditions could cause the relationship between sales and the other input variables to shift, resulting in a concept drift that affects the model's accuracy and performance.
 </p> 
 </li>
 </ul>
<h3>Data drift</h3>
 <ul>
<li><p>Data drift refers to the phenomenon where the statistical properties of the input data change over time. This can happen due to various reasons, such as changes in the data collection process, changes in user behavior, or changes in the underlying distribution of the data.

For example, let's say a company uses a machine learning model to detect fraudulent transactions in their online payment system. The model is trained on data from the past year and performs well in detecting fraud. However, the company introduces a new product line that attracts a different type of customer, resulting in a change in the distribution of the input data. This change in data distribution could result in a data drift that affects the model's accuracy and performance.

In both cases, concept drift and data drift can lead to a degradation in the performance of machine learning models over time. To address these issues, it's important to regularly monitor the model's performance and update it with new data or retraining it with different parameters as needed.
</p>
</li>
</ul>
 
 <h3> <li>Software Engineering issues</li> </h3>
 <h3>
</ol>
</ol>
