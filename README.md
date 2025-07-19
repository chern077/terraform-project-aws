#  AWS Infrastructure with Terraform

This project sets up a basic AWS infrastructure using **Terraform**. It includes:

- A **VPC** with multiple **public subnets**
- **EC2 instances** running in each subnet
- An **Internet Gateway** for external access
- An **S3 bucket** connected to the instances

![AWS Terraform Infra](https://github.com/user-attachments/assets/5762f919-2a09-4e5b-a016-1d1efea1af6b)



##  How to Use

1. **Install Terraform**: [terraform.io/downloads](https://terraform.io/downloads)
2. **Clone this repo**:
   git clone https://github.com/chern077/terraform-project-aws.git

   cd terraform-project-aws
3. **Initialise**
   terraform init
4. **Preview the plan**
   terrform plan
5. **Apply the changes**
   terraform apply

   


