### Terraform State

Terraform is a declarative approach kind of tool, it means whatever you write(declare) in the file you will get that. When infra is created through terraform it will create a file called
```
terraform.tfstate
```
Terraform use this file to keep track of what is created.
TF files are asked configuration = required state
state file is created infra = current state

Terraform responsibility to match the above 2 things 100%.

