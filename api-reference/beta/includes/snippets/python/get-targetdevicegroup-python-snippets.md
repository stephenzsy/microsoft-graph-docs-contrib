---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)


result = await graph_client.service_principals.by_service_principal_id('servicePrincipal-id').remote_desktop_security_configuration.target_device_groups.by_target_device_group_id('targetDeviceGroup-id').get()


```