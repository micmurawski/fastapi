# Image01 Playwright Run Subsystem

> 45 nodes

## Key Concepts

- **subprocess** (18 connections)
- **playwright_sync_api** (12 connections)
- **httpx** (10 connections)
- **commit_translation_changes()** (8 connections) — `scripts/translation_git.py`
- **translation_git.py** (6 connections) — `scripts/translation_git.py`
- **test_translate.py** (6 connections) — `tests/test_translate.py`
- **has_translation_changes()** (5 connections) — `scripts/translation_git.py`
- **cookie_param_models/image01.py** (5 connections) — `scripts/playwright/cookie_param_models/image01.py`
- **header_param_models/image01.py** (5 connections) — `scripts/playwright/header_param_models/image01.py`
- **json_base64_bytes/image01.py** (5 connections) — `scripts/playwright/json_base64_bytes/image01.py`
- **query_param_models/image01.py** (5 connections) — `scripts/playwright/query_param_models/image01.py`
- **request_form_models/image01.py** (5 connections) — `scripts/playwright/request_form_models/image01.py`
- **sql_databases/image01.py** (5 connections) — `scripts/playwright/sql_databases/image01.py`
- **sql_databases/image02.py** (5 connections) — `scripts/playwright/sql_databases/image02.py`
- **test_commit_translation_changes()** (4 connections) — `tests/test_translate.py`
- **run_git()** (3 connections) — `tests/test_translate.py`
- **separate_openapi_schemas/image01.py** (3 connections) — `scripts/playwright/separate_openapi_schemas/image01.py`
- **separate_openapi_schemas/image02.py** (3 connections) — `scripts/playwright/separate_openapi_schemas/image02.py`
- **image03.py** (3 connections) — `scripts/playwright/separate_openapi_schemas/image03.py`
- **image04.py** (3 connections) — `scripts/playwright/separate_openapi_schemas/image04.py`
- **image05.py** (3 connections) — `scripts/playwright/separate_openapi_schemas/image05.py`
- **run()** (2 connections) — `scripts/playwright/cookie_param_models/image01.py`
- **run()** (2 connections) — `scripts/playwright/header_param_models/image01.py`
- **run()** (2 connections) — `scripts/playwright/json_base64_bytes/image01.py`
- **run()** (2 connections) — `scripts/playwright/query_param_models/image01.py`
- *... and 20 more nodes in this community*

## Relationships

- [Tutorial013 Tutorial014 Tutorial003 Subsystem](Tutorial013_Tutorial014_Tutorial003_Subsystem.md) (7 shared connections)
- [Translate List Llm Subsystem](Translate_List_Llm_Subsystem.md) (6 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (4 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (3 shared connections)
- [Sponsors Graphql Defaultdict Subsystem](Sponsors_Graphql_Defaultdict_Subsystem.md) (2 shared connections)
- [Notify Translations Addcommentdata Subsystem](Notify_Translations_Addcommentdata_Subsystem.md) (1 shared connections)
- [Main Anyio Root Subsystem](Main_Anyio_Root_Subsystem.md) (1 shared connections)
- [Docs Build Lang Subsystem](Docs_Build_Lang_Subsystem.md) (1 shared connections)
- [Deploy Docs Status Subsystem](Deploy_Docs_Status_Subsystem.md) (1 shared connections)

## Source Files

- `scripts/playwright/cookie_param_models/image01.py`
- `scripts/playwright/header_param_models/image01.py`
- `scripts/playwright/json_base64_bytes/image01.py`
- `scripts/playwright/query_param_models/image01.py`
- `scripts/playwright/request_form_models/image01.py`
- `scripts/playwright/separate_openapi_schemas/image01.py`
- `scripts/playwright/separate_openapi_schemas/image02.py`
- `scripts/playwright/separate_openapi_schemas/image03.py`
- `scripts/playwright/separate_openapi_schemas/image04.py`
- `scripts/playwright/separate_openapi_schemas/image05.py`
- `scripts/playwright/sql_databases/image01.py`
- `scripts/playwright/sql_databases/image02.py`
- `scripts/translation_git.py`
- `tests/test_translate.py`

## Audit Trail

- EXTRACTED: 92 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*