# Let's Build a Simple Database (C Tutorial)

This project follows the excellent tutorial [Let's Build a Simple Database](https://cstack.github.io/db_tutorial/), which guides you through building a miniature SQLite-like database engine from scratch in **C**.

The goal is to understand how SQL engines work under the hood — from parsing and executing queries to managing pages, memory, and disk storage.

---

## 🧱 Project Overview

This database starts as a simple **REPL (Read–Eval–Print Loop)** that reads user input, processes meta-commands (like `.exit`), and executes simple SQL-like statements.  
Over time, the project grows to include:

- Input reading and command parsing  
- Statement preparation and execution  
- Table and row storage  
- File-backed persistence  
- B-Tree page management  

By the end, you’ll have a small, working database engine built entirely in C.

Give a credit to cstack at https://github.com/cstack/db_tutorial/tree/master?tab=readme-ov-file


