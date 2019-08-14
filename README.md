# Nodeflux C++ Style Guidelines

* Style based on Google:
  * Exception
  * Line length 80
  * { → fungsi di bawah, lainnya di kanan
  * PascalCase → Class, Concept, struct, enum, template parameter (example: TBoundingBox)
  * snake_case → function, namespace (no underscore),  variable, class member variable, member type
  * uppercase → macro
  * use typename in template (not class)
  * private member → with _ suffix (e.g martabak_)
  * auto → ga dienforce
  * use trailing return type, except with void
  * const by default
* Follow CppCoreGuidelines

## Enforced Style in clang-format

- [x] Max line length 80
- [x] curly bracket `{` for function will be on the newline
- [x] Pointer Alignment on the left

## Requirements

### Clang Tidy 8.0.0
List of Clang-Tidy checks can be found at https://releases.llvm.org/8.0.0/tools/clang/tools/extra/docs/clang-tidy/checks/list.html

### Clang Format 8.0.0
List of Clang-Format style options can be found at http://releases.llvm.org/8.0.0/tools/clang/docs/ClangFormatStyleOptions.html

