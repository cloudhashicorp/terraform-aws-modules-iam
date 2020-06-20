# terraform-aws-modules-iam

Authentication and authorization are words that will first ring in your mind whenever the AWS IAM is mentioned. In security perspective, this is where all the security of the entire infrastructure will start. The reason is AWS Identity and Access Management provides access to any AWS services and resources in secured manner. You can define who is the specific user or group that is allowed or denied access. AWS IAM controls the overall how the account should be access through the use of different policies and templates.
AWS IAM Let’s you do the following:

1. Manage IAM users and access
2. Manage Roles and permissions
3. Manage Federated users and permissions

Terraform offers a way to manage and provision AWS IAM via “Infrastructure-as-Code” . Combining with different tools like Ansible, Chef or Puppet it will provide the access and permission control in automated fashion.
In this example, the user has been defined using resource together with the IAM policy that will be used.

Using the modules in Terraform, the required IAM policy has been defined on what action and in which resource it should have access.

Combining the two and attaching the policy will create the defined user and access inside the AWS account which can be used to manage.
Here are the Argument Reference when creating the AWS IAM resource and policies.

https://www.terraform.io/docs/providers/aws/r/iam_user_policy_attachment.html
https://www.terraform.io/docs/providers/aws/r/iam_policy.html
https://www.terraform.io/docs/providers/aws/r/iam_user.html

You can clone the sample code below to start defining your users, permissions and access in your AWS account.
