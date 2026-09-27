# Router Websocket Verify Subsystem

> 45 nodes

## Key Concepts

- **test_ws_router.py** (37 connections) — `tests/test_ws_router.py`
- **WebSocket** (10 connections)
- **make_app()** (5 connections) — `tests/test_ws_router.py`
- **test_depend_err_handler()** (4 connections) — `tests/test_ws_router.py`
- **test_depend_err_middleware()** (4 connections) — `tests/test_ws_router.py`
- **test_depend_validation()** (4 connections) — `tests/test_ws_router.py`
- **CustomError** (3 connections) — `tests/test_ws_router.py`
- **index()** (3 connections) — `tests/test_ws_router.py`
- **router_ws_custom_error()** (3 connections) — `tests/test_ws_router.py`
- **routerindex()** (3 connections) — `tests/test_ws_router.py`
- **routerprefixindex()** (3 connections) — `tests/test_ws_router.py`
- **websocket_middleware()** (3 connections) — `tests/test_ws_router.py`
- **call_next()** (3 connections) — `tests/test_ws_router.py`
- **websocket_route** (3 connections)
- **router_native_prefix_ws()** (2 connections) — `tests/test_ws_router.py`
- **router_ws_decorator_depends()** (2 connections) — `tests/test_ws_router.py`
- **router_ws_depends_err()** (2 connections) — `tests/test_ws_router.py`
- **router_ws_depends_validate()** (2 connections) — `tests/test_ws_router.py`
- **routerindex2()** (2 connections) — `tests/test_ws_router.py`
- **routerindexparams()** (2 connections) — `tests/test_ws_router.py`
- **errorhandler()** (2 connections) — `tests/test_ws_router.py`
- **catcher()** (2 connections) — `tests/test_ws_router.py`
- **test_wrong_uri()** (2 connections) — `tests/test_ws_router.py`
- **middleware_constructor()** (2 connections) — `tests/test_ws_router.py`
- **wrapped_app()** (2 connections) — `tests/test_ws_router.py`
- *... and 20 more nodes in this community*

## Relationships

- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (4 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Main Config Settings Subsystem](Main_Config_Settings_Subsystem.md) (1 shared connections)
- [Dependency Injection & User Services](Dependency_Injection_&_User_Services.md) (1 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (1 shared connections)
- [Form Data & File Uploads](Form_Data_&_File_Uploads.md) (1 shared connections)

## Source Files

- `fastapi/middleware/__init__.py`
- `tests/test_ws_router.py`

## Audit Trail

- EXTRACTED: 65 (92%)
- INFERRED: 6 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*