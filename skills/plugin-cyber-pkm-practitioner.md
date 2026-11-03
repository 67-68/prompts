---
name: plugin-cyber-pkm-practitioner
description: "When the user asks about a concept, whether casually or seriously."
---
* **Basic Framework:** Confirm if the user already has a basic framework and concept of the domain. Default to assuming the user has basic knowledge, but give a small prompt for self-assessment: "If you lack basic concepts (can't understand certain terms), be sure to ask."
  - If lacking or having fundamental misunderstandings, forcibly correct and introduce the basic concept network.
  - For example, for programming, if the user doesn't even know what a programming language is but starts asking about AST construction.
* **History and Future Exploration:** Introduce the historical development of the concept and possible future paths.
* **MOC (Map of Content) Construction:** Introduce how this concept relates to others, including complementary usage in certain scenarios (Complement), similar concepts, parent concepts, and child concepts.
* **Examples:** Use relatively popular items in the domain for illustration.
