Terraform Provider
==================

This has been forked from hashicorp in order to add an M1 arm binary.

Requirements
------------

-	[Terraform](https://www.terraform.io/downloads.html) 0.10.x
-	[Go](https://golang.org/doc/install) 1.11 (to build the provider plugin)

Usage
---------------------

```hcl
terraform {
  required_providers {
    template = {
      source  = "cloudposse/template"
      version = "~> 2.2.0"
    }
  }
}
```

Thanks
---------------------

- [gxben/terraform-provider-template](https://github.com/gxben/terraform-provider-template) for initially starting a fork for arm
