# CATRINA Identity Integration

This repository contains the integration guide and related documentation for the CATRINA Identity platform.

---

### Documentation

Please select your preferred language to view the integration guide.

- [**English**](/docs/en/integration-guide.md) (Source - Most up-to-date)
- [**Japanese (日本語)**](/docs/ja/integration-guide.md)

### API Specification

Below you will find the technical API specification for your CATRINA Identity integration.

- [**View API Specification**](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/Meeco/CATRINA-Identity-Integration-Docs/main/api-spec.yaml)
- [**API Spec**](api-spec.yaml)

For a standard integration, the two most important endpoints are:

- **Create a Session:** `POST /identity/sessions`
- **Get Session Status and Verified Claims:** `GET /identity/sessions/{sessionId}`

---

> [!NOTE]
> The CATRINA Identity platform is still in active development and documentation will be updated frequently
