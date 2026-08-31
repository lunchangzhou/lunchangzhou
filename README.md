# 论昌周 · AI 应用开发工程师

> Java 后端开发工程师，专注于 AI Agent、RAG、Tool Calling、MCP 与可落地的 AI 产品。

我擅长把一个想法拆成可运行的产品：从需求分析、后端架构和模型接入，到前端交互、数据存储、部署与问题排查，持续关注系统的可维护性、稳定性和真实使用体验。

## 我正在寻找

AI 应用开发、AI Agent 应用开发、Java 后端开发岗位。

希望参与将大模型能力接入真实业务的团队，重点关注：

- Agent 工作流与工具调用
- RAG 知识库与检索增强
- AI 应用的会话、权限、限流和成本控制
- Java 后端服务、数据一致性与可观测性

## 技术方向

| 方向 | 实践内容 |
| --- | --- |
| AI 应用 | Spring AI、LangChain4j、Prompt、Chat Memory、Tool Calling、MCP、Multi-Agent |
| 检索增强 | 文档 ETL、向量化、PGvector、查询扩展、查询重写、元信息标注 |
| Java 后端 | Spring Boot 3、MyBatis-Plus、Spring Cloud、Dubbo、SSE、异步任务 |
| 数据与基础设施 | MySQL、Redis、Caffeine、Elasticsearch、COS、Docker、Nginx |
| 工程实践 | 设计模式、接口抽象、限流、分布式锁、索引优化、日志检索、监控告警 |
| 全栈交付 | Vue 3、React、FastAPI、Express、Serverless 部署 |

## 代表项目

### AI 超级智能体

- GitHub 仓库：`待补充`
- 在线演示：`待补充`

一个基于 Spring Boot 3 + Spring AI 的企业级 AI Agent 应用，支持多轮对话、持久化记忆、RAG 知识库、工具调用、MCP 服务和 SSE 流式输出。

核心实践：

- 统一接入通义、Ollama 等多种模型，保留模型切换和本地部署能力。
- 基于 ChatMemory、Advisor 和 MySQL + Redis 实现会话记忆持久化。
- 完成文档 ETL、PGvector 向量检索、元信息标注、多查询扩展和查询重写。
- 集成联网搜索、网页抓取、PDF 生成、资源下载等工具，并加入参数校验和用户上下文传递。
- 实现支持 Human-in-the-Loop 的分层 Agent，加入步骤上限、状态管理和死循环检测。
- 使用 SseEmitter + CompletableFuture 输出流式推理和工具执行过程。

### AI 零代码应用生成平台

- [GitHub 仓库](https://github.com/lunchangzhou/ai-code-generator)
- 在线演示：`待补充`

基于 Spring Boot 3 + LangChain4j 的 AI 应用生成平台。用户用自然语言描述需求，由 Agent 执行代码生成、解析、保存和部署流程，最终得到可访问的 Web 应用。

我重点实践了：

- 通过声明式 AI Service 接入 DeepSeek、通义等模型。
- 用门面、策略和模板方法组织不同应用生成模式，降低扩展成本。
- 使用 Redis 持久化对话历史，并通过 Caffeine 做多用户会话隔离。
- 使用时间游标分页查询历史消息，配合复合索引改善深分页查询。
- 封装 COS 文件上传与过期资源清理能力。
- 提供文件读写、修改、删除和目录读取工具，并增加路径与操作安全校验。
- 基于 Redisson RRateLimiter + Spring AOP 实现用户、IP、接口级令牌桶限流。

### AI 热点监控工具

- [GitHub 仓库](https://github.com/lunchangzhou/hot-monitor)
- 在线演示：`待补充`

基于 Express 5、React 19 和 OpenRouter 的 AI 热点监控工具，聚合多个信息源，利用模型进行内容审核、真假识别和相关性分析。

- 技术栈：Node.js、Express、React、TypeScript、Prisma、SQLite、Axios、Cheerio、node-cron
- 关注点：多源采集、定时任务、AI 分析、数据持久化和前端信息呈现

### AI 视频下载与内容总结工具

- [GitHub 仓库](https://github.com/lunchangzhou/video-downloader)
- 在线演示：`待补充`

基于 Vue 3、FastAPI、yt-dlp 和 DeepSeek 的内容处理工具，支持视频下载、AI 总结和 Stripe 国际支付接入。

- 技术栈：Vue 3、FastAPI、Python、yt-dlp、DeepSeek、Stripe
- 关注点：跨技术栈协作、异步任务、内容处理和产品化交付

## 业务系统经验

在继续教育平台财务系统中，我参与并负责过支付、订单、导出和日志可观测相关工作：

- 使用策略模式与工厂模式抽象微信、支付宝和商业银行支付差异。
- 重构重修费订单同步模型，围绕订单状态和审核记录维护账务一致性。
- 针对 50 万级数据导出，实践索引设计、分批查询和流式写入。
- 基于 Elasticsearch + Kibana 统一关键业务日志，支持按订单检索和异常追踪。

这些经验让我更关注 AI 应用落地时同样重要的工程问题：状态是否可追踪、失败是否可恢复、成本是否可控制、结果是否方便验证。

## 我的工作方式

- 先明确需求边界，再拆解任务和验收标准。
- 优先阅读官方文档和源码，记录关键设计决策。
- 用小步提交和可复现步骤降低排查成本。
- 借助 Cursor、Codex、GitHub Copilot 等工具提高效率，但保留人工审核和测试验证。
- 关注从模型调用到数据库、任务和前端的完整链路，而不只追求 Demo 能运行。

## 更多信息

- 作品集 / 个人站点：[lunchangzhou.com](https://lunchangzhou.com)
- 技术博客：[CSDN](https://blog.csdn.net/m0_74087660)
- 邮箱：`lunchangzhou@qq.com`

如果你正在做 AI Agent、企业 AI 应用或 Java 后端系统，欢迎交流。
