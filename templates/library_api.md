# <!replace --- The display name of the primary domain library, e.g. "IPFX", "scanpy", "MNE-Python", "Biopython" --- or add a link---> API Reference

See [computational-neuro library API reference](docs/domains/computational-neuro/library-api.md) for Brian2, SSM, and SBI.

> **Source**: <!replace --- URL to the library's source repository --- or add a link--->

Brian2: https://github.com/brian-team/brian2 | SSM: https://github.com/slinderman/ssm | SBI: https://github.com/sbi-dev/sbi
> **Docs**: <!replace --- URL to the library's official documentation --- or add a link--->

Brian2: https://brian2.readthedocs.io/ | SBI: https://sbi-dev.github.io/sbi/
> **Purpose**: This document provides the correct API surface for the
> primary domain library that your agent wraps or exposes. It is the
> authoritative reference for parameter names, types, defaults, and return
> values.

---

## Table of Contents

<!replace --- A numbered list linking to each major section --- or add a link--->

See [computational-neuro library table of contents](docs/domains/computational-neuro/library-api.md) for full reference.

1. [Core Classes](#1-core-classes)
2. [Key Functions](#2-key-functions)
3. [Common Pitfalls](#3-common-pitfalls)
4. [Quick-Start Recipes](#4-quick-start-recipes)

---

## 1. Core Classes

<!replace --- Document the main classes the agent will use. For each class, include: import statement, constructor signature with parameter descriptions, and key methods with their signatures and return types --- or add a link--->

See [computational-neuro core classes](docs/domains/computational-neuro/library-api.md#brian2) for Brian2, SSM, and SBI class references.

*Document your primary library's core classes here.*

---

## 2. Key Functions

<!replace --- Document standalone functions the agent will call. For each function: signature, parameter table, return value description --- or add a link--->

See [computational-neuro key functions](docs/domains/computational-neuro/library-api.md#brian2) for function references.

*Document your primary library's key functions here.*

---

## 3. Common Pitfalls

<!replace --- List gotchas, common mistakes, and parameter confusion that the agent should avoid --- or add a link--->

See [computational-neuro common pitfalls](docs/domains/computational-neuro/library-api.md#brian2-1) for per-library pitfall lists.

*List common mistakes and gotchas specific to this library.*

---

## 4. Quick-Start Recipes

<!replace --- Copy-paste code snippets for the most common tasks. Each recipe should be self-contained with imports, data loading, analysis, and result access --- or add a link--->

See [computational-neuro recipes](docs/domains/computational-neuro/library-api.md#quick-start-recipe-hh-neuron) for copy-paste code examples.

*Provide copy-paste recipes for common analysis tasks.*

---

## Notes

- This document should be kept in sync with the library version your
  agent targets.
- When the library is updated, review parameter names, defaults, and
  return value schemas for breaking changes.
- If the library has multiple major classes or modules, consider splitting
  this into multiple reference files.
