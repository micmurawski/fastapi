# APIRouter

> God node · 146 connections · `fastapi/routing.py`

**Community:** [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md)

## Connections by Relation

### calls
- test_startup_shutdown_handlers_as_parameters() `EXTRACTED`
- test_router_events() `EXTRACTED`
- test_router_include_context_matches_flattened_include_metadata() `EXTRACTED`
- test_apirouter_frontend_dependencies_protect_prefixed_frontend() `EXTRACTED`
- test_callback_override_generate_unique_id() `EXTRACTED`
- test_subrouter_top_level_include_overrides_generate_unique_id() `EXTRACTED`
- test_router_nested_lifespan_state() `EXTRACTED`
- test_apirouter_handle_fallback_without_include_context() `EXTRACTED`
- test_effective_body_fields_from_app_router_include_and_route_match_openapi() `EXTRACTED`
- test_included_unknown_route_is_ignored_and_can_return_default_404() `EXTRACTED`
- test_frontend_dependencies_do_not_run_when_api_route_wins() `EXTRACTED`
- test_app_path_operation_overrides_generate_unique_id() `EXTRACTED`
- test_router_include_overrides_generate_unique_id() `EXTRACTED`
- test_router_path_operation_overrides_generate_unique_id() `EXTRACTED`
- test_merged_mixed_state_lifespans() `EXTRACTED`
- test_get_openapi_accepts_filtered_route_contexts_with_effective_paths() `EXTRACTED`
- test_include_router_frontend_dependencies_apply_in_nested_order() `EXTRACTED`
- test_only_selected_frontend_mount_dependencies_run() `EXTRACTED`
- test_router_overrides_generate_unique_id() `EXTRACTED`
- test_merged_no_return_lifespans_return_none() `EXTRACTED`
- *…and 49 more `calls` connection(s) not listed (lowest-degree first to go)*

### contains
- routing.py `EXTRACTED`

### imports
- fastapi/__init__.py `EXTRACTED`
- test_frontend.py `EXTRACTED`
- test_router_include_context.py `EXTRACTED`
- test_sse.py `EXTRACTED`
- test_include_router_defaults_overrides.py `EXTRACTED`
- test_dependency_overrides.py `EXTRACTED`
- test_default_response_class.py `EXTRACTED`
- test_dependency_yield_scope.py `EXTRACTED`
- test_ws_router.py `EXTRACTED`
- test_default_response_class_router.py `EXTRACTED`
- test_generate_unique_id_function.py `EXTRACTED`
- test_security_oauth2_authorization_code_bearer_scopes_openapi.py `EXTRACTED`
- test_router_events.py `EXTRACTED`
- test_infer_param_optionality.py `EXTRACTED`
- test_custom_route_class.py `EXTRACTED`
- test_additional_responses_router.py `EXTRACTED`
- test_annotated.py `EXTRACTED`
- test_strict_content_type_nested.py `EXTRACTED`
- test_stream_bare_type.py `EXTRACTED`
- test_sub_callbacks.py `EXTRACTED`
- *…and 19 more `imports` connection(s) not listed (lowest-degree first to go)*

### method
- .api_route() `EXTRACTED`
- .include_router() `EXTRACTED`
- .__init__() `EXTRACTED`
- .app() `EXTRACTED`
- .add_api_route() `EXTRACTED`
- .get() `EXTRACTED`
- .put() `EXTRACTED`
- .post() `EXTRACTED`
- .delete() `EXTRACTED`
- .options() `EXTRACTED`
- .head() `EXTRACTED`
- .patch() `EXTRACTED`
- .trace() `EXTRACTED`
- ._match_low_priority() `EXTRACTED`
- .frontend() `EXTRACTED`
- .add_route() `EXTRACTED`
- ._mark_routes_changed() `EXTRACTED`
- .handle() `EXTRACTED`
- .websocket() `EXTRACTED`
- .on_event() `EXTRACTED`
- *…and 12 more `method` connection(s) not listed (lowest-degree first to go)*

### rationale_for
- `APIRouter` class, used to group *path operations*, for example to structure an… `EXTRACTED`

### references
- .__init__() `EXTRACTED`
- .include_router() `EXTRACTED`

### uses
- FastAPIError `INFERRED`
- DefaultPlaceholder `INFERRED`

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*