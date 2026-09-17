# AWS to Azure Service Mapping

| AWS Service               | Azure Equivalent                              | Key Difference                                                                                                                                |
| ------------------------- | --------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| VPC                       | Azure Virtual Network (VNet)                  | Both provide private networking, but Azure uses VNets and subnets to organize network resources.                                              |
| EC2                       | Azure Virtual Machines                        | Both provide virtual servers, but Azure VMs are managed within Azure resources and VNets.                                                     |
| Application Load Balancer | Azure Application Gateway                     | Both distribute HTTP/HTTPS traffic, but Application Gateway also provides web application routing features.                                   |
| RDS PostgreSQL            | Azure Database for PostgreSQL Flexible Server | Both provide managed PostgreSQL, but they use different Azure/AWS management and scaling models.                                              |
| Security Groups           | Network Security Groups (NSGs)                | AWS security groups are attached to resources/interfaces, while Azure NSGs can be associated with subnets or network interfaces.              |
| NAT Gateway               | Azure NAT Gateway                             | Both provide outbound internet access for private resources without exposing them directly to the internet.                                   |
| IAM Roles                 | Azure Managed Identities                      | Both allow applications to access Azure/AWS services without storing credentials in code, but Azure uses Managed Identities for this purpose. |
