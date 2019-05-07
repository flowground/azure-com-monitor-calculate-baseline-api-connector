# ![LOGO](logo.png) MonitorManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MonitorManagementClient API (version 2018-09-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-calculateBaseline_API/2018-09-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:26+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### **Lists the baseline values for a resource**.

*Tags:* `Baseline`

#### Input Parameters
* `resourceUri` - _required_ - The identifier of the resource. It has the following structure: subscriptions/{subscriptionName}/resourceGroups/{resourceGroupName}/providers/{providerName}/{resourceName}. For example: subscriptions/b368ca2f-e298-46b7-b0ab-012281956afa/resourceGroups/vms/providers/Microsoft.Compute/virtualMachines/vm1
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-calculate-baseline-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
