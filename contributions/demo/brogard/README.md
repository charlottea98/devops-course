# Demo: Multi-account CI/CD on AWS for a ToDo app
## Member

Name: André Brogärd

Mail: brogard@kth.se

Github: andrebrogard

## Proposal
The demo will show the resulting architecture of a ci/cd pipeline and the process for deploying this pipeline across AWS accounts (the purpose for multiple accounts will be stated). The pipeline will only use manual intervention to transition from staging to production environments (to emulate QA tests and approval). The pipeline will be written as IaC (AWS CDK) in the same repo as the application code.

This is highly relevant to DevOps. There are many design choices in such pipelines that would hinder efficiency, or compromise security, or scale poorly. This demonstration would serve the purpose of presenting a type of pipeline that would allow for at least efficency and security while gaining confidence that the application works. Furthermore by deploying infrastructure code and application code in the same repo makes them into a "deploy unit". This forces operations and developers to work more closely, but still allows them to work independently. 


