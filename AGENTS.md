---
apply: always
---

# Overview

This directory is home to the **Zopilote** project, a PEG parser Generator writen in `Zig`.  

The project is in the family of of projects **TatSu** (Python) and **OGoPEGo** (Go), which can be found in the symlinked directories `./tatsu` and `./ogopego`, respectively. The semntics of **ogopego** will be the same as that of its siblings, but implemented in the style of **Go**.

The semntics of **Zopilote** will be the same as that of ts sibling **TatSu**, and **OGoPEGo** will be the same as that of its siblings, implemented in `Zig.


# Context

* Read RULES.md and follow it strictly.
* Read README.md or README.rst as available to understand the project's purpose
* Study the project's source code to understand its structure and implementation
  strategies

## Core Operational Rules

* **Research Phase:** Study the following:

    * [README.md](README.md), 
    * [SYNTAX.md](SYNTAX.md), 
    * [.tatsu/README.rst](./tatsu/README.rst) 
    * [./ogopego/README.md](./tiexiu/README.md)
    * All the documents in [./tatsu/docs/](./tatsu/docs/)
  
  to establish PEG domain context.

* **Context Gathering:** Analyze the current project structure.

* **Source Mapping:** Cross-reference the Python and Rust sources in 
  their project directories.

* **Code Modification:** Do not use command-line tools for bulk directory/glob modifications. Target specific files one-by-one only when structural tools are insufficient.

* **Repository Health:** Do not use `git` commands that will alter the the contents or state of any file in the project. Only read-only commands like `git diff` are allowed. 

* **Ownership of the Assets:** The User is the sole owner of files and other assets. Never modify any file or asset without the explicit consent from the User.

* **Shared Understanding:** You will interview the User relentlessly about every aspect of a plan until it is certain that there is a shared understanding. Walk down each branch of the possible design tree resolving dependencies between decisions one-by-one.

* **Strict Compliance:** Adhere strictly to all the rules specified in the mentioned documents.

## Workflow

* Use `just` targets (defined in `Justfile`) instead of running tools directly.
* When you find bugs or issues in the codebase, stop and ask before fixing.
