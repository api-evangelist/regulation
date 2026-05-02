# Regulation

Regulation encompasses the rules, laws, and standards established by governments, agencies, and standards bodies that govern how businesses and individuals must operate. In the context of APIs and digital technology, regulation drives compliance requirements for data privacy (GDPR, CCPA), financial services (PSD2, Dodd-Frank), healthcare (HIPAA), and many other sectors. A rich ecosystem of APIs exists to access regulatory data, track regulatory changes, and automate compliance workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Compliance
- Governance
- Government
- Legal
- Policy
- Regulation
- Regulatory Change
- Risk Management

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

| Name | Description |
|------|-------------|
| [Regulations.gov API](https://open.gsa.gov/api/regulationsgov/) | Access to federal regulatory dockets, documents, and public comments |
| [Federal Register API](https://www.federalregister.gov/developers/documentation/api/v1) | Programmatic access to Federal Register documents since 1994 |
| [Compliance.ai Regulatory Change Management API](https://www.compliance.ai/api/) | Automated aggregation of regulatory changes from federal and state agencies |

## Resources

| Name | Type | URL |
|------|------|-----|
| Regulations.gov API - GSA Open Technology | Website | https://open.gsa.gov/api/regulationsgov/ |
| Federal Register API Documentation | Website | https://www.federalregister.gov/developers/documentation/api/v1 |
| Regulations.gov API - Data.gov Catalog | Website | https://catalog.data.gov/dataset/regulations-gov-api |
| Compliance.ai Developer Program | Website | https://www.compliance.ai/api/ |
| FINRA Developer Center | Website | https://developer.finra.org/ |
| Regulation - Wikipedia | Documentation | https://en.wikipedia.org/wiki/Regulation |

## Artifacts

### JSON Schema

| File | Description |
|------|-------------|
| [regulation-document-schema.json](json-schema/regulation-document-schema.json) | Schema for regulatory documents from the Federal Register and Regulations.gov |
| [regulation-comment-schema.json](json-schema/regulation-comment-schema.json) | Schema for public comments submitted to regulatory dockets |

### JSON Structure

| File | Description |
|------|-------------|
| [regulation-document-structure.json](json-structure/regulation-document-structure.json) | Field-level structure documentation for regulatory documents |

### JSON-LD

| File | Description |
|------|-------------|
| [regulation-context.jsonld](json-ld/regulation-context.jsonld) | JSON-LD context mapping regulatory concepts to schema.org and government data vocabulary |

### Examples

| File | Description |
|------|-------------|
| [regulation-document-federal-register-example.json](examples/regulation-document-federal-register-example.json) | Example EPA proposed rule from the Federal Register API |

### Vocabulary

| File | Description |
|------|-------------|
| [regulation-vocabulary.yml](vocabulary/regulation-vocabulary.yml) | Glossary of regulatory terminology including rulemaking, compliance, and RegTech concepts |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
