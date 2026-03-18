# ☁️ Azure Development

Master Microsoft Azure cloud services, deployment strategies, and DevOps practices.

## 🎯 Learning Goals

- [ ] Understand core Azure services and when to use each
- [ ] Deploy .NET and web applications to Azure App Service and Azure Functions
- [ ] Use Azure SQL Database and Azure Storage for data and blobs
- [ ] Secure applications with Azure Entra ID (AAD) and Key Vault
- [ ] Set up CI/CD pipelines with GitHub Actions targeting Azure
- [ ] Monitor applications with Application Insights and Azure Monitor
- [ ] Write Infrastructure as Code with Bicep
- [ ] Understand Azure networking basics (VNets, App Gateways, Private Endpoints)

## 🗺️ Learning Path

### Stage 1: Azure Fundamentals
- Azure portal navigation and resource groups
- Subscriptions, tenants, and resource management
- Core service categories: Compute, Storage, Networking, Identity
- Azure pricing model and cost management basics

### Stage 2: Compute & Hosting
- Azure App Service — deployment, scaling, deployment slots
- Azure Functions — serverless, triggers, bindings
- Azure Container Apps — containerised workloads
- Comparing hosting options for .NET apps

### Stage 3: Data & Storage
- Azure SQL Database setup and connection
- Azure Blob Storage and queues
- Azure Cosmos DB fundamentals
- Azure Redis Cache

### Stage 4: Identity & Security
- Azure Entra ID (Azure AD) concepts
- Managed Identities — eliminating secrets in code
- Azure Key Vault — storing and accessing secrets
- Role-Based Access Control (RBAC)

### Stage 5: DevOps & Automation
- GitHub Actions for CI/CD to Azure
- Azure DevOps pipelines (overview)
- Infrastructure as Code with Bicep
- Monitoring with Application Insights

## 📁 Folder Structure

```
topics/azure-development/
├── notes/       ← Add your markdown notes here
├── exercises/   ← Deployment configs, Bicep files, pipeline scripts
└── README.md    ← This file
```

## 🔗 Related Topics

- **.NET Development** — Deploying ASP.NET Core apps to Azure
- **SQL** — Azure SQL Database and Cosmos DB
- **PowerShell** — Azure CLI and Az PowerShell module for automation
- **Architecture** — Cloud architecture patterns, resilience, and scalability

## 🤖 Mentor

Use the `@azure-mentor` prompt for Azure-specific guidance, or `@mentor` with `topic = "Azure Development"`.
