# Sse With Router Subsystem

> 25 nodes

## Key Concepts

- **test_sse.py** (59 connections) — `tests/test_sse.py`
- **TestClient** (14 connections)
- **test_no_keepalive_when_fast()** (3 connections) — `tests/test_sse.py`
- **test_post_method_sse()** (3 connections) — `tests/test_sse.py`
- **test_raw_data_sent_without_json_encoding()** (3 connections) — `tests/test_sse.py`
- **test_sse_router_typed_openapi_schema()** (3 connections) — `tests/test_sse.py`
- **test_string_data_json_encoded()** (3 connections) — `tests/test_sse.py`
- **test_async_generator_no_annotation()** (2 connections) — `tests/test_sse.py`
- **test_async_generator_with_model()** (2 connections) — `tests/test_sse.py`
- **test_dict_items()** (2 connections) — `tests/test_sse.py`
- **test_mixed_plain_and_sse_events()** (2 connections) — `tests/test_sse.py`
- **test_sse_events_with_fields()** (2 connections) — `tests/test_sse.py`
- **test_sse_on_router_included_in_app()** (2 connections) — `tests/test_sse.py`
- **test_sse_router_typed_stream()** (2 connections) — `tests/test_sse.py`
- **test_sync_generator_no_annotation()** (2 connections) — `tests/test_sse.py`
- **test_sync_generator_with_model()** (2 connections) — `tests/test_sse.py`
- **test_default_response_class_on_app_openapi_schema()** (1 connections) — `tests/test_sse.py`
- **test_default_response_class_on_app_stream()** (1 connections) — `tests/test_sse.py`
- **test_default_response_class_on_parent_router_openapi_schema()** (1 connections) — `tests/test_sse.py`
- **test_default_response_class_on_parent_router_stream()** (1 connections) — `tests/test_sse.py`
- **SSE should work with POST (needed for MCP compatibility).** (1 connections) — `tests/test_sse.py`
- **Strings are always JSON-encoded (quoted).** (1 connections) — `tests/test_sse.py`
- **raw_data is sent as-is, not JSON-encoded.** (1 connections) — `tests/test_sse.py`
- **Typed SSE endpoint on a router should preserve itemSchema with contentSchema.** (1 connections) — `tests/test_sse.py`
- **No keepalive comment when items arrive quickly.** (1 connections) — `tests/test_sse.py`

## Relationships

- [Sse Items Stream Subsystem](Sse_Items_Stream_Subsystem.md) (17 shared connections)
- [Sse Data Server Subsystem](Sse_Data_Server_Subsystem.md) (5 shared connections)
- [Sse Format Event Subsystem](Sse_Format_Event_Subsystem.md) (4 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (2 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [CORS & Custom Middleware](CORS_&_Custom_Middleware.md) (2 shared connections)
- [Keepalive Ping Sse Subsystem](Keepalive_Ping_Sse_Subsystem.md) (2 shared connections)
- [Tutorial003b Read Users Subsystem](Tutorial003b_Read_Users_Subsystem.md) (1 shared connections)
- [Tutorial013 Tutorial014 Tutorial003 Subsystem](Tutorial013_Tutorial014_Tutorial003_Subsystem.md) (1 shared connections)
- [Background Tasks & Lifespan](Background_Tasks_&_Lifespan.md) (1 shared connections)
- [Static Files & Item Routing](Static_Files_&_Item_Routing.md) (1 shared connections)

## Source Files

- `tests/test_sse.py`

## Audit Trail

- EXTRACTED: 78 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*