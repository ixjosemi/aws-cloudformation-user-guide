# AWS OpsWorks ChefConfiguration Type<a name="aws-properties-opsworks-stack-chefconfiguration"></a>

Describes the Chef configuration for the [AWS::OpsWorks::Stack](aws-resource-opsworks-stack.md) resource type\. For more information, see [ChefConfiguration](https://docs.aws.amazon.com/opsworks/latest/APIReference/API_ChefConfiguration.html) in the *AWS OpsWorks Stacks API Reference*\.

## Syntax<a name="w4ab1c21c10d168c38c17b5"></a>

### JSON<a name="aws-properties-opsworks-stack-chefconfiguration-syntax.json"></a>

```
{
  "[BerkshelfVersion](#cfn-opsworks-chefconfiguration-berkshelfversion)" : String,
  "[ManageBerkshelf](#cfn-opsworks-chefconfiguration-manageberkshelf)" : Boolean
}
```

### YAML<a name="aws-properties-opsworks-stack-chefconfiguration-syntax.yaml"></a>

```
[BerkshelfVersion](#cfn-opsworks-chefconfiguration-berkshelfversion): String
[ManageBerkshelf](#cfn-opsworks-chefconfiguration-manageberkshelf): Boolean
```

## Properties<a name="w4ab1c21c10d168c38c17b7"></a>

`BerkshelfVersion`  <a name="cfn-opsworks-chefconfiguration-berkshelfversion"></a>
The Berkshelf version\.  
*Required*: No  
*Type*: String

`ManageBerkshelf`  <a name="cfn-opsworks-chefconfiguration-manageberkshelf"></a>
Whether to enable Berkshelf\.  
*Required*: No  
*Type*: Boolean