# Stream Cancellation Async Subsystem

> 5 nodes

## Key Concepts

- **stream_jsonl()** (3 connections) — `tests/test_stream_cancellation.py`
- **stream_raw()** (3 connections) — `tests/test_stream_cancellation.py`
- **get** (2 connections)
- **Async generator with no internal await - would hang without checkpoint.** (1 connections) — `tests/test_stream_cancellation.py`
- **JSONL async generator with no internal await.** (1 connections) — `tests/test_stream_cancellation.py`

## Relationships

- [Static Files & Item Routing](Static_Files_&_Item_Routing.md) (2 shared connections)

## Source Files

- `tests/test_stream_cancellation.py`

## Audit Trail

- EXTRACTED: 6 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*