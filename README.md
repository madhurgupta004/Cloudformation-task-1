# Cloudformation-task-1

## Task Description
### In Account A:
#### IAM User Bruce:
* Should have read/write permissions over Account B’s EC2 Services
* Should have the ability to attach the role bat-license-to-put in Account B to services
* Should have read permissions over objects of the S3 bucket contingency-plans in Account C

#### IAM User Clark:
* Should have admin permissions over all three accounts

### In Account B:
#### IAM Role/Instance Profile bat-license-to-put
* Should have write permissions over the S3 bucket contingency-plans in Account C
* Can be assumed by any EC2 Instance

### In Account C:
#### S3 Bucket contingency-plans
