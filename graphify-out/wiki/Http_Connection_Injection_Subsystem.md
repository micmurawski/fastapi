# Http Connection Injection Subsystem

> 9 nodes

## Key Concepts

- **test_http_connection_injection.py** (11 connections) — `tests/test_http_connection_injection.py`
- **requests.py** (3 connections) — `fastapi/requests.py`
- **extract_value_from_http_connection()** (2 connections) — `tests/test_http_connection_injection.py`
- **get_value_by_http()** (2 connections) — `tests/test_http_connection_injection.py`
- **get_value_by_ws()** (2 connections) — `tests/test_http_connection_injection.py`
- **test_value_extracting_by_http()** (1 connections) — `tests/test_http_connection_injection.py`
- **test_value_extracting_by_ws()** (1 connections) — `tests/test_http_connection_injection.py`
- **HTTPConnection** (1 connections)
- **get** (1 connections)

## Relationships

- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (2 shared connections)
- [Dependency Yield Websockets Subsystem](Dependency_Yield_Websockets_Subsystem.md) (1 shared connections)
- [Oauth2 Models Base Subsystem](Oauth2_Models_Base_Subsystem.md) (1 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (1 shared connections)
- [Background Tasks & Lifespan](Background_Tasks_&_Lifespan.md) (1 shared connections)

## Source Files

- `fastapi/requests.py`
- `tests/test_http_connection_injection.py`

## Audit Trail

- EXTRACTED: 16 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*