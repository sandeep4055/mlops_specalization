# Mlops_specalization
 
<h2>This repo has the notes and code of <strong>Machine Learning Engineering for Production (MLOps) Specialization on Coursera (offered by deeplearning.ai)</strong></h2>

<img src="https://user-images.githubusercontent.com/70133134/233529477-8487cc0b-432d-415e-8030-b8fe8fbcbbe5.png" width="100%">

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
These steps provide a high-level overview of the typical stages involved in an ML project, but the exact details may vary depending on the specific project and its requirements.<br><br>

![mlprojectsteps](https://user-images.githubusercontent.com/70133134/233526364-96b1a927-5d7a-42eb-bf3a-c51251afc28c.jpg)

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
</ul><br>

<img src="https://user-images.githubusercontent.com/70133134/233526817-8e492017-1ca3-42eb-8a69-56ab2094cbbf.gif" alt="deployment" width="800" height="450">

<h2>Key Challenges in deployment:</h2>
<ol>
<h3> <li> Conecept Drift & Data Drift </li> </h3>
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
<p>Concept Drift and Data Drift in Machine Learning Models (Illustrated)</p><br>
		
<img src="https://user-images.githubusercontent.com/70133134/233527662-2fdef9f9-3888-47d6-bb8b-b2902e6d8d43.png" width="700" height="450">
 
 <h3> <li>Software Engineering issues</li> </h3> 
 <ul>
    <li><strong>Real-time or Batch:</strong> Real-time deployment involves making predictions on incoming data as soon as it arrives, while batch deployment involves making predictions on a set of data at once. Real-time deployment is often used for applications where quick responses are needed, such as fraud detection or recommendation systems, while batch deployment is used for applications where latency is less critical, such as training or offline analytics.</li>
 
 <li><strong>Cloud or Edge/Browser:</strong> Cloud deployment involves hosting the machine learning model on a cloud platform such as Amazon Web Services, Google Cloud Platform, or Microsoft Azure, while edge or browser deployment involves hosting the model on a local device or browser. Cloud deployment offers scalability and accessibility, while edge or browser deployment offers lower latency and privacy.</li>

<li><strong>Compute Resources (CPU/GPU/TPU):</strong> The type of compute resources used in deployment can have a significant impact on the performance and cost of the machine learning model. Central processing units (CPUs) are commonly used for small-scale deployments, while graphics processing units (GPUs) and tensor processing units (TPUs) are used for larger-scale deployments that require high parallelism and faster processing times.</li>

<li><strong>Logging:</strong> Logging involves recording various metrics and events related to the machine learning model's performance, such as accuracy, latency, throughput, and error rates. This data is used to monitor the model's performance over time, identify issues or anomalies, and improve the model as needed.</li>

<li><strong>Security & Privacy:</strong> Security and privacy are critical considerations in machine learning deployment, as models can contain sensitive or confidential data. It's important to implement appropriate security measures such as data encryption, access control, and threat monitoring to prevent unauthorized access or attacks.</li>

<li><strong>Latency & Throughput:</strong> Latency and throughput are performance metrics that measure the time it takes for the machine learning model to respond to incoming requests and the number of requests it can handle per unit of time. Low latency and high throughput are critical for real-time applications such as recommendation systems or fraud detection, while batch applications may have more flexibility in these metrics.</li>
 </ul>  
</ol>
 
<h2>Deployment Patterns in ML Systems</h2>
<p>There are several deployment patterns used in machine learning (ML) systems. Three common patterns are shadow deployment, canary deployment, and blue-green deployment:</p>
 
<ul>
<h3><li>Shadow Deployment</h3>
<p>In a shadow deployment, a new version of the ML model is deployed alongside the existing model, but the traffic is still directed to the existing model. The new model processes a copy of the traffic and the output is compared to the output of the existing model to ensure that the new model is performing correctly. Once the new model has been validated, traffic can be gradually shifted to the new model.</p>
 
<h3><li>Canary Deployment</h3>
<p>In a canary deployment, a small percentage of traffic is directed to the new version of the ML model while the rest of the traffic is directed to the existing model. The performance of the new model is monitored and compared to the existing model to ensure that it is performing correctly. If the new model is performing well, traffic can gradually be shifted to the new model.</p>
 
<h3><li>Blue-Green Deployment</h3>
<p>In a blue-green deployment, two identical environments are set up, with one environment (the blue environment) running the current version of the ML model and the other environment (the green environment) running the new version of the model. Traffic is initially directed to the blue environment, while the green environment is set up and tested. Once the green environment has been validated, traffic can be gradually shifted to the green environment. If any issues are found with the new model, traffic can easily be redirected back to the blue environment.</p>
<p>Each of these deployment strategies has its own benefits and drawbacks, and the choice of strategy depends on the specific requirements of the ML system.</p>
 </ul>
 
 <h2>Automation Levels</h2>
 
 <p>The different degrees of automation in an ML system are:</p>
	<ul>
		<li><strong>Human Only:</strong> Tasks are performed entirely by human operators without any automation.</li>
		<li><strong>Shadow Mode:</strong> Automation is used to assist humans in performing tasks, but humans retain full control and decision-making power.</li>
		<li><strong>AI Assistance:</strong> Automation is used to assist humans in performing tasks, and AI algorithms provide recommendations or suggestions to guide human decision-making.</li>
		<li><strong>Partial Automation:</strong> Some aspects of the task are automated, but humans still play a significant role in decision-making and control.</li>
		<li><strong>Full Automation:</strong> The task is completely automated, and humans are only involved in monitoring or supervising the automated system.</li>
	</ul>
<h1> <li> Monitoring </li> </h1> 
<p>
Monitoring is a critical component of machine learning systems, as it allows for the detection of issues and anomalies that can affect the performance and accuracy of the models. Monitoring involves the collection of various metrics and events related to the ML system, such as model accuracy, latency, throughput, and error rates.
</p>

<p> Some key areas that should be monitored in an ML system include: </p>

<ul>

<li><strong> Data Quality:</strong>  Monitoring the quality of the input data is important to ensure that the data is representative of the real-world scenarios and that it is free from errors, missing values, or outliers. </li>

<li><strong> Model Performance:</strong>  Monitoring the performance of the model is critical to detect issues such as overfitting, underfitting, or concept drift. Metrics such as accuracy, precision, recall, F1 score, and AUC can be used to evaluate the model's performance. </li>

<li><strong> Resource Utilization:</strong>  Monitoring the resource utilization of the ML system, such as CPU, GPU, memory, and storage, is important to optimize the system's performance and reduce costs. </li>

<li><strong> Anomalies and Outliers:</strong>  Monitoring for anomalies and outliers in the input data and the model's predictions can help detect issues such as data drift, model bias, or attacks on the system. </li>

<li><strong> Feedback Loop:</strong>  Monitoring the feedback loop between the ML system and the end-users is important to evaluate the system's effectiveness in meeting the user's needs and to identify areas for improvement. </li>

</ul>
</br>
<p> To effectively monitor an ML system, it's important to set up automated monitoring processes that can generate alerts or notifications when issues or anomalies are detected. Monitoring should be performed regularly, and the monitoring processes should be updated as the system evolves and new issues are identified.</p>

<h2> These metrics can be broadly classified into three categories:</h2>
<ol>

<li><strong> Input metrics:</strong> Input metrics measure the quality and characteristics of the input data that is fed into the machine learning system. These metrics can help identify issues related to data quality, data preprocessing, and data bias. Some examples of input metrics include:</li>
<ul>
<li><strong> Data completeness:</strong> Measures the percentage of missing data in the input dataset.</li>
<li><strong> Data distribution:</strong> Measures the statistical properties of the input data, such as mean, variance, and skewness.</li>
<li><strong> Data bias:</strong> Measures the presence of bias in the input data, such as demographic bias or sampling bias.</li>
</ul>

<li><strong> Output metrics:</strong> Output metrics measure the performance and accuracy of the machine learning system in producing predictions or classifications. These metrics can help identify issues related to model performance, concept drift, or data drift. Some examples of output metrics include:</li>
<ul>
<li><strong> Accuracy:</strong> Measures the percentage of correct predictions made by the model.</li>
<li><strong> Precision:</strong> Measures the percentage of true positive predictions out of all positive predictions made by the model.</li>
<li><strong> Recall:</strong> Measures the percentage of true positive predictions out of all actual positive cases in the input data.</li>
<li><strong> F1 score:</strong> A combined metric that balances precision and recall.</li>
</ul>

<li><strong> Software metrics:</strong> Software metrics measure the behavior and performance of the machine learning system at the software level. These metrics can help identify issues related to model scalability, computational efficiency, or software bugs. Some examples of software metrics include:</li>
<ul>
<li><strong>Memory usage:</strong> Measures the amount of memory used by the machine learning system during training or prediction.</li>
<li><strong>CPU usage:</strong> Measures the amount of CPU resources used by the machine learning system during training or prediction.</li>
<li><strong>Latency:</strong> Measures the time it takes for the machine learning system to produce a prediction or classification.</li>
</ul>

</ol></br>

<p> By monitoring these metrics, machine learning engineers and data scientists can gain insights into the behavior and performance of the system, and identify areas for improvement or optimization.</p>
<p>
Yes, in addition to the input, output, and software metrics, customized metrics can also be defined to monitor specific aspects of the machine learning system that are important to a particular application or use case. Customized metrics can help track business-specific key performance indicators (KPIs), measure the success of specific features or functionalities, or provide more granular insights into the system's performance.
</p>

<p>
For example, in an e-commerce recommendation system, a customized metric could be defined to measure the click-through rate (CTR) of recommended products. This metric would be specific to the application and would provide valuable insights into the performance of the recommendation algorithm in terms of user engagement and revenue generation.
</p>

<p>
Customized metrics can be implemented using various monitoring tools and platforms, and can be integrated with existing input, output, and software metrics to provide a comprehensive view of the system's performance. It's important to carefully define and select customized metrics that are relevant to the business goals and objectives, and to regularly review and update them as the system evolves over time.
</p>

</ol>
