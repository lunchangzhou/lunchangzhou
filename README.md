# 程序员论周

**天津师范大学 · 软件工程 · 2026届本科**

📧 `lunchangzhou@qq.com` | 📄 **简历直达**：[在线简历](https://laoyujianli.com/share/QR2erj) | 📖 **技术博客**：[CSDN](https://blog.csdn.net/m0_74087660)

---

## 🎯 技术聚焦

**后端核心：**
- 熟悉 Java 编程语言，掌握常用类、集合、并发编程、JVM 内存模型和 GC 调优
- 熟悉 SSM + Spring Boot 开发框架，并能运用 Hutool、Lombok、Knife4j 等类库提高开发效率。
- 熟悉 MySQL 数据库，理解索引、事务、存储引擎、MVCC、锁、分库分表，且具备一定的 SQL 调优能力
- 熟悉 Redis，实践过基于 Redis 的分布式缓存、分布式 Session 登录、基于 Redisson 的分布式锁
- 熟悉 RabbitMQ 消息队列，有过手动消息确认、消息持久化、交换机定义、消息生产消费的实践
- 熟悉计算机网络、操作系统，如 HTTP、TCP / UDP、进程、线程、虚拟内存等
- 了解 Spring Cloud Alibaba、Dubbo、Nacos、Higress 网关，能将单体项目快速重构为微服务架构

**扩展技能：**
- 具备 Python 爬虫开发经验

---

## 🚀 项目经历

### 1. 优搭校园
- 使用 Redis 实现分布式 Session，解决集群间登录态同步问题；并使用 Hash 代替 String 来存储用户信息，节约了 35% 的内存并便于单字段的修改。
- 为解决首次访问系统的用户主页加载过慢的问题，使用 Spring Scheduler 定时任务来实现缓存预热，并通过分布式锁保证多机部署时定时任务不会重复执行。
- 为解决同一用户重复加入队伍、入队人数超限的问题，使用 Redisson 分布式锁来实现操作互斥，保证了接口幂等性。
- 使用编辑距离算法实现了根据标签匹配最相似用户的功能，并通过优先队列来减少 TOPN 运算过程中的内存占用。

### 2. AI 零代码应用生成平台
**GitHub 链接：** https://github.com/lunchangzhou/ai-code-generator

**项目介绍**：基于 Spring Boot3 + LangChain4j 的 AI 零代码应用生成平台。用户输入自然语言描述，由 AI Agent 自动执行一套完整工作流，最终一键部署为可访问的 Web 应用。

**负责工作**：
- 利用 LangChain4j 框架集成 DeepSeek、通义等多种 AI 大模型，通过声明式的 AI Service 编程模型快速实现模型调用和网站生成。
- 项目实现了原生、Vue 工程等多种网站生成模式，综合运用门面模式统一 AI 调用入口、策略模式与模板方法模式处理各类代码解析和保存逻辑，提升代码的可扩展性。
- 整合 Redis 和 LangChain4j 实现 AI 对话历史的持久化存储，支持通过多轮对话来优化生成的网站，并通过 AI Service + Caffeine 实现了多用户会话的隔离。
- 基于时间游标实现分页对话历史查询，避免传统的深分页性能问题，并通过建立复合索引进一步优化了查询性能 3 倍。
- 基于 COS 对象存储 SDK 封装了通用文件上传服务，将应用封面图上云持久化存储，并通过定时任务清理过期资源，节约成本。
- 开发了文件读、写、修改、删除、目录读取等文件操作工具，拓宽 AI 能力边界，并通过安全校验防止 AI 误操作导致应用损坏。
- 通过抽象 BaseTool 基类和利用 Spring 自动注入机制实现了 ToolManager，对所有 AI 工具进行统一注册和管理，提升系统的可扩展性。
  
---

## 📝 最新博客文章
<!-- BLOG-POST-LIST:START -->
- [坦克大战3.0：防重叠运动实现详解](https://blog.csdn.net/m0_74087660/article/details/157362291)
- [Java多线程实战：坦克大战子弹发射](https://blog.csdn.net/m0_74087660/article/details/157100881)
- [Java多线程入门：创建与结束线程](https://blog.csdn.net/m0_74087660/article/details/157100838)
<!-- BLOG-POST-LIST:END -->

