# Terraform Docker Infrastructure

## Task 3: Infrastructure as Code (IaC) with Terraform

### Objective

Provision a local Docker container using Terraform.

### Tools Used

- Terraform
- Docker
- Nginx

### Implementation

1. Configured the Docker provider in Terraform.
2. Created an Nginx Docker image using Terraform.
3. Created an Nginx Docker container.
4. Mapped Docker port 80 to host port 8081.
5. Initialized Terraform using `terraform init`.
6. Validated the configuration using `terraform validate`.
7. Previewed infrastructure changes using `terraform plan`.
8. Provisioned the infrastructure using `terraform apply`.
9. Verified the running container using Docker.
10. Checked Terraform resources using `terraform state list`.
11. Destroyed the infrastructure using `terraform destroy`.

### Access

During testing, Nginx was available at:

http://localhost:8081

### Terraform Resources

- `docker_image.nginx`
- `docker_container.nginx`

### Result

The Nginx Docker container was successfully provisioned using Terraform and later destroyed successfully.