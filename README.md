# Ilía challenger

- Aplicação Web NodeJS + Express
- github actions pipeline - Build > push on registry > Update no Helm chart

# Cluster AKS

 - Terraform repository

https://github.com/jessefs/terraform-repo

# Show DNS

az aks show --resource-group gr_test_k8s --name cluster_test_aks --query addonProfiles.httpApplicationRouting.config.HTTPApplicationRoutingZoneName -o table

