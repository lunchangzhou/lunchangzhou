# 程序员论周

**天津师范大学 · 软件工程 · 2026届本科**

📧 `lunchangzhou@qq.com` | 📄 **简历直达**：[在线简历](https://laoyujianli.com/share/QR2erj) | 📖 **技术博客**：[CSDN](https://blog.csdn.net/m0_74087660)

---

## 🎯 技术聚焦

**后端核心：**
*   **Java：** 熟练掌握集合、多线程并发编程（JUC）、JVM内存模型与垃圾回收机制
*   **框架：** 熟悉Spring Boot、Spring MVC、MyBatis-Plus生态，理解IoC、AOP等核心思想
*   **数据库：**
    *   **MySQL：** 索引优化、事务隔离级别、锁机制、有SQL调优经验
    *   **Redis：** 常用数据结构、持久化方案、缓存穿透/击穿/雪崩解决方案
*   **中间件：** 了解RabbitMQ基本模型与应用场景
*   **开发运维：** 熟练使用Git、Maven，掌握Linux常用命令，了解Docker基本操作

**扩展技能：**
*   了解Spring Cloud (Nacos, OpenFeign)微服务架构
*   可使用Vue + Element Plus进行基础前端开发
*   具备Python爬虫开发经验（Scrapy框架）

---

## 🚀 项目经历

> **说明**：以下为我独立完成的**真实项目**，代码已开源。项目均从实际问题出发，包含了技术选型、性能优化和问题解决的完整思考。

### 1. [**知乎风格问答社区 - 后端服务**](你的真实GitHub仓库链接)
*一个聚焦后端逻辑与性能优化的内容社区系统*
**技术栈：** Spring Boot 2.7, MyBatis-Plus, MySQL 8.0, Redis, JWT, Hutool
*   **核心设计：**
    *   采用**RESTful API**设计，实现用户认证、问题发布、回答、评论、点赞等核心功能模块。
    *   使用 **Redis** 实现高频访问的`用户信息`、`热点问题`缓存，降低数据库压力约60%。
    *   通过 **JWT** 实现无状态token认证，并设计拦截器统一处理权限验证。
*   **性能优化实践：**
    *   针对`问题列表`接口，使用MyBatis-Plus分页插件优化，并结合**覆盖索引**提升查询速度。
    *   对`点赞/取消点赞`功能，利用Redis的**Set数据结构**实现，并通过**定时任务**异步持久化到DB，保证响应速度。
*   **工程化：** 统一封装了业务异常和API响应对象，项目结构清晰，包含详细的接口文档与部署说明。
*   **项目链接：** [https://github.com/yourname/zhihu-project](https://github.com/yourname/zhihu-project)

### 2. [**校园二手书交易平台**](你的另一个真实项目仓库链接)
*一个包含完整前后端的校园级应用*
**技术栈：** Spring Boot, Vue 3, Element Plus, MySQL, Redis
*   **系统亮点：**
    *   **全栈实现：** 独立完成从数据库设计、后端API到前端页面的开发。
    *   **搜索优化：** 针对书名、描述字段，在数据库层实现**模糊查询优化**。
    *   **状态机管理：** 为商品订单设计了清晰的**状态流转逻辑**（待付款、已发货、已完成等）。
    *   **部署实践：** 项目已使用Docker容器化，并编写了一键部署脚本。
*   **项目链接：** [https://github.com/yourname/second-hand-books](https://github.com/yourname/second-hand-books)

---

## 📝 最新博客文章
<!-- BLOG-POST-LIST:START -->
- [Java异常处理最佳实践指南](https://blog.csdn.net/m0_74087660/article/details/156872493)
- [枚举与注解：提升代码可读性与维护性](https://blog.csdn.net/m0_74087660/article/details/156872300)
- [Java面向对象高级特性详解](https://blog.csdn.net/m0_74087660/article/details/156834053)
<!-- BLOG-POST-LIST:END -->

