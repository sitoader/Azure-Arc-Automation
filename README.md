# Azure Arc Automation

This repository contains scripts and resources to automate the process of enabling Azure Arc on servers across multiple customers. The automation includes creating customer tenants, adding subscriptions, enabling GDAP, installing the Arc agent, and configuring the servers.

## Overview

The goal of this project is to streamline the deployment and management of Azure Arc-enabled servers at scale. By automating these tasks, we aim to reduce manual effort, minimize errors, and ensure consistent configurations across all customer environments.

## Steps Included

1. **CMDB**: Storing and updating customers tenants info
2. **Partner Center**: Create customer tenants using the Partner Center API.
3. **Enable GDAP**: Enable Granular Delegated Admin Privileges for each customer tenant
4. **Install the Arc Agent**: Deploy the Azure Arc agent on servers
5. **Configure the Arc-Enabled servers**: configure servers properties such as license (SQL Servers), Extended Security Updates
6. **Azure Lighthouse**: onboard customers with Lighthouse to have a holistic overview 

## Getting Started

All steps are documented in the docs folder. Please start there for detailed instructions and additional information.

### Prerequisites

- Azure subscription
- Access to Partner Center
- PowerShell and Azure CLI installed
- Appropriate permissions to create and manage resources in Azure