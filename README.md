# ![LOGO](logo.png) StorageManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the StorageManagementClient API (version 2015-12-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-containers/2015-12-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:26+03:00

## API Description

The Admin Storage Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns the status of a container migration job.

*Tags:* `Containers`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `operationId` - _required_ - Operation Id.
* `api-version` - _required_ - REST Api Version.

### Cancel a container migration job.

*Tags:* `Containers`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `operationId` - _required_ - Operation Id.
* `api-version` - _required_ - REST Api Version.

### Returns the list of containers which can be migrated in the specified share.

*Tags:* `Containers`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `shareName` - _required_ - Share name.
* `api-version` - _required_ - REST Api Version.
* `Intent` - _required_ - The container migration intent.
* `MaxCount` - _optional_ - The maximum number of containers.
* `StartIndex` - _optional_ - The starting index the resource provider uses.

### Returns a list of destination shares that the system considers as best candidates for migration.

*Tags:* `Containers`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `shareName` - _required_ - Share name.
* `api-version` - _required_ - REST Api Version.

### Starts a container migration job to migrate containers to the specified destination share.

*Tags:* `Containers`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `shareName` - _required_ - Share name.
* `api-version` - _required_ - REST Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-containers-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
