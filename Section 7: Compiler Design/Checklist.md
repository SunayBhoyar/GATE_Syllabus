# GATE Compiler Design Preparation Checklist

## 1. **Lexical Analysis**
- [ ] **Fundamentals of Lexical Analysis**
  - [ ] Role and purpose of the lexical analyzer
  - [ ] Tokens, patterns, and lexemes
  - [ ] Input buffering and lookahead
- [ ] **Lexical Analyzer Implementation**
  - [ ] Regular expressions for specifying tokens
  - [ ] Conversion of regular expressions to finite automata
  - [ ] Handling lexical errors and recovery strategies

## 2. **Parsing**
- [ ] **Types of Parsers**
  - [ ] Top-down parsing
    - [ ] Recursive descent parsing
    - [ ] LL(1) parsing (First and Follow sets)
  - [ ] Bottom-up parsing
    - [ ] Shift-reduce parsing
    - [ ] LR(0), SLR(1), LALR(1), and LR(1) parsers
- [ ] **Syntax Analysis Concepts**
  - [ ] Parse trees and derivations (leftmost and rightmost)
  - [ ] Ambiguity in grammars and resolution techniques
- [ ] **Error Handling in Parsing**
  - [ ] Error detection and recovery strategies (panic-mode, phrase-level)

## 3. **Syntax-Directed Translation (SDT)**
- [ ] **SDT Schemes**
  - [ ] Definition and types (synthesized and inherited attributes)
  - [ ] Annotated parse trees
- [ ] **Syntax-Directed Definitions (SDDs)**
  - [ ] Dependency graphs and evaluation orders
- [ ] **Applications of SDT**
  - [ ] Intermediate code generation
  - [ ] Type checking and semantic analysis

## 4. **Runtime Environments**
- [ ] **Memory Organization**
  - [ ] Activation records and stack frame structure
  - [ ] Parameter passing methods (call by value, reference)
- [ ] **Dynamic Memory Allocation**
  - [ ] Heap and garbage collection mechanisms
- [ ] **Symbol Table Management**
  - [ ] Structure and operations (insertion, lookup)
  - [ ] Scope handling and management

## 5. **Intermediate Code Generation**
- [ ] **Intermediate Representations**
  - [ ] Three-address code (TAC), quadruples, and triples
  - [ ] Abstract syntax trees (ASTs)
- [ ] **Code Generation Techniques**
  - [ ] Generating TAC for expressions and control structures
  - [ ] Backpatching for code generation

## 6. **Code Optimization**
- [ ] **Local Optimization Techniques**
  - [ ] Peephole optimization
  - [ ] Algebraic simplifications
- [ ] **Data Flow Analysis**
  - [ ] Control flow graphs (CFGs)
  - [ ] Basic blocks and flow graphs
  - [ ] Optimization algorithms (e.g., constant propagation, dead code elimination)
- [ ] **Common Subexpression Elimination**
  - [ ] Identifying and optimizing repeated calculations

## 7. **Data Flow Analyses**
- [ ] **Liveness Analysis**
  - [ ] Constructing and analyzing live variable data
- [ ] **Constant Propagation**
  - [ ] Identifying and propagating constants
- [ ] **Other Analyses**
  - [ ] Loop invariant code motion
  - [ ] Reaching definitions and available expressions

