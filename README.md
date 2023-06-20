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
<h1> <li> SCOPING </li> </h1>

**Scoping** in MLOps refers to defining the boundaries and extent of an MLOps project or initiative. It involves clearly identifying and specifying the goals, objectives, and scope of work for implementing MLOps practices within an organization.

The steps in the scoping process for an AI project are as follows:

**Identify Business Problem**: Start by brainstorming and identifying the specific business problem or opportunity that you want to address using AI. This could be a pain point, a challenge, or a potential improvement area within your organization.

**Brainstorm AI Solutions**: Once you have identified the business problem, brainstorm potential AI solutions that could help address or solve the problem. Explore different AI techniques, algorithms, and approaches that could be applied.

**Assess Feasibility and Value**: Evaluate the feasibility and value of each potential AI solution. Consider factors such as data availability, quality, infrastructure requirements, expertise, cost, and potential benefits to the business. This assessment helps determine which AI solutions are most viable and valuable.

**Determine Milestones**: Define the key milestones and deliverables for the AI project. Break down the project into manageable phases or stages, and set clear objectives for each milestone. This helps in planning and tracking progress throughout the project.

**Budget for Resources**: Determine the resources required for the AI project, including budget considerations. This includes financial resources for acquiring necessary hardware, software, and talent, as well as allocating sufficient time and personnel for the project.

By following these steps, organizations can effectively scope an AI project, ensuring alignment between business objectives and AI solutions. This process helps in setting realistic expectations, allocating resources appropriately, and ultimately achieving successful implementation of AI solutions to address business problems.

When scoping an MLOps project, there are several key considerations:

**Project Goals**: Determine the specific objectives and outcomes the MLOps project aims to achieve. This could include improving model deployment speed, enhancing model monitoring and management, increasing automation in the ML lifecycle, or ensuring better collaboration between data scientists and operations teams.

**Scope of ML Pipeline**: Define the boundaries of the ML pipeline that will be covered by the MLOps implementation. This includes identifying the stages of the ML lifecycle that will be addressed, such as data collection, preprocessing, model training, evaluation, deployment, monitoring, and retraining.

**Infrastructure and Tooling**: Identify the infrastructure requirements and tooling necessary to support the MLOps process. This could involve selecting the appropriate cloud services, containerization platforms, version control systems, CI/CD pipelines, and monitoring tools based on the project's scope and goals.

**Team and Roles**: Determine the team members and roles involved in the MLOps project. This may include data scientists, ML engineers, software engineers, DevOps specialists, data engineers, and other relevant stakeholders. Clearly define their responsibilities and areas of collaboration.

**Timeline and Milestones**: Establish a timeline for the MLOps project, including key milestones and deliverables. Break down the implementation into manageable phases to ensure a smooth transition and adoption of MLOps practices.

**Risk Assessment**: Assess potential risks and challenges that may arise during the implementation of MLOps. Consider issues such as data security, model performance, scalability, compliance, and regulatory requirements. Develop mitigation strategies and contingency plans to address these risks.

By scoping an MLOps project effectively, organizations can ensure a clear understanding of the project's objectives, deliverables, and timelines. This helps in better resource allocation, stakeholder alignment, and successful implementation of MLOps practices to enhance the efficiency, scalability, and reliability of machine learning workflows.



<h1> <li> DATA </li> </h1>

In simple terms, **data** refers to information or facts that are collected or recorded. It can be any piece of information that is meaningful and can be stored, processed, or analyzed. Data can come in different forms, such as numbers, text, images, audio, or video. It is the raw material from which insights and knowledge can be derived.

Think of data as building blocks that can be used to understand and learn about something. For example, if you have a collection of temperature readings from different days, that data can tell you how the temperature changes over time. Similarly, if you have a list of customer purchases, that data can help you understand what products are popular and how much revenue is generated.

Data is everywhere around us, and we generate and encounter data in our daily lives. From the information we enter into online forms to the measurements taken by sensors in our smartphones, data is constantly being collected. The value of data lies in its ability to provide insights, make predictions, and inform decision-making in various fields like business, science, healthcare, and more.

To put it simply, data is like puzzle pieces that, when properly arranged and analyzed, can help us uncover patterns, understand relationships, and gain knowledge about a particular subject.


Data plays a critical role in MLOps (Machine Learning Operations) as it is the foundation on which machine learning models are built and deployed. Here are some key aspects of data in MLOps:

**Data Collection and Storage**: MLOps involves collecting and storing data from various sources to build machine learning models. This may include structured data from databases, unstructured data from text or image sources, or streaming data from real-time sources. Proper data collection and storage mechanisms need to be in place to ensure data availability and reliability for model training and inference.

**Data Preprocessing and Transformation**: Data often needs to be preprocessed and transformed before it can be used for model training. This involves tasks such as cleaning, normalizing, scaling, and feature engineering. MLOps pipelines incorporate these preprocessing steps to ensure consistent and reliable data preparation.

**Data Versioning and Management**: Just like code versioning, it is important to version and manage data in MLOps. This ensures that the training data used for a particular model version is properly documented and can be reproduced if needed. Data versioning also facilitates collaboration among data scientists and helps track changes in the data over time.

**Data Quality and Monitoring:** Data quality is crucial for the performance of machine learning models. MLOps involves monitoring the quality of data used in model training and inference. Data quality checks can be performed to identify missing values, outliers, or inconsistencies. Continuous monitoring helps identify issues and take corrective actions to ensure model accuracy and reliability.

**Data Governance and Compliance**: MLOps requires adherence to data governance and compliance regulations. This includes ensuring data privacy, security, and compliance with legal and ethical standards. Data access controls, encryption, and anonymization techniques may be employed to protect sensitive information.

**Data Pipeline Automation**: MLOps pipelines automate the data processing and model training workflows. This involves setting up automated data pipelines that handle data ingestion, preprocessing, model training, and deployment. Automation helps streamline the process, reduce manual errors, and ensure reproducibility.

Overall, effective management and utilization of data are crucial for successful MLOps implementation. Proper data handling, preprocessing, versioning, and monitoring are essential to ensure the accuracy, robustness, and ethical use of machine learning models in real-world applications.

## Structured Data VS Un-Structured Data

**Structured Data**:
Structured data refers to data that has a predefined format and is organized in a tabular or relational manner. It follows a consistent and well-defined schema, where each data field is assigned a specific data type. Structured data is typically stored in databases, spreadsheets, or other structured formats. Examples of structured data include tables with columns and rows, such as customer information in a CRM system or sales data in a transaction database.

**Key characteristics of structured data**:

**Well-defined schema**: Structured data has a predefined schema that outlines the structure, format, and data types of each field or attribute.

**Organized in a tabular manner**: Structured data is organized in rows and columns, making it easy to search, sort, and query using standard database operations.

**Clear relationships**: Structured data often involves relationships between different tables or entities, which are defined through keys or primary/foreign key relationships.

**Easy to process and analyze**: Structured data lends itself well to data processing and analysis using standard SQL queries or other relational operations. It is suitable for statistical analysis, reporting, and business intelligence.

**Examples of structured data**:

- Employee records with fields like name, ID, department, and salary stored in a database table.
- Financial data such as sales transactions with columns like date, product, quantity, and price in a spreadsheet.

**Unstructured Data**:
Unstructured data refers to data that does not have a predefined or organized format. It lacks a consistent structure, making it more challenging to analyze and process compared to structured data. Unstructured data can take various forms, including text documents, images, videos, audio files, social media posts, emails, and more.

**Key characteristics of unstructured data**:

**Lack of predefined structure**: Unstructured data does not conform to a fixed schema or format. It is often free-form and does not have a specific organization or predefined categories.

**Varied data types**: Unstructured data can contain text, images, audio, video, or a combination of different media types.

**Requires data preprocessing**: Unstructured data often needs preprocessing steps like text mining, natural language processing, image or audio analysis to extract meaningful information.

**Rich and contextual information**: Unstructured data can provide detailed and context-rich information, allowing for more nuanced analysis and insights.

**Examples of unstructured data**:

- Text documents like emails, articles, or social media posts.
- Images or videos captured from cameras or collected from the internet.
- Audio recordings of phone calls or meetings.

It's worth noting that semi-structured data lies between structured and unstructured data, combining some organizational structure with flexibility in data representation. Examples include XML files, JSON data, or HTML documents.

## Sources of Data:

In the context of machine learning and data analysis, data is obtained from various sources. Here are some common sources of data:

**Databases**: Databases are structured repositories that store data in a organized manner. They can include relational databases, such as MySQL or PostgreSQL, or NoSQL databases like MongoDB or Cassandra. Databases are commonly used to store structured and organized data, making them a valuable source for machine learning tasks.

**APIs (Application Programming Interfaces)**: APIs allow applications to communicate and exchange data with external systems or services. Many online platforms provide APIs that enable developers to retrieve data programmatically. Examples include social media APIs (e.g., Twitter API, Facebook Graph API), weather APIs, financial market APIs, and more. Using APIs, you can fetch data in real-time or access historical data for analysis.

**File Formats**: Data can be stored in various file formats, such as CSV (Comma-Separated Values), JSON (JavaScript Object Notation), XML (eXtensible Markup Language), Excel spreadsheets, or plain text files. These files can contain structured, semi-structured, or unstructured data. They are often used for sharing and exchanging data between different systems or as a means of data storage.

**Web Scraping**: Web scraping involves extracting data from websites by parsing and analyzing their HTML content. It allows you to collect data from websites that do not provide APIs or structured data feeds. Web scraping tools and libraries help automate the process of fetching and extracting data from web pages.

**Sensor Data**: In many domains, data is collected from various sensors, devices, or IoT (Internet of Things) devices. These sensors capture information such as temperature, humidity, pressure, location coordinates, or other environmental variables. Sensor data is often time-series data and is used in applications such as environmental monitoring, smart homes, or industrial automation.

**Public Datasets**: There are numerous public datasets available that can be used for machine learning and data analysis. These datasets are provided by organizations, government agencies, research institutes, and academic institutions. Examples include datasets like MNIST (handwritten digits), CIFAR-10 (image classification), UCI Machine Learning Repository datasets, and more.

**User-generated Content**: User-generated content, such as social media posts, comments, reviews, or user feedback, can serve as a valuable source of data. These sources can provide insights into user behavior, sentiment analysis, or customer preferences.

**Surveys and Questionnaires**: Surveys and questionnaires are structured data collection methods used to gather specific information from individuals or groups. The collected responses can be transformed into structured data for analysis.

It's important to note that when working with data, it is essential to consider data privacy, legal restrictions, and ethical considerations. Depending on the source and type of data, you may need to ensure compliance with relevant regulations and obtain necessary permissions or consents.




## Major Types of Data problems

In machine learning and data analysis, there are several common types of data problems that can affect the performance and reliability of models. Here are some major types of data problems:

**Missing Data**: Missing data occurs when there are gaps or incomplete entries in the dataset. This can be problematic as it can lead to biased or inaccurate analysis. Handling missing data involves strategies such as imputation (replacing missing values with estimated values) or exclusion of incomplete records.

**Outliers**: Outliers are data points that deviate significantly from the overall pattern of the dataset. Outliers can have a significant impact on statistical analysis and machine learning models, potentially skewing the results. Identifying and handling outliers can involve methods such as statistical techniques, visualization, or using robust algorithms.

**Imbalanced Data**: Imbalanced data refers to datasets where the number of samples in different classes or categories is heavily skewed. This can pose challenges for machine learning models, as they may be biased towards the majority class and perform poorly on the minority class. Techniques such as oversampling, undersampling, or using class weighting can help address the issue of imbalanced data.

**Noisy Data**: Noisy data contains errors or inconsistencies, which can be introduced during data collection, storage, or preprocessing. Noise can adversely affect model performance and lead to inaccurate results. Cleaning and preprocessing techniques, such as removing duplicates, correcting errors, or smoothing techniques, can help mitigate the impact of noisy data.

**Feature Selection and Dimensionality**: High-dimensional datasets with a large number of features can introduce challenges in model training and inference. Irrelevant or redundant features can degrade model performance or increase computational complexity. Feature selection and dimensionality reduction techniques, such as correlation analysis, feature importance ranking, or principal component analysis (PCA), can help address these issues.

**Biased Data**: Biased data occurs when the training data does not accurately represent the target population or exhibits systematic biases. This can lead to biased predictions or unfair outcomes. It is important to identify and address biases in the data, such as demographic biases or sampling biases, to ensure fairness and ethical use of machine learning models.

Addressing these data problems requires careful data preprocessing, cleaning, and selection techniques. It is crucial to understand the specific data challenges in a given context and apply appropriate strategies to mitigate their impact on the performance and reliability of machine learning models.



## How do we say that data is sufficient or not in ml?

Determining whether the available data is sufficient for machine learning depends on various factors, including the complexity of the problem, the size and quality of the dataset, and the requirements of the model. Here are some considerations to assess data sufficiency in machine learning:

**Adequate Sample Size**: Generally, having a larger dataset provides more representative information for the model to learn from. However, there is no fixed threshold for the minimum or maximum dataset size. It depends on the complexity of the problem and the number of features. A small dataset may be sufficient for simple problems, while more complex tasks may require larger datasets to capture the underlying patterns effectively.

**Representative Data**: The data should be representative of the target population or the problem domain. It should cover a diverse range of scenarios and include relevant variations and patterns. Biases or gaps in the data can lead to poor generalization and biased model performance. It is crucial to have a dataset that adequately captures the variations and patterns present in the real-world problem.

**Satisfactory Feature Coverage**: The dataset should encompass a sufficient range of features or variables that are relevant to the problem. The features should provide meaningful information and allow the model to discriminate between different classes or predict the target variable accurately. If the dataset lacks important features or has limited coverage, the model may struggle to learn the underlying patterns effectively.

**Data Quality**: The quality of the data is crucial for model training. It should be accurate, consistent, and free from errors, outliers, or missing values. Poor data quality can adversely affect model performance and lead to unreliable predictions. Data preprocessing steps, such as cleaning, normalization, and handling missing values, should be performed to ensure high-quality data.

**Validation Performance**: Evaluating the model's performance on a validation set can provide insights into the sufficiency of the data. If the model achieves satisfactory performance on the validation set, it indicates that the available data captures the essential patterns and variations. However, if the model struggles to generalize well or exhibits poor performance, it may suggest insufficient or inadequate data.

It is important to note that data sufficiency is not an absolute measure but rather a relative assessment based on the specific problem and model requirements. In some cases, collecting more data or employing data augmentation techniques may help improve model performance. Domain expertise and iterative experimentation can also guide the determination of data sufficiency in machine learning projects.


## DATA PIPELINE
A data pipeline refers to a series of steps or processes that are involved in collecting, processing, transforming, and delivering data from various sources to its destination for further analysis or consumption. It ensures that data flows smoothly and efficiently throughout the entire data lifecycle. Here's an example of a data pipeline:

Let's consider a scenario where an e-commerce company wants to analyze customer behavior and make personalized product recommendations. The data pipeline for this use case might involve the following steps:

**Data Ingestion**: The pipeline starts with the collection of data from various sources, such as the company's website, mobile app, or social media platforms. This data can include customer interactions, browsing history, purchase details, and demographic information. The data is ingested into the pipeline and stored in a centralized location like a database or data lake.

**Data Cleaning and Preprocessing**: Once the data is collected, it needs to be cleaned and preprocessed to ensure its quality and consistency. This involves removing duplicates, handling missing values, standardizing formats, and performing necessary transformations. For example, converting timestamps to a uniform format or normalizing categorical variables.

**Data Integration**: In this step, data from multiple sources is combined and integrated. For instance, merging customer data from the website and mobile app to create a comprehensive customer profile. Integration may also involve aggregating data from different databases or systems into a unified format.

**Data Transformation**: Data transformation involves applying various operations to the data to derive additional insights or features. This can include calculations, filtering, feature engineering, or creating new variables based on existing data. For example, calculating the total purchase amount for each customer or generating product affinity scores.

**Data Analysis and Modeling**: After the data is transformed, it is ready for analysis and modeling. This step involves using machine learning algorithms or statistical techniques to uncover patterns, build predictive models, or perform other types of data analysis. For our example, this could mean training a recommendation model based on customer behavior and purchase history.

**Data Visualization and Reporting**: The insights and results derived from the analysis need to be presented in a meaningful way. Data visualization techniques, such as charts, graphs, or dashboards, can be used to communicate the findings effectively. This allows stakeholders to understand the patterns and make informed decisions based on the data.

**Data Delivery**: Finally, the processed and analyzed data, along with the insights and reports, need to be delivered to the end-users or downstream systems. This could involve generating automated reports, feeding data into a business intelligence tool, or integrating with other applications for real-time decision-making.

Throughout the data pipeline, it's essential to consider data quality, security, and governance to ensure the accuracy, reliability, and privacy of the data. The pipeline can be automated using various tools and technologies to streamline the process and handle large volumes of data efficiently.

Overall, a data pipeline enables organizations to leverage data effectively by transforming raw data into valuable insights, enabling data-driven decision-making, and extracting maximum value from their data assets.


Metadata vs Data Provenance vs Data lineage?

- **Metadata** is the “data about the data”, which includes various information about the data assets, such as the type, format, structure, author, date created, date modified and file size.

- **Data lineage** provides an in-depth description of where data comes from including its analytic life cycle, data provenance is its historical record keeper. 

- **Data provenance** is responsible for providing a list of origin, including inputs, entities, systems, and processes related to specific data.

### Let's use a simple example to explain metadata, data provenance, and data lineage.

Imagine you have a recipe app that allows users to store and share their favorite recipes. Each recipe consists of various details such as the recipe name, ingredients, instructions, cooking time, and author name.

**Metadata**: In this context, metadata would be additional information about the recipe. For example, it could include the recipe category (e.g., dessert, main course), dietary information (e.g., vegetarian, gluten-free), cooking difficulty level, and ratings provided by users. Metadata provides extra context and attributes that help organize and search for recipes based on specific criteria.

**Data Provenance**: Data provenance in this scenario would capture the origin and history of a recipe. It would include details such as who created the recipe, when it was created, and any subsequent modifications made to it. For example, if a user modifies a recipe by adding or removing ingredients, the data provenance would record these changes, ensuring that the history of the recipe is preserved.

**Data Lineage**: Data lineage in the recipe app would show the flow of data from its creation to its final output. For instance, if a user creates a recipe by entering the ingredients and instructions, and then shares it with others, the data lineage would trace this flow. It would illustrate how the recipe data is processed, stored, and displayed within the app, including any transformations or manipulations performed on the data.

**To summarize**:

Metadata provides additional information about the recipe, such as category, dietary information, and difficulty level.
Data provenance captures the origin and history of the recipe, including who created it and any modifications made.
Data lineage shows the flow of data within the recipe app, illustrating how the recipe data is processed and displayed.
These concepts help in understanding and managing the recipe data, allowing users to search for recipes based on specific criteria, maintain a history of changes, and ensure transparency in how the data is used within the app.


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
	
## How Do We Determine Whether a Model is Good Enough?
To determine whether a model is good enough, we need to evaluate its performance based on a set of metrics that are relevant to the specific problem at hand. This involves establishing a baseline level of performance and comparing the model's performance against this baseline. Additionally, we need to consider factors such as the business context, potential biases, and the importance of different types of errors. Ultimately, a model is considered good enough if it meets the requirements of the specific use case and provides value to the stakeholders.

### So what is establishing a baseline level of performance?
Establishing a baseline level of performance is the process of creating a simple, easily interpretable model or heuristic that can be used as a benchmark to compare the performance of more complex models.

#### There are several ways to establish a baseline level of performance for a model:

1. ***Simple Models:*** A simple model with basic features can act as a baseline for more complex models. This can provide a starting point for comparison and help to determine if the additional complexity of a more advanced model is worth the effort.

2. ***Human-Level Performance:*** In some cases, human-level performance on a task can serve as a baseline for the model's performance. This is particularly useful in fields such as natural language processing or image recognition, where human-level performance is well established.

3. ***Previous Models:*** If there are existing models for a particular task or problem, their performance can serve as a baseline for comparison. This can help to identify areas where the new model is performing better or worse.

4. ***Random Guessing:*** For classification tasks, random guessing can be used as a baseline. The accuracy of a model should be significantly better than random guessing in order to be considered useful.

Establishing a baseline level of performance is important to understand the level of difficulty of the problem, to identify opportunities for improvement, and to evaluate the performance of the model over time.

# Experiment tracking

Experiment tracking in ML refers to the practice of recording and organizing experiments conducted during model development in order to enable better collaboration, replication, and analysis. It involves capturing details such as the model architecture, hyperparameters, training data, and evaluation metrics.

The benefits of experiment tracking include:

1. **Reproducibility:** By keeping a record of each experiment, it becomes easier to reproduce results and build on past work.

2. **Collaboration:** Teams can work together more effectively by sharing experiment details, avoiding duplicated work, and building on each other's findings.

3. **Analysis:** Experiment tracking enables data scientists to analyze the results of multiple experiments to identify patterns, test hypotheses, and refine models.

There are several tools and frameworks available for experiment tracking in ML, including open-source options like MLflow, DVC, and Neptune, as well as commercial products like Wandb, Comet, sagemaker studio, and Domino. These tools typically offer features like experiment versioning, visualization, and integration with other ML development tools. we can also use text files, spread sheets.



<h1><li> Error Analysis & Performance Auditing</li> </h1>
	
## Error Analysis
	
Error analysis is a process in machine learning model development that involves examining and analyzing the errors made by a model in order to identify patterns and sources of inaccuracies. This involves analyzing the mistakes made by the model on the test set and trying to identify common types of errors or patterns in the misclassified examples.

The goal of error analysis is to identify areas where the model can be improved, either through adjustments to the algorithm or through additional training data. By understanding the sources of errors and where the model is struggling, developers can make targeted improvements that can lead to better overall performance.

Error analysis can involve a variety of techniques, including visualizing misclassified examples, analyzing confusion matrices, and examining individual model predictions. It is an important step in the iterative process of model development and is often used in combination with other techniques such as hyperparameter tuning and model selection.

***Error Analysis is heart of machine learning model development.***

**NOTE:** In simple terms, ***Error analysis*** is like being a detective and trying to figure out why a model is making mistakes. Just like how a detective gathers clues and investigates a crime scene, we gather information about the model's errors and try to identify patterns or causes for those errors. This helps us understand where the model is struggling and what we can do to improve its performance.
	
### Examples :
	
- Suppose we are building a machine learning model to classify images of animals as either cats or dogs. During evaluation, we notice that the model is misclassifying a significant number of images of dogs as cats. To perform error analysis, we would examine these misclassified images in detail to understand why the model is making these mistakes.In doing so, we might discover that many of the misclassified dog images have backgrounds that are similar to those in the cat images, leading the model to focus on irrelevant features rather than the dog itself. We could then use this insight to improve the model's performance by providing it with more diverse training data that includes images of dogs with a wider variety of backgrounds.

- Suppose you are building a sentiment analysis model for a restaurant review website. You train your model on a dataset of customer reviews and their corresponding positive or negative sentiment labels. However, when you evaluate the model on a test set of reviews, you find that it is performing poorly on negative reviews.To conduct an error analysis, you might manually review a sample of the misclassified negative reviews to identify common errors the model is making. For example, you might find that the model is misclassifying reviews that use sarcasm or humor as negative, even though the overall sentiment is positive. Armed with this information, you could then modify the training data or adjust the model to better handle this type of language.
	
### Some Error Analysis Techniques :
#

There are several error analysis techniques that can be used in machine learning model development, including:

**1. Confusion matrix:** A table that summarizes the performance of a classification model by comparing the actual and predicted class labels.

**2. Precision and recall:** Metrics that measure the proportion of true positive predictions among all positive predictions (precision) and the proportion of true positive predictions among all actual positive examples (recall).

**3. Cross-validation:** A technique for evaluating the performance of a model by training and testing it on different subsets of the data.

**4. Learning curves:** Plots that show how the model's performance changes as the amount of training data increases.

**5. Feature importance analysis:** Identifying which features or variables have the greatest impact on the model's performance.

**6. Error visualization:** Plotting the errors made by the model to identify patterns and potential areas for improvement.

These techniques can help identify patterns in the model's errors and provide insights into areas that may require further tuning or adjustment.
	
### Prioritizing  error patterns :
#
	
Prioritizing which error patterns to address depends on several factors, including:

**1. Impact on the business:** Addressing error patterns that have a significant impact on the business should be a top priority.

**2. Frequency of occurrence:** Patterns that occur frequently should also be a priority, as they can have a significant cumulative impact on the model's overall performance.

**3. Ease of fixing:** Some error patterns may be easier to fix than others. Prioritizing patterns that can be addressed with relatively simple adjustments can help improve the model's performance more quickly.

**4. Potential for improvement:** Addressing error patterns that have a high potential for improvement can also be a good strategy. For example, if a particular error pattern is consistently leading to misclassification of a specific class, fixing that pattern could result in a significant improvement in overall accuracy.

By carefully considering these factors and prioritizing error patterns accordingly, model developers can focus their efforts on the areas that will have the greatest impact on the model's performance.
	
## Performance auditing 

Performance auditing in ML model development refers to the process of evaluating the performance of a model in production and identifying any discrepancies or deviations from the expected results. This is important to ensure that the model is still performing as intended and to identify any areas for improvement.

For example, let's say we have a customer churn prediction model for a telecom company. The model was initially trained on historical data and achieved high accuracy during testing. However, after deploying the model in production, the company notices that the number of false positives (i.e., customers predicted to churn but who actually don't) is much higher than expected.

To audit the performance of the model, the company may collect and analyze additional data from production, such as customer behavior or feedback. They may also compare the model's performance with the performance of other models or industry benchmarks. Through this auditing process, they may discover that the model was not properly accounting for certain types of customers or that the data used for training the model did not fully represent the diversity of the customer base.

Based on the findings from the performance audit, the company may choose to retrain the model with additional data or adjust the model's parameters to improve its performance in production. This iterative process of auditing and improving the model is crucial for ensuring that it continues to provide accurate and reliable predictions over time.

### Machine learning auditing frameworks
#

Machine learning auditing frameworks are a set of tools and methodologies used to assess and monitor the performance, fairness, and privacy of machine learning models. Some popular ML auditing frameworks include:

**1. AI Fairness 360:** Developed by IBM, this framework provides a set of algorithms and metrics to measure and mitigate bias in machine learning models.

**2. TensorBoard:** This is a visualization tool developed by Google for monitoring and debugging TensorFlow models. It provides an interface to analyze the performance of the model, visualize the training process, and identify errors and anomalies.

**3. What-If Tool:** Developed by Google, this tool provides an interactive interface for exploring and debugging machine learning models. It allows users to perform "what-if" analyses to understand how changes in the input data or model parameters affect the model's output.

**4. TensorFlow Model Analysis:** This is an open-source tool developed by Google for evaluating and debugging TensorFlow models. It provides a set of metrics and visualization tools to assess the model's performance and identify errors.

**5. LIME:** This is a framework for explaining the predictions of machine learning models. It provides a set of algorithms for generating local explanations of individual predictions, which can help users understand how the model is making decisions.

These frameworks can be used to audit the performance and behavior of machine learning models, and to identify and address issues related to fairness, accuracy, privacy, and security.


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
<h3> <li> Concept Drift & Data Drift </li> </h3>
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
