# terraform-azure-test
<!-- creer le plan  -->
terraform plan -out main.tfplan


<!-- appliquer le plan -->
terraform apply main.tfplan

<!-- detruire le plan  --->
terraform plan -destroy -out main.destroy.tfplan