# Forward Reference Method Subsystem

> 19 nodes

## Key Concepts

- **test_duplicate_models_openapi.py** (11 connections) — `tests/test_duplicate_models_openapi.py`
- **test_wrapped_method_forward_reference.py** (8 connections) — `tests/test_wrapped_method_forward_reference.py`
- **test_wrapped_method_type_inference()** (5 connections) — `tests/test_wrapped_method_forward_reference.py`
- **forwardref_method()** (4 connections) — `tests/forward_reference_type.py`
- **f()** (4 connections) — `tests/test_duplicate_models_openapi.py`
- **forward_reference_type.py** (4 connections) — `tests/forward_reference_type.py`
- **ForwardRefModel** (3 connections) — `tests/forward_reference_type.py`
- **app()** (3 connections) — `fastapi/routing.py`
- **passthrough()** (3 connections) — `tests/test_wrapped_method_forward_reference.py`
- **BaseModel** (3 connections)
- **Model** (2 connections) — `tests/test_duplicate_models_openapi.py`
- **Model2** (2 connections) — `tests/test_duplicate_models_openapi.py`
- **Model3** (2 connections) — `tests/test_duplicate_models_openapi.py`
- **method()** (2 connections) — `tests/test_wrapped_method_forward_reference.py`
- **test_get_api_route()** (1 connections) — `tests/test_duplicate_models_openapi.py`
- **test_openapi_schema()** (1 connections) — `tests/test_duplicate_models_openapi.py`
- **BaseModel** (1 connections)
- **get** (1 connections)
- **Regression test ensuring that when a method imported from another module is…** (1 connections) — `tests/test_wrapped_method_forward_reference.py`

## Relationships

- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (4 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (3 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (3 shared connections)
- [Static Files & Item Routing](Static_Files_&_Item_Routing.md) (1 shared connections)
- [Background Tasks & Lifespan](Background_Tasks_&_Lifespan.md) (1 shared connections)
- [Main Config Settings Subsystem](Main_Config_Settings_Subsystem.md) (1 shared connections)

## Source Files

- `fastapi/routing.py`
- `tests/forward_reference_type.py`
- `tests/test_duplicate_models_openapi.py`
- `tests/test_wrapped_method_forward_reference.py`

## Audit Trail

- EXTRACTED: 33 (89%)
- INFERRED: 4 (11%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*