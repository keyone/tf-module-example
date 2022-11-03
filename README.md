# tf-module-example

https://youtu.be/POM73N3Vgw0


## Usage

```
module "my_ec2_instance" {
  source              = "github.com/keyone/tf-module-example"
  ec2_instance_type   = "t3.micro"
  ec2_instance_name   = "My instance"
  number_of_instances = 1
  ec2_ami_id          = <your AMI ID to use to launch the instance>
}
```