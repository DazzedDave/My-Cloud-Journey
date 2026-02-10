# My-Cloud-Journey

A place to document my transition from networking to Azure cloud engineering

My Azure Portfolio
I am an experienced networking professional transitioning into Cloud Engineering.

Current Goals:

[ ] Complete AZ-900 Certification

[ X ] Build a Secure Azure VNet

[ ] Set up a Cloud Resume

## Project 1: Secure Azure VNet Architecture
**Goal:** Design and deploy a secure, two-tier cloud network using Infrastructure as Code (IaC).

### 🏗️ Architecture Diagram
[View Architecture Diagram](project-1-diagram.png)
*Note: This diagram shows the logical flow from the Internet to the Public tier, with a separate Private tier for secure data.*

### 🛠️ Technical Specifications
- **Virtual Network:** `Main-VNet` (Address space: `10.0.0.0/16`) [cite: 2]
- **Public Subnet:** `10.0.1.0/24` — Used for internet-facing resources like web servers.
- **Private Subnet:** `10.0.2.0/24` — Used for internal resources like databases.
- **Resource Group:** `Project-Secure-Office` [cite: 2]

### 🚀 Key Skills Demonstrated
- **Azure Networking:** Configuring VNets and Subnets with proper CIDR notation.
- **Infrastructure as Code (IaC):** Exporting and managing ARM templates (JSON) in GitHub.
- **Technical Documentation:** Creating clear architectural visuals to explain complex cloud setups.
