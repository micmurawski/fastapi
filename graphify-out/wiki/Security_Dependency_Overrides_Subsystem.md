# Security Dependency Overrides Subsystem

> 21 nodes

## Key Concepts

- **SecurityScopes** (21 connections) — `fastapi/security/oauth2.py`
- **test_dependency_security_overrides.py** (14 connections) — `tests/test_dependency_security_overrides.py`
- **test_security_scopes_dont_propagate.py** (11 connections) — `tests/test_security_scopes_dont_propagate.py`
- **dep3()** (6 connections) — `tests/test_security_scopes_dont_propagate.py`
- **get_scopes()** (6 connections) — `tests/test_security_scopes_dont_propagate.py`
- **get_user_override()** (3 connections) — `tests/test_dependency_security_overrides.py`
- **security1()** (3 connections) — `tests/test_security_scopes_dont_propagate.py`
- **security2()** (3 connections) — `tests/test_security_scopes_dont_propagate.py`
- **get_data_override()** (2 connections) — `tests/test_dependency_security_overrides.py`
- **get_user()** (2 connections) — `tests/test_dependency_security_overrides.py`
- **read_user()** (2 connections) — `tests/test_dependency_security_overrides.py`
- **test_override_data()** (2 connections) — `tests/test_dependency_security_overrides.py`
- **test_override_security()** (2 connections) — `tests/test_dependency_security_overrides.py`
- **scopes** (2 connections)
- **get_data()** (1 connections) — `tests/test_dependency_security_overrides.py`
- **test_normal()** (1 connections) — `tests/test_dependency_security_overrides.py`
- **test_security_scopes_dont_propagate()** (1 connections) — `tests/test_security_scopes_dont_propagate.py`
- **get** (1 connections)
- **Any** (1 connections)
- **get** (1 connections)
- **This is a special class that you can define in a parameter in a dependency to…** (1 connections) — `fastapi/security/oauth2.py`

## Relationships

- [Tutorial005 User Token Subsystem](Tutorial005_User_Token_Subsystem.md) (6 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (4 shared connections)
- [OpenAPI Utilities & Schema Compatibility](OpenAPI_Utilities_&_Schema_Compatibility.md) (3 shared connections)
- [HTTP Basic & OAuth2 Security](HTTP_Basic_&_OAuth2_Security.md) (3 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (3 shared connections)
- [Dependency Paramless Scopes Subsystem](Dependency_Paramless_Scopes_Subsystem.md) (2 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (2 shared connections)
- [Models Callable Gen Subsystem](Models_Callable_Gen_Subsystem.md) (1 shared connections)
- [Oauth2 Models Base Subsystem](Oauth2_Models_Base_Subsystem.md) (1 shared connections)
- [Oauth2 Doc Pattern Subsystem](Oauth2_Doc_Pattern_Subsystem.md) (1 shared connections)

## Source Files

- `fastapi/security/oauth2.py`
- `tests/test_dependency_security_overrides.py`
- `tests/test_security_scopes_dont_propagate.py`

## Audit Trail

- EXTRACTED: 52 (93%)
- INFERRED: 4 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*