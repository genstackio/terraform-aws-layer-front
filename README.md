# AWS Front Terraform module

Terraform module which creates the resources to host a front web app on AWS.

## Usage

```hcl
module "front" {
  source      = "genstackio/front/aws"

  bucket_name = "name-of-the-bucket"
  dns         = "front.mydomain.com"
  dns_zone    = "id-of-the-route53-zone"
}
```
