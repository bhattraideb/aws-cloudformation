# Deploy AWS Lambda using AWS CloudFormation
This repo deploy AWS lambda using AWS CloudFormation. 
The Lambda function will retrieve the SSM parameters and store them into S3 as 'parameters.txt' file.

### Before deoplying
 - Replace `XXXXXXXXXXXXXX` with ARN of your your Parameter store name on `(lambda-template)` file on line 24 and 
also the s3 bucket ARN `arn:aws:s3:::cloud-formation-dxc-test` with your bucket ARN. If you don't have those already 
created make sure you create those first and replace in the file 

