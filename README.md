# Sunny‘ Books

[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

Table of Content
=================

   * [<a href="00-PDF/README.md">【eBook List】</a>](#ebook-list)
   * [【Reading Notes】](#reading-notes)
      * [【编程思想】](#编程思想)
         * [<a href="Programme/colon-classroom/">*《冒号课堂》</a>](#冒号课堂)
         * [<a href="Programme/functional-thinking/">《函数式编程思维》</a>](#函数式编程思维)
         * [<a href="Programme/Thinking-Like-A-Programmer/">《Thinking Like A Programmer》</a>](#thinking-like-a-programmer)
      * [【编程语言】](#编程语言)
         * [【Java】](#java)
            * [<a href="Language/Java/Thinking-in-Java/README.md">《Thinking in Java》</a>](#thinking-in-java)
            * [<a href="Language/Java/Effective-Java/README.md">《Effective Java》</a>](#effective-java)
            * [<a href="Language/Java/art_of_java_concurrency_programming/README.md">*《Java 并发编程的艺术》</a>](#java-并发编程的艺术)
            * [<a href="Language/Java/java-MT-thread-DP/README.md">《图解 Java 多线程设计模式》</a>](#图解-java-多线程设计模式)
            * [<a href="Language/Java/java-performance-the-definitive-guide/README.md">*《Java 性能权威指南》</a>](#java-性能权威指南)
         * [【Lua】](#lua)
            * [<a href="Language/Lua/lua_programming/README.md">~《Lua 程序设计》</a>](#lua-程序设计)
         * [【C &amp; C  】](#c--c)
            * [<a href="Language/C&amp;C  /linux-c-programming/README.md">*《Linux C 编程一站式学习》</a>](#linux-c-编程一站式学习)
      * [【软件设计】](#软件设计)
         * [<a href="SE/Philosophy-of-SD/README.md">《软件设计的哲学(A Philosophy of Software Design)》</a>](#软件设计的哲学a-philosophy-of-software-design)
         * [<a href="SE/OOAD/README.md">《Object-Oriented Analysis and Design with Applications（面向对象分析与设计）》</a>](#object-oriented-analysis-and-design-with-applications面向对象分析与设计)
         * [<a href="">《分析模式：可复用的对象模型（Analysis Patterns : Reusable Object Models）》</a>](#分析模式可复用的对象模型analysis-patterns--reusable-object-models)
         * [【DDD 领域驱动设计】](#ddd-领域驱动设计)
            * [<a href="SD/DDD/README.md">《领域驱动设计：软件核心复杂性应对之道》</a>](#领域驱动设计软件核心复杂性应对之道)
            * [<a href="SD/Impl-DDD/README.md">《实现领域驱动设计》</a>](#实现领域驱动设计)
      * [【架构】](#架构)
         * [<a href="Arch/SAD/README.md">《系统架构设计》</a>](#系统架构设计)
         * [<a href="">《系统架构：复杂系统的产品设计与开发》</a>](#系统架构复杂系统的产品设计与开发)
         * [<a href="Arch/PoEAA/README.md">《企业应用架构模式（PoEAA）》</a>](#企业应用架构模式poeaa)
         * [<a href="Arch/POSA/README.md">《面向模式的软件架构 - 卷1 ：模式系统》</a>](#面向模式的软件架构---卷1-模式系统)
         * [<a href="Arch/Scalable-Arch/README.md">*《可伸缩架构 : 面向增长应用的高可用》</a>](#可伸缩架构--面向增长应用的高可用)
         * [<a href="Arch/Clean-Arch/README.md">《架构整洁之道》</a>](#架构整洁之道)
         * [<a href="Arch/JESA/README.md">《恰如其分的软件架构 - 风险驱动的设计方法》</a>](#恰如其分的软件架构---风险驱动的设计方法)
         * [<a href="Arch/TAOS/README.md">《架构即未来 - 现代企业可扩展的架构、流程和组织》</a>](#架构即未来---现代企业可扩展的架构流程和组织)
         * [<a href="">O'Reilly《Software Architecture Patterns》</a>](#oreillysoftware-architecture-patterns)
         * [【分布式架构】](#分布式架构)
            * [<a href="Arch/DSSF/README.md">*《分布式服务框架：原理与实践》</a>](#分布式服务框架原理与实践)
            * [<a href="Arch/AAP/README.md">《Akka 应用模式： 分布式应用程序设计实践指南》</a>](#akka-应用模式-分布式应用程序设计实践指南)
         * [【微服务架构】](#微服务架构)
            * [<a href="Arch/MSAPP/README.md">《Micro-Services AntiPatterns and Pitfalls》</a>](#micro-services-antipatterns-and-pitfalls)
      * [【软件工程】](#软件工程)
         * [<a href="SE/BMS/README.md">《代码不朽 — 编写可维护代码的10大要则》</a>](#代码不朽--编写可维护代码的10大要则)
      * [【数据库】](#数据库)
         * [<a href="DB/hp-mysql/README.md">*《高性能 MySQL》</a>](#高性能-mysql)
         * [<a href="DB/mysql-innodb/README.md">*《MySQL 内核 : InnoDB 存储引擎》</a>](#mysql-内核--innodb-存储引擎)
         * [<a href="DB/effective_mysql_sql_statements/README.md">《Effective MySQL : Optimizing SQL Statements》</a>](#effective-mysql--optimizing-sql-statements)
         * [<a href="">《Relational Database Index Design and the Optimizers》</a>](#relational-database-index-design-and-the-optimizers)
         * [<a href="DB/effective_sql/README.md">《Effective SQL : 编写高质量SQL语句的61个有效方法》</a>](#effective-sql--编写高质量sql语句的61个有效方法)
      * [【Web】](#web)
         * [<a href="Web/understanding-nginx/README.md">《深入理解 Nginx：模块开发和架构解析》</a>](#深入理解-nginx模块开发和架构解析)
         * [<a href="Web/restful-web-apis/README.md">《RESTful Web APIS》</a>](#restful-web-apis)
         * [<a href="Web/java-restful-web-service-in-action/README.md">《Java RESTful Web Service 实战》</a>](#java-restful-web-service-实战)
         * [<a href="Web/write-a-java-web-framework/README.md">《架构探险 ：从零开始写 Java Web 框架》</a>](#架构探险-从零开始写-java-web-框架)
      * [【大数据】](#大数据)
         * [<a href="BigData/design-data-intensive-app/README.md">*《数据密集型应用系统设计》</a>](#数据密集型应用系统设计)
         * [<a href="BigData/mapreduce-dp/README.md">《MapReduce 设计模式》</a>](#mapreduce-设计模式)
         * [<a href="BigData/data-algorithms/README.md">《数据算法 ： Hadoop/Spark 大数据处理技巧》</a>](#数据算法--hadoopspark-大数据处理技巧)
         * [<a href="BigData/streaming-architecture/README.md">《流式架构 ： Kafka 与 MapR Streams 数据流处理》</a>](#流式架构--kafka-与-mapr-streams-数据流处理)
         * [<a href="BigData/programming-hive/README.md">《Hive 编程指南》</a>](#hive-编程指南)
         * [<a href="BigData/DataStrategy/README.md">《数据战略》</a>](#数据战略)
         * [【区块链】](#区块链)
            * [<a href="Blockchain/dapp/README.md">*《去中心化应用 : 区块链技术概述》</a>](#去中心化应用--区块链技术概述)
            * [<a href="Blockchain/algos_in_blockchain/README.md">《区块链核心算法解析》</a>](#区块链核心算法解析)
      * [【性能】](#性能)
         * [<a href="Programme/profile/sys-performance/">《性能之巅：洞悉系统、企业和云计算》</a>](#性能之巅洞悉系统企业和云计算)
         * [<a href="Programme/profile/BPF-Perf/README.md">《BPF Performance Tools: Linux System and Application Observability》</a>](#bpf-performance-tools-linux-system-and-application-observability)
      * [【基础技术】](#基础技术)
         * [<a href="Basics/mastering-RE/README.md">《Mastering RE》</a>](#mastering-re)
      * [【计算机架构体系】](#计算机架构体系)
         * [<a href="https://www.e-reading.club/bookreader.php/138837/Jacob,_Ng,_Wang_-_Memory_systems._Cache,_DRAM,_Disk.pdf" rel="nofollow">《Memory Systems Cache, DRAM, Disk》</a>](#memory-systems-cache-dram-disk)
         * [<a href="https://akkadia.org/drepper/cpumemory.pdf" rel="nofollow">《What Every Programmer Should Know About Memory》</a>](#what-every-programmer-should-know-about-memory)
      * [【产品】](#产品)
         * [【黑客增长】](#黑客增长)
            * [<a href="Product/GrowthHackers/README.md">*《增长黑客》</a>](#增长黑客)
            * [<a href="Product/CGO/README.md">《首席增长官》</a>](#首席增长官)
            * [<a href="Product/SmartGrowth/README.md">《智能增长》</a>](#智能增长)
         * [<a href="Product/LeanAnalytics/README.md">《精益数据分析》</a>](#精益数据分析)