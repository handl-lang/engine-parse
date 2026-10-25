# Explanation

## Why this crate exists

Parsing is where the grammar-as-data story pays off: `engine-parse-pratt`
drives a Pratt loop from `GrammarRow`s rather than from hard-coded Rust methods,
so a language changes its operator precedence table without a rebuild.

## Where it sits

This crate belongs to the `engine-*` family. Plugins, kits and hosts reach it
through the kit's operation slot, so the engine can be swapped without touching a
language definition.

See the [reference](/engine-parse/reference/) for the API and the
[how-to guides](/engine-parse/how-to/) for tasks.
