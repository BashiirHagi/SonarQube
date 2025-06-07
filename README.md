#  SonarQube Integration with Azure Pipelines

This repository demonstrates How SonarQube is integrated into Azure Pipelines to perform code analysis to detect security vulnerabilities and ensure code quality. The scan would be triggered when developers push their source code to the repository as part of their CI/CD process. 

---

## 📦 Features

-  Integrates SonarQube as a step into the Azure Pipelines
-  Parameterized pipeline stages using YAML files - separating prepare and scan tasks
-  It scans source code for bugs and vulnerabilities producing analysis reports 
-  Generates SonarQube dashboard reports using prepared templates


--- 

## 🔧 Technology Stack

- Azure DevOps Pipelines
- SonarQube
- YAML-based definition file for CI/CD
- (Optional) Self-hosted or cloud-based SonarQube instance

---

## 📁 File Structure

```bash
.
├── azure-pipelines.yml               
├── templates/
│   ├── build.yml                     
│   └── code-scanning/
│       ├── sonarqube-prepare.yml    
│       └── sonarqube-scan.yml       
├── README.md
```

 Repository Readme updated in 2025 to improve clarity and readability. The core project was originally built in 2023.
