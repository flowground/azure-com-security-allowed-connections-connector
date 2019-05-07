# ![LOGO](logo.png) Security Center **flow**ground Connector

## Description

A generated **flow**ground connector for the Security Center API (version 2015-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/security-allowedConnections/2015-06-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:53+03:00

## API Description

API spec for Microsoft.Security (Azure Security Center) resource provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets the list of all possible traffic between resources for the subscription

*Tags:* `AllowedConnections`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID
* `api-version` - _required_ - API version for the operation

### Gets the list of all possible traffic between resources for the subscription and location.

*Tags:* `AllowedConnections`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `api-version` - _required_ - API version for the operation

### Gets the list of all possible traffic between resources for the subscription and location, based on connection type.

*Tags:* `AllowedConnections`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `connectionType` - _required_ - The type of allowed connections (Internal, External)
    Possible values: Internal, External.
* `api-version` - _required_ - API version for the operation

## License

**flow**ground :- Telekom iPaaS / azure-com-security-allowed-connections-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
