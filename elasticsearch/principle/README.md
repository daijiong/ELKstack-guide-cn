# 架构原理

本书作为 ELKstack 指南，关注于 Elasticsearch 在日志和数据分析场景的应用，并不打算对底层的 Lucene 原理或者 Java 编程做详细的介绍，但是 Elasticsearch 层面上的一些架构设计，对我们做性能调优，故障处理，具有非常重要的影响。

所以，作为 ES 部分的起始章节，先从数据流向和分布的层面，介绍一下 ES 的工作原理，以及相关的可控项。各位读者可以跳过这节先行阅读后面的运维操作部分，但作为性能调优的基础知识，依然建议大家抽时间返回来了解。