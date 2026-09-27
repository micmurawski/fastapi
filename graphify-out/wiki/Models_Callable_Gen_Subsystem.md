# Models Callable Gen Subsystem

> 65 nodes

## Key Concepts

- **test_dependency_models.py** (38 connections) — `tests/test_dependency_models.py`
- **Dependant** (35 connections) — `fastapi/dependencies/models.py`
- **dependencies/models.py** (32 connections) — `fastapi/dependencies/models.py`
- **solve_dependencies()** (30 connections) — `fastapi/dependencies/utils.py`
- **get_request_handler()** (25 connections) — `fastapi/routing.py`
- **_is_async_gen_callable()** (18 connections) — `fastapi/dependencies/models.py`
- **_is_gen_callable()** (18 connections) — `fastapi/dependencies/models.py`
- **_get_cache_key()** (15 connections) — `fastapi/dependencies/models.py`
- **_is_coroutine_callable()** (15 connections) — `fastapi/dependencies/models.py`
- **_uses_scopes()** (11 connections) — `fastapi/dependencies/models.py`
- **_CallIdentity** (10 connections) — `fastapi/dependencies/models.py`
- **_get_computed_scope()** (10 connections) — `fastapi/dependencies/models.py`
- **_get_oauth_scopes()** (10 connections) — `fastapi/dependencies/models.py`
- **_is_security_scheme()** (9 connections) — `fastapi/dependencies/models.py`
- **_get_security_scheme()** (8 connections) — `fastapi/dependencies/models.py`
- **_is_async_gen_callable_cached()** (8 connections) — `fastapi/dependencies/models.py`
- **_is_coroutine_callable_cached()** (8 connections) — `fastapi/dependencies/models.py`
- **_is_gen_callable_cached()** (8 connections) — `fastapi/dependencies/models.py`
- **_unwrapped_call()** (8 connections) — `fastapi/dependencies/models.py`
- **_solve_generator()** (8 connections) — `fastapi/dependencies/utils.py`
- **test_callable_classification_is_shared_by_call()** (8 connections) — `tests/test_dependency_models.py`
- **_get_openapi_dependency_data()** (7 connections) — `fastapi/openapi/utils.py`
- **test_callable_classification()** (7 connections) — `tests/test_dependency_models.py`
- **test_callable_classification_cache_supports_large_apps()** (7 connections) — `tests/test_dependency_models.py`
- **test_derived_values_are_not_stored_on_dependant()** (7 connections) — `tests/test_dependency_models.py`
- *... and 40 more nodes in this community*

## Relationships

- [OpenAPI Utilities & Schema Compatibility](OpenAPI_Utilities_&_Schema_Compatibility.md) (51 shared connections)
- [Background Tasks & Lifespan](Background_Tasks_&_Lifespan.md) (13 shared connections)
- [Form Data & File Uploads](Form_Data_&_File_Uploads.md) (10 shared connections)
- [Response Models & Status Codes](Response_Models_&_Status_Codes.md) (7 shared connections)
- [CORS & Custom Middleware](CORS_&_Custom_Middleware.md) (4 shared connections)
- [Oauth2 Models Base Subsystem](Oauth2_Models_Base_Subsystem.md) (4 shared connections)
- [Api Key The Subsystem](Api_Key_The_Subsystem.md) (2 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [Tutorial002 Notification Send Subsystem](Tutorial002_Notification_Send_Subsystem.md) (1 shared connections)
- [Security Dependency Overrides Subsystem](Security_Dependency_Overrides_Subsystem.md) (1 shared connections)
- [Response Model Annotation Subsystem](Response_Model_Annotation_Subsystem.md) (1 shared connections)

## Source Files

- `fastapi/concurrency.py`
- `fastapi/dependencies/models.py`
- `fastapi/dependencies/utils.py`
- `fastapi/openapi/utils.py`
- `fastapi/routing.py`
- `tests/test_dependency_models.py`

## Audit Trail

- EXTRACTED: 245 (85%)
- INFERRED: 42 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*