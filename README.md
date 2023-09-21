### Prerequisites

Terraform version 1.4:
<https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli>

AWS CLI v2:
<https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html>

Configure AWS CLI profile:
<https://registry.terraform.io/providers/hashicorp/aws/latest/docs>
<https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html#cli-configure-quickstart-precedence>


### Infrastructure provisioning
Please check your AWS Region and Access keys in ../variables.tf
1. Open terminal

2. cd into the directory housing all the tf files

3. Add index.html and error.html to a folder and name it "html"

4. Run:

terraform init

4. Run:

terraform apply

5. Wait until VPC is created.

6. Log into AWS Console and confirm VPC has been created. 

7. Run:

terraform destroy 

