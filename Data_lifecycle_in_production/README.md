# Table of Contents
- [Overview Of Machine learning in Production](#overview-of-machine-learning-in-production)
- [Brief view of Ml Pipelines](#brief-view-of-ml-pipelines)
- [DAGS](#dags)
- [Pipeline Orchestration Frameworks in MLOps](#pipeline-orchestration-frameworks-in-mlops)
- [TFX in MLOps](#tfx-in-mlops)
- [TFX Portability Compared to Other Pipeline Orchestration Frameworks](#tfx-portability-compared-to-other-pipeline-orchestration-frameworks)
- []






# Overview Of Machine learning in Production
### Traditional ML : 
*Traditional ML* focuses on developing and training machine learning models.

![Screenshot (2)](https://github.com/sandeep4055/mlops_specalization/assets/70133134/d7fffaba-5946-446b-8af5-676be1056f9f)

### Production ML
*Production ML* involves deploying and managing models in real-world production environments to deliver ongoing value and performance.

![Screenshot (27)](https://github.com/sandeep4055/mlops_specalization/assets/70133134/6dff6a79-9701-40a6-a56d-d41f8832cf96)

### Production Ml vs Traditional Ml
![Screenshot (29)](https://github.com/sandeep4055/mlops_specalization/assets/70133134/6a5221e4-275b-44b3-99a9-de806dec2b44)

#### So in brief production Ml is Machine learning Development + Modern Software development

![Screenshot (30)](https://github.com/sandeep4055/mlops_specalization/assets/70133134/94951e31-7bd5-4617-acf0-ba793d9a1bee)

#### So the Production Ml requires all these 4 steps
- **Scoping**
- **Data**
- **Modelling**
- **Deployment**

![Screenshot (31)](https://github.com/sandeep4055/mlops_specalization/assets/70133134/67fd87ff-f6ad-4458-abd8-38c66ab259d5)

# Brief view of Ml Pipelines
**ML pipelines** are a systematic and automated approach to manage and streamline the end-to-end process of building, deploying, and maintaining machine learning models, including steps like **data ingestion**, **preprocessing**, **model training**, **evaluation**, and **deployment**. They help ensure **reproducibility**, **scalability**, and **efficiency** in ML workflows.

#### Below is one version MLOPS used in Production by CD_foundation 

![Screenshot (32)](https://github.com/sandeep4055/mlops_specalization/assets/70133134/eed54a05-8e8d-405b-910d-0ca8dd552903)

#### Below is Netflix’s ML framework

![Netflix-SC-Architecture-Diagram-1024x499](https://github.com/sandeep4055/mlops_specalization/assets/70133134/2ae5e8d7-db2c-49e4-8850-f3e5b410dc89)

#### Below is Ubers’s MLOPS design

![image9-9](https://github.com/sandeep4055/mlops_specalization/assets/70133134/8815abc7-41d1-4bcd-ae24-480e051e3705)

# DAG'S

DAGs (Directed Acyclic Graphs) are a type of data structure used to represent a collection of tasks or operations that have dependencies between them. In a DAG, the tasks are represented as nodes, and the dependencies between tasks are represented as directed edges. The term "acyclic" means that there are no cycles or loops in the graph, ensuring that the tasks can be executed in a specific order without any conflicts or infinite loops. DAGs are commonly used in various fields, including machine learning, to define and visualize the flow and dependencies of complex processes or workflows. In the context of ML pipelines, DAGs are used to represent the sequence and dependencies of data processing, model training, evaluation, and other tasks, enabling efficient and reliable execution of the pipeline.
![dag](https://github.com/sandeep4055/mlops_specalization/assets/70133134/6d0114ec-d6bc-4d7b-b75f-27d9f4fbecb1)


# Pipeline Orchestration Frameworks in MLOps
Pipeline orchestration frameworks are essential in MLOps to automate the overall workflow, from data gathering, EDA, data augmentation, to model building and deployment. These frameworks help improve the performance and management of the entire model, resulting in quick and easy deployment. Here are some of the best pipeline orchestration frameworks for MLOps:
1. **Kubeflow**: Kubeflow is an open-source machine learning platform that provides a simple, collaborative interface for managing and creating custom workflows and their pipelines. It is designed to simplify the deployment of ML workflows on Kubernetes, making it easier to scale and manage ML workloads.
   
2. **Airflow**: Apache Airflow is a popular open-source platform for programmatically authoring, scheduling, and monitoring workflows. It provides a simple interface for creating complex workflows and can be used to manage machine learning pipelines.


3. **MLRun**: MLRun is an open-source MLOps framework that helps manage the entire pipeline from development to deployment. It introduces tracking, automation, and rapid experimentation to help data scientists build, run, and monitor ML tasks and pipelines.

4. **Prefect**: Prefect is a workflow management system designed for modern infrastructure. It is an open-source platform that provides a simple interface for creating complex workflows and can be used to manage machine learning pipelines.

5. **Flyte**:Flyte is an open-source platform that provides an easy way to create concurrent, scalable, and maintainable workflows for machine learning. It is designed to simplify the deployment of ML workflows on Kubernetes, making it easier to scale and manage ML workloads.
   
These frameworks can be used to automate and manage workflows and pipeline infrastructure, track and monitor models for further analysis, and manage different dependencies between tasks. They also integrate with popular cloud platforms such as Google Cloud Platform, Amazon Web Services, and Microsoft Azure.

In conclusion, pipeline orchestration frameworks are essential in MLOps to automate the overall workflow, from data gathering, EDA, data augmentation, to model building and deployment. Kubeflow, Airflow, MLRun, Prefect, and Flyte are some of the best pipeline orchestration frameworks for MLOps.

# How to choose the right pipeline orchestration framework for your MLOps workflow?

Choosing the right pipeline orchestration framework for your MLOps workflow can be a challenging task. There are several aspects to consider, such as scalability, community support, ease of use, integration with cloud platforms, and specific features. In this response, we will explore some of the most important aspects to consider and provide some guidance on how to choose the right pipeline orchestration framework for your MLOps workflow.

### Aspects to Consider
1. **Scalability**: Scalability is an important aspect to consider when choosing a pipeline orchestration framework for your MLOps workflow. You want a framework that can handle large amounts of data and can scale up or down as needed. Some frameworks, such as **Kubeflow** and **Flyte**, are designed to run on **Kubernetes**, which makes them highly scalable and able to handle large workloads.

2. **Community Support**: Community support is another important aspect to consider when choosing a pipeline orchestration framework for your MLOps workflow. A framework with a large and active community can provide you with access to a wealth of knowledge and resources, including documentation, tutorials, and support forums. Frameworks such as **Airflow and MLflow** have large and active communities, which can be a valuable resource for users

3. **Ease of Use**: Ease of use is another important aspect to consider when choosing a pipeline orchestration framework for your MLOps workflow. You want a framework that is easy to use and can be quickly adopted by your team. Some frameworks, such as **Prefect** and **MLRun**, are designed to be easy to use and require minimal setup and configuration.

4. **Integration with Cloud Platforms**: Integration with cloud platforms is another important aspect to consider when choosing a pipeline orchestration framework for your MLOps workflow. You want a framework that can integrate with your existing cloud infrastructure, such as Google Cloud Platform, Amazon Web Services, or Microsoft Azure. Some frameworks, such as **Kubeflow** and **MLflow**, have built-in integrations with popular cloud platforms, which can make it easier to deploy and manage your models.

5. **Specific Features**: Specific features are another important aspect to consider when choosing a pipeline orchestration framework for your MLOps workflow. You want a framework that has the specific features you need to manage your workflow, such as experiment tracking, model serving, and automated testing. Some frameworks, such as **Airflow** and **MLflow**, have built-in features for experiment tracking and model serving, while others, such as **Flyte and Prefect**, are designed to be highly customizable and can be tailored to your specific needs.

### How to Choose the Right Framework
- To choose the right pipeline orchestration framework for your MLOps workflow, you should consider the aspects mentioned above and evaluate each framework based on your specific needs. You should also consider factors such as the size of your team, the complexity of your workflow, and your budget.
  
- It's also a good idea to try out different frameworks and see which one works best for your team. Many frameworks offer free trials or open-source versions that you can use to test their features and functionality.
  
- Finally, you should also consider the long-term viability of the framework. You want a framework that is actively maintained and has a road-map for future development. Frameworks with large and active communities, such as Airflow and Kubeflow, are more likely to have long-term viability and continued development.
In conclusion, choosing the right pipeline orchestration framework for your MLOps workflow requires careful consideration of several aspects, including scalability, community support, ease of use, integration with cloud platforms, and specific features. By evaluating each framework based on your specific needs and testing them out, you can find the right framework for your team and ensure the long-term success of your MLOps workflow.

# TFX in MLOps
![tensorflow-extended-tfx-logo-social](https://github.com/sandeep4055/mlops_specalization/assets/70133134/980a7d0e-38b2-41e7-ade5-7b85a20da86d)

**TFX (TensorFlow Extended)** is an end-to-end platform for deploying production ML pipelines. TFX uses Apache Airflow to author workflows as directed acyclic graphs (DAGs) of tasks. TFX is designed to be portable to multiple environments and orchestration frameworks, including Apache Beam and Kubeflow. 

TFX provides a set of standard components and libraries that can be used to build and deploy ML models in production. These components include data validation, preprocessing, training, and serving. TFX also provides a configuration framework and shared libraries to integrate common components needed to define, launch, and monitor your machine learning system. 

When choosing a pipeline orchestration framework for your MLOps workflow, TFX can be a good option to consider. TFX provides a set of standard components and libraries that can be used to build and deploy ML models in production. It also integrates with popular orchestration frameworks such as Apache Airflow, Apache Beam, and Kubeflow

However, when choosing a pipeline orchestration framework, it's important to consider several aspects, such as scalability, community support, ease of use, integration with cloud platforms, and specific features. You should evaluate each framework based on your specific needs and consider factors such as the size of your team, the complexity of your workflow, and your budget.

In conclusion, TFX is a powerful platform for deploying production ML pipelines that can be integrated with popular orchestration frameworks such as Apache Airflow and Kubeflow. When choosing a pipeline orchestration framework for your MLOps workflow, it's important to consider several aspects and evaluate each framework based on your specific needs.

# TFX Portability Compared to Other Pipeline Orchestration Frameworks
TFX is designed to be portable to multiple environments and orchestration frameworks, including Apache Airflow, Apache Beam, and Kubeflow. This means that TFX pipelines can be run on various orchestrators, making it easier to implement MLOps and automate the ML process.

In terms of portability, TFX is comparable to other pipeline orchestration frameworks such as Apache Airflow and Kubeflow. Apache Airflow is a general-purpose workflow management system that can be used for a wide range of tasks and can be run on various environments, including on-premise and cloud platforms. Kubeflow is an open-source ML platform dedicated to making deployments of ML workflows on Kubernetes simple, portable.




# Importance Of DATA



Data is a crucial component in the field of machine learning. It refers to the set of observations or measurements that can be used to train a machine-learning model. The quality and quantity of data available for training and testing play a significant role in determining the performance of a machine-learning model. Here are some of the key reasons why data is important in machine learning:

1. **Quality of Data**: The quality of data used for training machine learning models is critical to the performance of the model. Poor quality data can lead to inaccurate predictions and classifications. It is important to ensure that the data is clean, accurate, and relevant to the problem being solved.

2. **Quantity of Data**: The quantity of data available for training and testing also plays a significant role in determining the performance of a machine-learning model. More data generally leads to better performance, as the model has more examples to learn from.

3. **Type of Data**: Data can be in various forms such as numerical, categorical, or time-series data, and can come from various sources such as databases, spreadsheets, or APIs.It is important to choose the right type of data for the problem being solved.

4. **Data Preparation**: Data preparation is a crucial step in the machine learning process. It involves cleaning, transforming, and normalizing the data to make it suitable for training the model. This step can be time-consuming and requires domain expertise

In conclusion, data is the most important and must-have food for machine learning. The quality and quantity of data available for training and testing play a significant role in determining the performance of a machine-learning model. It is important to ensure that the data is clean, accurate, and relevant to the problem being solved. More data generally leads to better performance, and it is important to choose the right type of data for the problem being solved. Data preparation is a crucial step in the machine learning process and requires domain expertise.


# Data Collection and Monitoring

# Data Pipeline









