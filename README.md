# 👋 你好，我是ZhuoqunNiu

### 后端工程师 · 基础设施 · 分布式系统

主要关注 **Infrastructure / Distributed Systems / Cloud Native / AI Infrastructure**。

喜欢从系统底层和工程机制出发，研究并实现分布式系统、缓存与存储、云原生控制面、并发运行时以及 Agent Infrastructure。

> **把系统做出来，也理解它为什么这样工作。**

---

## 🚀 重点项目

### [clusterManager](https://github.com/gpvi/clusterManager)

**Redis 集群编排与分布式缓存基础设施**

一个基于 Go 构建的基础设施项目，将 **Redis Cluster 编排、分布式缓存、Kubernetes Operator、gRPC 控制面**结合起来。

主要包含：

* Kubernetes Operator / CRD / Reconcile
* Redis Cluster 创建、扩缩容与生命周期管理
* Kubernetes / Podman / Containerd 多后端
* LRU、Consistent Hash、Singleflight
* 热 Key 检测与副本机制
* SWIM Gossip / 节点发现
* gRPC 远程控制接口
* SQLite 状态持久化
* Redis Slot 并发迁移
* 测试、Race Detection 与故障处理

**技术栈：** `Go` `Kubernetes` `Redis` `gRPC` `Gossip` `SQLite`

---

### [ThreadPool](https://github.com/gpvi/ThreadPool)

**C++ 并发运行时与线程池**

一个 Header-only C++ Thread Pool，重点研究**任务调度、线程生命周期、取消机制、Coroutine 以及并发系统可靠性**。

主要包含：

* C++14 基础实现
* C++20 Coroutine 支持
* Future / Task 调度
* Cooperative Cancellation
* Drain / Cancel Pending / Timed Shutdown
* 动态 Worker 扩缩容
* Coroutine 调度与队列背压
* 异常处理
* Windows / Linux 跨平台
* ASan / UBSan / TSan / Valgrind
* Stress Test 与 Benchmark

**技术栈：** `C++` `Concurrency` `Coroutine` `CMake`

---

### [MysqlAgent](https://github.com/gpvi/MysqlAgent)

**面向数据库操作的 Agent Runtime**

一个围绕 **Agent Workflow、Tool Calling、安全控制与自愈机制**设计的实验性 AI Infrastructure 项目。

核心流程：

```text
        Planner
           │
           ▼
        Safety
           │
           ▼
       Executor
           │
           ▼
       Observer
           │
           ▼
       Explainer
```

主要关注：

* Multi-Agent Workflow
* 显式状态机
* Structured Tool Calling
* Schema RAG
* SQL 生成与自动修复
* Safety Check / RBAC
* Retry / Replan
* Execution Tracing
* Audit Log
* MySQL / PostgreSQL / DuckDB

**技术栈：** `Python` `LLM` `Agent` `RAG` `State Machine`

---

## 🧱 关注方向

### 分布式系统

* 分布式缓存
* 服务发现
* Gossip / Failure Detection
* Replication
* 一致性与容错
* 存储系统

### Cloud Native

* Kubernetes
* Operator / Controller
* CRD
* Control Plane
* Container Runtime
* gRPC
* Observability

### Systems & Performance

* C++ 并发
* Thread Pool
* Coroutine
* Task Scheduling
* Memory / Cache
* Benchmark & Profiling

### AI Infrastructure

* Agent Runtime
* Workflow Orchestration
* Tool Calling
* RAG
* Agent Safety
* LLM Infrastructure

---

## 🛠️ 技术栈

**语言**

`Go` · `C++` · `Python` · `Java` · `TypeScript`
