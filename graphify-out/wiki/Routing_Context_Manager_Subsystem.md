# Routing Context Manager Subsystem

> 19 nodes

## Key Concepts

- **_DefaultLifespan** (7 connections) — `fastapi/routing.py`
- **_AsyncLiftContextManager** (6 connections) — `fastapi/routing.py`
- **_wrap_gen_lifespan_context()** (6 connections) — `fastapi/routing.py`
- **.__aexit__()** (3 connections) — `fastapi/routing.py`
- **.__init__()** (3 connections) — `fastapi/routing.py`
- **_T** (3 connections)
- **.__aenter__()** (2 connections) — `fastapi/routing.py`
- **.__call__()** (2 connections) — `fastapi/routing.py`
- **wrapper()** (2 connections) — `fastapi/routing.py`
- **.__aenter__()** (1 connections) — `fastapi/routing.py`
- **.__aexit__()** (1 connections) — `fastapi/routing.py`
- **.__init__()** (1 connections) — `fastapi/routing.py`
- **AbstractAsyncContextManager** (1 connections)
- **BaseException** (1 connections)
- **AbstractContextManager** (1 connections)
- **TracebackType** (1 connections)
- **Wraps a synchronous context manager to make it async. This is vendored from…** (1 connections) — `fastapi/routing.py`
- **Wrap a generator-based lifespan context into an async context manager. This is…** (1 connections) — `fastapi/routing.py`
- **Default lifespan context manager that runs on_startup and on_shutdown handlers.…** (1 connections) — `fastapi/routing.py`

## Relationships

- [Background Tasks & Lifespan](Background_Tasks_&_Lifespan.md) (3 shared connections)
- [Response Models & Status Codes](Response_Models_&_Status_Codes.md) (3 shared connections)

## Source Files

- `fastapi/routing.py`

## Audit Trail

- EXTRACTED: 24 (96%)
- INFERRED: 1 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*