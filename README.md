# Cloud Scale Machine Learning Workshop

This workshop is designed to get attendees up to speed on the rudiments of modern machine learning at cloud scale. 
Attendees can expect to learn the following:

- An Overview of Machine Learning
- Popular Machine Learning Frameworks
- Azure Machine Learning service
- Experimentation, Model Management, and Deployment
- Hyperparameter optimization, automatic machine learning, and the machine learning pipeline

This one-day workshop will be divided into 4 distinct segments with a lecture and lab portion. 

## Hour 1 – An Overview of Machine Learning
This section will introduce the foundational concepts of machine learning primarily focusing on techniques for supervised learning. This section will delve into practical approaches for creating local machine learning models using both scikit-learn and TensorFlow.
- Intro to ML
- Function (machine made)
- intro scikit-learn
- intro tensorflow
- Setup -  [Click here for Setup Steps](setup.md)

## Hour 2 – Hands on with scikit-learn and TensorFlow
This hands-on lab includes setting up a local development environment as well as two machine learning problems attendees will solve with scikit-learn and TensorFlow

- Lab - [scikit-learn Digits](https://github.com/cloudscaleml/scikit-digits)
- Lab - [scikit-learn Wine Reviews](https://github.com/cloudscaleml/scikit-nlp)
- Lab - [TensorFlow Digits](https://github.com/cloudscaleml/tfsimple-digits)

## Hour 3 – Understanding Azure Machine Learning service
This portion of the workshop will introduce attendees to the basics of Azure Machine Learning service. Concepts such as a workspace, compute environment, data stores, experiments, etc. will be introduced in preparation for a machine learning experiment in the cloud. 

- Intro to Azure Machine Learning service
- Logical Layout vs Physical Resources
- Tour through Datasources, Compute, Experiments etc
- Run our first experiment
- Briefly touch on deployment in AML

## Hour 4 – Your First Machine Learning Experiment in the Cloud
The goal of this lab is to create an Azure Machine Learning (AML) workspace and compute environment in order to run an experiment in the cloud. Attendees will essentially be lift-and-shifting Hour 2 code and running it in the cloud.

- Lab - [cloudrun-digits](https://github.com/cloudscaleml/cloudrun-digits)
- Lab - [clouddeploy-digits](https://github.com/cloudscaleml/clouddeploy-digits)

## Hour 5 – Advanced Experimentation Techniques in Azure Machine Learning service
This section of the workshop will delve into three advanced techniques available for experimentation in Azure Machine Learning service: hyperparameter tuning, automatic machine learning, and pipelines. The first two features are designed to create agility in the data science process by automating several repetitive tasks associated with starting a new project. The last feature (pipelines) is designed to simplify complex multi-step machine learning scenarios by discretizing disparate steps without having to sacrifice speed and efficiency.

- Intro to deep learning (safe for beginners) for hyperparameter optimization
- Hyperparameter tuning
- Automated Machine Learning
- Intro to Pipelines

## Hour 6 – Hands-on Advanced Experimentation in Azure Machine Learning service
The lab portion will contain exercises designed to help attendees better understand automatic hyperparameter tuning, automatic machine learning, and Azure Machine Learning pipelines.

- Lab - [hyperparam-digits](https://github.com/cloudscaleml/hyperparams-digits)
- Lab - [automl-digits](https://github.com/cloudscaleml/automl-digits)


## Hour 7 – The Intersection of Data Science and DevOps
This section will introduce attendees to 3 features in Azure Machine Learning service designed to manage the artifacts associated with machine learning: model, image, and service management. Attendees will also learn what to do when things change. What should happen when data has changed and machine learning models no longer work? What if there’s a better machine learning model for the problem? 

- Intro to machine learning assets (what are they and how to use them)
- AML Pipelines (in more depth)
- AzDO Pipelines (differences, use cases, release pipeline)

## Hour 8 – Automating your Machine Learning Pipeline in the Cloud
The goal of this hands-on lab is to promote machine learning models created during the workshop all the way to production. 

- Lab - [first-pipeline](https://github.com/cloudscaleml/seer/blob/master/firstpipeline.md)
- Lab - [seer-pipeline](https://github.com/cloudscaleml/seer/blob/master/seerpipeline.md)
- Lab - [AzDO Release Pipeline](https://github.com/cloudscaleml/seer/blob/master/azdodeploy.md)
