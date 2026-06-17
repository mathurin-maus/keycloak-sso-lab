# Keycloak SSO Lab

## Overview

This project is a personal lab environment built to learn and experiment with Identity and Access Management (IAM) and Single Sign-On (SSO) concepts using Keycloak.

The lab was created while preparing a Keycloak-based SSO project in a professional environment. The objective is to better understand authentication flows, centralized identity management and application integration with an Identity Provider (IdP).

## Environment

- Rocky Linux
- Docker
- Keycloak
- Nginx
- Web Browser

## Objectives

- Understand Keycloak architecture
- Deploy an Identity Provider (IdP)
- Configure authentication and authorization
- Implement Single Sign-On (SSO)
- Connect multiple applications to a centralized authentication service
- Explore IAM concepts and access management

## Architecture

```text
Rocky Linux VM
│
└── Docker
    │
    ├── Keycloak
    │
    ├── Nginx Application #1
    │
    └── Nginx Application #2
```

Keycloak acts as the central Identity Provider. Multiple web applications authenticate users through Keycloak, allowing centralized authentication and Single Sign-On between services.

## Current Status

- [x] Rocky Linux virtual machine deployment
- [x] Docker installation and configuration
- [x] Keycloak deployment in a container
- [x] First Nginx application deployment
- [x] First application integration with Keycloak
- [ ] Second application integration
- [ ] SSO validation between applications
- [ ] User and role management tests
- [ ] Advanced authentication flow experiments

## Technologies

| Technology | Purpose |
|------------|----------|
| Rocky Linux | Operating System |
| Docker | Containerization |
| Keycloak | Identity Provider (IdP) |
| Nginx | Test Applications |
| SSO | Centralized Authentication |
| IAM | Identity and Access Management |

## Learning Outcomes

Through this project, I am gaining practical experience with:

- Identity and Access Management (IAM)
- Single Sign-On (SSO)
- Keycloak administration
- Dockerized services
- Linux administration
- Authentication and authorization concepts
- Application integration with an Identity Provider

## Future Improvements

- Add screenshots and deployment diagrams
- Configure multiple user roles
- Explore OpenID Connect (OIDC)
- Explore OAuth 2.0 flows
- Test Identity Federation
- Implement MFA scenarios
