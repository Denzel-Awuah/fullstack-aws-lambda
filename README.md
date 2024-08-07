# fullstack-aws-lambda

Created Full-Stack Thesaurus Application to perform operations on entered words and phrases 

- Create Frontend using React JS & Redux toolkit, Deployed Frontend App using AWS Amplify 
- Created Backend using a Spring Cloud function. Clients send requests to an AWS API Gateway, which forwards the request to the AWS lambda where the Spring Cloud function is deployed.
- The Spring Cloud function communicates with an AWS DynamoDB table and returns data back to the client (React app) 


## App Preview 
![Application](./react-thesaurus/public/v2/thesaurus.png)


<br>

## Deployment Strategy
![Application](./fullstack-deployment.drawio.png)
