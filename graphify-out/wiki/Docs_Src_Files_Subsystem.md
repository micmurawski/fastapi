# Docs Src Files Subsystem

> 18 nodes

## Key Concepts

- **command** (18 connections)
- **render_banner_sponsors()** (6 connections) — `scripts/docs.py`
- **generate_docs_src_versions()** (4 connections) — `scripts/docs.py`
- **generate_docs_src_versions_for_file()** (4 connections) — `scripts/docs.py`
- **live()** (4 connections) — `scripts/docs.py`
- **copy_py39_to_py310()** (3 connections) — `scripts/docs.py`
- **get_banner_sponsors()** (3 connections) — `scripts/docs.py`
- **remove_unused_docs_src()** (3 connections) — `scripts/docs.py`
- **render_banner_sponsors_partial()** (3 connections) — `scripts/docs.py`
- **serve()** (3 connections) — `scripts/docs.py`
- **update_docs_includes_py39_to_py310()** (3 connections) — `scripts/docs.py`
- **A quick server to preview a built site with translations. For development,…** (1 connections) — `scripts/docs.py`
- **Serve the English docs with livereload from the source files.** (1 connections) — `scripts/docs.py`
- **Render the sponsor banner partial from sponsors.yml.** (1 connections) — `scripts/docs.py`
- **Generate Python version-specific files for all .py files in docs_src.** (1 connections) — `scripts/docs.py`
- **For each docs_src file/directory with a _py39 label that has no _py310…** (1 connections) — `scripts/docs.py`
- **Update .md files in docs/en/ to replace _py39 includes with _py310 versions.…** (1 connections) — `scripts/docs.py`
- **Delete .py files in docs_src that are not included in any .md file under docs/.** (1 connections) — `scripts/docs.py`

## Relationships

- [Docs Build Lang Subsystem](Docs_Build_Lang_Subsystem.md) (16 shared connections)
- [Docs Config The Subsystem](Docs_Config_The_Subsystem.md) (3 shared connections)
- [Docs Add Permalinks Subsystem](Docs_Add_Permalinks_Subsystem.md) (3 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (1 shared connections)

## Source Files

- `scripts/docs.py`

## Audit Trail

- EXTRACTED: 42 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*