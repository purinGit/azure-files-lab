# azure-files-lab
Azure Files configuration with AD DS

# Azure Files with Active Directory

This project documents how I configured Azure Files with on-premises Active Directory authentication.

## What I did
- Created an Azure File share
- Integrated with AD DS for authentication
- Configured DFS for redundancy

## Tools Used
- Azure Portal
- PowerShell
- Windows Server 2019

## Key Learnings
- Importance of correct DFS namespace permissions
- How to bind Azure Files to a domain-joined VM

## Diagram
![Architecture](diagram/azure-files-arch.png)
