

# V1beta2DeploymentStrategy

DeploymentStrategy describes how to replace existing pods with new ones.
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rollingUpdate** | [**V1beta2RollingUpdateDeployment**](V1beta2RollingUpdateDeployment.md) |  |  [optional]
**type** | **String** | Type of deployment. Can be \&quot;Recreate\&quot; or \&quot;RollingUpdate\&quot;. Default is RollingUpdate. |  [optional]



