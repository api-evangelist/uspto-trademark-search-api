# USPTO Trademark Search API

Instant trademark search and brand protection via the USPTO Trademark Search API. Check if a trademark keyword is available, search active trademarks, look up marks by serial number, and search by owner from United States Patent and Trademark Office data. Updated daily. Enables trademark availability checking, portfolio research, competitive intelligence, and due diligence workflows.

## Overview

| Property | Value |
|---|---|
| **Type** | Collection |
| **Position** | Provider |
| **Access** | Public |
| **Base URL** | https://uspto-trademark.p.rapidapi.com |
| **Created** | 2025-05-27 |
| **Modified** | 2026-05-03 |

## Tags

`Brand` `Brand Protection` `Business` `Data` `Government Data` `Intellectual Property` `Legal` `Search` `Trademark` `USPTO`

## APIs

### USPTO Trademark Search API Endpoints

The core API for accessing USPTO trademark data, offering keyword search, availability checking, serial number lookups, owner searches, and database status. Supports pagination.

**Human URL:** [https://rapidapi.com/pentium10/api/uspto-trademark](https://rapidapi.com/pentium10/api/uspto-trademark)

**Base URL:** [https://uspto-trademark.p.rapidapi.com](https://uspto-trademark.p.rapidapi.com)

#### Operations

| Method | Path | Summary |
|---|---|---|
| GET | `/v1/trademarkSearch/{keyword}/{searchType}` | Search Trademarks by Keyword |
| GET | `/v1/trademarkAvailable/{keyword}` | Check Trademark Availability |
| GET | `/v1/trademarkBySerial/{serialNumber}` | Get Trademark by Serial Number |
| GET | `/v1/trademarkOwner/{owner}` | Search Trademarks by Owner |
| GET | `/v1/databaseStatus` | Get Database Status |

#### Properties

- [Documentation](https://rapidapi.com/pentium10/api/uspto-trademark)
- [FAQ](https://rapidapi.com/pentium10/api/uspto-trademark/tutorials/faq-)
- [Pricing](https://rapidapi.com/pentium10/api/uspto-trademark/pricing)
- [Blog — Part 1](https://medium.com/p/71274363605b)
- [Blog — Part 2](https://medium.com/p/19efc7e1cc6)
- [Status Page](https://rapidapi.com/pentium10/api/uspto-trademark#endpoints)
- [Terms of Service](https://rapidapi.com/terms/)
- [OpenAPI Spec](openapi/uspto-trademark-search-api-openapi.yml)

## Artifacts

### OpenAPI Specification

- [uspto-trademark-search-api-openapi.yml](openapi/uspto-trademark-search-api-openapi.yml)

### Spectral Rules

Ruleset enforcing USPTO Trademark Search API conventions: versioned paths, camelCase operationIds, Title Case summaries, required responses, and parameter validation.

- [uspto-trademark-search-api-rules.yml](rules/uspto-trademark-search-api-rules.yml)

### Naftiko Capabilities

Workflow capabilities for trademark research and brand protection.

| File | Description |
|---|---|
| [capabilities/trademark-research.yaml](capabilities/trademark-research.yaml) | Trademark research workflow — search, availability check, serial lookup, owner portfolio, database status |
| [capabilities/shared/uspto-trademark-search.yaml](capabilities/shared/uspto-trademark-search.yaml) | Shared per-API definition for USPTO Trademark Search |

### JSON Schema

- [uspto-trademark-search-api-trademark-schema.json](json-schema/uspto-trademark-search-api-trademark-schema.json)

### JSON Structure

- [uspto-trademark-search-api-trademark-structure.json](json-structure/uspto-trademark-search-api-trademark-structure.json)

### JSON-LD Context

- [uspto-trademark-search-api-context.jsonld](json-ld/uspto-trademark-search-api-context.jsonld)

### Examples

| File | Operation |
|---|---|
| [searchTrademarks-example.json](examples/uspto-trademark-search-api-searchTrademarks-example.json) | Search Trademarks by Keyword |
| [checkTrademarkAvailability-example.json](examples/uspto-trademark-search-api-checkTrademarkAvailability-example.json) | Check Trademark Availability |
| [getTrademarkBySerialNumber-example.json](examples/uspto-trademark-search-api-getTrademarkBySerialNumber-example.json) | Get Trademark by Serial Number |
| [getDatabaseStatus-example.json](examples/uspto-trademark-search-api-getDatabaseStatus-example.json) | Get Database Status |

### Vocabulary

- [uspto-trademark-search-api-vocabulary.yml](vocabulary/uspto-trademark-search-api-vocabulary.yml)

## Common Properties

- [Signup](https://rapidapi.com/pentium10/api/uspto-trademark/)
- [Login](https://rapidapi.com/developer/dashboard)
- [Documentation](https://rapidapi.com/pentium10/api/uspto-trademark)
- [Pricing](https://rapidapi.com/pentium10/api/uspto-trademark/pricing)
- [Terms of Service](https://rapidapi.com/terms/)
- [Twitter](https://twitter.com/martonkodok)

## Maintainers

**MartonKodok** — android482-one@yahoo.com
