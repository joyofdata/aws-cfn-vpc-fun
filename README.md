# aws-cfn-vpc-fun

Structure:

```
VPC:
  PublicSubnet:
    - EC2-Instance
    - IGW
    - NAT
    - Route to IGW
  PrivateSubnet:
    - EC2-Instance
    - Route to NAT
    - Route to S3VPCEndpoint
  S3VPCEndpoint
```