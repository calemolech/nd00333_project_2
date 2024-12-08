*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Your Project Title Here

*TODO:* Write an overview to your project.

This project aimed to develop a machine learning model on Microsoft Azure ML, deploy it via an endpoint, and consume it in an environment. 

The process included running an AutoML classification experiment, selecting the best-performing model (VotingEnsemble) from a bank dataset, and enabling Application Insights for monitoring. 

The model was accessed through endpoints with proper keys, using Swagger UI for API documentation and Docker for containerized interaction. 

Finally, the entire workflow was automated with a Jupyter Notebook pipeline, including testing the model, evaluating performance with a confusion matrix, and creating a REST endpoint.

## Architectural Diagram
In this project, I will following the below steps:
- Authentication
- Automated ML Experiment
- Deploy the best model
- Enable logging
- Swagger Documentation
- Consume model endpoints
- Create and publish a pipeline
- Documentation

![](/images/00_architect.png)

Data Source Data: https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv

## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screenshots required to demonstrate key steps. 
1. Create new data set

![](/images/01_dataset.png)
![](/images/02_dataset_detailed.png)

2. Manual training with stater notebook

![](/images/03_notebook_automl.png)
![](/images/04_notebook_automl_detailed.png)

3. Creating a New Automated ML run, It take more than 2 hour to run, to I just screenshot it

![](/images/05_automl.png)
![](/images/06_automl_detailed.png)

4. Deploy endpoint 

![](/images/07_endpoint_nb.png)
![](/images/09_endpoint_result.png)
![](/images/10_endpoint_swagger.png)
![](/images/11_endpoint_bechmark.png)

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
