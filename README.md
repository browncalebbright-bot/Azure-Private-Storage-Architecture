# Azure Private Storage Architecture

## Project Overview

This project demonstrates the implementation of secure Azure Storage using Private Endpoints, Private DNS Zones, and Shared Access Signatures (SAS).

The solution was designed to restrict public access to storage resources while enabling secure private connectivity within Azure.

## Architecture

```text
Virtual Network
        │
        ▼
Private Endpoint
        │
        ▼
Storage Account
        │
        ▼
Blob Container
```

## Business Objective

The objective of this project was to improve storage security by reducing public exposure and implementing private connectivity to Azure Storage resources.

## Technologies Used

- Microsoft Azure
- Azure Storage Account
- Blob Storage
- Shared Access Signature (SAS)
- Private Endpoint
- Private DNS Zone
- Azure Virtual Network

## Implementation Steps

1. Created an Azure Storage Account
2. Created Blob Containers
3. Uploaded test data to Blob Storage
4. Generated Shared Access Signature (SAS) tokens
5. Configured a Private Endpoint
6. Created and linked a Private DNS Zone
7. Validated private connectivity
8. Verified secure access to storage resources

## Skills Demonstrated

- Azure Storage Administration
- Blob Storage Management
- Storage Security
- Private Networking
- DNS Configuration
- SAS Token Management
- Access Control

## Lessons Learned

- Securing Azure Storage using private connectivity
- Managing storage access using SAS tokens
- Understanding Private Endpoint architecture
- Configuring Azure DNS for private resources

## Outcome

Successfully implemented a private Azure Storage architecture using Private Endpoints and Private DNS Zones while maintaining controlled access through SAS tokens.
