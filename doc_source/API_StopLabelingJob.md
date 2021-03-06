# StopLabelingJob<a name="API_StopLabelingJob"></a>

Stops a running labeling job\. A job that is stopped cannot be restarted\. Any results obtained before the job is stopped are placed in the Amazon S3 output bucket\.

## Request Syntax<a name="API_StopLabelingJob_RequestSyntax"></a>

```
{
   "[LabelingJobName](#SageMaker-StopLabelingJob-request-LabelingJobName)": "string"
}
```

## Request Parameters<a name="API_StopLabelingJob_RequestParameters"></a>

For information about the parameters that are common to all actions, see [Common Parameters](CommonParameters.md)\.

The request accepts the following data in JSON format\.

 ** [LabelingJobName](#API_StopLabelingJob_RequestSyntax) **   <a name="SageMaker-StopLabelingJob-request-LabelingJobName"></a>
The name of the labeling job to stop\.  
Type: String  
Length Constraints: Minimum length of 1\. Maximum length of 63\.  
Pattern: `^[a-zA-Z0-9](-*[a-zA-Z0-9])*`   
Required: Yes

## Response Elements<a name="API_StopLabelingJob_ResponseElements"></a>

If the action is successful, the service sends back an HTTP 200 response with an empty HTTP body\.

## Errors<a name="API_StopLabelingJob_Errors"></a>

For information about the errors that are common to all actions, see [Common Errors](CommonErrors.md)\.

 **ResourceNotFound**   
Resource being access is not found\.  
HTTP Status Code: 400

## See Also<a name="API_StopLabelingJob_SeeAlso"></a>

For more information about using this API in one of the language\-specific AWS SDKs, see the following:
+  [AWS Command Line Interface](https://docs.aws.amazon.com/goto/aws-cli/sagemaker-2017-07-24/StopLabelingJob) 
+  [AWS SDK for \.NET](https://docs.aws.amazon.com/goto/DotNetSDKV3/sagemaker-2017-07-24/StopLabelingJob) 
+  [AWS SDK for C\+\+](https://docs.aws.amazon.com/goto/SdkForCpp/sagemaker-2017-07-24/StopLabelingJob) 
+  [AWS SDK for Go](https://docs.aws.amazon.com/goto/SdkForGoV1/sagemaker-2017-07-24/StopLabelingJob) 
+  [AWS SDK for Go \- Pilot](https://docs.aws.amazon.com/goto/SdkForGoPilot/sagemaker-2017-07-24/StopLabelingJob) 
+  [AWS SDK for Java](https://docs.aws.amazon.com/goto/SdkForJava/sagemaker-2017-07-24/StopLabelingJob) 
+  [AWS SDK for JavaScript](https://docs.aws.amazon.com/goto/AWSJavaScriptSDK/sagemaker-2017-07-24/StopLabelingJob) 
+  [AWS SDK for PHP V3](https://docs.aws.amazon.com/goto/SdkForPHPV3/sagemaker-2017-07-24/StopLabelingJob) 
+  [AWS SDK for Python](https://docs.aws.amazon.com/goto/boto3/sagemaker-2017-07-24/StopLabelingJob) 
+  [AWS SDK for Ruby V2](https://docs.aws.amazon.com/goto/SdkForRubyV2/sagemaker-2017-07-24/StopLabelingJob) 