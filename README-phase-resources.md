# 🚀 Phase 1 — **Foundation & Internals** (Variables, Memory Model, Data Types)

---

## 📚 Books
- **Fluent Python** by Luciano Ramalho — Chapters 1–6 (Data Model, Sequences, Functions)
- **Python Cookbook** (O’Reilly) — Sections on data structures and functions
- **CPython Internals Book** (Anthony Shaw) — *First 3 chapters (Memory and Objects)*

---

## 🔥 Repositories
| Repo | What to learn |
|:---|:---|
| [cpython](https://github.com/python/cpython) | Study `Objects/` and `Include/` folders (memory layouts). |
| [pympler](https://github.com/pympler/pympler) | Memory profiling and object size analysis. |
| [objgraph](https://github.com/mgedmin/objgraph) | Visualize object graphs and reference counts. |
| [psutil](https://github.com/giampaolo/psutil) | Learn resource (memory/CPU) monitoring in Python. |
| [memory_profiler](https://github.com/pythonprofilers/memory_profiler) | Fine-grained memory usage tracking per line. |
| [tracemalloc](https://github.com/python/cpython/blob/main/Lib/tracemalloc.py) | How CPython traces memory allocations. |
| [micropython](https://github.com/micropython/micropython) | A smaller, embedded version of CPython. Great for internals. |
| [garbage-collector-examples](https://github.com/tonybaloney/python-gc) | Examples of how Python GC (Garbage Collector) works. |
| [sysmon-python](https://github.com/olafhartong/sysmon-modular) | Lightweight system monitors. |
| [gdb-python-extension](https://github.com/python/cpython/tree/main/Tools/gdb) | Python extensions for GDB to debug internals. |

### 🧩 Good First Issue Repos
- [firstcontributions/first-contributions](https://github.com/firstcontributions/first-contributions)  
- [up-for-grabs.net projects](https://github.com/up-for-grabs/up-for-grabs.net)

---

## 🧠 Important LeetCode Questions
- 217. **Contains Duplicate** (Hashing / Memory efficiency)
- 242. **Valid Anagram** (Memory for frequency count)
- 128. **Longest Consecutive Sequence** (HashSet, memory optimization)
- 36. **Valid Sudoku** (Multiple structures managing memory)
- 389. **Find the Difference** (Small memory tricks, XOR)

---

# 🚀 Phase 2 — **Functions, Scope, Callables, Closures**

---

## 📚 Books
- **Fluent Python** — Chapters 7–9 (Functions as first-class objects, closures)
- **Effective Python** — Item 15–22 (Functions and closures best practices)

---

## 🔥 Repositories
| Repo | What to learn |
|:---|:---|
| [invoke](https://github.com/pyinvoke/invoke) | A task execution tool using callables. |
| [click](https://github.com/pallets/click) | Elegant command-line interfaces based on functions. |
| [fastapi](https://github.com/tiangolo/fastapi) | Learn function-based routing, dependency injection. |
| [rich](https://github.com/Textualize/rich) | Beautiful CLI functions, decorators, and callables. |
| [python-fire](https://github.com/google/python-fire) | Create CLIs automatically from functions and objects. |
| [functools source code](https://github.com/python/cpython/blob/main/Lib/functools.py) | Core library for callables. |
| [hatch](https://github.com/pypa/hatch) | Python project management built around function hooks. |
| [typer](https://github.com/tiangolo/typer) | Simpler fast CLI using annotations and function introspection. |
| [optuna](https://github.com/optuna/optuna) | Learn functional optimization, closures. |
| [fireplace](https://github.com/nedbat/fireplace) | Learning projects for Python callable objects. |

### 🧩 Good First Issue Repos
- [goodfirstissue.dev](https://goodfirstissue.dev/)

---

## 🧠 Important LeetCode Questions
- 20. **Valid Parentheses** (Stack-based call and return matching)
- 155. **Min Stack** (Closure-inspired optimizations)
- 46. **Permutations** (Backtracking functions)
- 78. **Subsets** (Recursive closure depth understanding)
- 191. **Number of 1 Bits** (Bit manipulation inside function calls)

---

# 🚀 Phase 3 — **Iterators, Generators, Context Managers**

---

## 📚 Books
- **Fluent Python** — Chapter 14–17 (Iterators, generators, context managers)
- **Python Cookbook** — Iterators and Context Manager recipes.

---

## 🔥 Repositories
| Repo | What to learn |
|:---|:---|
| [more-itertools](https://github.com/more-itertools/more-itertools) | Advanced generator tricks. |
| [boltons](https://github.com/mahmoud/boltons) | Tiny Python utilities — many based on generators. |
| [aiohttp](https://github.com/aio-libs/aiohttp) | Async generator usage for web handling. |
| [trio](https://github.com/python-trio/trio) | Structured concurrency with generator-based async. |
| [asyncpg](https://github.com/MagicStack/asyncpg) | Async iterators in database drivers. |
| [contextlib source code](https://github.com/python/cpython/blob/main/Lib/contextlib.py) | How `contextlib` is implemented natively. |
| [pathlib](https://github.com/python/cpython/blob/main/Lib/pathlib.py) | Lazy iterators over filesystems. |
| [itertools recipes](https://github.com/python/cpython/blob/main/Doc/includes/itertools-recipes.py) | Elegant iterator recipes. |
| [pdir2](https://github.com/laike9m/pdir2) | Pretty printing of attributes, uses generators. |
| [curio](https://github.com/dabeaz/curio) | Earlier project by David Beazley on generators and coroutines. |

### 🧩 Good First Issue Repos
- [first-timers-only/first-timers-only](https://github.com/first-timers-only/first-timers-only)

---

## 🧠 Important LeetCode Questions
- 206. **Reverse Linked List** (Custom iterator)
- 2. **Add Two Numbers** (Generator-like iteration)
- 138. **Copy List with Random Pointer** (Iterator vs generator understanding)
- 23. **Merge k Sorted Lists** (Priority queue, lazy merging)
- 328. **Odd Even Linked List** (Special pointer iteration)

---

# 🚀 Phase 4 — **OOP, Decorators, Descriptors**

---

## 📚 Books
- **Fluent Python** — Chapters 18–23 (Classes, Properties, Descriptors, Decorators)
- **Effective Python** — Item 26–30 (Classes and interfaces)

---

## 🔥 Repositories
| Repo | What to learn |
|:---|:---|
| [attrs](https://github.com/python-attrs/attrs) | Dataclass and OOP best practices. |
| [pydantic](https://github.com/pydantic/pydantic) | Validating Python classes efficiently. |
| [dataclasses-json](https://github.com/lidatong/dataclasses-json) | JSON serialization using decorators. |
| [cattrs](https://github.com/python-attrs/cattrs) | Classes and attributes library. |
| [marshmallow](https://github.com/marshmallow-code/marshmallow) | Serialization using descriptors. |
| [django](https://github.com/django/django) | Django ORM models: classes + descriptors + metaclasses. |
| [sqlalchemy](https://github.com/sqlalchemy/sqlalchemy) | Full use of OOP, decorators, and descriptors. |
| [sanic](https://github.com/sanic-org/sanic) | Async classes and routing with decorators. |
| [pyramid](https://github.com/Pylons/pyramid) | MVC framework using OOP decorators heavily. |
| [cookiecutter](https://github.com/cookiecutter/cookiecutter) | Templates with classes and decorators inside. |

---

## 🧠 Important LeetCode Questions
- 146. **LRU Cache** (Class and decorator understanding)
- 295. **Find Median from Data Stream** (OOP with heaps)
- 460. **LFU Cache** (Complex class hierarchy)
- 208. **Implement Trie (Prefix Tree)** (Classic OOP)
- 380. **Insert Delete GetRandom O(1)** (OOP + set and map)

---

# 🚀 Phase 5 — **Metaprogramming, AST, CPython Internals**

---

## 📚 Books
- **Fluent Python** — Chapters 24–28 (Metaclasses, attribute programming)
- **CPython Internals Book** — Deeper chapters (Bytecode, Interpreter loop)

---

## 🔥 Repositories
| Repo | What to learn |
|:---|:---|
| [pluggy](https://github.com/pytest-dev/pluggy) | Plugin system using metaprogramming. |
| [pytest](https://github.com/pytest-dev/pytest) | Heavy decorator and metaclass usage. |
| [sphinx](https://github.com/sphinx-doc/sphinx) | AST and code documentation tooling. |
| [pydantic-core](https://github.com/pydantic/pydantic-core) | Rust-backed Python internals. |
| [astor](https://github.com/berkerpeksag/astor) | AST manipulation and conversion to source. |
| [black](https://github.com/psf/black) | Code formatting based on AST parsing. |
| [isort](https://github.com/PyCQA/isort) | Sorting imports using AST. |
| [hypothesis](https://github.com/HypothesisWorks/hypothesis) | Property-based testing, meta code generation. |
| [bytecode](https://github.com/python/bytecode) | Python bytecode manipulation. |
| [codemod](https://github.com/facebook/codemod) | Refactoring Python code automatically. |

---

## 🧠 Important LeetCode Questions
- 399. **Evaluate Division** (Building graphs dynamically like AST)
- 269. **Alien Dictionary** (Build order from graph)
- 332. **Reconstruct Itinerary** (Dynamic structure parsing)
- 301. **Remove Invalid Parentheses** (AST-like parsing problem)
- 772. **Basic Calculator III** (Building expression trees)

---

# ⚡ Note:
If you want, I can also prepare:
- **Cheat-sheets for each phase** (Python-specific)
- **Example issue templates for GitHub Projects**
- **A public GitHub repo template** you can clone for tracking your weekly projects.

---
  
