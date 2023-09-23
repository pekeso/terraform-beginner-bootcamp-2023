# Terraform Beginner Bootcamp 2023

This is the Terraform Beginner Bootcamp by Andrew Brown & Team.

## Week 0

The first week is about setting up the environment for the bootcamp and quite a bunch of introductory topics. 

### SEMANTIC VERSIONING :mage:

Given a version number **MAJOR.MINOR.PATCH**, increment the:

MAJOR version when you make incompatible API changes
MINOR version when you add functionality in a backward compatible manner
PATCH version when you make backward compatible bug fixes
Additional labels for pre-release and build metadata are available as extensions to the **MAJOR.MINOR.PATCH** format.

### INSTALL THE TERRAFORM CLI

The Terraform CLI installation instructions have changed due to gpg keyring changes. So we needed to refer to the latest install CLI instructions via Terraform documentation and change the scripting for install.

[Install Terraform CLI](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

#### Refactoring into Bash Scripts

While fixing the Terraform CLI gpg depreciation issues, we noticed that bash scripts steps were a lot of code. So we decided to create a bash script to install the Terraform CLI.

The bash script is located here: [./bin/install_terraform_cli](./bin/install_terraform_cli)