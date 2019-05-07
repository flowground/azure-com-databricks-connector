# ![LOGO](logo.png) DatabricksClient **flow**ground Connector

## Description

A generated **flow**ground connector for the DatabricksClient API (version 2018-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/databricks/2018-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:56+03:00

## API Description

ARM Databricks

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available RP operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.

### Gets all the workspaces within a subscription.

*Tags:* `Workspaces`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Gets all the workspaces within a resource group.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Deletes the workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `workspaceName` - _required_ - The name of the workspace.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Gets the workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `workspaceName` - _required_ - The name of the workspace.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Updates a workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `workspaceName` - _required_ - The name of the workspace.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Creates a new workspace.

*Tags:* `Workspaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. The name is case insensitive.
* `workspaceName` - _required_ - The name of the workspace.
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

## License

**flow**ground :- Telekom iPaaS / azure-com-databricks-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
