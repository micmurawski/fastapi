# Tutorial001 Httpsredirect Main Subsystem

> 7 nodes

## Key Concepts

- **advanced_middleware/tutorial001_py310.py** (5 connections) — `docs_src/advanced_middleware/tutorial001_py310.py`
- **test_advanced_middleware/test_tutorial001.py** (3 connections) — `tests/test_tutorial/test_advanced_middleware/test_tutorial001.py`
- **main()** (2 connections) — `docs_src/advanced_middleware/tutorial001_py310.py`
- **httpsredirect.py** (2 connections) — `fastapi/middleware/httpsredirect.py`
- **test_middleware()** (1 connections) — `tests/test_tutorial/test_advanced_middleware/test_tutorial001.py`
- **get** (1 connections)
- **starlette_middleware_httpsredirect** (1 connections)

## Relationships

- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (1 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (1 shared connections)

## Source Files

- `docs_src/advanced_middleware/tutorial001_py310.py`
- `fastapi/middleware/httpsredirect.py`
- `tests/test_tutorial/test_advanced_middleware/test_tutorial001.py`

## Audit Trail

- EXTRACTED: 9 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*