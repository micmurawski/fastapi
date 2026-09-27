# Sse Format Event Subsystem

> 8 nodes

## Key Concepts

- **format_sse_event()** (10 connections) — `fastapi/sse.py`
- **test_format_sse_event_splitlines_behavior_in_data()** (3 connections) — `tests/test_sse.py`
- **test_server_sent_event_single_line_fields_reject_newlines()** (3 connections) — `tests/test_sse.py`
- **_split_sse_lines()** (2 connections) — `fastapi/sse.py`
- **test_format_sse_event_splitlines_behavior_in_comment()** (2 connections) — `tests/test_sse.py`
- **parametrize** (2 connections)
- **Doc** (1 connections)
- **Build SSE wire-format bytes from **pre-serialized** data. The result always…** (1 connections) — `fastapi/sse.py`

## Relationships

- [Sse With Router Subsystem](Sse_With_Router_Subsystem.md) (4 shared connections)
- [CORS & Custom Middleware](CORS_&_Custom_Middleware.md) (2 shared connections)
- [Models Callable Gen Subsystem](Models_Callable_Gen_Subsystem.md) (1 shared connections)
- [Form Data & File Uploads](Form_Data_&_File_Uploads.md) (1 shared connections)
- [Background Tasks & Lifespan](Background_Tasks_&_Lifespan.md) (1 shared connections)
- [Sse Data Server Subsystem](Sse_Data_Server_Subsystem.md) (1 shared connections)

## Source Files

- `fastapi/sse.py`
- `tests/test_sse.py`

## Audit Trail

- EXTRACTED: 16 (94%)
- INFERRED: 1 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*