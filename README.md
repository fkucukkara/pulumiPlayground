# Pulumi Playground for Azure (C#)

This repository is a **Pulumi playground** designed for experimenting with infrastructure-as-code (IaC) on Azure using C#. It serves as a template and sandbox for business-related projects, enabling rapid prototyping and learning.

## What is Pulumi?

[Pulumi](https://www.pulumi.com/) is an open-source infrastructure-as-code platform that allows you to define, deploy, and manage cloud resources using familiar programming languages such as C#, TypeScript, Python, and Go. Pulumi supports multiple cloud providers, including Azure, AWS, and GCP.

## Project Structure

- **Program.cs**: Main entry point for defining Azure resources using Pulumi and C#.
- **README.md**: Project documentation and usage instructions.

## Features

- Written in C# for .NET developers.
- Deploys Azure resources (e.g., Resource Groups, Storage Accounts).
- Easily extensible for business-specific infrastructure needs.
- Follows Pulumi and Azure best practices.

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (6.0 or later)
- [Pulumi CLI](https://www.pulumi.com/docs/get-started/install/)
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli) (for authentication)
- An Azure account

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/fkucukkara/pulumiPlayground.git
   cd pulumiPlayground
   ```

2. **Install dependencies:**
   ```sh
   dotnet restore
   ```

3. **Login to Pulumi:**
   ```sh
   pulumi login
   ```

4. **Login to Azure:**
   ```sh
   az login
   ```

5. **Preview the deployment:**
   ```sh
   pulumi preview
   ```

6. **Deploy to Azure:**
   ```sh
   pulumi up
   ```

7. **Destroy resources (when finished):**
   ```sh
   pulumi destroy
   ```

## Customization

- Modify `Program.cs` to add or change Azure resources.
- Use Pulumi packages to extend functionality as needed.

## Useful Links

- [Pulumi Azure Provider Docs](https://www.pulumi.com/registry/packages/azure/)
- [Pulumi C# API Docs](https://www.pulumi.com/docs/reference/pkg/dotnet/)
- [Azure Documentation](https://docs.microsoft.com/en-us/azure/)

## License
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)