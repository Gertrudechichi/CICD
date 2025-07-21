
## <a name="Overview">🤖 Overview</a>

I created a reusable template leveraging AWS cloudformation service to define the infrastructure resources needed for an application which simplifies application deployment on AWS with just a few clicks, reducing human error. Also, Integrating it with AWS CodePipeline enabled automated CI/CD, allowing for rapid and reliable code delivery to production.
 
 Setting up a deployment of an application by using several linux commands can be very tiring and it is also susceptible to errors because it requires manual configuration of linux servers, manually installing and configuring dependencies and also troubleshooting linux issues leading to downtime when making updates to your existing application in the production environment definitely not recommended for business solutions. “Hoping” to have fewer errors during deployment is not a good business strategy!

Anytime I am designing a cloud infrastructure, I keep in mind the wise words of Werner Vogels, "Everything fails, so plan for failure and nothing fails," which is why I always anticipate for failure and mitigate failure and downtime in my design.
 
 Taking into account AWS well architected framework, I designed a framework that is reusable, and highly available with less administrative burden. I recently setup a Continuous Integration/Continuous Deployment pipeline using AWS Cloudformation, AWS Codepipeline and Github to deploy an application in the production environment . 

This solution provides a better approach, one that eliminates human error and speeds up the deployment process.
