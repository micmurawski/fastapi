# Validation Error Context Subsystem

> 25 nodes

## Key Concepts

- **test_validation_error_context.py** (25 connections) — `tests/test_validation_error_context.py`
- **request_validation_handler()** (4 connections) — `tests/test_validation_error_context.py`
- **response_validation_handler()** (4 connections) — `tests/test_validation_error_context.py`
- **websocket_validation_handler()** (4 connections) — `tests/test_validation_error_context.py`
- **ExceptionCapture** (3 connections) — `tests/test_validation_error_context.py`
- **exception_handler** (3 connections)
- **get** (3 connections)
- **WebSocket** (3 connections)
- **Item** (2 connections) — `tests/test_validation_error_context.py`
- **get_item()** (2 connections) — `tests/test_validation_error_context.py`
- **get_sub_item()** (2 connections) — `tests/test_validation_error_context.py`
- **get_user()** (2 connections) — `tests/test_validation_error_context.py`
- **subapp_websocket_endpoint()** (2 connections) — `tests/test_validation_error_context.py`
- **test_validation_error_with_no_context()** (2 connections) — `tests/test_validation_error_context.py`
- **test_validation_error_with_only_path()** (2 connections) — `tests/test_validation_error_context.py`
- **websocket_endpoint()** (2 connections) — `tests/test_validation_error_context.py`
- **Request** (2 connections)
- **.capture()** (1 connections) — `tests/test_validation_error_context.py`
- **.__init__()** (1 connections) — `tests/test_validation_error_context.py`
- **test_request_validation_error_includes_endpoint_context()** (1 connections) — `tests/test_validation_error_context.py`
- **test_response_validation_error_includes_endpoint_context()** (1 connections) — `tests/test_validation_error_context.py`
- **test_subapp_request_validation_error_includes_endpoint_context()** (1 connections) — `tests/test_validation_error_context.py`
- **test_subapp_websocket_validation_error_includes_endpoint_context()** (1 connections) — `tests/test_validation_error_context.py`
- **test_websocket_validation_error_includes_endpoint_context()** (1 connections) — `tests/test_validation_error_context.py`
- **BaseModel** (1 connections)

## Relationships

- [Form Data & File Uploads](Form_Data_&_File_Uploads.md) (6 shared connections)
- [Response Model Annotation Subsystem](Response_Model_Annotation_Subsystem.md) (2 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)
- [Static Files & Item Routing](Static_Files_&_Item_Routing.md) (1 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (1 shared connections)

## Source Files

- `tests/test_validation_error_context.py`

## Audit Trail

- EXTRACTED: 41 (93%)
- INFERRED: 3 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*