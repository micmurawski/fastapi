# Middleware Custom Exception Subsystem

> 7 nodes

## Key Concepts

- **ContentSizeLimitMiddleware** (6 connections) — `tests/test_custom_middleware_exception.py`
- **.receive_wrapper()** (3 connections) — `tests/test_custom_middleware_exception.py`
- **.__call__()** (2 connections) — `tests/test_custom_middleware_exception.py`
- **.__init__()** (2 connections) — `tests/test_custom_middleware_exception.py`
- **inner()** (2 connections) — `tests/test_custom_middleware_exception.py`
- **ASGIApp** (1 connections)
- **Content size limiting middleware for ASGI applications Args: app (ASGI…** (1 connections) — `tests/test_custom_middleware_exception.py`

## Relationships

- [Dependency Injection & User Services](Dependency_Injection_&_User_Services.md) (2 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)

## Source Files

- `tests/test_custom_middleware_exception.py`

## Audit Trail

- EXTRACTED: 8 (80%)
- INFERRED: 2 (20%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*