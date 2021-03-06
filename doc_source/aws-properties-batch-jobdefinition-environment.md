# AWS Batch JobDefinition Environment<a name="aws-properties-batch-jobdefinition-environment"></a>

The `Environment` property type specifies environment variables to use in a job definition\.

## Syntax<a name="aws-properties-batch-jobdefinition-environment-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-batch-jobdefinition-environment-syntax.json"></a>

```
{
  "[Value](#cfn-batch-jobdefinition-environment-value)" : String,
  "[Name](#cfn-batch-jobdefinition-environment-name)" : String
}
```

### YAML<a name="aws-properties-batch-jobdefinition-environment-syntax.yaml"></a>

```
[Value](#cfn-batch-jobdefinition-environment-value): String
[Name](#cfn-batch-jobdefinition-environment-name): String
```

## Properties<a name="aws-properties-batch-jobdefinition-environment-properties"></a>

`Value`  <a name="cfn-batch-jobdefinition-environment-value"></a>
The value of the environment variable\.  
 *Required*: no  
*Type*: String  
 *Update requires*: No Interruption 

`Name`  <a name="cfn-batch-jobdefinition-environment-name"></a>
The name of the environment variable\.  
 *Required*: no  
*Type*: String  
 *Update requires*: No Interruption 