# Terraform 
It helps to automate and manage infrastructure/ platform / services that rum on them. 
Terraform is open source and uses declarative language (Define the end state instead of steps to do it). 
It is used in provisioning infrastructure for deployment. This includes creating VPC, installing docker, spinning up servers, creating AWS users and permissions. 

Terraform has two main components
- Core: It uses two inputs. The config and the state
- Providers : AWS, Azure, Gpc, kubernetes etc

  Terraform commands:
  - Init: This initializes terraform by downloading plugins and providers to your local
  - Refresh: It gives the current state of the infrastructure
  - Plan: It compares required output to what's existing currently and creates the plan that needs to be executed
  - Apply: This executes the plan, creates the resources
  - Destroy: Destroy the resources
