# Project Title: Operationalizing Machine Learning


## Project Summary

The dataset (https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv) used in this project contains data about marketing campaign of a Portuguese banking institution and we seek to predict if the client will subscribe to a term deposit (variable y in the dataset).


## Stages That Make Up The Overall Flow
![Work-flow](https://user-images.githubusercontent.com/65784601/105206319-86108500-5b46-11eb-948e-5d21e3086e94.png)


Authentication is crucial for the continuous flow of operations. Continuous Integration and Delivery system (CI/CD) rely on uninterrupted flows. When authentication is not set properly, it requires human interaction and thus, the flow is interrupted. An ideal scenario is that the system doesn't stop waiting for a user to input a password. So whenever possible, it's good to use authentication with automation.
##### Authentication types
###### Key-based
###### Token based
In this project I deployed the model using Azure Container Instances service which is a Key-based authentication.

### Registering Dataset

![ds](https://user-images.githubusercontent.com/65784601/105841054-534a0f00-5fd4-11eb-9f1b-61f5b61b95bd.png)



## Step 2: Create AutoML Experiment
### Used STANDARD_DS12_V2 Machine size


![compute](https://user-images.githubusercontent.com/65784601/105841055-534a0f00-5fd4-11eb-9955-8485ce9e1781.png)
![exp](https://user-images.githubusercontent.com/65784601/105842375-5ba34980-5fd6-11eb-8a88-0ed021a06a0f.png)



### Best model after completion is VotingEnsemble


![model](https://user-images.githubusercontent.com/65784601/105841121-6e1c8380-5fd4-11eb-9892-d56b0507d760.png)

## Step 3: Deploy Best Model
## Deploy Best Model

### Used Azure container Instance and enabled authentication


### Model Deployed
![deploy](https://user-images.githubusercontent.com/65784601/105841154-7b397280-5fd4-11eb-9b1c-8aa18b961757.png)

## Step 4: Anable Application Insights to retrieve log and  Visualize Performance.
### Updating and running logs.py
![app insights](https://user-images.githubusercontent.com/65784601/105841250-9ad09b00-5fd4-11eb-893b-28b919c091d5.png)

### Application insights enabled and accessed from the endpoints
![app insight true](https://user-images.githubusercontent.com/65784601/105841253-9c01c800-5fd4-11eb-90e9-1c606e4335d0.png)


## Step 5: Consume Model
###  Consume model using Swagger


![swaggerssh](https://user-images.githubusercontent.com/65784601/105841311-b0de5b80-5fd4-11eb-8afe-5793e361b5a0.png)

### Consume Model endpoints

![swaggerrr](https://user-images.githubusercontent.com/65784601/105841334-b8056980-5fd4-11eb-92ab-eecb671c4f1b.png)
![swaggerdata](https://user-images.githubusercontent.com/65784601/105841345-bd62b400-5fd4-11eb-8a75-c39c3bdff8ec.png)

## Step 6: Comsume Model Endpoints
### Updating the endpoint.py

![update endpoints](https://user-images.githubusercontent.com/65784601/105845234-bb9bef00-5fda-11eb-9b2e-3b8d640ca92c.png)




### Running endpoints.py to interact with the model
![score](https://user-images.githubusercontent.com/65784601/105842352-50e8b480-5fd6-11eb-83f9-217765a86575.png)
## Step 7.

### Create, Publish and Consume a Pipeline in python SDK. Ran the cells in the notebook after downloading the config.json file and keeping in same dirrectory as the notebook.

#### Completed Pipeline run in notebook

![jupter notebook](https://user-images.githubusercontent.com/65784601/105216694-308ea500-5b53-11eb-82a2-606003a3aab6.png)

#### Pipeline run completed in Azureml Studio
![AzureStudio1](https://user-images.githubusercontent.com/65784601/105216775-4dc37380-5b53-11eb-8e86-b207a3b0b7e9.png)

#### View in AzureML Studio
![AzureStudio](https://user-images.githubusercontent.com/65784601/105216777-4dc37380-5b53-11eb-8529-fa6298fcaacd.png)
#### Published Pipeline showing REST endpoints
![published pipeline](https://user-images.githubusercontent.com/65784601/105218551-94b26880-5b55-11eb-8e92-48a0faf61e7f.png)


### Screen Recording Link
#### https://www.youtube.com/watch?v=R8-qIZLQzgI&t=80s

# Corrections

![score](https://user-images.githubusercontent.com/65784601/105845243-c0f93980-5fda-11eb-9524-a37dd7b41262.png)
![notebook run](https://user-images.githubusercontent.com/65784601/106018017-65ee4200-60c1-11eb-8ba3-b792cbd8548f.png)
![aml comp](https://user-images.githubusercontent.com/65784601/106018122-7e5e5c80-60c1-11eb-8ad5-08ff4c73e0b6.png)
![aml studio run](https://user-images.githubusercontent.com/65784601/106018139-81594d00-60c1-11eb-8579-fbcb00fc4f80.png)
![amlcomp](https://user-images.githubusercontent.com/65784601/106018152-85856a80-60c1-11eb-8492-ca3216bfd7da.png)
![both](https://user-images.githubusercontent.com/65784601/106018160-86b69780-60c1-11eb-9fcd-f151036a8b41.png)
![comptd](https://user-images.githubusercontent.com/65784601/106018170-88805b00-60c1-11eb-9a50-718f793977c2.png)
![endpoint comp](https://user-images.githubusercontent.com/65784601/106018184-8cac7880-60c1-11eb-9fde-684cb4cfdf91.png)
![pipeline](https://user-images.githubusercontent.com/65784601/106018192-8ddda580-60c1-11eb-910e-761cc75ac3c2.png)
![active](https://user-images.githubusercontent.com/65784601/106018202-903fff80-60c1-11eb-9498-9e46df56baff.png)


### Standout Suggestions

Enabling Deep Learning expecially when the data is somewhat large and also also in the case of steps taken in AutoML in handling unbalanced data which could have a negative effect.

###

