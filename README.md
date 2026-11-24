# Minha API - FastAPI com CI/CD

API desenvolvida com FastAPI, conteinerizada com Docker e automatizada com pipelines de CI/CD via GitHub Actions para deploy na AWS EC2.

## Fluxo de Deploy
- **`develop`**: Deploy automático para o ambiente de homologação.
- **`main`**: Deploy para o ambiente de produção protegido com aprovação obrigatória (*Required reviewers*).
