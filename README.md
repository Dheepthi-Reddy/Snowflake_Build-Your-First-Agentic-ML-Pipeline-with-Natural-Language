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
Snowflake Notebooks just like jupyter notebooks.



