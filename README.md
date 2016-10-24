# Terraform
Terraform

### terraform plan

```sh
$ terraform plan \
  -var 'access_key='$TERRAFORM_AWS_ACCESS_KEY \
  -var 'secret_key='$TERRAFORM_AWS_SECRET_KEY

```

Generate and show an execution plan


### terraform apply

```sh
$ terraform apply \
  -var 'access_key='$TERRAFORM_AWS_ACCESS_KEY \
  -var 'secret_key='$TERRAFORM_AWS_SECRET_KEY
```

Builds or changes infrastructure

### terraform show

```sh
$ terraform show
```

Inspect Terraform state or plan

### terraform apply

```sh
$ terraform destroy \
  -var 'access_key='$TERRAFORM_AWS_ACCESS_KEY \
  -var 'secret_key='$TERRAFORM_AWS_SECRET_KEY
```

Completely destroy the Terraform-managed infrastructure
