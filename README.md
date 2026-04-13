# The-Linux-Programming-Interface-Michael-Kerrisk-

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

- Chapter 1: History and Standards
- Chapter 2: Fundamental Concepts
- Chapter 3: System Programming Concepts

> 🎯 **Relevant 42 projects:** All system-level projects — provides foundational understanding of Linux/UNIX architecture.
</details>

<details>
<summary><strong>Part II: File I/O (Ch 4–5)</strong></summary>

- Chapter 4: File I/O — The Universal I/O Model
- Chapter 5: File I/O — Further Details

> 🎯 **Relevant 42 projects:** `get_next_line`, `pipex`, `minishell`
</details>

<details>
<summary><strong>Part III: Processes & Memory (Ch 6–9)</strong></summary>

- Chapter 6: Processes
- Chapter 7: Memory Allocation
- Chapter 8: Users and Groups
- Chapter 9: Process Credentials

> 🎯 **Relevant 42 projects:** `pipex`, `minishell`, `philosophers`
</details>

<details>
<summary><strong>Part IV: Signals & Time (Ch 10–23)</strong></summary>

- Chapter 10: Time
- Chapter 11: System Limits and Options
- Chapter 12: System and Process Information
- Chapter 20: Signals — Fundamental Concepts
- Chapter 21: Signals — Signal Handlers
- Chapter 22: Signals — Advanced Features
- Chapter 23: Timers and Sleeping

> 🎯 **Relevant 42 projects:** `minishell` (signals), `philosophers` (time & sleeping), `pipex` (signals)
</details>

<details>
<summary><strong>Part V: Process Creation & Termination (Ch 24–28)</strong></summary>

- Chapter 24: Process Creation
- Chapter 25: Process Termination
- Chapter 26: Monitoring Child Processes
- Chapter 27: Program Execution
- Chapter 28: Process Creation and Program Execution in More Detail

> 🎯 **Relevant 42 projects:** `pipex` (fork, exec, waitpid), `minishell` (fork, exec, process management), `philosophers bonus` (fork, waitpid, kill)
</details>

<details>
<summary><strong>Part VI: Threads (Ch 29–33)</strong></summary>

- Chapter 29: Threads — Introduction
- Chapter 30: Threads — Thread Synchronization
- Chapter 31: Threads — Thread Safety and Per-Thread Storage
- Chapter 32: Threads — Thread Cancellation
- Chapter 33: Threads — Further Details

> 🎯 **Relevant 42 projects:** `philosophers` (threads, mutexes, data races), `webserv`, `ft_irc`
</details>

<details>
<summary><strong>Part VII: System V IPC (Ch 43–48)</strong></summary>

- Chapter 43: Inter-Process Communication Overview
- Chapter 44: Pipes and FIFOs
- Chapter 45: System V IPC — Introduction
- Chapter 46: System V Message Queues
- Chapter 47: System V Semaphores
- Chapter 48: System V Shared Memory

> 🎯 **Relevant 42 projects:** `pipex` (pipes), `minishell` (pipes, heredoc), `philosophers bonus` (IPC concepts)
</details>

<details>
<summary><strong>Part VIII: POSIX IPC & Semaphores (Ch 51–53)</strong></summary>

- Chapter 51: POSIX IPC — Introduction
- Chapter 52: POSIX Message Queues
- Chapter 53: POSIX Semaphores

> 🎯 **Relevant 42 projects:** `philosophers bonus` (sem_open, sem_wait, sem_post)
</details>

<details>
<summary><strong>Part IX: Sockets (Ch 56–61)</strong></summary>

- Chapter 56: Sockets — Introduction
- Chapter 57: Sockets — UNIX Domain
- Chapter 58: Sockets — TCP/IP Networks
- Chapter 59: Sockets — Internet Domain
- Chapter 60: Sockets — Server Design
- Chapter 61: Sockets — Advanced Topics

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
