# 1. Foundations: Python, algorithms, CS

> Russian version: [01_foundations.md](../ru/01_foundations.md)

> **Goal:** write production-ready Python, understand core computer science, and pass coding interview rounds.

---

## What an ML Engineer should know

### Python advanced
- [ ] Data types, mutability, `copy` / `deepcopy`
- [ ] OOP: classes, inheritance, mixins, dataclasses, `__slots__`
- [ ] Decorators, context managers, generators, iterators
- [ ] Type hints, `typing`, `mypy`, `pydantic`
- [ ] Async programming: `asyncio`, `async` / `await`
- [ ] Threads vs processes, GIL
- [ ] Testing: `pytest`, fixtures, mocks, coverage
- [ ] Dependency management: `poetry`, `uv`, `pip-tools`
- [ ] Linters and formatters: `ruff`, `black`, `pre-commit`

### Computer science
- [ ] Data structures: list, dict, set, deque, heap, trie
- [ ] Algorithms: sorting, BFS/DFS, dynamic programming, two pointers, sliding window
- [ ] Time and memory complexity, Big-O
- [ ] OS basics: processes, threads, memory, IPC
- [ ] Networking: HTTP/HTTPS, TCP/UDP, REST, gRPC, WebSockets

### Developer tools
- [ ] Git: branching, rebase, conflict resolution, hooks
- [ ] Linux: shell, `grep` / `sed` / `awk`, systemd, ssh, tmux
- [ ] IDE: PyCharm or VS Code
- [ ] Docker basics, deeper practice in MLOps

---

## Resources

| Type | Resource | Level |
|---|---|:---:|
| Book | Fluent Python, Luciano Ramalho | *** |
| Course | [CS50P](https://cs50.harvard.edu/python/) | * |
| Course | [Algorithms, Part I](https://www.coursera.org/learn/algorithms-part1) | ** |
| Practice | [LeetCode](https://leetcode.com) - 100-150 Easy/Medium problems | ** |
| Practice | [Codeforces](https://codeforces.com) | ** |
| Linux | [The Missing Semester](https://missing.csail.mit.edu/) | ** |
| Git | [Pro Git](https://git-scm.com/book/en/v2) | ** |

---

## Checkpoint project

Build a Python CLI tool that:
- parses CSV and JSON,
- calculates basic statistics,
- is covered with `pytest` tests, target 80%+ coverage,
- is packaged with `poetry` or `uv`,
- has a `Dockerfile`,
- is published on GitHub with README and GitHub Actions for linting and tests.
