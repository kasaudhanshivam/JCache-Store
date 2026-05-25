# JCache - In-Memory Key-Value Store

## Overview
JCache is a high-performance, thread-safe, in-memory caching engine engineered from scratch using **Core Java**. It mimics the foundational behavior of enterprise caching systems by providing $O(1)$ time complexity for data retrieval and storage operations.

## Core Features
* **Thread-Safety:** Utilizes `ConcurrentHashMap` to handle concurrent read/write operations efficiently across multiple threads without data corruption.
* **Custom Eviction Policy:** Implements a robust **Least Recently Used (LRU)** algorithm using a custom Doubly Linked List to seamlessly manage memory bounds and evict stale data when capacity is reached.
* **Object-Oriented Design:** Structured using strict OOD principles to decouple the eviction logic from the storage engine, ensuring the system is scalable for future policies (like LFU or FIFO).

## Tech Stack
* **Language:** Java (Core Java)
* **Concepts:** Multithreading, Java Collections Framework, Data Structures (Hash Maps, Doubly Linked Lists), OOPs.

---
*Note: This repository is currently undergoing active development. Refactoring existing algorithmic logic into a modular object-oriented architecture. Commits in progress.*
