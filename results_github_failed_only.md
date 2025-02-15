### Terraform Scan Results:

```
Passed Checks: 4, Failed Checks: 4, Skipped Checks: 0
```

| Check ID    | Check Name                                                                                                | Resource            | Guideline                                                                                                                                               | File       |
|-------------|-----------------------------------------------------------------------------------------------------------|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| CKV_AWS_135 | Ensure that EC2 is EBS optimized                                                                          | aws_instance.my_ec2 | [Link](https://docs.prismacloud.io/en/enterprise-edition/policy-reference/aws-policies/aws-general-policies/ensure-that-ec2-is-ebs-optimized)           | /main-1.tf |
| CKV_AWS_79  | Ensure Instance Metadata Service Version 1 is not enabled                                                 | aws_instance.my_ec2 | [Link](https://docs.prismacloud.io/en/enterprise-edition/policy-reference/aws-policies/aws-general-policies/bc-aws-general-31)                          | /main-1.tf |
| CKV_AWS_8   | Ensure all data stored in the Launch configuration or instance Elastic Blocks Store is securely encrypted | aws_instance.my_ec2 | [Link](https://docs.prismacloud.io/en/enterprise-edition/policy-reference/aws-policies/aws-general-policies/general-13)                                 | /main-1.tf |
| CKV2_AWS_41 | Ensure an IAM role is attached to EC2 instance                                                            | aws_instance.my_ec2 | [Link](https://docs.prismacloud.io/en/enterprise-edition/policy-reference/aws-policies/aws-iam-policies/ensure-an-iam-role-is-attached-to-ec2-instance) | /main-1.tf |

---
### Terraform Plan Scan Results:

```
Passed Checks: 4, Failed Checks: 4, Skipped Checks: 0
```

| Check ID    | Check Name                                                                                                | Resource            | Guideline                                                                                                                                               | File         |
|-------------|-----------------------------------------------------------------------------------------------------------|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| CKV_AWS_135 | Ensure that EC2 is EBS optimized                                                                          | aws_instance.my_ec2 | [Link](https://docs.prismacloud.io/en/enterprise-edition/policy-reference/aws-policies/aws-general-policies/ensure-that-ec2-is-ebs-optimized)           | /tfplan.json |
| CKV_AWS_79  | Ensure Instance Metadata Service Version 1 is not enabled                                                 | aws_instance.my_ec2 | [Link](https://docs.prismacloud.io/en/enterprise-edition/policy-reference/aws-policies/aws-general-policies/bc-aws-general-31)                          | /tfplan.json |
| CKV_AWS_8   | Ensure all data stored in the Launch configuration or instance Elastic Blocks Store is securely encrypted | aws_instance.my_ec2 | [Link](https://docs.prismacloud.io/en/enterprise-edition/policy-reference/aws-policies/aws-general-policies/general-13)                                 | /tfplan.json |
| CKV2_AWS_41 | Ensure an IAM role is attached to EC2 instance                                                            | aws_instance.my_ec2 | [Link](https://docs.prismacloud.io/en/enterprise-edition/policy-reference/aws-policies/aws-iam-policies/ensure-an-iam-role-is-attached-to-ec2-instance) | /tfplan.json |

---
