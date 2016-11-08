# Naming Convention
A set of reusable naming conventions for services like AWS.

## AWS
`[client]-[project]-[aws-service]-[?aws-subservice]-[?branch]-[?version]`

 - `client` The client short-name, eg: `Acme`
 - `project` The project short-name, eg: `Blog`
 - `aws-service` The abbreviated AWS service this name is being applied too, eg: `ec2`, `sg` (security group), `rds` etc.
 - **Optional** `aws-subservice` The abbreviated AWS sub-service this name is being applied too, eg: `mysql` etc.
 - **Optional** `branch` The branch of work this is applicable too, eg: `prod`, `dev` etc.
 - **Optional** `version` The major version number of the application, eg: `v0`, `v7` etc.

### Examples
 - An ELB for the production environment, version 1.0.0: `acme-blog-elb-prod-v1`
 - A RDS mysql instance for the staging environment, version 2.0.0: `acme-blog-rds-mysql-staging-v2`
