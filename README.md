# azure_devops_cicd_yaml_configs_terraform_infra_pipeline
## Overview

This repository contains YAML configurations for setting up CI/CD pipelines in Azure DevOps, along with Terraform scripts for infrastructure provisioning. The goal is to automate the deployment process and manage infrastructure as code.

## Prerequisites

- Azure DevOps account
- Azure subscription
- Terraform installed locally
- Azure CLI installed locally

## Repository Structure

- `.azure-pipelines/`: Contains YAML files for Azure DevOps pipelines.

## Getting Started

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/azure_devops_cicd_yaml_configs_terraform_infra_pipeline.git
    cd azure_devops_cicd_yaml_configs_terraform_infra_pipeline
    ```

2. **Configure Azure DevOps Pipelines:**
    - Navigate to Azure DevOps and create a new pipeline.
    - Select the repository and configure the pipeline using the YAML files in the `.azure-pipelines/` directory.

3. **Provision Infrastructure with Terraform:**
    - Navigate to the `terraform/` directory.
    - Initialize Terraform:
      ```sh
      terraform init
      ```
    - Apply the Terraform scripts to provision resources:
      ```sh
      terraform apply
      ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the existing style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please open an issue in the repository or contact the maintainers.
