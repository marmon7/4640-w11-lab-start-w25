# 4640-w11-lab-start-w25

Commands to run starting from project root:

1. ./scripts/import_lab_key "path to public key"
2. cd terraform
3. terraform init
4. terraform apply
5. cd ../ansible
6. ansible-playbook playbook.yml

when done with vms starting from project root:
1. cd terraform
2. terraform destroy
3. ../scripts/delete_lab_key

Front end Server Image
![frontend]("server-img.jpg")