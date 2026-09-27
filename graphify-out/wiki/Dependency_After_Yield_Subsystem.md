# Dependency After Yield Subsystem

> 27 nodes

## Key Concepts

- **test_dependency_after_yield_streaming.py** (25 connections) — `tests/test_dependency_after_yield_streaming.py`
- **Any** (7 connections)
- **get_broken_session_stream()** (5 connections) — `tests/test_dependency_after_yield_streaming.py`
- **get_stream_session()** (5 connections) — `tests/test_dependency_after_yield_streaming.py`
- **get_stream_simple()** (5 connections) — `tests/test_dependency_after_yield_streaming.py`
- **get** (5 connections)
- **Session** (4 connections) — `tests/test_dependency_after_yield_streaming.py`
- **acquire_session()** (4 connections) — `tests/test_dependency_after_yield_streaming.py`
- **get_broken_session_data()** (4 connections) — `tests/test_dependency_after_yield_streaming.py`
- **get_data()** (4 connections) — `tests/test_dependency_after_yield_streaming.py`
- **broken_dep_session()** (3 connections) — `tests/test_dependency_after_yield_streaming.py`
- **dep_session()** (3 connections) — `tests/test_dependency_after_yield_streaming.py`
- **SessionDep** (3 connections)
- **test_broken_session_stream_no_raise()** (2 connections) — `tests/test_dependency_after_yield_streaming.py`
- **BrokenSessionDep** (2 connections)
- **iter_data()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- **iter_data()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- **iter_data()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- **.__init__()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- **.__iter__()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- **test_broken_session_data()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- **test_broken_session_data_no_raise()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- **test_broken_session_stream_raise()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- **test_regular_no_stream()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- **test_stream_session()** (1 connections) — `tests/test_dependency_after_yield_streaming.py`
- *... and 2 more nodes in this community*

## Relationships

- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (2 shared connections)
- [CORS & Custom Middleware](CORS_&_Custom_Middleware.md) (2 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [Static Files & Item Routing](Static_Files_&_Item_Routing.md) (1 shared connections)

## Source Files

- `tests/test_dependency_after_yield_streaming.py`

## Audit Trail

- EXTRACTED: 51 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*