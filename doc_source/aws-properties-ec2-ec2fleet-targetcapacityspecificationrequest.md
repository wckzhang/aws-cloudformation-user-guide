# Amazon EC2 EC2Fleet TargetCapacitySpecificationRequest<a name="aws-properties-ec2-ec2fleet-targetcapacityspecificationrequest"></a>

<a name="aws-properties-ec2-ec2fleet-targetcapacityspecificationrequest-description"></a>The `TargetCapacitySpecificationRequest` property type specifies the number of units to request for an EC2 Fleet\. You can choose to set the target capacity in terms of instances or a performance characteristic that is important to your application workload, such as vCPUs, memory, or I/O\. If the request type is `maintain`, you can specify a target capacity of `0` and add capacity later\. 

<a name="aws-properties-ec2-ec2fleet-targetcapacityspecificationrequest-inheritance"></a> `TargetCapacitySpecificationRequest` is a property of the [AWS::EC2::EC2Fleet](aws-resource-ec2-ec2fleet.md) resource\.

## Syntax<a name="aws-properties-ec2-ec2fleet-targetcapacityspecificationrequest-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-ec2-ec2fleet-targetcapacityspecificationrequest-syntax.json"></a>

```
{
  "[DefaultTargetCapacityType](#cfn-ec2-ec2fleet-targetcapacityspecificationrequest-defaulttargetcapacitytype)" : String,
  "[OnDemandTargetCapacity](#cfn-ec2-ec2fleet-targetcapacityspecificationrequest-ondemandtargetcapacity)" : Integer,
  "[SpotTargetCapacity](#cfn-ec2-ec2fleet-targetcapacityspecificationrequest-spottargetcapacity)" : Integer,
  "[TotalTargetCapacity](#cfn-ec2-ec2fleet-targetcapacityspecificationrequest-totaltargetcapacity)" : Integer
}
```

### YAML<a name="aws-properties-ec2-ec2fleet-targetcapacityspecificationrequest-syntax.yaml"></a>

```
[DefaultTargetCapacityType](#cfn-ec2-ec2fleet-targetcapacityspecificationrequest-defaulttargetcapacitytype): String
[OnDemandTargetCapacity](#cfn-ec2-ec2fleet-targetcapacityspecificationrequest-ondemandtargetcapacity): Integer
[SpotTargetCapacity](#cfn-ec2-ec2fleet-targetcapacityspecificationrequest-spottargetcapacity): Integer
[TotalTargetCapacity](#cfn-ec2-ec2fleet-targetcapacityspecificationrequest-totaltargetcapacity): Integer
```

## Properties<a name="aws-properties-ec2-ec2fleet-targetcapacityspecificationrequest-properties"></a>

`DefaultTargetCapacityType`  <a name="cfn-ec2-ec2fleet-targetcapacityspecificationrequest-defaulttargetcapacitytype"></a>
The default `TotalTargetCapacity`, which is either `Spot` or `On-Demand`\.   
 *Required*: No  
 *Type*: String  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`OnDemandTargetCapacity`  <a name="cfn-ec2-ec2fleet-targetcapacityspecificationrequest-ondemandtargetcapacity"></a>
The number of On\-Demand units to request\.  
 *Required*: No  
 *Type*: Integer  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`SpotTargetCapacity`  <a name="cfn-ec2-ec2fleet-targetcapacityspecificationrequest-spottargetcapacity"></a>
The number of Spot units to request\.  
 *Required*: No  
 *Type*: Integer  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

`TotalTargetCapacity`  <a name="cfn-ec2-ec2fleet-targetcapacityspecificationrequest-totaltargetcapacity"></a>
The number of units to request, filled using `DefaultTargetCapacityType`\.   
 *Required*: Yes  
 *Type*: Integer  
 *Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt) 

## See Also<a name="aws-properties-ec2-ec2fleet-targetcapacityspecificationrequest-seealso"></a>
+ [TargetCapacitySpecificationRequest](https://docs.aws.amazon.com/AWSEC2/latest/APIReference/API_TargetCapacitySpecificationRequest.html) in the *Amazon EC2 API Reference*