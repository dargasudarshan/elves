## GoLang Unit Testing Best Practices Guide

A contributor needs to understand &/ take care of below items:

### Topics - 1

```yaml
Topics:
  - Do I need to care about Unit Testing ?
  - Where do I start from ?
  - What is code coverage ?
  - How much code coverage is enough ?
  - How do you measure code coverage ?
```

#### Refer

```yaml
A Simple GoLang Code:
  - https://golang.org/src/strings/compare.go
However, its Unit Test Code has lots of LOC:
  - https://golang.org/src/strings/compare_test.go
A GoLang Code with many functions:
  - https://golang.org/src/strings/strings.go
Unit Test Code too has similar no of functions with much more LOC:
  - https://golang.org/src/strings/strings_test.go
```

### Topics - 2

```yaml
Topics:
  - What is boundary testing ?
  - What is positive testing ?
  - What is negative testing ?
  - What is value based testing ?
  - What is table driven testing ?
```

#### Refer

```yaml
Table Driven Testing:
  - https://dave.cheney.net/2013/06/09/writing-table-driven-tests-in-go
```

### Topics - 3

```yaml
Topics:
  - Do you write appropriate comments against your unit test code ?
  - Have you been finding it difficult to understand above _test files ?
  - Would it have been better if the _test files were commented appropriately ?
```

### Topics - 4

```yaml
Topics:
  - What it takes to achieve 100% unit test coverage ?
  - Did you know ? A code that is not designed well cannot achieve 100% test coverage.
```

#### Refer

```yaml
Interfaces and Composition for Effective Unit Testing in GoLang: 
  - https://nathanleclaire.com
```

### Topics - 5

```yaml
Topics:
  - What %age of critical bugs could have been caught during Unit Testing phase ?
```
