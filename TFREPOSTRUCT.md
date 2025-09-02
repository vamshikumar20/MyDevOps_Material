.
├── .github/
│   └── workflows/
│       └── terraform.yml              # GitHub Actions pipeline for Terraform IaC [7]
│
├── envs/                              # Environment-specific configurations
│   ├── dev/
│   │   └── main.tf                    # Terraform code for Development
│   ├── stage/
│   │   └── main.tf                    # Terraform code for Staging
│   └── prod/
│       └── main.tf                    # Terraform code for Production
│
├── modules/                           # Reusable Terraform modules
│   ├── vpc/
│   ├── ec2/
│   └── eks/
│
├── global/                            # Shared provider, variables and outputs
│   ├── provider.tf
│   ├── variables.tf
│   └── outputs.tf
│
├── README.md                          # Documentation
└── versions.tf                        # Terraform version and provider constraints
