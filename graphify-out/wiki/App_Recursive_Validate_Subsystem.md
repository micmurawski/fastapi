# App Recursive Validate Subsystem

> 10 nodes

## Key Concepts

- **app.py** (9 connections) — `tests/test_validate_response_recursive/app.py`
- **BaseModel** (3 connections)
- **test_validate_response_recursive.py** (3 connections) — `tests/test_validate_response_recursive/test_validate_response_recursive.py`
- **RecursiveItem** (2 connections) — `tests/test_validate_response_recursive/app.py`
- **RecursiveItemViaSubmodel** (2 connections) — `tests/test_validate_response_recursive/app.py`
- **RecursiveSubitemInSubmodel** (2 connections) — `tests/test_validate_response_recursive/app.py`
- **get_recursive()** (2 connections) — `tests/test_validate_response_recursive/app.py`
- **get_recursive_submodel()** (2 connections) — `tests/test_validate_response_recursive/app.py`
- **get** (2 connections)
- **test_recursive()** (1 connections) — `tests/test_validate_response_recursive/test_validate_response_recursive.py`

## Relationships

- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (1 shared connections)

## Source Files

- `tests/test_validate_response_recursive/app.py`
- `tests/test_validate_response_recursive/test_validate_response_recursive.py`

## Audit Trail

- EXTRACTED: 16 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*