#  TF AWS EKS
lodge Terraform AWS EKS Implementation

## Summary
This repository implements the [CMD EKS cluster module](https://github.com/cmdlabs/terraform-aws-eks).

## Cluster Setup
Here are the components required to set up the EKS cluster:


## Diagram
-------

.. image:: diagram.png
  :align: right

## How to
This repository follows the 3 musketeers pattern, thus all tooling is packaged in docker containers and all required commands are Makefile targets. Environment variables are used to specify certain variables. These are documented in envvars.yml and will be automatically checked to ensure they are set prior to any commands being ran against your accounts.

