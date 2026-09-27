# FastAPI

> God node · 830 connections · `fastapi/applications.py`

**Community:** [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md)

## Connections by Relation

### calls
- create_app() `EXTRACTED`
- test_startup_shutdown_handlers_as_parameters() `EXTRACTED`
- get_app_client() `EXTRACTED`
- test_router_events() `EXTRACTED`
- test_frontend_dependency_restores_existing_dependency_stacks() `EXTRACTED`
- test_router_include_context_matches_flattened_include_metadata() `EXTRACTED`
- create_openapi_app() `EXTRACTED`
- test_apirouter_frontend_dependencies_protect_prefixed_frontend() `EXTRACTED`
- test_frontend_dependency_overrides_apply() `EXTRACTED`
- test_callback_override_generate_unique_id() `EXTRACTED`
- test_subrouter_top_level_include_overrides_generate_unique_id() `EXTRACTED`
- get_client() `EXTRACTED`
- get_client() `EXTRACTED`
- test_router_nested_lifespan_state() `EXTRACTED`
- test_effective_body_fields_from_app_router_include_and_route_match_openapi() `EXTRACTED`
- test_included_unknown_route_is_ignored_and_can_return_default_404() `EXTRACTED`
- client_fixture() `EXTRACTED`
- test_app_middleware_still_runs_for_frontend_dependencies() `EXTRACTED`
- test_frontend_dependencies_do_not_run_when_api_route_wins() `EXTRACTED`
- test_frontend_static_files_lookup_errors() `EXTRACTED`
- *…and 182 more `calls` connection(s) not listed (lowest-degree first to go)*

### contains
- applications.py `EXTRACTED`

### imports
- fastapi/__init__.py `EXTRACTED`
- test_frontend.py `EXTRACTED`
- test_response_model_as_return_annotation.py `EXTRACTED`
- test_router_include_context.py `EXTRACTED`
- test_dependency_wrapped.py `EXTRACTED`
- test_general_performance.py `EXTRACTED`
- test_dependency_contextmanager.py `EXTRACTED`
- test_sse.py `EXTRACTED`
- tests/main.py `EXTRACTED`
- test_body/test_optional_list.py `EXTRACTED`
- test_body/test_optional_str.py `EXTRACTED`
- test_include_router_defaults_overrides.py `EXTRACTED`
- test_dependency_overrides.py `EXTRACTED`
- test_body/test_list.py `EXTRACTED`
- test_body/test_required_str.py `EXTRACTED`
- test_form/test_list.py `EXTRACTED`
- test_form/test_required_str.py `EXTRACTED`
- test_default_response_class.py `EXTRACTED`
- test_dependency_yield_scope.py `EXTRACTED`
- test_cookie/test_required_str.py `EXTRACTED`
- *…and 549 more `imports` connection(s) not listed (lowest-degree first to go)*

### inherits
- Starlette `EXTRACTED`

### method
- .__init__() `EXTRACTED`
- .get() `EXTRACTED`
- .put() `EXTRACTED`
- .post() `EXTRACTED`
- .delete() `EXTRACTED`
- .options() `EXTRACTED`
- .head() `EXTRACTED`
- .patch() `EXTRACTED`
- .trace() `EXTRACTED`
- .include_router() `EXTRACTED`
- .api_route() `EXTRACTED`
- .add_api_route() `EXTRACTED`
- .setup() `EXTRACTED`
- .websocket() `EXTRACTED`
- .exception_handler() `EXTRACTED`
- .openapi() `EXTRACTED`
- .__call__() `EXTRACTED`
- .middleware() `EXTRACTED`
- .on_event() `EXTRACTED`
- .frontend() `EXTRACTED`
- *…and 3 more `method` connection(s) not listed (lowest-degree first to go)*

### rationale_for
- `FastAPI` app class, the main entrypoint to use FastAPI. Read more in the… `EXTRACTED`

### references
- generate_openapi() `EXTRACTED`
- _run_asgi_and_cancel() `EXTRACTED`
- lifespan() `EXTRACTED`
- client_fixture() `EXTRACTED`
- client_fixture() `EXTRACTED`
- test_events() `EXTRACTED`
- test_openapi_schema() `EXTRACTED`
- get_client() `EXTRACTED`
- get_client() `EXTRACTED`
- get_client() `EXTRACTED`
- lifespan() `EXTRACTED`
- test_events() `EXTRACTED`
- test_openapi_schema() `EXTRACTED`
- test_get_root() `EXTRACTED`
- test_post_files() `EXTRACTED`
- test_post_upload_file() `EXTRACTED`
- test_get_root() `EXTRACTED`
- test_post_files() `EXTRACTED`
- test_post_upload_file() `EXTRACTED`
- test_post_file_no_token() `EXTRACTED`
- *…and 7 more `references` connection(s) not listed (lowest-degree first to go)*

### uses
- [HTTPException](HTTPException.md) `INFERRED`
- [Depends](Depends_2.md) `INFERRED`
- RequestValidationError `INFERRED`
- DefaultPlaceholder `INFERRED`
- WebSocketRequestValidationError `INFERRED`
- AsyncExitStackMiddleware `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*