# Training.AwsInfra Learning Project

## Objective
This project is intended to be used as a project where I can practice some tech/concepts:

- Infra in general, not only AWS
- IaC (Initially Terraform)
- Subnets
- Memcached and/or Redis
- Web application firewall (WAF)
- Applicaiton Load Balance (ALB)
- Nginx
- Aurora PostgreSQL / Amazon RDS PostgreSQL
- New Relic / Datadog
- CDN
- Github actions

## Application
And mention in the object, the only reason for this application to exist is for training regarding infrastructure.
What application does or does not is only important to enable the creation of a formula for provissioning cache, storage, memory and cpu.

That said, the scope of the application is a simple URL shortening. The scope will grow as i go want to go through different kind of problems.

Possible features to enrich the infrastructure training:
- Data retention: The urls shall exist for only X ammount of time after the last usage
  - May lead to: Creating of a rotine such as cron procedure, lambda with event bridge...
- Scalability: The application shall be able to support thousands of concurrent requests
  - May lead to: Orchestration of containers, Loading balancing, sharding db, distributed cache...
- Cost Management: The total cost of the application can be greater than the free tier
  - May lead to: Using self managed services/bare metal, caching/cdn...
- Performance: All requests must be processed in at most X miliseconds
  - May lead to: Caching, db index management, better network managament...
- Continuous deployment: All approved and tested push to main code trunk shall be deployed to production with zero downtime
  - CI/CD, IaC, Zero-downtime deployments...


## Relevant info for developing:
