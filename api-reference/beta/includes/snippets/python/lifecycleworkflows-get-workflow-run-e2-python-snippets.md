---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = RunRequestBuilder.RunRequestBuilderGetQueryParameters(
		select = ["id","failedTasksCount","failedUsersCount","processingStatus","totalTasksCount","totalUnprocessedTasksCount","totalUsersCount"],
)

request_configuration = RunRequestBuilder.RunRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.identity_governance.lifecycle_workflows.workflows.by_workflow_id('workflow-id').runs.by_run_id('run-id').get(request_configuration = request_configuration)


```