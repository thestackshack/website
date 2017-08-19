## Welcome to The Stack Shack

The Stack Shack is a collection of AWS CloudFormation stacks that can be used to setup your new project.

### Stacks
* [Static Website, S3, SSL, CodeCommit, CI/CD](https://github.com/thestackshack/static-website-s3-codecommit)
* [Serverless API with CI/CD](https://github.com/thestackshack/serverless-api-cicd)
* [Serverless Contact Us Form](https://github.com/thestackshack/serverless-contact-us-form)

### Best Practices
Best practices dictates that each stack **should** include the following items.  

|Best Practice|Details|
|-|-|
|Security|Use the latest security best practices.  SSL, IAM, KMS, VPN, etc...|
|Auto Scaling|We want our apps to automatically handle increased traffic but also be cheap to run.|
|CI/CD|Continuous Integration & Continuous Delivery.  The litmus test is how fast a new dev can ship code to production.|
|IaC|Infrastructure as Code.  All infrastructure changes should be done through code.|
|Logging|It is important to have a logging implementation that makes it easy for developers to track down bugs.|
|Monitoring|It is important to have a monitoring implementation that makes it easy for developers to visualize the state of the stack.|
|DevOps|A system should be in place to alert developers when problems arise.  Developers should easily be able to asses the situation via the logs and quickly push out a hotfix if needed.|
|Backup & Recovery|All persistent storage needs to have a backup and recovery plan that is easy to execute.|
