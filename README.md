# learn-terraform-aws-nginx-wordpress-mysql
How to setup nginx, wordpress and mysql with terraform and claude.io

# setup aliases
```ruby
alias k=kubectl; alias tf="terraform"; alias tfa="terraform apply --auto-approve"; alias tfd="terraform destroy --auto-approve"; alias tfm="terraform init; terraform fmt; terraform validate; terraform plan"
```
## https://developer.hashicorp.com/terraform/install
Install if running at cloudshell
```ruby
sudo yum install -y yum-utils shadow-utils; sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo; sudo yum -y install terraform
```
