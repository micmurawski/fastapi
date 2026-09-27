# Webhooks Security New Subsystem

> 6 nodes

## Key Concepts

- **new_subscription()** (7 connections) — `tests/test_webhooks_security.py`
- **Subscription** (4 connections) — `tests/test_webhooks_security.py`
- **test_dummy_webhook()** (3 connections) — `tests/test_webhooks_security.py`
- **bearer_scheme** (1 connections)
- **BaseModel** (1 connections)
- **When a new user subscribes to your service we'll send you a POST request with…** (1 connections) — `tests/test_webhooks_security.py`

## Relationships

- [HTTP Basic & OAuth2 Security](HTTP_Basic_&_OAuth2_Security.md) (3 shared connections)
- [Nested Models & Content Types](Nested_Models_&_Content_Types.md) (1 shared connections)
- [Tutorial005 User Token Subsystem](Tutorial005_User_Token_Subsystem.md) (1 shared connections)

## Source Files

- `tests/test_webhooks_security.py`

## Audit Trail

- EXTRACTED: 11 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*