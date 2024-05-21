# KQL Queries Repository

Welcome to the KQL Paradise. This repository contains various Kusto Query Language (KQL) scripts organized by technology and use case. The structure of the repository is designed to facilitate easy navigation and efficient access to different types of queries.

## Repository Structure

The repository is divided into folders based on different technologies. Each folder contains KQL files related to that specific technology. The naming convention for the KQL files is as follows:

- **S_**: Snippets
- **D_**: Detection
- **H_**: Hunting Queries
- **W_**: Workbooks

### Folders

Below is a list of the folders and their respective purposes:

- **Sentinel Cost Control**: Contains KQL queries focused on monitoring and controlling costs associated with Microsoft Sentinel.
- **Intune**: Contains KQL queries related to Microsoft Intune for device management.
- **M365**: Contains KQL queries for Microsoft 365 applications and services.
- **Defender**: Contains KQL queries for Microsoft Defender security products.
- **Health**: Contains KQL queries related to system health and performance monitoring.

### Example Structure

├── Sentinel Cost Control
│ ├── S_example_query.kql
│ ├── D_cost_detection.kql
│ ├── H_cost_hunting.kql
│ └── W_cost_workbook.kql
├── Intune
│ ├── S_example_query.kql
│ ├── D_intune_detection.kql
│ ├── H_intune_hunting.kql
│ └── W_intune_workbook.kql
├── M365
│ ├── S_example_query.kql
│ ├── D_m365_detection.kql
│ ├── H_m365_hunting.kql
│ └── W_m365_workbook.kql
├── Defender
│ ├── S_example_query.kql
│ ├── D_defender_detection.kql
│ ├── H_defender_hunting.kql
│ └── W_defender_workbook.kql
├── Health
│ ├── S_example_query.kql
│ ├── D_health_detection.kql
│ ├── H_health_hunting.kql
│ └── W_health_workbook.kql
└── README.md


## File Naming Conventions

To maintain consistency and clarity, please use the following prefixes for your KQL files:

- **S_**: Snippets - Short, reusable code fragments.
- **D_**: Detection - Queries used for detecting specific conditions or anomalies.
- **H_**: Hunting Queries - Queries used for threat hunting and investigation.
- **W_**: Workbooks - Queries that are part of or used in workbooks for reporting and visualization.

## Contributing

We welcome contributions to this repository. If you have a KQL query to share, please ensure it adheres to the naming conventions and is placed in the appropriate folder. When contributing, please include a brief description of the query and its purpose in the file comment header.

Thank you for your contributions and for helping  build a comprehensive KQL query repository!

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
