# DEPLOY EC2 - TERRAFORM, and Connect it to your visual code  :space_invader:

Tired of creating devevlopment labs  manually , try something for a few minutes? this for you 

### Pre-requisites

* Terraform installed
* AWS cli installed on a host 
* * AWS credentials

### Deployment Instructions 
* Install Terraform
* Clone this repository
* Run a ```terraform init``` to grab providers and modules
* Run ```aws_configure``` and establish your credentials
* Run a ```terraform_apply``` and wait 10 - 15 minutes
### Deployment Instructions - EC2 Instances
* Install Terraform
* Clone this repository
* Edit the variables in ```variables.tf``` to match any unique values you want to apply to your instances
* Generate a key for ssh and put in the .ssh folder on windows ```ssh-keygen```
* Run a ```terraform init``` to grab providers and modules
* Run ```aws_configure``` and establish your credentials and create you profile in ```.profile``` folder
* Run a ```terraform_apply``` and wait 10 - 15 minutes
* Profit
