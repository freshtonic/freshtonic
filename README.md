### Hi, I'm James 👋

Principal engineer and former CTO in Sydney. I work in **Rust**, **PostgreSQL internals** and **applied cryptography**, and I build with LLM agents every day, designing the test oracles and evals that make agent-written code trustworthy.

Most recently I was CTO, then Principal Engineer, at [CipherStash](https://github.com/cipherstash) (2021–2026), where I led the wire-protocol implementation and SQL type checker / transpiler in [CipherStash Proxy](https://github.com/cipherstash/proxy): a Rust PostgreSQL proxy that keeps equality, range, ordering, grouping and search working over encrypted data.

#### What I'm building

- **[pgtk](https://github.com/freshtonic/pgtk)**: PostgreSQL's own understanding of SQL, as Rust libraries. Parse, analyse and type-check SQL the way the server does, with no server.
  - **pgtk-sql**, the fastest independent Postgres parser: 39 MB/s, 2.2× faster than sqlparser, 1,533 tests. Accepts exactly what PostgreSQL 14–19 beta accepts, with 0 differences from PostgreSQL's raw parser across its regression suite.
  - **pgtk-analyze** returns result-column and parameter types, or the server's exact error and SQLSTATE, without a server.
  - Try it in the browser: **[pgtk playground](https://freshtonic.github.io/pgtk-playground/)**.
- **[recursa](https://github.com/freshtonic/recursa)**: an AST-first parser generator for Rust. Write the AST as Rust types; get an LR parser, visitors, a pretty-printer and railroad diagrams. pgtk-sql is built on it. 874 tests.
- **[pgtk-proto](https://github.com/freshtonic/pg-proto)**: a session-typed PostgreSQL wire protocol library for proxies, poolers, drivers and servers. Illegal protocol sequences are compile errors.
- **[git-queue](https://github.com/freshtonic/git-queue)** and **[tree-pool](https://github.com/freshtonic/tree-pool)**: tooling for agent-driven development (stacked PRs; pools of pre-warmed clones for parallel coding agents).

#### What I'm looking for

Senior hands-on IC roles (Principal / Staff / Lead Engineer) and contract work: systems, databases, security and encryption, back end. Based in Sydney; open to remote.

📫 [freshtonic@gmail.com](mailto:freshtonic@gmail.com) · [LinkedIn](https://www.linkedin.com/in/james-sadler-5399ba143/)
