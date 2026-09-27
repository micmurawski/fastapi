# Schema Split Message Subsystem

> 11 nodes

## Key Concepts

- **test_no_schema_split.py** (13 connections) — `tests/test_no_schema_split.py`
- **create_message()** (4 connections) — `tests/test_no_schema_split.py`
- **Message** (3 connections) — `tests/test_no_schema_split.py`
- **MessageEventType** (3 connections) — `tests/test_no_schema_split.py`
- **MessageOutput** (3 connections) — `tests/test_no_schema_split.py`
- **BaseModel** (3 connections)
- **MessageEvent** (2 connections) — `tests/test_no_schema_split.py`
- **Enum** (2 connections)
- **test_create_message()** (1 connections) — `tests/test_no_schema_split.py`
- **test_openapi_schema()** (1 connections) — `tests/test_no_schema_split.py`
- **str** (1 connections)

## Relationships

- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Nested Models & Content Types](Nested_Models_&_Content_Types.md) (1 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)

## Source Files

- `tests/test_no_schema_split.py`

## Audit Trail

- EXTRACTED: 21 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*