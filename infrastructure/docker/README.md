# Docker Configurations

This directory contains Docker configurations for the TITAN RV Platform.

## Planned Contents

- Docker Compose files for development environment
- Production Docker configurations
- Volume management
- Network configurations

## Component Containers

The platform uses the following containers:

1. **ERPNext**
   - Database: MariaDB
   - Redis for caching
   - Application server

2. **SuiteCRM**
   - Database: MySQL
   - Apache web server
   - PHP-FPM

3. **OpenProject**
   - Database: PostgreSQL
   - Redis for caching
   - Application server

4. **E-commerce (Spree/Bagisto)**
   - Database: PostgreSQL
   - Redis for caching
   - Application server

5. **Custom Services**
   - API Gateway
   - Authentication Service
   - Notification Service
   - Reporting Service

## Development Setup

The development environment will use Docker Compose to orchestrate all containers locally.

### Planned Files

- `docker-compose.yml` - Main composition file
- `docker-compose.override.yml` - Local development overrides
- `.env.example` - Environment variable template

## Production Setup

Production deployment will use Kubernetes, but Docker images will be defined here.

### Planned Files

- `Dockerfile.*` - Dockerfiles for custom services
- `docker-compose.prod.yml` - Production-ready composition for reference
