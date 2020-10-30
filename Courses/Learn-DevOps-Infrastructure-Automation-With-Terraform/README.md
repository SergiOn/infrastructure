## Learn DevOps: Infrastructure Automation With Terraform

https://www.udemy.com/course/learn-devops-infrastructure-automation-with-terraform

#### About

Learn how to automate your infrastructure with terraform. Covers Terraform with AWS, Packer, Docker, ECS, EKS, Jenkins

#### Repository

https://github.com/wardviaene/terraform-course

#### Useful Commands

* plan
```bash
terraform plan
```

* shortcut for plan & apply - avoid this in production
```bash
terraform apply
```

* terraform plan and write the plan to out file
```bash
terraform plan -out out.terraform
```

* apply terraform plan using out file
```bash
terraform apply out.terraform
```

* show current state
```bash
terraform show
```

* show state in JSON format
```bash
cat terraform.tfstate
```

#### Reference Documentation

* Download URL: https://www.terraform.io/downloads.html

* AWS Resources: https://www.terraform.io/docs/providers/aws/

* List of providers: https://www.terraform.io/docs/providers/index.html

* List of AMIs for ubuntu: https://cloud-images.ubuntu.com/locator/ec2/ (hint: make sure not to pick arm64 if you're on amd64)

