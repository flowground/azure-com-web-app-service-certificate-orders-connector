# ![LOGO](logo.png) AppServiceCertificateOrders API Client **flow**ground Connector

## Description

A generated **flow**ground connector for the AppServiceCertificateOrders API Client API (version 2018-02-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/web-AppServiceCertificateOrders/2018-02-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:21+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List all certificate orders in a subscription.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Validate information for a certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get certificate orders in a resource group.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Delete an existing certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get a certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order..
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Create or update a certificate purchase order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Create or update a certificate purchase order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### List all certificates associated with a certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Delete the certificate associated with a certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `name` - _required_ - Name of the certificate.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get the certificate associated with a certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `name` - _required_ - Name of the certificate.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Creates or updates a certificate and associates with key vault secret.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `name` - _required_ - Name of the certificate.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Creates or updates a certificate and associates with key vault secret.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `name` - _required_ - Name of the certificate.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Reissue an existing certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Renew an existing certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Resend certificate email.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Verify domain ownership for this certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Verify domain ownership for this certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Verify domain ownership for this certificate order.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `certificateOrderName` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Retrieve the list of certificate actions.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Retrieve email history.

*Tags:* `AppServiceCertificateOrders`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of the certificate order.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

## License

**flow**ground :- Telekom iPaaS / azure-com-web-app-service-certificate-orders-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
