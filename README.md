# n8n: Self-Hosted Workflow Automation

This template deploys a self-hosted instance of [n8n]([[https://n8n.io/](https://n8n.partnerlinks.io/chasestarnes)](n8n)), a powerful workflow automation tool. It leverages a PostgreSQL database for robust data storage and management.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app)

## ✨ Features

- **n8n Workflow Engine**: Create and manage complex automation workflows with ease.
- **PostgreSQL Database**: Reliable and scalable data storage for your n8n instance.
- **Self-Hosted**: Full control over your data and workflows.
- **Customizable**: Easily extendable with custom functions and integrations.

## 🚀 Quick Deploy

1. Click the "Deploy on Railway" button above.
2. Configure the required environment variables (see below).
3. Click "Deploy" and wait for the build to complete.

## 🔧 Environment Variables

Ensure you set the following environment variables:

- `DB_POSTGRESDB_DATABASE`: Name of your PostgreSQL database
- `DB_POSTGRESDB_HOST`: Host address of your PostgreSQL server
- `DB_POSTGRESDB_PASSWORD`: Password for your PostgreSQL user
- `DB_POSTGRESDB_PORT`: Port number for PostgreSQL (default: 5432)
- `DB_POSTGRESDB_USER`: Username for your PostgreSQL database
- `N8N_BASIC_AUTH_ACTIVE`: Set to `true` to enable basic authentication
- `N8N_BASIC_AUTH_USER`: Username for n8n basic auth (if enabled)
- `N8N_BASIC_AUTH_PASSWORD`: Password for n8n basic auth (if enabled)

## 📚 Learn More

- [n8n Documentation](https://docs.n8n.io/)
- [n8n Community Forum](https://community.n8n.io/)

## 🐳 Docker Image

This template uses the official n8n Docker image. For more details, visit:
[https://hub.docker.com/r/n8nio/n8n](https://hub.docker.com/r/n8nio/n8n)

## 🔒 Security Note

Remember to secure your n8n instance, especially when self-hosting. Review the [security documentation](https://docs.n8n.io/hosting/security/) for best practices.
