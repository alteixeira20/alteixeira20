# 42 Projects

This document lists the core projects completed during the **42 Common Core**, with a focus on systems programming, correctness, and tooling.  
Projects are ordered roughly by increasing complexity and architectural depth.

| Project | Description | Rank | Language(s) | Result |
|--------|-------------|------|-------------|--------|
| [libft](https://github.com/alteixeira20/42_libft) | Custom C standard library reimplementation used as the foundation for all subsequent projects, with strict memory discipline and extensive self-written tests. | 0 | C | 125 / 125 |
| [ft_printf](https://github.com/alteixeira20/42_printf) | Rebuilt `printf` with full flag parsing, format handling, and a dedicated regression tester to validate edge cases. | 1 | C | 125 / 125 |
| [get_next_line](https://github.com/alteixeira20/42_get_next_line) | Line-oriented file descriptor reader with static buffering; bonus handles multiple descriptors concurrently. | 1 | C | 125 / 125 |
| Born2beRoot | Linux system administration on a virtual machine: user management, services, firewall rules, and basic security hardening. | 1 | Bash / Linux | 125 / 125 |
| [push_swap](https://github.com/alteixeira20/42_push_swap) | Two-stack sorting engine focused on move minimisation, chunking strategies, and automated validation tooling. | 2 | C | 125 / 125 |
| [minitalk](https://github.com/alteixeira20/42_minitalk) | Signal-based IPC system implementing client/server communication via bitwise encoding and acknowledgements. | 2 | C | 125 / 125 |
| [so_long](https://github.com/alteixeira20/42_so_long) | 2D game using MiniLibX with map validation, sprite handling, event loops, and deterministic game state updates. | 2 | C | 125 / 125 |
| [minishell](https://github.com/alteixeira20/42_minishell) | Bash-like shell implementing parsing, expansion, pipes, redirections, builtins, signal handling, and automated Bash-parity testing. | 3 | C | 101 / 125 |
| [philosophers](https://github.com/alteixeira20/42_philosophers) | Concurrency problem solved with threads, mutexes, and a timing monitor to prevent deadlocks and starvation. | 3 | C | 100 / 125 |
| [cub3D](https://github.com/alteixeira20/42_cub3d) | Raycasting engine with strict scene validation, real-time rendering, and tooling-first correctness (custom testers, Valgrind workflows). | 4 | C | 125 / 125 |
| [C++ Modules 00–09](https://github.com/alteixeira20/42_cpp) | Progressive C++98 modules covering OOP, RAII, inheritance, templates, STL usage, and type safety. | 4 | C++ | In progress |

---

### Notes
- All C projects are developed under **strict memory and norm constraints**, with additional self-written testers beyond the required scope.
- Debugging and validation rely heavily on **Valgrind**, **GDB**, and automated test harnesses to make behaviour observable and reproducible.
- Later projects prioritise **architecture clarity**, **defensive parsing**, and **predictable execution flow** over feature breadth.
