# Cache Dependency Counter Subsystem

> 12 nodes

## Key Concepts

- **test_dependency_cache.py** (15 connections) — `tests/test_dependency_cache.py`
- **get** (4 connections)
- **get_counter()** (2 connections) — `tests/test_dependency_cache.py`
- **get_scope_counter()** (2 connections) — `tests/test_dependency_cache.py`
- **get_sub_counter()** (2 connections) — `tests/test_dependency_cache.py`
- **get_sub_counter_no_cache()** (2 connections) — `tests/test_dependency_cache.py`
- **dep_counter()** (1 connections) — `tests/test_dependency_cache.py`
- **super_dep()** (1 connections) — `tests/test_dependency_cache.py`
- **test_normal_counter()** (1 connections) — `tests/test_dependency_cache.py`
- **test_security_cache()** (1 connections) — `tests/test_dependency_cache.py`
- **test_sub_counter()** (1 connections) — `tests/test_dependency_cache.py`
- **test_sub_counter_no_cache()** (1 connections) — `tests/test_dependency_cache.py`

## Relationships

- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (2 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (1 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (1 shared connections)
- [HTTP Basic & OAuth2 Security](HTTP_Basic_&_OAuth2_Security.md) (1 shared connections)

## Source Files

- `tests/test_dependency_cache.py`

## Audit Trail

- EXTRACTED: 19 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*