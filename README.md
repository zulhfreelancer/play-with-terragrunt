Terragrunt x Terraform exercise

## Usage:

```
# Option 1: pull Terraform configs from remote
$ cd staging/civo
$ terragrunt plan|apply

# Option 2: pull Terraform configs from local filesystem
# terragrunt plan|apply --terragrunt-source /path/to/local/repo//module
$ terragrunt plan|apply --terragrunt-source ~/project/terraform-configs//civo
```

## Resources:

- https://youtu.be/LuKYu9ASGyo
- https://github.com/cloud-native-skunkworks/cnskunkworks-terragrunt
- https://github.com/cloud-native-skunkworks/cnskunkworks-terraform
