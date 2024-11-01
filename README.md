# Software Engineering Learning Path 💎

A curated collection of high-quality software engineering resources focusing on Python, Go, algorithms and software architecture. Each resource has been carefully selected for its depth and practical value. This is my personal reading list - a mix of articles I've found enlightening and ones I plan to dive into.

## 📚 Table of Contents
- [Python Deep Dive](#python-deep-dive)
  - [Python Internals Series](#python-internals-series)
  - [Python Advanced Concepts](#python-advanced-concepts)
- [Testing](#testing)
- [Databases](#databases)
- [API Design](#api-design)
- [Security](#security)
- [System Design](#system-design)
  - [Fundamentals](#fundamentals)
  - [Scalability](#scalability)
  - [Distributed Systems](#distributed-systems)
- [Software Architecture](#software-architecture)
  - [Best Practices](#best-practices)
  - [Testing](#testing)
  - [DevOps](#devops)
- [Algorithms & Data Structures](#algorithms--data-structures)
- [Books & Long Reads](#books--long-reads)


## Python

### Python Internals Series
A comprehensive series explaining Python's internal workings:

1. [How the CPython VM Works](https://tenthousandmeters.com/blog/python-behind-the-scenes-1-how-the-cpython-vm-works/)
2. [How the CPython Compiler Works](https://tenthousandmeters.com/blog/python-behind-the-scenes-2-how-the-cpython-compiler-works/)
3. [How Python Bytecode is Executed](https://tenthousandmeters.com/blog/python-behind-the-scenes-4-how-python-bytecode-is-executed/)
4. [How Variables are Implemented](https://tenthousandmeters.com/blog/python-behind-the-scenes-5-how-variables-are-implemented-in-cpython/)
5. [How Python Object System Works](https://tenthousandmeters.com/blog/python-behind-the-scenes-6-how-python-object-system-works/)
6. [How Python Attributes Work](https://tenthousandmeters.com/blog/python-behind-the-scenes-7-how-python-attributes-work/)
7. [How Python Integers Work](https://tenthousandmeters.com/blog/python-behind-the-scenes-8-how-python-integers-work/)
8. [How Python Strings Work](https://tenthousandmeters.com/blog/python-behind-the-scenes-9-how-python-strings-work/)
9. [How Python Dictionaries Work](https://tenthousandmeters.com/blog/python-behind-the-scenes-10-how-python-dictionaries-work/)
10. [How the Python Import System Works](https://tenthousandmeters.com/blog/python-behind-the-scenes-11-how-the-python-import-system-works/)
11. [How async/await Works](https://tenthousandmeters.com/blog/python-behind-the-scenes-12-how-asyncawait-works-in-python/)
12. [The GIL and its Effects on Multithreading](https://tenthousandmeters.com/blog/python-behind-the-scenes-13-the-gil-and-its-effects-on-python-multithreading/)

### Python Advanced Concepts
- [Python Design Patterns](https://python-patterns.guide/)
- [Context Variables](https://docs.python.org/3/library/contextvars.html)
- [Internals of Sets and Dicts](https://www.fluentpython.com/extra/internals-of-sets-and-dicts/)
- [Weak References](https://www.fluentpython.com/extra/weak-references/)
- [Slots Inheritance](https://stackoverflow.com/questions/1816483/how-does-inheritance-of-slots-in-subclasses-actually-work)
- [Classic Coroutines](https://www.fluentpython.com/extra/classic-coroutines/)
- [Preventing SQL Injection with Python](https://realpython.com/prevent-python-sql-injection/#using-query-parameters-in-sql)
- [A Curious Course on Coroutines and Concurrency - David Beazley](https://www.dabeaz.com/coroutines/Coroutines.pdf)

### Python Books
- [Fluent Python](https://www.oreilly.com/library/view/fluent-python-2nd/9781492056348/)
- [Cosmic Python - DDD in Practice](https://www.cosmicpython.com/book/preface.html)

## Go

### Articles
- [Circuit Breaker Pattern in Go](https://rednafi.com/go/circuit_breaker/)
- [Interface Guards in Go](https://rednafi.com/go/interface_guards/)

### Go Books
- [The GO Programming Language](http://www.cs.uniroma2.it/upload/2017/TSC/The%20Go%20Programming%20Language.pdf)

## Testing
- [Mocks Aren't Stubs](https://martinfowler.com/articles/mocksArentStubs.html)
- [Microservice Testing Strategies](https://martinfowler.com/articles/microservice-testing/)

## Databases

### Basics
- [Database Fundamentals](https://tontinton.com/posts/database-fundementals/?utm_source=tldrwebdev)
- [Introduction to Transaction Isolation Levels](https://fauna.com/blog/introduction-to-transaction-isolation-levels)

### Postgres
- [Window Functions](https://www.postgresql.org/docs/current/tutorial-window.html)
- [Indexes](https://www.postgresql.org/docs/17/indexes.html)
- [Transaction Isolation in Postgres](https://www.thenile.dev/blog/transaction-isolation-postgres?utm_source=tldrnewsletter)

## API Design
- [Richardson Maturity Model (REST)](https://martinfowler.com/articles/richardsonMaturityModel.html)
- [Introduction to GraphQL](https://graphql.org/learn/)
- [Netflix: Learnings from Adopting GraphQL](https://netflixtechblog.com/our-learnings-from-adopting-graphql-f099de39ae5f)

## Security
- [OWASP Top 10](https://owasp.org/Top10/#welcome-to-the-owasp-top-10-2021)

## System Design

### Fundamentals
- [DNS Explained](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)
- [Inter-Process Communication (IPC)](https://www.geeksforgeeks.org/inter-process-communication-ipc/)
- [Latency Numbers Every Programmer Should Know](https://colin-scott.github.io/personal_website/research/interactive_latency.html)

### Scalability
- [Scaling to 11 Million+ Users on AWS](https://highscalability.com/a-beginners-guide-to-scaling-to-11-million-users-on-amazons/)
- [Rate Limiting with Redis and Lua](https://blog.callr.tech/rate-limiting-for-distributed-systems-with-redis-and-lua/)
- [Limiting Concurrency with Semaphore](https://rednafi.com/python/limit_concurrency_with_semaphore/)

### Distributed Systems
- [Single-Decree Paxos](https://mwhittaker.github.io/blog/single_decree_paxos/)
- [Lamport's Logical Clocks](https://mwhittaker.github.io/blog/lamports_logical_clocks/)
- [Visualizing Linearizability](https://mwhittaker.github.io/blog/visualizing_linearizability/)
- [CAP Theorem Illustrated](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/)
- [Bloom Filters by Example](https://llimllib.github.io/bloomfilter-tutorial/)
- [Consistent Hashing](https://tom-e-white.com/2007/11/consistent-hashing.html)

## Software Architecture

### Basics
- [Consistent Hashing Explained](https://systemdesign.one/consistent-hashing-explained/)

### Best Practices
- [Data Structures & Algorithms in Practice](https://blog.pragmaticengineer.com/data-structures-and-algorithms-i-actually-used-day-to-day/)
- [Exponential Backoff And Jitter](https://aws.amazon.com/blogs/architecture/exponential-backoff-and-jitter/)
- [Retry Throttling](https://aws.amazon.com/blogs/developer/introducing-retry-throttling/)

### Architecture Patterns
- [Hexagonal Architecture at Netflix](https://netflixtechblog.com/ready-for-changes-with-hexagonal-architecture-b315ec967749)
- [Microservice Architecture at Medium](https://medium.engineering/microservice-architecture-at-medium-9c33805eb74f)
- [Cloud Design Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/)
- [GitLab Production Architecture](https://handbook.gitlab.com/handbook/engineering/infrastructure/production/architecture/)
- [Netflix: Evolving WebSocket Proxy](https://netflixtechblog.com/pushy-to-the-limit-evolving-netflixs-websocket-proxy-for-the-future-b468bc0ff658)

### Distributed Systems
- [Paxos Algorithm](https://en.wikipedia.org/wiki/Paxos_(computer_science))
- [Raft Consensus Algorithm](https://en.wikipedia.org/wiki/Raft_(algorithm))
- [CAP Theorem Explained](https://www.ibm.com/topics/cap-theorem)

### Caching & Data Layers
- [Caching Strategies Guide](https://codeahoy.com/2017/08/11/caching-strategies-and-how-to-choose-the-right-one/)
- [Netflix: TimeSeries Data Abstraction Layer](https://netflixtechblog.com/introducing-netflix-timeseries-data-abstraction-layer-31552f6326f8)
- [Netflix: Key-Value Data Abstraction Layer](https://netflixtechblog.com/introducing-netflixs-key-value-data-abstraction-layer-1ea8a0a11b30)
- [DynamoDB Architecture Deep Dive](https://medium.com/swlh/architecture-of-amazons-dynamodb-and-why-its-performance-is-so-high-31d4274c3129)

### Gen AI
- [LLM Visualization](https://bbycroft.net/llm)

### Companies' Architectures
- [Building Bluesky: a Distributed Social Network](https://newsletter.pragmaticengineer.com/p/bluesky)
- [Scaling ChatGPT](https://newsletter.pragmaticengineer.com/p/scaling-chatgpt)
- [Creating the Notion API](https://www.notion.so/blog/creating-the-notion-api)
- [Herding elephants: Lessons learned from sharding Postgres at Notion](https://www.notion.so/blog/sharding-postgres-at-notion)
- [The Great Re-shard: adding Postgres capacity (again) with zero downtime at Notion](https://www.notion.so/blog/the-great-re-shard)
- [The data model behind Notion's flexibility](https://www.notion.so/blog/data-model-behind-notion)
- [Transaction ID Wraparound in Postgres at Sentry](https://blog.sentry.io/transaction-id-wraparound-in-postgres/)

## System Design Interview Prep
- [System Design Interview Questions 2024](https://www.educative.io/blog/system-design-interview-questions)
- [Consistent Hashing in System Design Interviews](https://interviewnoodle.com/how-to-use-consistent-hashing-in-a-system-design-interview-b738be3a1ae3)

### DevOps
- [Linux Performance Analysis in 60,000 Milliseconds](https://netflixtechblog.com/linux-performance-analysis-in-60-000-milliseconds-accc10403c55)
- [Docker Image Building Best Practices](https://docs.docker.com/get-started/workshop/09_image_best/)
- [DORA Metrics](https://en.wikipedia.org/wiki/DevOps_Research_and_Assessment)
- [Google SRE](https://sre.google/sre-book/table-of-contents/)

## Algorithms & Data Structures

### Complexity & Performance
- [Big-O Algorithm Complexity Cheat Sheet](https://www.bigocheatsheet.com/)
- [A Unified Theory of Garbage Collection](https://www.cs.cornell.edu/courses/cs6120/2019fa/blog/unified-theory-gc/)

### LeetCode Patterns
- [Dynamic Programming Patterns](https://leetcode.com/discuss/study-guide/458695/Dynamic-Programming-Patterns)
- [Substring Problem Patterns](https://leetcode.com/problems/minimum-window-substring/solutions/26808/Here-is-a-10-line-template-that-can-solve-most-'substring'-problems/)
- [Backtracking Problem Patterns](https://leetcode.com/problems/permutations/solutions/18239/A-general-approach-to-backtracking-questions-in-Java-(Subsets-Permutations-Combination-Sum-Palindrome-Partioning)/)
- [Two Pointers Patterns](https://leetcode.com/discuss/study-guide/1688903/Solved-all-two-pointers-problems-in-100-days)
- [Binary Search Patterns](https://leetcode.com/discuss/study-guide/786126/Python-Powerful-Ultimate-Binary-Search-Template.-Solved-many-problems)
- [Sliding Window Patterns](https://leetcode.com/problems/frequency-of-the-most-frequent-element/solutions/1175088/C++-Maximum-Sliding-Window-Cheatsheet-Template/)
- [Graph Patterns](https://leetcode.com/discuss/study-guide/655708/Graph-For-Beginners-Problems-or-Pattern-or-Sample-Solutions)

## Books & Long Reads
- [Scalable Web Architecture and Distributed Systems](https://aosabook.org/en/v2/distsys.html)
- [The Architecture of Open Source Applications](https://aosabook.org/en/)
- [High Scalability - All Time Favourites](http://highscalability.squarespace.com/all-time-favorites/)
- [Disaster Recovery of Workloads on AWS: Recovery in the Cloud](https://docs.aws.amazon.com/pdfs/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-workloads-on-aws.pdf)

## 🤝 Contributing
Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md) before submitting pull requests.