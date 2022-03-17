# terraform-aviatrix-aws-spoke
#Angepasst durch Jörg auf neues Modul

# This module will be deprecated in favor of the new multi-cloud spoke module
The Multi-Cloud can be found here: https://registry.terraform.io/modules/terraform-aviatrix-modules/mc-spoke/aviatrix/latest
This legacy module will remain available in the Terraform registry and on Github for the forseable future, but please plan to replace any usage of it with the multi-cloud spoke module.
This module will no longer be maintained and updated.

### Description
This module deploys a very simple spoke VPC, with a public and a private subnet in each availability zone. Spoke gateways are created in the public subnets of the 2 first AZ's.
