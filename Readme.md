This is an excellent collection of technical resources! I've grouped your bookmarks into the following main categories for easier navigation.

***

## 💻 Programming Languages & Concurrency

This group includes resources for specific languages, focusing heavily on modern concurrency models and performance.

* **Rust (Async & Low-Level):**
    * [Introduction - Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/)
    * [100 Exercises To Learn Rust](https://rust-exercises.com/100-exercises/)
    * **Async Rust** in Three Parts, Runtimes, and the official [Asynchronous Programming in Rust](https://rust-lang.github.io/async-book/)
    * [Rust Atomics and Locks by Mara Bos](https://marabos.nl/atomics/)
    * [A half-hour to learn Rust](https://fasterthanli.me/articles/a-half-hour-to-learn-rust)
    * [Ethereum, but made in Rust](https://0xrusowsky.github.io/blog/articles/ethereum-made-in-rust/) and [Ethereum Virtual Machine (in Rust) - Part 1](https://0xrusowsky.github.io/blog/articles/revm-pt1/)

* **Go (Golang):**
    * **Concurrency:** [Notes on structured concurrency, or: Go statement considered harmful](https://vorpus.org/blog/notes-on-structured-concurrency-or-go-statement-considered-harmful/), [Building conc: Better structured concurrency for Go](https://sourcegraph.com/blog/building-conc-better-structured-concurrency-for-go), and [Using WaitGroups in Go without Leaky Abstractions](https://sarat.dev/blog/waitgroup-leaky-abstractions/)
    * [go-gc.pdf](https://go.dev/talks/2015/go-gc.pdf) (Garbage Collection)
    * [Hacking sum types with Go generics](https://blog.lawrencejones.dev/go-sum-type/)
    * [Go Optimization Guide](https://goperf.dev/)
* **Concurrency & I/O Multiplexing (General):**
    * A large cluster of links on **epoll, select, and kqueue**, which are fundamental APIs for non-blocking I/O on Linux and other systems.
    * [Structured Concurrency](https://www.youtube.com/watch?v=1Wy5sq3s2rg) (Multiple links) and [Concurrency | Zaid Humayun’s Blog](https://redixhumayun.github.io/concurrency/#Atomics)
    * [Multithreaded Asynchronous I/O & I/O Completion Ports](https://www.drdobbs.com/cpp/multithreaded-asynchronous-io-io-comple/201202921) (Windows I/O)
* **Other Languages & Concepts:**
    * [Useful online resources to learn Haskell](https://pusher.com/blog/best-free-online-resources-to-learn-haskell/#references)
    * [Introduction to libuv](https://nikhilm.github.io/uvbook/introduction.html)
    * [ContinuationsSB.pdf](https://www.cs.cmu.edu/~me/courses/15-150-Spring2020/lectures/12/ContinuationsSB.pdf) and [Continuation-Passing Style](https://www.youtube.com/watch?v=0-h8bwNXaTc)
    * [C++ at Google: Here Be Dragons](https://google-engtools.blogspot.com/2011/05/c-at-google-here-be-dragons.html)

***

## 🌐 Distributed Systems & Networking

This is a deep-dive collection into system design, consensus, and network protocols.

* **Consensus & Reliability:**
    * **CRDTs (Conflict-free Replicated Data Types):** [CRDT Research Meetup Lisbon](https://www.youtube.com/playlist?list=PLuhRWgmPaHtTVkko1ZTn-qcGb-n6EqHff), [CRDT Talks](https://www.youtube.com/playlist?list=PLuhRWgmPaHtSvjFsjaVm_Fj9nXuwW35Ai), and [Journal Club - CRDT JSON Datatype](https://www.youtube.com/watch?v=TRvQzwDyVro)
    * [Assignment 4: Raft Leader Election](https://gwadvnet20.github.io/assignments/raft-election/)
    * [Navigating the Jungle of Distributed Systems: Zookeeper and Leader Election](https://hewi.blog/navigating-the-jungle-of-distributed-systems-a-guide-to-zookeeper-and-leader-election-algorithms)
    * [A Brief Tour of FLP Impossibility](https://web.archive.org/web/20230603122927/https://www.the-paper-trail.org/post/2008-08-13-a-brief-tour-of-flp-impossibility/)
    * [Memory Consistency Models: A Tutorial](https://jamesbornholt.com/blog/memory-models/)

* **Messaging & Data Flow:**
    * **Kafka:** [White Paper Summaries | Apache Kafka](https://hewi.blog/white-paper-summaries-apache-kafka), [Kafka Internals](https://www.pyblog.xyz/kafka-internals), [Diskless Kafka - The Cloud-Native Revolution](https://www.geeknarrator.com/blog/diskless-kafka-kip-1150)
    * [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
    * [Every Outbox Needs an Inbox](https://newsletter.systemdesignclassroom.com/p/every-outbox-needs-an-inbox)

* **Core Systems & Learning:**
    * [Learning Distributed Systems: where to start?](https://muratbuffalo.blogspot.com/2020/06/learning-about-distributed-systems.html)
    * [Introduction to Reliable and Secure Distributed Programming - Textbook](https://www.distributedprogramming.net/)
    * [COS 418 - S22 - Distributed Systems](https://www.cs.princeton.edu/courses/archive/spr22/cos418/schedule.html) (Course)
    * [How Apple built iCloud to store billions of databases](https://read.engineerscodex.com/p/how-apple-built-icloud-to-store-billions)

* **Networking:**
    * [From LAN to VXLAN](https://labs.iximiuz.com/courses/computer-networking-fundamentals/from-lan-to-vxlan?expand=all)
    * [Understanding TLS](https://newsletter.francofernando.com/p/understanding-tls-how-data-stays)
    * [What's Smoother Than Your Morning Espresso Pull? Bridging Gaps with BGP and Cilium!](https://www.youtube.com/watch?v=SgKNIGmXqq8&pp=ygUMY29udGFpbmVybGli)

***

## 🧠 Machine Learning, AI & Data Science

This section covers deep learning fundamentals, large language models (LLMs), and scalable data algorithms.

* **Deep Learning & LLMs:**
    * **Core Concepts:** [Understanding and Coding the Self-Attention Mechanism of Large Language Models From Scratch](https://sebastianraschka.com/blog/2023/self-attention-from-scratch.html), [Flash Attention](https://liyuan24.github.io/writings/flash_attention.html)
    * **Architectures:** [MobileNet Research Paper Walkthrough](https://www.youtube.com/watch?v=HD9FnjVwU8g), [From Transformer to LLM](https://scholar.harvard.edu/binxuw/classes/machine-learning-scratch/materials/transformers)
    * **Training Large Models:** [Techniques for training large neural networks](https://openai.com/index/techniques-for-training-large-neural-networks/), [How to Train Really Large Models on Many GPUs?](https://lilianweng.github.io/posts/2021-09-25-train-large/)
    * **Reading Lists:** [Language Modeling Reading List](https://eugeneyan.com/writing/llm-reading-list/), [Foundational must read GPT/LLM papers](https://community.openai.com/t/foundational-must-read-gpt-llm-papers/197003)

* **Algorithms & Big Data Systems:**
    * **Approximate Nearest Neighbor (ANN):** [DiskANN and the Vamana Algorithm](https://zilliz.com/learn/DiskANN-and-the-Vamana-Algorithm), [Great Algorithms Are Not Enough | Pinecone](https://www.pinecone.io/blog/hnsw-not-enough/)
    * **Data Sketching:** [Algorithms for Big Data: Lecture 07 - CountSketch, l\_p sampling, Graph sketching](http://www.infocobuild.com/education/audio-video-courses/computer-science/CS229R-Fall2015-Harvard/lecture-07.html)
    * [My favorite algorithm (and data structure): HyperLogLog](https://odino.org/my-favorite-data-structure-hyperloglog/)
    * [Exploring Hidden Markov Models](https://nipunbatra.github.io/hmm/)
    * [Kalman Filter](https://www.weideng.org/posts/kalman_filter/)

* **ML Systems & Hardware:**
    * [Hardware Accelerators for Machine Learning (CS 217)](https://cs217.stanford.edu/) (Course & Readings)
    * [11-767: On-Device Machine Learning](https://strubell.github.io/teaching/11-767/) (Course)

***

## 💾 Databases & Data Engineering

Resources focusing on data storage, processing, and warehousing.

* **Data Lake/Warehouse:**
    * **Apache Iceberg:** [Apache Iceberg Internals Dive Deep On Performance](https://relentless-leader.com/apache-iceberg-performance-dive-deep.html), [Architectural Insights](https://www.dremio.com/resources/guides/apache-iceberg-an-architectural-look-under-the-covers/), and [Ultimate Directory of Apache Iceberg Resources](https://dev.to/alexmercedcoder/ultimate-directory-of-apache-iceberg-resources-56i0)
    * [Apache Spark Architecture 101](https://www.chaosgenius.io/blog/apache-spark-architecture/#:~:text=1,Directed%20Acyclic%20Graphs%20%28DAGs)), [Why Apache Spark RDD is immutable?](https://luminousmen.com/post/why-apache-spark-rdd-is-immutable)

* **Database Internals & Design:**
    * [FoundationDB: A Distributed Unbundled Transactional Key Value Store](https://www.micahlerner.com/2021/06/12/foundationdb-a-distributed-unbundled-transactional-key-value-store.html)
    * [DuckDB is Probably the Most Important Geospatial Software of the Last Decade](https://www.dbreunig.com/2025/05/03/duckdb-is-the-most-impactful-geospatial-software-in-a-decade.html)
    * [CS 6530 – Adv. Database Systems](https://users.cs.utah.edu/~pandey/courses/cs6530/fall24/index.html) (Course)
    * [Modern Hardware for Future Databases](https://transactional.blog/blog/2024-modern-database-hardware)
    * [Why physical storage of your database tables might matter](https://lambda.blinkit.com/why-physical-storage-of-your-database-tables-might-matter-74b563d664d9?gi=5a37f3d3e66e)

* **Data Quality & Pipeline:**
    * [What Is An ETL Pipeline?](https://estuary.dev/blog/what-is-an-etl-pipeline/)
    * [DataHub: Popular metadata architectures explained](https://www.linkedin.com/blog/engineering/data-management/datahub-popular-metadata-architectures-explained)
    * [In-Memory Data Quality Check - Tutorial with Great Expectation](https://towardsdatascience.com/in-memory-data-quality-check-tutorial-with-great-expectation-54913b1c37fa/)

***

## 🖥️ Computer Architecture & Operating Systems

This category includes resources on hardware fundamentals, system programming, and virtualization.

* **Low-Level & Kernel:**
    * [CS:APP3e, Bryant and O'Hallaron](https://csapp.cs.cmu.edu/3e/students.html) (The famous "Computer Systems: A Programmer's Perspective" book)
    * [Dive into Systems :: Dive Into Systems](https://diveintosystems.org/book/index.html)
    * [Beginner's Guide to Linkers](https://www.lurklurk.org/linkers/linkers.html) and [ELF the Executable and Linkable Format](https://www.linkedin.com/pulse/elf-executable-linkable-format-ronal-antonio-aguirre-villalobos-/)
    * [Deep into Container — Linux Namespaces and Cgroups](https://faun.pub/kubernetes-story-linux-namespaces-and-cgroups-what-are-containers-made-from-d544ac9bd622) and [How to Run a Container Without an Image](https://iximiuz.com/en/posts/you-dont-need-an-image-to-run-a-container/)

* **Hardware & Performance:**
    * [Fundamentals of CMOS Devices](https://www.iue.tuwien.ac.at/phd/gehring/node11.html) and [Digital Integrated Circuits](https://eecs.berkeley.edu/book/online-specializations-programs/ic/courses/eew241a/)
    * [CPU Cache Basics](https://dev.to/larapulse/cpu-cache-basics-57ej) and [Measuring Cache Latencies](https://stackoverflow.com/questions/21369381/measuring-cache-latencies)
    * [Memory Systems](https://safari.ethz.ch/memory_systems/2018/doku.php?id=start)

* **Virtualization & Security:**
    * **Hypervisors:** Multiple links on building a **Hypervisor From Scratch** in Rust and general concepts.
    * [AppArmor](https://apparmor.net/)

***

## 🖼️ Computer Graphics & Rendering

This set of bookmarks is focused on the theory and practice of photo-realistic rendering.

* [Scratchapixel 3.0, Learn Computer Graphics Programming](https://www.scratchapixel.com/index.html) (A comprehensive online textbook)
* **Physically-Based Rendering (PBR):**
    * [Photo-realistic vs. Physically-based Rendering](https://radsite.lbl.gov/radiance/refer/Notes/rendering_note.html)
    * [s2012\_pbs\_disney\_brdf\_notes\_v3.pdf](https://blog.selfshadow.com/publications/s2012-shading-course/burley/s2012_pbs_disney_brdf_notes_v3.pdf) (The foundational Disney BRDF paper)
    * [Rendering the Moana Island Scene Part 1: Implementing the Disney BSDF](https://schuttejoe.github.io/post/disneybsdf/)
* [An Introduction to the Browser Rendering Pipeline](https://webperf.tips/tip/browser-rendering-pipeline/)
* [Graphics Programming - Where To Start?](https://www.stefanpijnacker.nl/article/graphics-programming-where-to-start/)

***

## 📚 General Systems & Career

This group contains general-purpose resources, reading lists, personal sites, and courses.

* **Technical Papers & Collections:**
    * [Fermat's Library](https://fermatslibrary.com/)
    * [papers-we-love/machine\_learning](https://github.com/papers-we-love/papers-we-love/tree/main/machine_learning)
    * [The Bitter Lesson](http://www.incompleteideas.net/IncIdeas/BitterLesson.html) (AI Philosophy)
    * [research!rsc: Zip Files All The Way Down](https://research.swtch.com/zip) (Rob Pike's blog)
    * [The Treacherous Optimization](https://ridiculousfish.com/blog/posts/old-age-and-treachery.html)

* **Career & Technical Culture:**
    * [Accelerate](https://itrevolution.com/product/accelerate/) (DevOps book)
    * [xkcd: Standards](https://xkcd.com/927/)
    * [advice\_column - James C. Hoe](https://users.ece.cmu.edu/~jhoe/doku/doku.php?id=advice_column)
    * [Leaving Google – Airs – Ian Lance Taylor](https://www.airs.com/blog/archives/670)

* **Courses & Textbooks:**
    * [Applied Mathematical Methods by Bhaskar Dasgupta](https://home.iitk.ac.in/~dasgupta/MathBook/)
    * [Virtualization and Cloud Computing](https://www.cse.iitb.ac.in/~mythili/virtcc/index.html)
    * [CS 7280/4973 – Data Structures & Algorithms for Scalable Computing](https://www.khoury.northeastern.edu/home/pandey/courses/cs7280/spring25/index.html)
