# Gitlab-Terraform-CI
This template defines four jobs: install_terraform, plan, apply, and destroy. The install_terraform job installs Terraform on the runner. The plan job runs the terraform plan command to preview the changes that will be made. The apply job runs the terraform apply command to apply the changes. And the destroy job runs the terraform destroy command to tear down the infrastructure.

You will need to setup YOUR_ACCESS_KEY_ID, YOUR_SECRET_ACCESS_KEY, and YOUR_DEFAULT_REGION with your own AWS credentials and default region , Make sure you configure the AWS before running this script.

For image you can use your custom image also you can use a single image to run all your jobs.
