# 程序员论周

**天津师范大学 · 软件工程 · 2026届本科**

📧 `lunchangzhou@qq.com` | 📄 **简历直达**：[在线简历](https://laoyujianli.com/share/QR2erj) | 📖 **技术博客**：[CSDN](https://blog.csdn.net/m0_74087660)

---

## 🎯 技术聚焦

**后端核心：**
- 熟悉 Java 编程语言，掌握常用类、集合框架、并发编程、JVM 内存模型和 GC 调优
- 熟悉 SSM + Spring Boot 开发框架，能够使用 MyBatis Plus + MyBatis X 自动生成基础 CRUD 代码
- 熟悉 MySQL 数据库及库表设计，能够通过创建索引、Explain 分析等方式优化性能
- 熟悉 Redis，实践过基于 Redis 的分布式缓存、分布式 Session 登录、基于 Redisson 的分布式锁
- 熟悉 RabbitMQ 消息队列，有过手动消息确认、消息持久化、交换机定义、消息生产消费的实践
- 了解 Spring Cloud Alibaba、Dubbo、Nacos、Higress 网关，能将单体项目快速重构为微服务架构
- 熟悉 Vue 框架及组件库，了解 TailWind CSS 框架

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

**项目介绍**：基于 Spring Boot3 + LangChain4j + LangGraph4j 的 AI 零代码应用生成平台。用户输入自然语言描述，由 AI Agent 自动执行一套完整工作流，最终一键部署为可访问的 Web 应用。

**负责工作**：
- 为代码生成、智能路由、质量检查等不同 AI 任务设计系统提示词，并利用阿里云百炼模型对比能力进行调优，通过少样本等技巧提升 LLM 输出的准确性。
- 基于时间游标实现分页对话历史查询，避免传统的深分页性能问题，并通过建立复合索引进一步优化了查询性能 3 倍。
- 将项目构建、封面生成等耗时 I/O 密集型任务异步化，防止请求线程阻塞；通过 Java 21 的虚拟线程执行，避免了传统线程池的资源开销。
- 基于 LangGraph4j 实现了包含素材搜集、代码生成、质量检查、项目构建的多节点自动化工作流，将复杂的应用生成过程流程化。
- 基于 Redisson 的 RRateLimiter 和 Spring AOP，通过自定义注解实现了用户 / IP / 接口级的令牌桶限流，保障 AI 接口的稳定性和成本可控。
- 利用 1Panel 面板 + Docker 容器在 Linux 服务器上快速搭建了前后端环境，并通过 Nginx 配置反向代理后端接口，解决了跨域问题。
- 基于 ARMS 实现多维系统监控告警、Prometheus + Grafana 实现自定义业务指标监控（如大模型 Token 用量），全方位提升可观测性，便于分析系统。
  
---

## 📝 最新博客文章
<!-- BLOG-POST-LIST:START -->
- [坦克大战3.0：防重叠运动实现详解](https://blog.csdn.net/m0_74087660/article/details/157362291)
- [Java多线程实战：坦克大战子弹发射](https://blog.csdn.net/m0_74087660/article/details/157100881)
- [Java多线程入门：创建与结束线程](https://blog.csdn.net/m0_74087660/article/details/157100838)
<!-- BLOG-POST-LIST:END -->

