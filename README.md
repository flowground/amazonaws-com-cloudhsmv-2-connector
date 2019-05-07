# ![LOGO](logo.png) AWS CloudHSM V2 **flow**ground Connector

## Description

A generated **flow**ground connector for the AWS CloudHSM V2 API (version 2017-04-28).

Generated from: https://api.apis.guru/v2/specs/amazonaws.com/cloudhsmv2/2017-04-28/swagger.json<br/>
Generated at: 2019-05-07T17:35:07+03:00

## API Description

For more information about AWS CloudHSM, see <a href="http://aws.amazon.com/cloudhsm/">AWS CloudHSM</a> and the <a href="http://docs.aws.amazon.com/cloudhsm/latest/userguide/">AWS CloudHSM User Guide</a>.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Copy an AWS CloudHSM cluster backup to a different region.

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### Creates a new AWS CloudHSM cluster.

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### Creates a new hardware security module (HSM) in the specified AWS CloudHSM cluster.

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### Deletes a specified AWS CloudHSM backup. A backup can be restored up to 7 days after the DeleteBackup request. For more information on restoring a backup, see <a>RestoreBackup</a>

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### Deletes the specified AWS CloudHSM cluster. Before you can delete a cluster, you must delete all HSMs in the cluster. To see if the cluster contains any HSMs, use <a>DescribeClusters</a>. To delete an HSM, use <a>DeleteHsm</a>.

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### Deletes the specified HSM. To specify an HSM, you can use its identifier (ID), the IP address of the HSM's elastic network interface (ENI), or the ID of the HSM's ENI. You need to specify only one of these values. To find these values, use <a>DescribeClusters</a>.

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### <p>Gets information about backups of AWS CloudHSM clusters.</p> <p>This is a paginated operation, which means that each response might contain only a subset of all the backups. When the response contains only a subset of backups, it includes a <code>NextToken</code> value. Use this value in a subsequent <code>DescribeBackups</code> request to get more backups. When you receive a response with no <code>NextToken</code> (or an empty or null value), that means there are no more backups to get.</p>

#### Input Parameters
* `MaxResults` - _optional_ - Pagination limit
* `NextToken` - _optional_ - Pagination token
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### <p>Gets information about AWS CloudHSM clusters.</p> <p>This is a paginated operation, which means that each response might contain only a subset of all the clusters. When the response contains only a subset of clusters, it includes a <code>NextToken</code> value. Use this value in a subsequent <code>DescribeClusters</code> request to get more clusters. When you receive a response with no <code>NextToken</code> (or an empty or null value), that means there are no more clusters to get.</p>

#### Input Parameters
* `MaxResults` - _optional_ - Pagination limit
* `NextToken` - _optional_ - Pagination token
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### Claims an AWS CloudHSM cluster by submitting the cluster certificate issued by your issuing certificate authority (CA) and the CA's root certificate. Before you can claim a cluster, you must sign the cluster's certificate signing request (CSR) with your issuing CA. To get the cluster's CSR, use <a>DescribeClusters</a>.

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### <p>Gets a list of tags for the specified AWS CloudHSM cluster.</p> <p>This is a paginated operation, which means that each response might contain only a subset of all the tags. When the response contains only a subset of tags, it includes a <code>NextToken</code> value. Use this value in a subsequent <code>ListTags</code> request to get more tags. When you receive a response with no <code>NextToken</code> (or an empty or null value), that means there are no more tags to get.</p>

#### Input Parameters
* `MaxResults` - _optional_ - Pagination limit
* `NextToken` - _optional_ - Pagination token
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### Restores a specified AWS CloudHSM backup that is in the <code>PENDING_DELETION</code> state. For more information on deleting a backup, see <a>DeleteBackup</a>.

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### Adds or overwrites one or more tags for the specified AWS CloudHSM cluster.

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

### Removes the specified tag or tags from the specified AWS CloudHSM cluster.

#### Input Parameters
* `Action` - _required_
* `Version` - _required_
* `X-Amz-Content-Sha256` - _optional_
* `X-Amz-Date` - _optional_
* `X-Amz-Algorithm` - _optional_
* `X-Amz-Credential` - _optional_
* `X-Amz-Security-Token` - _optional_
* `X-Amz-Signature` - _optional_
* `X-Amz-SignedHeaders` - _optional_

## License

**flow**ground :- Telekom iPaaS / amazonaws-com-cloudhsmv-2-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
