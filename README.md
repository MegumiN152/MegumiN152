<h1 align="center"> <a href="https://sunguoqi.com/"> <img src="https://readme-typing-svg.herokuapp.com/?lines=console.log(%22Hello%2C%20World!%22);祝您今天愉快!&center=true&size=27"> </a> </h1>
<a href="https://github.com/luoye6/computer-vision-in-action">
    <img align="right" src="https://komarev.com/ghpvc/?username=luoye6&label=Visitors&color=red&style=flat&logo=github" alt="gtihub-visitors" />
</a>
 
## Hi, 👋  I'm <a href="https://github.com/jacffg">MegumiN152</a>
 <p align="center">
  🎯 Java 后端工程师 | 💻 专注于高并发、高可用系统设计 | 🌱 求职中
</p>

---

## 🚀 关于我
- 📚 **学历**：江西财经大学 软件工程（本科，2021.09 - 2025.07）  
- 🔍 **技能**：
  - 熟练掌握 JavaSE 特性（集合、多线程、反射、自定义注解等）。
  - 熟悉主流框架：Spring、Spring Boot、MyBatis、MyBatis-Plus 等。
  - 擅长数据库优化与设计，熟练使用 MySQL、Redis、Elastic Stack 等。
  - 深入理解分布式系统开发，掌握消息队列（RabbitMQ）、缓存优化（Redisson）等技术。
  - 了解企业级性能和安全优化方案，如 RBAC 鉴权、流控熔断降级、分布式锁、反爬虫等。
  - 熟悉常见设计模式（单例、工厂、观察者等）。

---

## 💼 项目经历
### [HHOJ判题平台](http://www.huanghao.icu/)
> **技术栈**：Spring Boot, MySQL, Redis, Elasticsearch, RabbitMQ, Nacos，Docker,AI大模型，gateway网关

- **项目简介**：一个面向程序员的OJ判题平台，支持题目检索、题目提交记录、题目标记、评论点赞、数据统计等功能。
- **技术亮点**：
- 基于 SpringCloud微服务+ MQ + Docker +AIGC+JWT的编程题目评测系统。系统能够根据管理员预设的题目用例对用户提交的代码进行执行和评测；系统中 自主实现的代码沙箱可作为独立服务供其他开发者调用。
    + 自主设计判题机模块的架构。定义了代码沙箱的抽象调用接口和多种实现类（比如远程/本地沙箱），并通过静态工厂+ Spring配置化的方式实现了对多种代码沙箱的灵活调用。
    + 后端自定义Prompt预设模板并封装题目内容，通过对接AIGC接口生成对应的题解分析和代码。
    + 为防止某用户恶意占用系统资源，基于 Redisson 的 RateLimiter 实现分布式限流，控制单用户提交题目和评论的频率。
    + 通过自测代码沙箱。模拟了多种程序异常情况并针对性解决，如使用守护线程+Thread.Sleep等待机制实现类对进程的超时中断、使用 黑白名单+字典树的方式实现了对敏感操作的限制。
    + 为保证沙箱宿主机的稳定性，选用Docker隔离用户代码，使用 Docker Java库创建容器隔离执行代码，并通过tty和Docker进行传参交互，从而实现了更安全的代码沙箱。
    + 为防止判题操作执行时间较长，在题目服务中将用户提交 id 发送给 RabbitMQ 消息队列，并通过 Direct 交换机转发给判题队列，由判题服务进行消费，异步更新提交状态。


### 上海衡南智能有限公司
- **职责**：
    - 复旦学情屏：基于Spring Boot开发Classin数据对接接口，日均处理10万+条课堂行为数据，通过Redis缓存+异步落盘优化，接口响应≤200ms，前端查询性能提升70%。
    - 物联网设备协议：基于Netty实现PDU/矩阵等设备高并发控制（5000+连接），设计Jar包热加载方案，部署效率提升95%，心跳检测机制保障系统稳定性99.9%。
    - 交大教务调度：交大运动会期间，通过MySQL批量集合操作（替代游标）优化课程调度，冲突检测性能提升300%，任务耗时从15分钟降至45秒，事件调度实现零人工干预。

---

## 🛠 技术栈
- **语言**：Java | SQL | JavaScript
- **框架**：Spring Boot | MyBatis | SpringCloud
- **工具**：Redis | RabbitMQ | Elastic Stack | Docker | Git
- **设计模式**：单例模式 | 策略模式 | 工厂模式 | 观察者模式

---

## 📫 联系方式
- 📧 邮箱：3105755134@qq.com  
- 🌐 GitHub：[MegumiN152](https://github.com/MegumiN152)  

---

<p align="center">
  ❤️ 如果你有合适的 Java 后端岗位机会，请随时联系我！
</p>

You are my ![Visitor Count](https://profile-counter.glitch.me/wisdom-zhe/count.svg) visitor,Thank You!😘


