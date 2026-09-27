# Json Path Fast Subsystem

> 10 nodes

## Key Concepts

- **test_dump_json_fast_path.py** (11 connections) — `tests/test_dump_json_fast_path.py`
- **Item** (4 connections) — `tests/test_dump_json_fast_path.py`
- **get_default()** (3 connections) — `tests/test_dump_json_fast_path.py`
- **get_explicit()** (3 connections) — `tests/test_dump_json_fast_path.py`
- **test_default_response_class_skips_json_dumps()** (2 connections) — `tests/test_dump_json_fast_path.py`
- **test_explicit_response_class_uses_json_dumps()** (2 connections) — `tests/test_dump_json_fast_path.py`
- **get** (2 connections)
- **BaseModel** (1 connections)
- **When no response_class is set, the fast path serializes directly to JSON bytes…** (1 connections) — `tests/test_dump_json_fast_path.py`
- **When response_class is explicitly set to JSONResponse, the normal path is used…** (1 connections) — `tests/test_dump_json_fast_path.py`

## Relationships

- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)
- [Static Files & Item Routing](Static_Files_&_Item_Routing.md) (1 shared connections)

## Source Files

- `tests/test_dump_json_fast_path.py`

## Audit Trail

- EXTRACTED: 18 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*