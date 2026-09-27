# Release Prepare Version Subsystem

> 22 nodes

## Key Concepts

- **prepare()** (17 connections) — `scripts/prepare_release.py`
- **prepare_release.py** (16 connections) — `scripts/prepare_release.py`
- **release_notes()** (12 connections) — `scripts/prepare_release.py`
- **current_version()** (11 connections) — `scripts/prepare_release.py`
- **update_version_file()** (8 connections) — `scripts/prepare_release.py`
- **bump_version()** (6 connections) — `scripts/prepare_release.py`
- **get_current_version()** (6 connections) — `scripts/prepare_release.py`
- **parse_version()** (3 connections) — `scripts/prepare_release.py`
- **dir_okay** (3 connections)
- **exists** (3 connections)
- **file_okay** (3 connections)
- **readable** (3 connections)
- **command** (3 connections)
- **envvar** (3 connections)
- **help** (3 connections)
- **Option** (3 connections)
- **test_update_version_file()** (2 connections) — `tests/test_prepare_release.py`
- **test_update_version_file_requires_newer_version()** (2 connections) — `tests/test_prepare_release.py`
- **BumpType** (2 connections)
- **Argument** (1 connections)
- **writable** (1 connections)
- **Prepare a release by updating the package version and release notes.** (1 connections) — `scripts/prepare_release.py`

## Relationships

- [Release Prepare Notes Subsystem](Release_Prepare_Notes_Subsystem.md) (9 shared connections)
- [Path Operations & Common Dependencies](Path_Operations_&_Common_Dependencies.md) (5 shared connections)
- [Bumptype Parametrize Bump Subsystem](Bumptype_Parametrize_Bump_Subsystem.md) (1 shared connections)
- [Sub-Applications & Mounting](Sub-Applications_&_Mounting.md) (1 shared connections)
- [Docs Build Lang Subsystem](Docs_Build_Lang_Subsystem.md) (1 shared connections)
- [Tutorial001 Read Tutorial008 Subsystem](Tutorial001_Read_Tutorial008_Subsystem.md) (1 shared connections)
- [Test Client & Endpoint Validation](Test_Client_&_Endpoint_Validation.md) (1 shared connections)
- [Annotated Pydantic Schema Validation](Annotated_Pydantic_Schema_Validation.md) (1 shared connections)

## Source Files

- `scripts/prepare_release.py`
- `tests/test_prepare_release.py`

## Audit Trail

- EXTRACTED: 66 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*