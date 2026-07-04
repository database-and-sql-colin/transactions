# Transactions

## Overview

This project explores database transaction concepts and concurrency control in relational systems. The focus is on understanding how databases maintain correctness and consistency when multiple operations occur simultaneously or when failures happen mid-operation.

## Problem Statement

In real-world systems, multiple users and services may read and write data concurrently, often to the same resources. Without proper transaction handling, this can lead to race conditions, dirty reads, inconsistent state, and data corruption. This project explores how transactions solve these problems using ACID guarantees and isolation mechanisms.

## Learning Objectives

- Understand ACID properties (Atomicity, Consistency, Isolation, Durability)
- Learn how transactions are executed in relational databases
- Explore concurrency control mechanisms
- Understand isolation levels and their tradeoffs
- Identify and reason about common concurrency anomalies
- Learn how locking and MVCC work conceptually
- Apply transaction concepts to real-world backend systems

## Planned Topics

### Core Transaction Concepts
- BEGIN / COMMIT / ROLLBACK
- Transaction boundaries
- Atomic operations

### ACID Properties
- Atomicity
- Consistency
- Isolation
- Durability

### Isolation Levels
- Read Uncommitted
- Read Committed
- Repeatable Read
- Serializable

### Concurrency Problems
- Dirty reads
- Non-repeatable reads
- Phantom reads
- Lost updates

### Concurrency Control
- Locking mechanisms (row-level, table-level concepts)
- Optimistic concurrency control
- MVCC (Multi-Version Concurrency Control)

---

## Engineering Considerations

- Balancing consistency vs performance
- Tradeoffs between isolation levels
- Handling concurrent updates in backend services
- Designing systems that avoid race conditions
- Retry and failure handling strategies

---

## Integration Ideas

- PostgreSQL (primary transaction environment)
- Payment Service (transactional workflows)
- Inventory Service (stock consistency)
- ETL pipelines (batch transaction safety)
- Backend services (real-world transactional APIs)

---

## Status

🟡 Planned
