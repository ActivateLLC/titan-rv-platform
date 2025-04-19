# TITAN RV Platform

Integrated business platform for TITAN RV luxury mining truck conversions.

## Overview

The TITAN RV Platform is a comprehensive technology infrastructure designed to support the operations of TITAN RV, a premium mining truck conversion business specializing in transforming industrial mining haul trucks into luxury expedition vehicles.

## Architecture

This platform integrates several open-source systems to create a complete business solution:

- **ERPNext** - Enterprise Resource Planning for inventory, purchasing, and financial management
- **SuiteCRM** - Customer Relationship Management for ultra-high-net-worth clientele
- **OpenProject** - Project management for complex conversion builds
- **Spree/Bagisto** - E-commerce platform for digital products and maintenance subscriptions

## Repository Structure

```
/titan-rv-platform
├── /docs                     # Documentation
│   ├── /architecture         # System architecture designs
│   ├── /user-guides          # End-user documentation
│   └── /developer-guides     # Developer documentation
├── /infrastructure           # Infrastructure as code
│   ├── /docker               # Docker configurations
│   ├── /kubernetes           # Kubernetes configurations
│   └── /terraform            # Terraform scripts
├── /integrations             # Custom integration code
│   ├── /erpnext              # ERPNext customizations
│   ├── /suitecrm             # SuiteCRM customizations
│   ├── /openproject          # OpenProject customizations
│   └── /ecommerce            # Spree/Bagisto customizations
├── /scripts                  # Utility scripts
│   ├── /setup                # Setup scripts
│   ├── /migration            # Data migration scripts
│   └── /backup               # Backup scripts
└── /services                 # Custom microservices
    ├── /api-gateway          # API gateway service
    ├── /auth-service         # Authentication service
    ├── /notification-service # Notification service
    └── /reporting-service    # Custom reporting service
```

## Getting Started

Instructions for setting up the development environment will be added soon.

## License

This project is licensed under the MIT License - see the LICENSE file for details.