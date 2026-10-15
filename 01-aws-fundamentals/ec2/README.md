# Amazon EC2

## 1. Definition

Amazon EC2 (Elastic Compute Cloud) is an AWS service that provides virtual servers called instances.

## 2. Why Do We Use EC2?

- To host websites and applications.
- To run software on virtual servers.
- To create development and testing environments.
- To adjust computing capacity according to application requirements.

## 3. Important EC2 Components

| Component | Purpose |
|---|---|
| AMI | Image used to launch an instance |
| Instance type | Defines compute resources |
| Key pair | Supports key-based authentication methods |
| Security group | Controls permitted network traffic |
| EBS | Provides block storage volumes |
| VPC | Provides network isolation and configuration |

## 4. Basic Instance Launch Flow

1. Choose an instance name.
2. Select an AMI.
3. Select an instance type.
4. Configure a key pair if required.
5. Configure networking and security.
6. Configure storage.
7. Review settings and launch when ready.

## 5. Security and Cost Notes

- Verify current pricing before launching an instance.
- Allow only required network traffic.
- Protect private keys and credentials.
- Stop or terminate resources when no longer needed, as appropriate.
- Check for remaining billable resources after a lab.

## 6. Interview Practice

**Q1. What is EC2?**

EC2 is an AWS service that provides virtual servers.

**Q2. What is an AMI?**

An AMI is an image used to launch an EC2 instance.

**Q3. What is a security group?**

A security group controls permitted network traffic.

## 7. Learning Status

- [ ] Understand AMI and instance types.
- [ ] Understand key pairs and security groups.
- [ ] Understand EBS storage.
- [ ] Complete a safe practical lab.