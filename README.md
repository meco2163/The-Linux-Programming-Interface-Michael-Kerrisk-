# 📚 Technical Books & Resources

A curated collection of essential technical books and reference materials in PDF format, gathered throughout my learning journey in software engineering.

---

## 📖 Books

### Systems Programming

| Book | Author | Topics |
|------|--------|--------|
| [The Linux Programming Interface](The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf) | Michael Kerrisk | Linux/UNIX system programming, processes, threads, IPC, sockets, file I/O |

<!--
### C / C++

| Book | Author | Topics |
|------|--------|--------|

### Networking

| Book | Author | Topics |
|------|--------|--------|

### Algorithms & Data Structures

| Book | Author | Topics |
|------|--------|--------|

### Other

| Book | Author | Topics |
|------|--------|--------|
-->

---

## 🔍 Quick Reference — The Linux Programming Interface

<details>
<summary><strong>Part I: Fundamental Concepts (Ch 1–3)</strong></summary>

- [Chapter 1: History and Standards](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=51)
- [Chapter 2: Fundamental Concepts](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=71)
- [Chapter 3: System Programming Concepts](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=93)

> 🎯 **Relevant 42 projects:** All system-level projects — provides foundational understanding of Linux/UNIX architecture.
</details>

<details>
<summary><strong>Part II: File I/O (Ch 4–5)</strong></summary>

- [Chapter 4: File I/O — The Universal I/O Model](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=119)
- [Chapter 5: File I/O — Further Details](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=145)

> 🎯 **Relevant 42 projects:** `get_next_line`, `pipex`, `minishell`
</details>

<details>
<summary><strong>Part III: Processes & Memory (Ch 6–9)</strong></summary>

- [Chapter 6: Processes](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=163)
- [Chapter 7: Memory Allocation](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=183)
- [Chapter 8: Users and Groups](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=201)
- [Chapter 9: Process Credentials](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=217)

> 🎯 **Relevant 42 projects:** `pipex`, `minishell`, `philosophers`
</details>

<details>
<summary><strong>Part IV: Signals & Time (Ch 10–23)</strong></summary>

- [Chapter 10: Time](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=239)
- [Chapter 11: System Limits and Options](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=261)
- [Chapter 12: System and Process Information](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=279)
- [Chapter 20: Signals — Fundamental Concepts](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=437)
- [Chapter 21: Signals — Signal Handlers](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=473)
- [Chapter 22: Signals — Advanced Features](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=497)
- [Chapter 23: Timers and Sleeping](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=533)

> 🎯 **Relevant 42 projects:** `minishell` (signals), `philosophers` (time & sleeping), `pipex` (signals)
</details>

<details>
<summary><strong>Part V: Process Creation & Termination (Ch 24–28)</strong></summary>

- [Chapter 24: Process Creation](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=565)
- [Chapter 25: Process Termination](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=581)
- [Chapter 26: Monitoring Child Processes](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=593)
- [Chapter 27: Program Execution](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=621)
- [Chapter 28: Process Creation and Program Execution in More Detail](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=649)

> 🎯 **Relevant 42 projects:** `pipex` (fork, exec, waitpid), `minishell` (fork, exec, process management), `philosophers bonus` (fork, waitpid, kill)
</details>

<details>
<summary><strong>Part VI: Threads (Ch 29–33)</strong></summary>

- [Chapter 29: Threads — Introduction](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=669)
- [Chapter 30: Threads — Thread Synchronization](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=691)
- [Chapter 31: Threads — Thread Safety and Per-Thread Storage](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=717)
- [Chapter 32: Threads — Thread Cancellation](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=735)
- [Chapter 33: Threads — Further Details](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=747)

> 🎯 **Relevant 42 projects:** `philosophers` (threads, mutexes, data races), `webserv`, `ft_irc`
</details>

<details>
<summary><strong>Part VII: System V IPC (Ch 43–48)</strong></summary>

- [Chapter 43: Inter-Process Communication Overview](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=917)
- [Chapter 44: Pipes and FIFOs](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=933)
- [Chapter 45: System V IPC — Introduction](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=967)
- [Chapter 46: System V Message Queues](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=985)
- [Chapter 47: System V Semaphores](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1005)
- [Chapter 48: System V Shared Memory](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1039)

> 🎯 **Relevant 42 projects:** `pipex` (pipes), `minishell` (pipes, heredoc), `philosophers bonus` (IPC concepts)
</details>

<details>
<summary><strong>Part VIII: POSIX IPC & Semaphores (Ch 51–53)</strong></summary>

- [Chapter 51: POSIX IPC — Introduction](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1087)
- [Chapter 52: POSIX Message Queues](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1095)
- [Chapter 53: POSIX Semaphores](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1117)

> 🎯 **Relevant 42 projects:** `philosophers bonus` (sem_open, sem_wait, sem_post)
</details>

<details>
<summary><strong>Part IX: Sockets (Ch 56–61)</strong></summary>

- [Chapter 56: Sockets — Introduction](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1195)
- [Chapter 57: Sockets — UNIX Domain](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1227)
- [Chapter 58: Sockets — TCP/IP Networks](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1243)
- [Chapter 59: Sockets — Internet Domain](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1265)
- [Chapter 60: Sockets — Server Design](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1299)
- [Chapter 61: Sockets — Advanced Topics](https://github.com/meco2163/The-Linux-Programming-Interface-Michael-Kerrisk-/blob/main/The%20Linux%20Programming%20Interface-Michael%20Kerrisk.pdf#page=1321)

> 🎯 **Relevant 42 projects:** `ft_irc`, `webserv`
</details>

---

## 🗺️ 42 Project Roadmap — What to Read

| 42 Project | Recommended Chapters |
|------------|---------------------|
| **get_next_line** | Ch 4–5 (File I/O) |
| **pipex** | Ch 4–5 (File I/O), Ch 24–27 (Processes), Ch 44 (Pipes) |
| **minishell** | Ch 4–5 (File I/O), Ch 6 (Processes), Ch 20–22 (Signals), Ch 24–27 (Process Creation & Execution), Ch 44 (Pipes) |
| **philosophers** | Ch 6 (Processes), Ch 10, 23 (Time & Sleeping), Ch 29–31 (Threads & Mutexes) |
| **philosophers bonus** | Ch 24–26 (Process Creation), Ch 20–22 (Signals), Ch 53 (POSIX Semaphores) |
| **ft_irc** | Ch 29–33 (Threads), Ch 56–61 (Sockets) |
| **webserv** | Ch 29–33 (Threads), Ch 56–61 (Sockets), Ch 60 (Server Design) |

---

## 📌 How to Use

1. Click on any book link in the table above to view/download the PDF
2. Use the collapsible chapter lists as a quick reference guide

---

## 🤝 Contributing

If you have a suggestion for a great technical book to add, feel free to open an issue or submit a pull request.

---

*Maintained by [mekaplan](https://github.com/meco2163)*
