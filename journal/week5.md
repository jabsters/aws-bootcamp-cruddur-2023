# Week 5 — DynamoDB and Serverless Caching

* Watched Ashish's video https://www.youtube.com/watch?v=gFPljPNnK2Q
* Scripts https://www.youtube.com/watch?v=pIGi_9E_GwA
  * All scripts were created and committed
* Feature implementation / mega refactoring https://www.youtube.com/watch?v=dWHOsXiAIBU
  * https://github.com/omenking/aws-bootcamp-cruddur-2023/tree/week-5-again-again
  * Incredibly hard to follow.
* Updating a Message Group using DynamoDB Streams https://www.youtube.com/watch?v=zGnzM_YdMJU
  * https://github.com/omenking/aws-bootcamp-cruddur-2023/blob/week-5/journal/week5.md
  * Followed along, but I did not create the DynamoDB on production in fear of financial costs. I will do so later when I need to.
  * I created the lambda and gave it full permissions.

> Notes so I don't lose them
> 
> https://us-west-2.console.aws.amazon.com/cognito/v2/idp/user-pools?region=us-west-2
> 
> export AWS_COGNITO_USER_POOL_ID="USER_POOL_ID"
> 
> gp env AWS_COGNITO_USER_POOL_ID="USER_POOL_ID"
