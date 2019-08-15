# Stub Domains Private Cluster

This example illustrates how to create a private cluster that adds
custom stub domains to kube-dns.

It will:

- Create a private cluster
- Remove the default kube-dns configmap
- Add a new kube-dns configmap with custom stub domains

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

To provision this example, run the following from within this directory:

- `terraform init` to get the plugins
- `terraform plan` to see the infrastructure plan
- `terraform apply` to apply the infrastructure build
- `terraform destroy` to destroy the built infrastructure