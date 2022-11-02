# AWS-api
# Inspiration
AWS helps you use the cloud to turn ideas into opportunities—creating new ways to grow, increase efficiency, and serve customers better. Our customer-obsessed culture, industry-leading cloud services, and global customer and partner community offer a unique set of tools and expertise for solving problems and exploring possibilities. 
## What it does
Web APIs that direct HTTP queries to Lambda functions can be built and documented using the tools provided by API Gateway. Controls for authentication and permission allow you to secure access to your API. Your APIs may direct traffic across the internet or may only be available inside your VPC.
One or more methods, like GET or POST, are defined by resources in your API. Requests are forwarded by integrations in methods to Lambda functions or other integration types. To match all requests that fit a pattern, you can use specific resource and method types, or you can describe each resource and method separately. All paths leading to a resource are caught by a proxy resource. All HTTP methods are caught by the ANY method.
 We deployed the API and got the common URL link to trigger the API using POSTMAN tool 

# How we built it
We built the following model of API gateway integration with AWS lambda and in the lambda function we used Nodejs for writing the command the logic that was needed to trigger the API call and then we deployed the API and got the common URL link to trigger the API using POSTMAN tool 

# Challenges we ran into
Sometimes we used to get many error in the integrating the API and testing it with the postman tool using various HTTP requests. But then we overcame  those challenges

# Accomplishments that we're proud of
We made this API Call using a serverless lambda function on AWS which makes the tasks so easy and we dont have to manage the server manually for every call it will be automatically triggered using the lambda function.

# What we learned
We learnt how to integrate the API gateway with AWS lambda and then test it with POSTMAN tool.
Web APIs that direct HTTP queries to Lambda functions can be built and documented using the tools provided by API Gateway. 
# What's next for AWS API TAG
Next for this we can then do that with Python 3.9x and make it with more http methods such as POST/PUT etc and we can also merge it with Dynamo DB and other Databases to store the data automatically using AWS lambda and API Gateway .
