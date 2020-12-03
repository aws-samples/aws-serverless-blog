# Canary Deployments using Amazon API Gateway and AWS Lambda
This stack creates an example to show how to do canary release deployment in Amazon API Gateway and AWS Lambda.


## Services Used
* <a href="https://aws.amazon.com/api-gateway/" target="_blank">Amazon API Gateway</a>
* <a href="https://aws.amazon.com/lambda/" target="_bank">AWS Lambda</a>



## Deploying
1. Download the [CloudFormation Template](cf-template.yml)
2. Open the <a href="https://console.aws.amazon.com/cloudformation/" target="_blank">CloudFormation console</a>
3. Create stack 
4. Choose "Upload a template file" and select the file downloaded. 
5. Enter a name and click Next
6. Select **Create stack**


## Cleanup
1. Open the <a href="https://console.aws.amazon.com/cloudformation/" target="_blank">CloudFormation console</a>
1. Locate a stack named *Canary-Serverless* 
1. Select the radio option next to it
1. Select **Delete**
1. Select **Delete stack** to confirm


## License

This library is licensed under the MIT-0 License. See the LICENSE file.
