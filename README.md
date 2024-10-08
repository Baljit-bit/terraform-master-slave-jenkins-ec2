# terraform-master-slave-jenkins-ec2
<p>Create `IAM User` to use access ID and secret ID as credentials to connect to AWS from local terrraform.
Credentails can be used as environment variable or credentials file.</p>


<b>COMMANDS</b><br />
For formatting Terraform configuration files
```bash
terraform fmt
```
Prepare the working directory for use with Terraform, it performs Backend Initialization, Child Module Installation, and Plugin Installation.
```bash
terraform init
```
Validation the configuration files.
```bash
terraform validate
```
Plan will generate an execution plan, showing you what actions will be taken without actually performing the planned actions.
```bash
terraform plan
```
Create or update infrastructure depending on the configuration files.
```bash
terraform apply
```
Lists out all the resources that are tracked in the current state file.
```bash
terraform state list
```
Destroy the infrastructure managed by Terraform.
```bash
terraform destroy
```