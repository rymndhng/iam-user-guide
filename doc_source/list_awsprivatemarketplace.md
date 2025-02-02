# Actions, Resources, and Condition Keys for AWS Private Marketplace<a name="list_awsprivatemarketplace"></a>

AWS Private Marketplace \(service prefix: `aws-marketplace`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](https://docs.aws.amazon.com/marketplace/latest/buyerguide/)\.
+ View a list of the [API operations available for this service](https://docs.aws.amazon.com/marketplace/latest/buyerguide/)\.
+ Learn how to secure this service and its resources by [using IAM](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) permission policies\.

**Topics**
+ [Actions Defined by AWS Private Marketplace](#awsprivatemarketplace-actions-as-permissions)
+ [Resources Defined by AWS Private Marketplace](#awsprivatemarketplace-resources-for-iam-policies)
+ [Condition Keys for AWS Private Marketplace](#awsprivatemarketplace-policy-keys)

## Actions Defined by AWS Private Marketplace<a name="awsprivatemarketplace-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. Use policies to grant permissions to perform an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\.

The **Resource** column indicates whether each action supports resource\-level permissions\. If there is no value for this column, you must specify all resources \("\*"\) in the `Resource` element of your policy statement\. If the column includes a resource type, then you can specify an ARN of that type in a statement with that action\. Required resources are indicated in the table with an asterisk \(\*\)\. If you specify a resource\-level permission ARN in a statement using this action, then it must be of this type\. Some actions support multiple resource types\. If the resource type is optional \(not indicated as required\), then you can choose to use one but not the other\.

For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  

| Actions | Description | Access Level | Resource Types \(\*required\) | Condition Keys | Dependent Actions | 
| --- | --- | --- | --- | --- | --- | 
|   [ AssociateProductsWithPrivateMarketplace ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Adds new approved products to the Private Marketplace\. This action can be performed by any account in an AWS Organization, provided the user has permissions to do so, and the Organization's Service Control Policies allow it\. | Write |  |  |  | 
|   [ CreatePrivateMarketplace ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Creates a Private Marketplace for the individual account, or for the entire AWS Organization if one exists\. This action can only be performed by the master account if using an AWS Organization\. | Write |  |  |  | 
|   [ CreatePrivateMarketplaceProfile ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Creates a Private Marketplace Profile that customizes the white label experience on the AWS Marketplace website for the individual account, or for the entire AWS Organization if one exists\. This action can only be performed by the master account if using an AWS Organization\. | Write |  |  |  | 
|   [ DescribePrivateMarketplaceProducts ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Describes the status of requested products in the Private Marketplace for administrative purposes\. This action can be performed by any account in an AWS Organization, provided the user has permissions to do so, and the Organization's Service Control Policies allow it\. | List |  |  |  | 
|   [ DescribePrivateMarketplaceProfile ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Describes details about the Private Marketplace Profile for administrative purposes\. This action can be performed by any account in an AWS Organization, provided the user has permissions to do so, and the Organization's Service Control Policies allow it\. | Read |  |  |  | 
|   [ DescribePrivateMarketplaceStatus ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Describes the status of the Private Marketplace for administrative purposes\. This action can be performed by any account in an AWS Organization, provided the user has permissions to do so, and the Organization's Service Control Policies allow it\. | Read |  |  |  | 
|   [ DisassociateProductsFromPrivateMarketplace ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Removes approved products from the Private Marketplace\. This action can be performed by any account in an AWS Organization, provided the user has permissions to do so, and the Organization's Service Control Policies allow it\. | Write |  |  |  | 
|   [ ListPrivateMarketplaceProducts ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Queryable list for the products and status of products in the Private Marketplace for administrative purposes\. This action can be performed by any account in an AWS Organization, provided the user has permissions to do so, and the Organization's Service Control Policies allow it\. | List |  |  |  | 
|   [ StartPrivateMarketplace ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Starts the Private Marketplace, enabling the customized AWS Marketplace experience, and enabling restrictions on the procurement of products based on what is available in the Private Marketplace\. This action can be performed by any account in an AWS Organization, provided the user has permissions to do so, and the Organization's Service Control Policies allow it\. | Write |  |  |  | 
|   [ StopPrivateMarketplace ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Stops the Private Marketplace, disabling the customized AWS Marketplace experience and removing the Private Marketplace procurement restrictions on products\. This action can be performed by any account in an AWS Organization, provided the user has permissions to do so, and the Organization's Service Control Policies allow it\. | Write |  |  |  | 
|   [ UpdatePrivateMarketplaceProfile ](https://docs.aws.amazon.com/marketplace/latest/buyerguide/private-marketplace.html) \[permission only\] | Updates the Private Marketplace Profile that customizes the white label experience on the AWS Marketplace website for the individual account, or for the entire AWS Organization if one exists\. This action can be performed by any account in an AWS Organization, provided the user has permissions to do so, and the Organization's Service Control Policies allow it\. | Write |  |  |  | 

## Resources Defined by AWS Private Marketplace<a name="awsprivatemarketplace-resources-for-iam-policies"></a>

AWS Private Marketplace does not support specifying a resource ARN in the `Resource` element of an IAM policy statement\. To allow access to AWS Private Marketplace, specify `“Resource”: “*”` in your policy\.

## Condition Keys for AWS Private Marketplace<a name="awsprivatemarketplace-policy-keys"></a>

Private Marketplace has no service\-specific context keys that can be used in the `Condition` element of policy statements\. For the list of the global context keys that are available to all services, see [Available Keys for Conditions](reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.