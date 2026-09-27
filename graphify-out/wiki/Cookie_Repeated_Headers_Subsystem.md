# Cookie Repeated Headers Subsystem

> 6 nodes

## Key Concepts

- **test_repeated_cookie_headers.py** (9 connections) — `tests/test_repeated_cookie_headers.py`
- **get_direct_cookie()** (2 connections) — `tests/test_repeated_cookie_headers.py`
- **get_indirect_cookie()** (2 connections) — `tests/test_repeated_cookie_headers.py`
- **get** (2 connections)
- **set_indirect_cookie()** (1 connections) — `tests/test_repeated_cookie_headers.py`
- **test_cookie_is_set_once()** (1 connections) — `tests/test_repeated_cookie_headers.py`

## Relationships

- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (2 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (1 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (1 shared connections)
- [Response Models & Status Codes](Response_Models_&_Status_Codes.md) (1 shared connections)

## Source Files

- `tests/test_repeated_cookie_headers.py`

## Audit Trail

- EXTRACTED: 11 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*