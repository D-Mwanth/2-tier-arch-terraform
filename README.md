### Configure aws cli
```bash
aws configure
```
- Confirm the aws cli is confugired.
```bash
aws configure list
```

### Terrfaorm init
- create terrafrom alias
```bash
alias tf=terraform
```
```bash
terraform init
```
- Format the code.
```bash
terraform fmt --recursive
```
- Validate the terraform configuration is error free.
```bash
terraform validate
```
Validation was successful.

Run terraform plan to see the number of resorces that will be created.
```bash

```

- Reconfigure init.
```bash
terraform init -reconfigure
```
- Run terraform plan to see which resources will be created.
```bash
terraform plan
```
