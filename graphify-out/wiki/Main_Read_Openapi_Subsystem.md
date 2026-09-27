# Main Read Openapi Subsystem

> 8 nodes

## Key Concepts

- **test_testing/test_main_a.py** (5 connections) — `tests/test_tutorial/test_testing/test_main_a.py`
- **app_testing/app_a_py310/main.py** (4 connections) — `docs_src/app_testing/app_a_py310/main.py`
- **app_testing/app_a_py310/test_main.py** (4 connections) — `docs_src/app_testing/app_a_py310/test_main.py`
- **test_read_main()** (3 connections) — `docs_src/app_testing/app_a_py310/test_main.py`
- **read_main()** (2 connections) — `docs_src/app_testing/app_a_py310/main.py`
- **test_main()** (2 connections) — `tests/test_tutorial/test_testing/test_main_a.py`
- **test_openapi_schema()** (1 connections) — `tests/test_tutorial/test_testing/test_main_a.py`
- **get** (1 connections)

## Relationships

- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (1 shared connections)

## Source Files

- `docs_src/app_testing/app_a_py310/main.py`
- `docs_src/app_testing/app_a_py310/test_main.py`
- `tests/test_tutorial/test_testing/test_main_a.py`

## Audit Trail

- EXTRACTED: 13 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*