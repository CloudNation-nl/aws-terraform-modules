# aws-terraform-modules
Public modules for use with Terraform

# Usage

Call as a module from Terraform: 

```
module "s3" {
  source = "github.com/CloudNation-nl/aws-terraform-modules//s3/v0.0.1"
  bucket = "mybucket"
}
```

Run `terraform init` and `terraform plan`

# Versioning

Modules once uploaded will never change. New versions can have minor fixes (vx.x.1->2), added resources (vx.1->2.x) or breaking changes (v1->2.x.x)

# License, Bugs, issues and questions

CloudNation offers these modules free of charge. If you're missing features, find a bug or need other support, please create an issue on Github.

# Adding modules

Please open a Pull Request for any new versions, make sure to adhere to the versioning strategy and to update the README.md with the changes made. Pull requests are automatically verified using `terraform fmt` and `terraform validate`. To ensure these tests succeed, perform these against your changes first.