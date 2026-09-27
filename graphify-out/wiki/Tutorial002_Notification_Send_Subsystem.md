# Tutorial002 Notification Send Subsystem

> 12 nodes

## Key Concepts

- **BackgroundTasks** (24 connections) — `fastapi/background.py`
- **background_tasks/tutorial002_an_py310.py** (8 connections) — `docs_src/background_tasks/tutorial002_an_py310.py`
- **background_tasks/tutorial002_py310.py** (7 connections) — `docs_src/background_tasks/tutorial002_py310.py`
- **send_notification()** (6 connections) — `docs_src/background_tasks/tutorial002_an_py310.py`
- **send_notification()** (4 connections) — `docs_src/background_tasks/tutorial001_py310.py`
- **get_query()** (4 connections) — `docs_src/background_tasks/tutorial002_an_py310.py`
- **send_notification()** (4 connections) — `docs_src/background_tasks/tutorial002_py310.py`
- **write_log()** (3 connections) — `docs_src/background_tasks/tutorial002_an_py310.py`
- **get_query()** (3 connections) — `docs_src/background_tasks/tutorial002_py310.py`
- **write_log()** (3 connections) — `docs_src/background_tasks/tutorial002_py310.py`
- **write_notification()** (2 connections) — `docs_src/background_tasks/tutorial001_py310.py`
- **A collection of background tasks that will be called after a response has been…** (1 connections) — `fastapi/background.py`

## Relationships

- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (8 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (6 shared connections)
- [OpenAPI Utilities & Schema Compatibility](OpenAPI_Utilities_&_Schema_Compatibility.md) (3 shared connections)
- [Nested Models & Content Types](Nested_Models_&_Content_Types.md) (3 shared connections)
- [Dependency Contextmanager Context Subsystem](Dependency_Contextmanager_Context_Subsystem.md) (2 shared connections)
- [Models Callable Gen Subsystem](Models_Callable_Gen_Subsystem.md) (1 shared connections)
- [Dependency Contextmanager Async Subsystem](Dependency_Contextmanager_Async_Subsystem.md) (1 shared connections)
- [Background Add The Subsystem](Background_Add_The_Subsystem.md) (1 shared connections)
- [Background Tasks & Lifespan](Background_Tasks_&_Lifespan.md) (1 shared connections)
- [Response Models & Status Codes](Response_Models_&_Status_Codes.md) (1 shared connections)

## Source Files

- `docs_src/background_tasks/tutorial001_py310.py`
- `docs_src/background_tasks/tutorial002_an_py310.py`
- `docs_src/background_tasks/tutorial002_py310.py`
- `fastapi/background.py`

## Audit Trail

- EXTRACTED: 40 (83%)
- INFERRED: 8 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*