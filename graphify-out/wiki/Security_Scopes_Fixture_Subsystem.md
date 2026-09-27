# Security Scopes Fixture Subsystem

> 10 nodes

## Key Concepts

- **test_security_scopes.py** (11 connections) — `tests/test_security_scopes.py`
- **app_fixture()** (5 connections) — `tests/test_security_scopes.py`
- **client_fixture()** (3 connections) — `tests/test_security_scopes.py`
- **fixture** (3 connections)
- **call_counter_fixture()** (2 connections) — `tests/test_security_scopes.py`
- **test_security_scopes_dependency_called_once()** (2 connections) — `tests/test_security_scopes.py`
- **endpoint()** (1 connections) — `tests/test_security_scopes.py`
- **get_db()** (1 connections) — `tests/test_security_scopes.py`
- **get_user()** (1 connections) — `tests/test_security_scopes.py`
- **TestClient** (1 connections)

## Relationships

- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (3 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (2 shared connections)
- [HTTP Basic & OAuth2 Security](HTTP_Basic_&_OAuth2_Security.md) (1 shared connections)

## Source Files

- `tests/test_security_scopes.py`

## Audit Trail

- EXTRACTED: 19 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*