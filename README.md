# terraform-polkadot-aws-global

[![open-issues](https://img.shields.io/github/issues-raw/insight-infrastructure/terraform-polkadot-aws-global?style=for-the-badge)](https://github.com/insight-infrastructure/terraform-polkadot-aws-global/issues)
[![open-pr](https://img.shields.io/github/issues-pr-raw/insight-infrastructure/terraform-polkadot-aws-global?style=for-the-badge)](https://github.com/insight-infrastructure/terraform-polkadot-aws-global/pulls)

## Features

This module...

## Terraform Versions

For Terraform v0.12.0+

## Usage

```
module "this" {
    source = "github.com/insight-infrastructure/terraform-polkadot-aws-global"

}
```
## Examples

- [defaults](https://github.com/insight-infrastructure/terraform-polkadot-aws-global/tree/master/examples/defaults)

## Known  Issues
No issue is creating limit on this module.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Providers

| Name | Version |
|------|---------|
| aws | n/a |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:-----:|
| api\_asg\_enable | Enable API ASG IAM role | `bool` | `true` | no |

## Outputs

| Name | Description |
|------|-------------|
| api\_asg\_iam\_instance\_profile | n/a |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

## Testing
This module has been packaged with terratest tests

To run them:

1. Install Go
2. Run `make test-init` from the root of this repo
3. Run `make test` again from root

## Authors

Module managed by [insight-infrastructure](https://github.com/insight-infrastructure)

## Credits

- [Anton Babenko](https://github.com/antonbabenko)

## License

Apache 2 Licensed. See LICENSE for full details.