## Welcome to The Stack Shack

The Stack Shack is a collection of AWS CloudFormation stacks that can be used to setup your new project.

### Stacks
* [Static Website, S3, SSL, CodeCommit](static-website-s3-codecommit)

### Best Practices
Best practices dictates that each stack **should** include the following items.  

|Best Practice|Details|
|-|-|
|Security|Use the latest security best practices.  SSL, IAM, KMS, VPN, etc...|
|Auto Scaling|We want our apps to automatically handle increased traffic and at the same time reducing costs during decreased traffic.|
|CI/CD|Continuous Integration & Continuous Delivery.  It must be fast and easy for a experienced and new developer to ship code to production.|
|IaC|Infrastructure as Code.  All infrastructure changes should be done through CloudFormation.|
|Logging|It is important to have a logging implementation that makes it easy for developers to track down bugs.|
|Monitoring|It is important to have a monitoring implementation that makes it easy for developers to visualize the state of the stack.|
|DevOps|A system should be in place to alert developers when problems arise.  Developers should easily be able to asses the situation via the logs and monitors and quickly push out a hotfix if needed.|
|Backup & Recovery|All persistent storage needs to have a backup and recovery plan that is easy to execute.|
