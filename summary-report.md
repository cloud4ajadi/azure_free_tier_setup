# Azure Free Tier Setup Summary Report

## Resourse Group Creation & Region Selection

I created a resourse group named NextGen-DHF-RG in South Africa North region.
I selected the South Africa North Azure region because it is geographically closer to Nigeria and provides lower latency compared to European or US regions.

## Deployed Resource

# Virtual Machine
I deployed an Ubuntu Linux VM in the previously created resource group with the following config details:
- Name: test-vm
- Resource group: NextGen-DHF-RG
- Location: South Africa North (Zone 1)
- OS: Linux (ubuntu 24.04)
- Size: Standard B2ats v2 (2 vcpus, 1 GiB memory)

# Storage Account
I deployed an Azure Storage Account chosen Azure blob storage as a test resource. The deployment process helped me understand:
- Resource validation
- Resource groups
- Azure regions
- Deployment workflows



## Shared Responsibility Model

For the deployed Storage Account, Microsoft Azure is responsible for:
- Physical hardware
- Networking
- Datacenter security
- Infrastructure availability

I am responsible for:
- Access management
- Data security
- Proper configuration
- Monitoring usage and costs

## IAM and RBAC Understanding

I explored Microsoft Entra ID and RBAC concepts. RBAC allows administrators to assign permissions based on user roles rather than assigning permissions individually.

## Cost Management

I accessed the Cost Management + Billing section and reviewed budget and cost analysis tools to ensure that resource usage remains within Azure Free Tier limits.
I also setup a Butget of $5 with 80% forecast alert.