# Tutorial001 Main Sub Subsystem

> 9 nodes

## Key Concepts

- **test_sub_applications/test_tutorial001.py** (7 connections) — `tests/test_tutorial/test_sub_applications/test_tutorial001.py`
- **sub_applications/tutorial001_py310.py** (5 connections) — `docs_src/sub_applications/tutorial001_py310.py`
- **read_main()** (2 connections) — `docs_src/sub_applications/tutorial001_py310.py`
- **read_sub()** (2 connections) — `docs_src/sub_applications/tutorial001_py310.py`
- **get** (2 connections)
- **test_main()** (1 connections) — `tests/test_tutorial/test_sub_applications/test_tutorial001.py`
- **test_openapi_schema_main()** (1 connections) — `tests/test_tutorial/test_sub_applications/test_tutorial001.py`
- **test_openapi_schema_sub()** (1 connections) — `tests/test_tutorial/test_sub_applications/test_tutorial001.py`
- **test_sub()** (1 connections) — `tests/test_tutorial/test_sub_applications/test_tutorial001.py`

## Relationships

- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (1 shared connections)

## Source Files

- `docs_src/sub_applications/tutorial001_py310.py`
- `tests/test_tutorial/test_sub_applications/test_tutorial001.py`

## Audit Trail

- EXTRACTED: 13 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*