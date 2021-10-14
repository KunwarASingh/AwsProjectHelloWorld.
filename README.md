# AwsProjectHelloWorld.
#This project deploys a VPC, with a pair of public and private subnets in 2 AZs. 
#It deploys an internet gateway, with a default route on the public subnets.
 #It deploys 2 NAT gateways (one in each AZ),and default routes for them in the private subnets.
 #It deploys an AutoScaling Group with Application Load Balancer.
