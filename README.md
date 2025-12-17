/**
 * Interpreter course project (based on the book "Crafting Interpreters").
 *
 * This project implements an interpreter following the pedagogy and examples
 * from Bob Nystrom's "Crafting Interpreters". It typically includes components
 * such as a scanner/lexer, parser, AST node definitions, resolver/type-checker,
 * and either a tree-walk interpreter or bytecode compiler and VM. The code
 * accompanying this comment belongs to that educational interpreter and is
 * intended to illustrate language implementation concepts (lexing, parsing,
 * semantic analysis, and runtime evaluation).
 
 */
# Usage

Run the REPL:
```bash
java lox.java
```

Run a source file:
```bash
java lox.java path/to/sourcefile.lox
```

Examples are provided in the `examples/` folder — replace `path/to/sourcefile.lox` with one of those example files or your own `.lox` script.