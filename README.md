# 👋 Introducing Workspaces

Workspaces in Terraform are independently managed state files.

Terraform stores the state of the applied configuration in a file which its creates called terraform.tfstate, in certain situations you can use the same configuration for different contexts (like different environments) 

Terraform does use workspaces by default, if you don't declare a workspace, you are still working on that default workspace.