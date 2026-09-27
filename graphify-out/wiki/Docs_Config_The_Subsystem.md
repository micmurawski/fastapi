# Docs Config The Subsystem

> 7 nodes

## Key Concepts

- **update_languages()** (7 connections) — `scripts/docs.py`
- **get_updated_config_content()** (6 connections) — `scripts/docs.py`
- **get_en_config()** (4 connections) — `scripts/docs.py`
- **new_lang()** (4 connections) — `scripts/docs.py`
- **Any** (3 connections)
- **Generate a new docs translation directory for the language LANG.** (1 connections) — `scripts/docs.py`
- **Update the docs config Languages section including all the available languages.** (1 connections) — `scripts/docs.py`

## Relationships

- [Docs Build Lang Subsystem](Docs_Build_Lang_Subsystem.md) (7 shared connections)
- [Docs Src Files Subsystem](Docs_Src_Files_Subsystem.md) (3 shared connections)

## Source Files

- `scripts/docs.py`

## Audit Trail

- EXTRACTED: 18 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*