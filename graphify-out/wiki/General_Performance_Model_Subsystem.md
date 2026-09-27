# General Performance Model Subsystem

> 57 nodes

## Key Concepts

- **test_general_performance.py** (60 connections) — `tests/benchmarks/test_general_performance.py`
- **TestClient** (23 connections)
- **_bench_get()** (19 connections) — `tests/benchmarks/test_general_performance.py`
- **get** (16 connections)
- **dep_b()** (11 connections) — `tests/benchmarks/test_general_performance.py`
- **_bench_post_json()** (9 connections) — `tests/benchmarks/test_general_performance.py`
- **_expected_large_payload_json_bytes()** (9 connections) — `tests/benchmarks/test_general_performance.py`
- **ItemOut** (8 connections) — `tests/benchmarks/test_general_performance.py`
- **LargeOut** (6 connections) — `tests/benchmarks/test_general_performance.py`
- **async_validated()** (6 connections) — `tests/benchmarks/test_general_performance.py`
- **sync_validated()** (6 connections) — `tests/benchmarks/test_general_performance.py`
- **async_model_no_response_model()** (5 connections) — `tests/benchmarks/test_general_performance.py`
- **async_model_with_response_model()** (5 connections) — `tests/benchmarks/test_general_performance.py`
- **sync_model_no_response_model()** (5 connections) — `tests/benchmarks/test_general_performance.py`
- **sync_model_with_response_model()** (5 connections) — `tests/benchmarks/test_general_performance.py`
- **ItemIn** (4 connections) — `tests/benchmarks/test_general_performance.py`
- **LargeIn** (4 connections) — `tests/benchmarks/test_general_performance.py`
- **async_dict_with_response_model()** (4 connections) — `tests/benchmarks/test_general_performance.py`
- **sync_dict_with_response_model()** (4 connections) — `tests/benchmarks/test_general_performance.py`
- **test_async_return_large_dict_with_response_model()** (4 connections) — `tests/benchmarks/test_general_performance.py`
- **test_async_return_large_dict_without_response_model()** (4 connections) — `tests/benchmarks/test_general_performance.py`
- **test_async_return_large_model_with_response_model()** (4 connections) — `tests/benchmarks/test_general_performance.py`
- **test_async_return_large_model_without_response_model()** (4 connections) — `tests/benchmarks/test_general_performance.py`
- **test_sync_return_large_dict_with_response_model()** (4 connections) — `tests/benchmarks/test_general_performance.py`
- **test_sync_return_large_dict_without_response_model()** (4 connections) — `tests/benchmarks/test_general_performance.py`
- *... and 32 more nodes in this community*

## Relationships

- [Response Models & Status Codes](Response_Models_&_Status_Codes.md) (11 shared connections)
- [Nested Models & Content Types](Nested_Models_&_Content_Types.md) (4 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (3 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (3 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (2 shared connections)
- [Json Type Stream Subsystem](Json_Type_Stream_Subsystem.md) (1 shared connections)
- [CORS & Custom Middleware](CORS_&_Custom_Middleware.md) (1 shared connections)

## Source Files

- `tests/benchmarks/test_general_performance.py`

## Audit Trail

- EXTRACTED: 170 (98%)
- INFERRED: 3 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*