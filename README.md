`terraform init -upgrade`

`terraform plan -out main.tfplan`

`terraform apply main.tfplan`

to ssh into create vm...

`terraform output private_key`

copy the text and paste it in a key.pem file

`chmod 6000 key.pem`

`ssh -i key.pem azureadmin@<vm-public-ip>`

https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-terraform?tabs=azure-cli
