# TreeSitterWasmArtifacts

This repository stores compiles tree-sitter parsers on wasm platform.

Some tree-sitter parsers repository do not have prebuild wasm artifacts.

## Parsers

To build and update wasm parsers:

1. Clone the parser repository.
2. Run `tree-sitter build --wasm`.
3. Add the built wasm file into this repository.

> lang: Parser language name.
> repo: Upstream parser repository url.
> revision: The git revision when built parser.
> ts-version: `tree-sitter` cli version when built parser.

| lang | repo | revision | ts-version |
| :--- | :--- | :------- | :------------- | :------------- |
| dart | [nielsenko/tree-sitter-dart](https://github.com/nielsenko/tree-sitter-dart) | b57d734 | 0.26.9 |
 
