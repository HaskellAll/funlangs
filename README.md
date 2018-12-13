<!-- DO NOT EDIT THIS FILE -->
<!-- edit funlangs.hs instead -->

# Functional languages

There is no such thing as a functional language.
There are only languages with different functional features.

## Functional features

| Feature | C | C++ | Haskell | Idris | Java | OCaml | Python | Rust | Scala |
|---|---|---|---|---|---|---|---|---|---|
| Closures | :x: | :warning: | :heavy_check_mark: | :heavy_check_mark: |  | :heavy_check_mark: | :heavy_check_mark: | :warning: | :heavy_check_mark: |
| Downwards Funarg Problem | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Functions | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Lambda Abstraction Syntax | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :warning: | :heavy_check_mark: | :heavy_check_mark: |
| Pure Functions | :x: | :warning: | :heavy_check_mark: | :heavy_check_mark: | :x: | :x: | :x: | :x: | :x: |
| Tail Call Optimization |  |  | :heavy_check_mark: | :heavy_check_mark: | :x: |  |  |  |  |
| Upwards Funarg Problem | :x: | :warning: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |

## Supporting features

| Feature | C | C++ | Haskell | Idris | Java | OCaml | Python | Rust | Scala |
|---|---|---|---|---|---|---|---|---|---|
| Ad Hoc Polymorphism | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |  |
| Algebraic Data Types | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: |  | :heavy_check_mark: | :x: | :heavy_check_mark: |  |
| Dependent Types | :x: | :x: | :x: | :heavy_check_mark: |  | :x: | :x: | :x: |  |
| Forces Immutability | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: |  | :heavy_check_mark: | :x: | :heavy_check_mark: |  |
| Immutable Data | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |  |
| Laziness | :x: | :x: | :heavy_check_mark: | :x: |  | :x: | :x: | :x: |  |
| Parametric Modules | :x: | :x: | :warning: | :heavy_check_mark: |  |  | :x: | :x: |  |
| Parametric Polymorphism |  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |  |
| Pattern Matching |  | :warning: | :heavy_check_mark: | :heavy_check_mark: |  |  | :warning: | :warning: |  |
| Pattern Matching Alternatives |  |  | :heavy_check_mark: | :heavy_check_mark: |  |  |  | :heavy_check_mark: |  |
| Pattern Matching Variable Introduction |  |  | :heavy_check_mark: | :heavy_check_mark: |  |  | :heavy_check_mark: | :heavy_check_mark: |  |
| Polymorphic Recursion | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: | :x: | :heavy_check_mark: | :warning: |  |  |
| Referential Transparency |  |  | :heavy_check_mark: | :heavy_check_mark: |  |  |  |  |  |
| Static Typing | :warning: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: |
| Totality Checking | :x: | :x: | :x: | :heavy_check_mark: |  | :x: | :x: | :x: |  |
| Uniqueness Types | :x: | :x: | :x: | :heavy_check_mark: |  | :x: | :x: | :heavy_check_mark: |  |
| Universe Polymorphism | :x: | :x: | :x: | :heavy_check_mark: |  | :x: | :x: | :x: |  |

## Scores

A well implemented feature counts as 1,
a hard-to-use one counts as 0.5.
Supporting featurues count twice less.

| Language | Score |
|----------|-------|
| Idris | 15.0 |
| Haskell | 13.25 |
| Rust | 9.25 |
| OCaml | 8.5 |
| Python | 7.0 |
| C++ | 6.75 |
| Scala | 5.5 |
| Java | 4.5 |
| C | 2.25 |

