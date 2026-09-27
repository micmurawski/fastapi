# Openapi Utils Dependency Subsystem

> 13 nodes

## Key Concepts

- **create_openapi_app()** (9 connections) — `tests/benchmarks/utils.py`
- **benchmarks/utils.py** (9 connections) — `tests/benchmarks/utils.py`
- **generate_openapi()** (7 connections) — `tests/benchmarks/utils.py`
- **benchmarks/test_openapi.py** (6 connections) — `tests/benchmarks/test_openapi.py`
- **memory_benchmarks/test_openapi.py** (6 connections) — `tests/memory_benchmarks/test_openapi.py`
- **test_openapi_dependency_graph()** (4 connections) — `tests/benchmarks/test_openapi.py`
- **test_openapi_dependency_graph()** (4 connections) — `tests/memory_benchmarks/test_openapi.py`
- **create_dependency()** (2 connections) — `tests/benchmarks/utils.py`
- **dependency()** (1 connections) — `tests/benchmarks/utils.py`
- **endpoint()** (1 connections) — `tests/benchmarks/utils.py`
- **timeout** (1 connections)
- **Any** (1 connections)
- **timeout** (1 connections)

## Relationships

- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (5 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (4 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [CORS & Custom Middleware](CORS_&_Custom_Middleware.md) (1 shared connections)

## Source Files

- `tests/benchmarks/test_openapi.py`
- `tests/benchmarks/utils.py`
- `tests/memory_benchmarks/test_openapi.py`

## Audit Trail

- EXTRACTED: 28 (88%)
- INFERRED: 4 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*