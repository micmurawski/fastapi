# Sse Data Server Subsystem

> 14 nodes

## Key Concepts

- **ServerSentEvent** (25 connections) — `fastapi/sse.py`
- **stream_items()** (3 connections) — `docs_src/server_sent_events/tutorial002_py310.py`
- **stream_logs()** (3 connections) — `docs_src/server_sent_events/tutorial003_py310.py`
- **test_data_and_raw_data_mutually_exclusive()** (3 connections) — `tests/test_sse.py`
- **._check_data_exclusive()** (2 connections) — `fastapi/sse.py`
- **test_server_sent_event_float_retry_rejected()** (2 connections) — `tests/test_sse.py`
- **test_server_sent_event_negative_retry_rejected()** (2 connections) — `tests/test_sse.py`
- **test_server_sent_event_null_id_rejected()** (2 connections) — `tests/test_sse.py`
- **get** (1 connections)
- **get** (1 connections)
- **BaseModel** (1 connections)
- **model_validator** (1 connections)
- **Represents a single Server-Sent Event. When `yield`ed from a *path operation…** (1 connections) — `fastapi/sse.py`
- **Cannot set both data and raw_data.** (1 connections) — `tests/test_sse.py`

## Relationships

- [CORS & Custom Middleware](CORS_&_Custom_Middleware.md) (8 shared connections)
- [Sse With Router Subsystem](Sse_With_Router_Subsystem.md) (5 shared connections)
- [Sse Items Stream Subsystem](Sse_Items_Stream_Subsystem.md) (4 shared connections)
- [Background Tasks & Lifespan](Background_Tasks_&_Lifespan.md) (1 shared connections)
- [Nested Models & Content Types](Nested_Models_&_Content_Types.md) (1 shared connections)
- [Models Callable Gen Subsystem](Models_Callable_Gen_Subsystem.md) (1 shared connections)
- [OpenAPI Utilities & Schema Compatibility](OpenAPI_Utilities_&_Schema_Compatibility.md) (1 shared connections)
- [Sse Format Event Subsystem](Sse_Format_Event_Subsystem.md) (1 shared connections)

## Source Files

- `docs_src/server_sent_events/tutorial002_py310.py`
- `docs_src/server_sent_events/tutorial003_py310.py`
- `fastapi/sse.py`
- `tests/test_sse.py`

## Audit Trail

- EXTRACTED: 24 (69%)
- INFERRED: 11 (31%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*