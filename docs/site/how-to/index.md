# How-to guides

Task recipes. Each assumes sibling checkouts of this repo and of the platform
repos it patches.

## Implement a parser

Implement `ParserEngine` and produce an `Ast` arena. Follow `engine-parse-pratt`'s root-node convention so downstream passes can rely on it.
