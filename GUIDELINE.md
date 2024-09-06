### Step 1. Install tfenv and an appropriate version of Terraform
### Step 2. Create an administrator user in AWS
### Step 3. Create AWS infrastructure with Terraform
cd setup/terraform
terraform apply
### Step 4. Generate AWS access keys for GitHub Actions
### Step 5. Add GitHub Action user to Kubernetes
cd setup
./init.sh
### Output 
Link Backend: 
http://a8881fa6c73a549d69751e4fb0bc6ebd-1817487359.us-east-1.elb.amazonaws.com/movies
Link Frontend:
http://a0e26740bfee74c779a133d5ccfdd1da-126635731.us-east-1.elb.amazonaws.com/