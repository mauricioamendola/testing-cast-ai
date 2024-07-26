# Playing around with [Cast.ai](https://cast.ai/)

## Playground deployment

```sh {"id":"01J3D9GR1M0SZR0ECB8Q79Y7V7","promptEnv":"yes"}
cd tf-cluster
export TF_VAR_region="us-east-1"
export AWS_DEFAULT_REGION="us-east-1"
export AWS_ACCESS_KEY_ID=[ACCESS_KEY]
export AWS_SECRET_ACCESS_KEY=[Secret KEY]
```

```sh {"id":"01J3D9H86AVGCC6P3TN4KFF5SH"}
cd tf-cluster
terraform init
terraform plan

```

```sh {"id":"01J3K27P3S0Y57N0VP27YJPJG0"}
cd tf-cluster
terraform plan
```

```sh {"id":"01J3D9HDYJGRC2CPJR964FJ88C"}
cd tf-cluster && terraform apply
```

```sh {"id":"01J3DRX1607DY3GW6TK2XB1BX9"}
## Clean resources
terraform destroy
```