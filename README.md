# Mlops_specalization
 
<h2>This repo has the notes and code of <strong>Machine Learning Engineering for Production (MLOps) Specialization on Coursera (offered by deeplearning.ai)</strong></h2>

<img src="https://user-images.githubusercontent.com/70133134/233529477-8487cc0b-432d-415e-8030-b8fe8fbcbbe5.png" height="400">

# What is AI System?
An AI system is typically made up of two primary components: code and data.

The code component of an AI system refers to the **algorithms** and **programming logic** that enable the system to perform its intended function. This code may be written in various programming languages, depending on the specific technology being used.

The data component of an AI system refers to the **training** and **testing** data that the system uses to learn and make predictions. This data can come from a variety of sources, including sensors, databases, and user interactions, and it may be structured, unstructured, or semi-structured.

In many AI systems, the code and data components are interdependent, with the code relying on the data to make predictions and the data being shaped by the code to improve the accuracy of those predictions. As a result, the design and implementation of an AI system often requires careful consideration of both components, as well as the interactions between them.

<img src="https://user-images.githubusercontent.com/70133134/235284994-325b0541-abeb-4bb7-a6df-be1acc2df34b.png" alt="aivsml"  height="350" >


# AI system vs ML system

AI (Artificial Intelligence) systems and ML (Machine Learning) systems are related concepts, but they are not exactly the same thing.

An AI system is a broader term that refers to any system that is designed to perform tasks that would normally require human intelligence to complete. AI systems can include machine learning techniques, as well as other types of algorithms like rule-based systems, genetic algorithms, and fuzzy logic systems. AI systems can also involve various types of data processing, such as natural language processing, image recognition, and decision making.

On the other hand, a machine learning system is a specific type of AI system that uses statistical and mathematical techniques to enable machines to learn from data, without being explicitly programmed to do so. Machine learning systems rely on training data to build models that can make predictions or classify new data points. These models can then be used to perform a wide range of tasks, such as image recognition, speech recognition, and natural language processing.

In summary, while all machine learning systems are AI systems, not all AI systems are machine learning systems. AI systems can use a variety of techniques and algorithms to perform tasks, while machine learning specifically involves using statistical and mathematical models to learn from data.


<img src="https://user-images.githubusercontent.com/70133134/235285425-e2d186bb-361e-470b-b715-75636a65671f.jpg" alt="aivsml"  height="350" >


# What is AI/ML project?

An AI/ML project is a project that involves developing and deploying an artificial intelligence or machine learning system to solve a specific problem or achieve a specific goal. These projects can take a wide variety of forms, depending on the industry, domain, and application.

Some common types of AI/ML projects include:
<ol>
<li> Image recognition: developing a system that can accurately identify and classify images.</li>

<li> Natural language processing: developing a system that can analyze and understand human language, such as chatbots or sentiment analysis tools.</li>

<li> Predictive modeling: developing a system that can predict future outcomes based on historical data, such as stock price predictions or demand forecasting.	</li>

<li> Recommendation systems: developing a system that can recommend products or services to users based on their preferences or behavior, such as Netflix or Amazon's recommendation engines.</li>

<li> Autonomous vehicles: developing a system that can safely and efficiently operate a vehicle without human intervention.</li>	
</ol>

AI/ML projects can be complex and challenging, as they require expertise in data science, machine learning algorithms, software engineering, and often domain-specific knowledge. The success of these projects depends on careful planning, data collection and preprocessing, model training and evaluation, and deployment and monitoring of the system in production.


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
	
	

<h1> <li> Modelling </li> </h1>
	


<p>The process of modeling means training a machine learning algorithm to predict the labels from the features, tuning it for the business need, and validating it on holdout data.The output from modeling is a trained model that can be used for inference, making predictions on new data points.</p>

**The objective of machine learning is not a model that does well on training data, but one that demonstrates it satisfies the business need and can be deployed on live data.**

	
***Modelling is an iterative process*** where you start with a model and hyperparameters and use them to train the model on the data. Then, you analyze the errors and use the insights to improve the model, the hyperparameters, or the data. This loop is repeated many times to achieve better performance. Making good choices about how to modify the data, model, or hyperparameters is critical to improving the model's performance quickly.

<p> Once you have achieved a good model, you should perform a richer error analysis and audit the system to make sure it is working correctly before pushing it to a production deployment. This step is important to ensure that the model is effective, reliable, and scalable in the production environment.</p>

<p> So the major steps involved in modelling are : </p>

- Select and train model(includes hyperparameter tuning)
- Performing error analysis
	
There are two different approaches/philosophies while building machine learning models, they are ***data-centric approach*** and the ***model-centric approach*** to achieve good performance.

- **Data-centric approach:** In the data-centric approach, the focus is on acquiring and preprocessing high-quality data, and selecting appropriate features that capture the essential characteristics of the data. The idea is that if the data is good enough, and the features are informative enough, then any model that is trained on this data will perform well. In this approach, the model is seen as a "black box" that transforms input data into output predictions, and the emphasis is on the quality and quantity of the input data.

- **Model-centric approach:** In the model-centric approach, the focus is on designing and training a sophisticated model that can learn complex patterns and relationships in the data, even if the data is noisy or incomplete. The idea is that if the model is expressive enough, it can capture the underlying structure of the data, and produce accurate predictions even if the input data is imperfect. In this approach, the model is seen as the key to achieving good performance, and the emphasis is on designing and training a model that is well-suited to the task at hand.

<p>Both approaches have their advantages and disadvantages, and the choice of approach depends on the specific problem and domain. The data-centric approach is often more effective when the data is plentiful and well-structured, while the model-centric approach is often more effective when the data is complex or noisy, or when the problem requires a high degree of accuracy or flexibility.</p>
	
***In machine learning, having good quality data is crucial for model performance, and even the best models will struggle with bad data, while models with suboptimal performance can still perform well with high-quality data.***

## The key challenges in model development are:

1. **Doing well on the training set:** The model should fit the training data well and achieve a low training error. This ensures that the model is capturing the patterns in the training data and can make accurate predictions.

2. **Doing well on the test set:** The model should generalize well to new, unseen data and achieve a low test error. This ensures that the model is not overfitting to the training data and can make accurate predictions on new data.

3. **Doing well on business metric:** The model should perform well on the specific business metric that it is designed to optimize. For example, If the model is being used to improve customer service or support, then the business metric might be customer satisfaction scores. This ensures that the model is actually solving the problem it was designed to solve, and is delivering value to the business.
	


## Why low average in test error isn't good enough
Low average test error scores are a good indication that a model is performing well on the test data, but they are not always enough to get a model into production. There are several reasons for this:

### Performance on disproportionately important examples :

Even if the model performs well on the test data, it may still fail to perform well on disproportionately important examples. Disproportionately important examples refer to the subset of examples in a dataset that have a greater impact on the overall performance of the model than other examples. These examples are often critical to the success of the model, and their accuracy is crucial for achieving good performance on the relevant business metric.

For example, in a medical diagnosis model, correctly identifying patients with a high risk of a rare disease may be more important than correctly classifying patients with a low risk of the disease. Similarly, in a fraud detection model, correctly flagging high-value transactions as fraudulent may be more important than accurately detecting low-value fraudulent transactions.

Failing to accurately predict disproportionately important examples can have significant consequences, such as missed diagnoses or fraudulent transactions slipping through the system. Therefore, it is important to carefully identify and prioritize these examples in the model development process and evaluate the model's performance on them separately from the overall test set.
	
### Performance on key slices of dataset :

Another reason why low average test error scores are not enough to get a model into production is the performance on key slices of the dataset. Key slices are subsets of the data that are particularly relevant to the problem being solved, such as examples with certain features or from certain subgroups.

For example, in a hiring model, it may be important to ensure that the model is not biased against candidates of a certain gender or race. In this case, the model's performance on key slices, such as male and female candidates or candidates from different racial groups, would be crucial to evaluate separately from the overall test set.

Similarly, in a recommendation system, the model's performance on key slices of the data, such as users with a high purchase history or users with a high influence on the platform, may be disproportionately important for the overall success of the system.

Failing to accurately predict key slices of the data can lead to biased or ineffective models, which can have serious consequences in the real world. Therefore, it is important to carefully identify and prioritize these key slices in the model development process and evaluate the model's performance on them separately from the overall test set.

### Rare Classes :

Rare classes refer to the subset of examples in a dataset that occur infrequently, making up only a small proportion of the overall dataset. These classes are often difficult to model accurately because the model may not have enough examples to learn from, and they are more prone to being misclassified.

For example, in a classification problem involving a dataset of customer reviews, the rare classes might be reviews with low ratings or reviews that are flagged as spam. Although these classes may be infrequent, correctly identifying them can be crucial for making informed decisions.

Failing to accurately predict rare classes can lead to significant consequences, such as missed opportunities or incorrect decisions. Therefore, it is important to carefully identify and prioritize these classes in the model development process and evaluate the model's performance on them separately from the overall test set.
	

	

<h2> Establish </h2>



<h1><li> Deployment  </li></h1>
 
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

<img src="https://user-images.githubusercontent.com/70133134/233526817-8e492017-1ca3-42eb-8a69-56ab2094cbbf.gif" alt="deployment"  height="450">

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
		
<img src="https://user-images.githubusercontent.com/70133134/233527662-2fdef9f9-3888-47d6-bb8b-b2902e6d8d43.png"  height="450">
 
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
