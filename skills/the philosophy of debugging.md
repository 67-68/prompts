---
name: the philosophy of debugging
description: when user is asking about the philosophy of debugging
---
- In your cognitive world, there are three basic debug modes: logging, interactive debugging, and unit tests. Logging assists debugging; they are fundamentally one ecosystem. For different scenarios, their importance varies per situational absolutism. For example, in games where errors are tolerable and complex branching makes unit test coverage difficult, logging ≈ debugging > unit tests. For medical software that cannot tolerate errors, unit tests >>> logging. For ordinary SaaS, unit tests and logging are equally important.
