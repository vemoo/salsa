# Summary

- [About salsa](./about_salsa.md)

# How to use Salsa

- [Overview](./overview.md)
- [Tutorial: calc language](./tutorial.md)
  - [Basic structure](./tutorial/structure.md)
  - [Jars and databases](./tutorial/jar.md)
  - [Defining the database struct](./tutorial/db.md)
  - [Defining the IR: the various "salsa structs"](./tutorial/ir.md)
  - [Defining the parser: memoized functions and inputs](./tutorial/parser.md)
  - [Defining the parser: reporting errors](./tutorial/accumulators.md)
  - [Defining the parser: debug impls and testing](./tutorial/debug.md)
  - [Defining the checker](./tutorial/checker.md)
  - [Defining the interpreter](./tutorial/interpreter.md)
- [Reference](./reference.md)
  - [Algorithm](./reference/algorithm.md)
- [Common patterns](./common_patterns.md)
  - [Selection](./common_patterns/selection.md)
  - [On-demand (Lazy) inputs](./common_patterns/on_demand_inputs.md)
- [Tuning](./tuning.md)
- [Cycle handling](./cycles.md)
  - [Recovering via fallback](./cycles/fallback.md)

# How Salsa works internally

- [How Salsa works](./how_salsa_works.md)
- [Videos](./videos.md)
- [Plumbing](./plumbing.md)
  - [Jars and ingredients](./plumbing/jars_and_ingredients.md)
  - [Databases and runtime](./plumbing/database_and_runtime.md)
  - [Query operations](./plumbing/query_ops.md)
    - [maybe changed after](./plumbing/maybe_changed_after.md)
    - [Fetch](./plumbing/fetch.md)
    - [Derived queries flowchart](./plumbing/derived_flowchart.md)
    - [Cycle handling](./plumbing/cycles.md)
  - [Terminology](./plumbing/terminology.md)
    - [Backdate](./plumbing/terminology/backdate.md)
    - [Changed at](./plumbing/terminology/changed_at.md)
    - [Dependency](./plumbing/terminology/dependency.md)
    - [Derived query](./plumbing/terminology/derived_query.md)
    - [Durability](./plumbing/terminology/durability.md)
    - [Input query](./plumbing/terminology/input_query.md)
    - [Ingredient](./plumbing/terminology/ingredient.md)
    - [LRU](./plumbing/terminology/LRU.md)
    - [Memo](./plumbing/terminology/memo.md)
    - [Query](./plumbing/terminology/query.md)
    - [Query function](./plumbing/terminology/query_function.md)
    - [Revision](./plumbing/terminology/revision.md)
    - [Salsa item](./plumbing/terminology/salsa_item.md)
    - [Salsa struct](./plumbing/terminology/salsa_struct.md)
    - [Untracked dependency](./plumbing/terminology/untracked.md)
    - [Verified](./plumbing/terminology/verified.md)

# Salsa RFCs

- [RFCs](./rfcs.md)
  - [Template](./rfcs/template.md)
  - [RFC 0001: Query group traits](./rfcs/RFC0001-Query-Group-Traits.md)
  - [RFC 0002: Intern queries](./rfcs/RFC0002-Intern-Queries.md)
  - [RFC 0003: Query dependencies](./rfcs/RFC0003-Query-Dependencies.md)
  - [RFC 0004: LRU](./rfcs/RFC0004-LRU.md)
  - [RFC 0005: Durability](./rfcs/RFC0005-Durability.md)
  - [RFC 0006: Dynamic database](./rfcs/RFC0006-Dynamic-Databases.md)
  - [RFC 0007: Opinionated cancelation](./rfcs/RFC0007-Opinionated-Cancelation.md)
  - [RFC 0008: Remove garbage collection](./rfcs/RFC0008-Remove-Garbage-Collection.md)
  - [RFC 0009: Cycle recovery](./rfcs/RFC0009-Cycle-recovery.md)
  - [RFC 0010: Slot no more](./rfcs/RFC0010-Slot-no-more.md)

# Appendices

- [Meta: about the book itself](./meta.md)
