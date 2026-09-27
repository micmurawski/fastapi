# Tutorial004 Main Request Subsystem

> 7 nodes

## Key Concepts

- **test_behind_a_proxy/test_tutorial004.py** (5 connections) — `tests/test_tutorial/test_behind_a_proxy/test_tutorial004.py`
- **behind_a_proxy/tutorial004_py310.py** (4 connections) — `docs_src/behind_a_proxy/tutorial004_py310.py`
- **read_main()** (3 connections) — `docs_src/behind_a_proxy/tutorial004_py310.py`
- **test_main()** (1 connections) — `tests/test_tutorial/test_behind_a_proxy/test_tutorial004.py`
- **test_openapi_schema()** (1 connections) — `tests/test_tutorial/test_behind_a_proxy/test_tutorial004.py`
- **get** (1 connections)
- **Request** (1 connections)

## Relationships

- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (1 shared connections)

## Source Files

- `docs_src/behind_a_proxy/tutorial004_py310.py`
- `tests/test_tutorial/test_behind_a_proxy/test_tutorial004.py`

## Audit Trail

- EXTRACTED: 10 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*