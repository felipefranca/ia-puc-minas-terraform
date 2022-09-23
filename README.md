<!-- BEGIN_TF_DOCS -->

## Nome dos integrantes (Dupla):

Felipe Jonata Oliveira França e Breno Marques Lomasso Costa

## Site

![S3](https://github.com/felipefranca/ia-puc-minas-terraform/blob/master/site.png?raw=true)

## URL TO ACESS
http://52.55.244.88:8080/

## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | 4.26.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 4.26.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_instance.this](https://registry.terraform.io/providers/hashicorp/aws/4.26.0/docs/resources/instance) | resource |
| [aws_internet_gateway.this](https://registry.terraform.io/providers/hashicorp/aws/4.26.0/docs/resources/internet_gateway) | resource |
| [aws_key_pair.this](https://registry.terraform.io/providers/hashicorp/aws/4.26.0/docs/resources/key_pair) | resource |
| [aws_route.this](https://registry.terraform.io/providers/hashicorp/aws/4.26.0/docs/resources/route) | resource |
| [aws_security_group.sg-web](https://registry.terraform.io/providers/hashicorp/aws/4.26.0/docs/resources/security_group) | resource |
| [aws_subnet.this](https://registry.terraform.io/providers/hashicorp/aws/4.26.0/docs/resources/subnet) | resource |
| [aws_vpc.this](https://registry.terraform.io/providers/hashicorp/aws/4.26.0/docs/resources/vpc) | resource |
| [aws_ami.ubuntu](https://registry.terraform.io/providers/hashicorp/aws/4.26.0/docs/data-sources/ami) | data source |
| [aws_availability_zones.available](https://registry.terraform.io/providers/hashicorp/aws/4.26.0/docs/data-sources/availability_zones) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_aws_instance_type"></a> [aws\_instance\_type](#input\_aws\_instance\_type) | n/a | `string` | n/a | yes |
| <a name="input_aws_profile"></a> [aws\_profile](#input\_aws\_profile) | n/a | `string` | n/a | yes |
| <a name="input_aws_public_key"></a> [aws\_public\_key](#input\_aws\_public\_key) | value | `string` | n/a | yes |
| <a name="input_aws_region"></a> [aws\_region](#input\_aws\_region) | n/a | `string` | n/a | yes |
| <a name="input_prefix"></a> [prefix](#input\_prefix) | n/a | `string` | n/a | yes |

## Outputs

No outputs.
<!-- END_TF_DOCS -->

## Infracost

![INFRA COST](https://github.com/felipefranca/ia-puc-minas-terraform/blob/master/infra-cost.png?raw=true)

## Screenshots

![S3](https://github.com/felipefranca/ia-puc-minas-terraform/blob/master/buckets-S3.png?raw=true)
![EC2](https://github.com/felipefranca/ia-puc-minas-terraform/blob/master/ec2.png?raw=true)
![EFS](https://github.com/felipefranca/ia-puc-minas-terraform/blob/master/efs.png?raw=true)
![ENVIROMENTS](https://github.com/felipefranca/ia-puc-minas-terraform/blob/master/enviroments.png?raw=true)
![INDEX FILE MOUNTED VOLUME](https://github.com/felipefranca/ia-puc-minas-terraform/blob/master/file-index.html-efs-mounted-volume.png?raw=true)
![PROD STATE](https://github.com/felipefranca/ia-puc-minas-terraform/blob/master/prod-state.png?raw=true)
![VPC](https://github.com/felipefranca/ia-puc-minas-terraform/blob/master/vpc.png?raw=true)


