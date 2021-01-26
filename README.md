# Project Title: Operationalizing Machine Learning


## Project Summary

The dataset (https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv) used in this project contains data about marketing campaign of a Portuguese banking institution and we seek to predict if the client will subscribe to a term deposit (variable y in the dataset).


## Stages That Make Up The Overall Flow
![Work-flow](https://user-images.githubusercontent.com/65784601/105206319-86108500-5b46-11eb-948e-5d21e3086e94.png)


Authentication is crucial for the continuous flow of operations. Continuous Integration and Delivery system (CI/CD) rely on uninterrupted flows. When authentication is not set properly, it requires human interaction and thus, the flow is interrupted. An ideal scenario is that the system doesn't stop waiting for a user to input a password. So whenever possible, it's good to use authentication with automation.
##### Authentication types
###### Key-based
###### Token based
In this project I used Azure Container Instances service which is a Key-based authentication.

### Registering Dataset






### Used STANDARD_DS12_V2 Machine size





### Best model after completion is VotingEnsemble





## Deploy Best Model

### Used Azure container Instance and enabld authentication





### Model Deployed



### Updating and running logs.py


### Application insights enabled and accessed from the endpoints


###  Consume model using Swagger



### Consume Model endpoints


### Step 7.

### Create, Publish and Consume a Pipeline in python SDK. Ran the cells in the notebook after downloading the config.json file and keeping in smae dirrectory as the notebook.

#### Completed Pipeline run in notebook

![jupter notebook](https://user-images.githubusercontent.com/65784601/105216694-308ea500-5b53-11eb-82a2-606003a3aab6.png)

#### Pipeline run completed in Azure Studio
![AzureStudio1](https://user-images.githubusercontent.com/65784601/105216775-4dc37380-5b53-11eb-8e86-b207a3b0b7e9.png)

#### View in Azure Studio
![AzureStudio](https://user-images.githubusercontent.com/65784601/105216777-4dc37380-5b53-11eb-8529-fa6298fcaacd.png)
#### Published Pipeline showing REST endpoints
![published pipeline](https://user-images.githubusercontent.com/65784601/105218551-94b26880-5b55-11eb-8e92-48a0faf61e7f.png)


### Standout Suggestion

Enabling Deep Learning expecially when the data is somewhat large.

