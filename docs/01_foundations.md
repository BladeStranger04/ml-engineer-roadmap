# 🐍 1. Foundations — Python, алгоритмы, CS

> **Цель этапа:** уверенно писать продакшен-код на Python, понимать как работает компьютер, проходить алгоритмические секции собеседований.

---

## 🎯 Что должен знать ML Engineer

### Python (Advanced)
- [ ] Типы данных, mutable/immutable, copy/deepcopy
- [ ] ООП: классы, наследование, миксины, dataclasses, `__slots__`
- [ ] Декораторы, контекстные менеджеры, генераторы, итераторы
- [ ] Типизация (`typing`, `mypy`), `pydantic`
- [ ] Асинхронность: `asyncio`, `async/await`
- [ ] Многопоточность vs многопроцессорность, GIL
- [ ] Тесты: `pytest`, фикстуры, моки, coverage
- [ ] Менеджмент зависимостей: `poetry` / `uv` / `pip-tools`
- [ ] Линтеры/форматтеры: `ruff`, `black`, `pre-commit`

### Computer Science
- [ ] Структуры данных: list, dict, set, deque, heap, trie
- [ ] Алгоритмы: сортировки, BFS/DFS, DP, two pointers, sliding window
- [ ] Сложность по времени и памяти (Big-O)
- [ ] Базы ОС: процессы, потоки, память, IPC
- [ ] Сети: HTTP/HTTPS, TCP/UDP, REST, gRPC, WebSockets

### Инструменты разработчика
- [ ] Git: ветвление, rebase, conflict resolution, git hooks
- [ ] Linux: bash, grep/sed/awk, systemd, ssh, screen/tmux
- [ ] IDE: PyCharm / VS Code + плагины
- [ ] Docker (введение, глубже — в MLOps)

---

## 📚 Ресурсы

| Тип | Ресурс | Уровень |
|---|---|:---:|
| 📖 Книга | «Fluent Python» Лучано Рамальо | ⭐⭐⭐ |
| 🎥 Курс | [Поколение Python (Stepik)](https://stepik.org/course/58852) | ⭐ |
| 🎥 Курс | [Алгоритмы: теория и практика — Computer Science Center](https://stepik.org/course/217) | ⭐⭐ |
| 🎥 Курс | [ШАД — Алгоритмы и структуры данных](https://education.yandex.ru/handbook/algorithms) | ⭐⭐⭐ |
| 💻 Практика | [LeetCode](https://leetcode.com) — 100–150 задач Easy/Medium | ⭐⭐ |
| 💻 Практика | [Codeforces](https://codeforces.com) | ⭐⭐ |
| 🎥 Linux | [Курс «Введение в Linux» (Stepik)](https://stepik.org/course/73) | ⭐ |
| 🎥 Git | [Git для начинающих — Хирьянов](https://www.youtube.com/watch?v=zZBiln_2FhM) | ⭐ |

---

## ✅ Контрольный проект

Напиши **CLI-утилиту** на Python, которая:
- парсит CSV/JSON,
- считает простую статистику,
- покрыта тестами `pytest` (≥80% coverage),
- собрана через `poetry`,
- имеет `Dockerfile`,
- лежит на GitHub с README + GitHub Actions (lint + tests).
