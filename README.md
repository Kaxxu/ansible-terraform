# terraform-ansible

Simple role to download the newest `stable amd64/x64` [Terraform](https://www.terraform.io/)
version for Linux without using or setting variable.

### Role Information
The Role will install Terraform in `/usr/bin/`.

The final task include:

`become: true`

Included tag for every task:

`tags: terraform`

### File Structure
```
terraform-ansible
├── LICENSE
├── README.md
└── tasks
    └── main.yml

1 directory, 3 files
```