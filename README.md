# Build Your First Agentic ML Pipeline with Natural Language

Why Snowflake and Why Snowflake is the right place to build these workflows.

Hard part isn't the model but how to get the right context to the model.

context: Agent has all the information that it needs to do its job.
Often it does not.
In enterprises the data is spread across multiple systems, and mostly in seperate system than our ML work is done.

This means agent working in the our ML environment can not see the data very well. 

Bringing all the ML work inside Snowflake means everything is governed by default, so we can discover and manage the data and manage access to that data. 
Safely give the agent the right access to work effectively.

So we solve the context problem by bringing the ML workflow and models into the data platform.

## Agentic ML workflow in snowflake:

Container Runtime, is the bottom layer which has compute layer for machine learning, we can have access to CPU's and GPU's depending on scale of workflows.
To libraries like Pytorch, XGBoost and etc. for model traning, inference and development.

In the next set we have, complete layer of ML tools:
Develop & Iterate: Snowflake ML APIs tracking
Orchestrate & Automate: ML Jobs
Manage: Model registry and Feature store
Deploy & serve: Model serving and Feature serving
Monitor: Model observability and explainability

Next layers:
Snowflake Notebooks just like Jupyter notebooks. Can use any other IDE of choice.

At the top layer:
We have Cortex Code (also called COCO). It is a Snowflake's general purpose AI coding assistant, ties everything together and speeds the automation for ML development.

## What makes the Cortex Code different:
- Deeply integrated with Snowflake, so it comes preloaded with Snowflake and ML best practices
- It is a multi agent under the hood, if there is a complex task, it makes the workflow faster by assigning it to the sub agents to work paralalley.
- We can run the code written by COCO in a sandbox environment safely without damaging the local system files or production database.
- COCO is iterative, so it learns from any corrections made.

## E-commerce lifetime value prediction Model:

Doing through Natural language and no coding.

By letting the COCO drive us in building the model, we will train multiple iteration models and we will automatically run batch inference on these models.

- Creating Synthetic dataset.
- Perform EDA
- Registering the model and inferencing.
- Generate Predictions.



