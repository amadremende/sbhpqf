最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang k8s 日志收集 efk 简单架构
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.ujrpwh.asia/arts/391103.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.ujrpwh.asia/arts/091730.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.ujrpwh.asia/arts/234685.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.ujrpwh.asia/arts/468228.Doc

原标题：动态定时任务业务调度实现
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.ujrpwh.asia/arts/958388.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.ujrpwh.asia/arts/063399.Doc

原标题：nodejs 集群模式多核利用实现
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.ujrpwh.asia/arts/080104.Doc

原标题：CORS 跨域问题多种解决方案
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.ujrpwh.asia/arts/611122.Doc

原标题：全量回归测试提升代码质量
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.ujrpwh.asia/arts/607038.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.ujrpwh.asia/arts/640395.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.ujrpwh.asia/arts/151881.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.ujrpwh.asia/arts/687919.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.ujrpwh.asia/arts/235962.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.ujrpwh.asia/arts/422353.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.ujrpwh.asia/arts/426559.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.ujrpwh.asia/arts/024037.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.ujrpwh.asia/arts/717634.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.ujrpwh.asia/arts/713558.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.ujrpwh.asia/arts/595748.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.ujrpwh.asia/arts/025444.Doc

原标题：大事务拆分防止连接池耗尽
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.ujrpwh.asia/arts/373623.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.ujrpwh.asia/arts/454881.Doc

原标题：提交第一个开源 PR 完整流程
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.ujrpwh.asia/arts/855959.Doc

原标题：线上接口超时故障排查思路
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.ujrpwh.asia/arts/448839.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.ujrpwh.asia/arts/274689.Doc

原标题：golang rsa 非对称加密签名验签
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.ujrpwh.asia/arts/199936.Doc

原标题：golang prometheus 指标暴露实现
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.ujrpwh.asia/arts/563627.Doc

原标题：全平台系统环境变量配置
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.ujrpwh.asia/arts/013388.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.ujrpwh.asia/arts/824655.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.ujrpwh.asia/arts/078725.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.ujrpwh.asia/arts/599862.Doc

原标题：K8s 镜像拉取网络故障修复
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.ujrpwh.asia/arts/681862.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.ujrpwh.asia/arts/526244.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.ujrpwh.asia/arts/167133.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.ujrpwh.asia/arts/578659.Doc

原标题：golang 系统设计日志系统架构思路
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.ujrpwh.asia/arts/396841.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.ujrpwh.asia/arts/106608.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.ujrpwh.asia/arts/151246.Doc

原标题：前端下载导出文件功能实现
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.ujrpwh.asia/arts/436052.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.ujrpwh.asia/arts/672809.Doc


二、踩坑排错｜Troubleshooting
原标题：golang http 服务性能优化调参
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.ujrpwh.asia/arts/969880.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.ujrpwh.asia/arts/309864.Doc

原标题：css 动画性能优化 GPU 加速
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.ujrpwh.asia/arts/452068.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.ujrpwh.asia/arts/581740.Doc

原标题：Docker 容器网络不通排查
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.ujrpwh.asia/arts/829623.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.ujrpwh.asia/arts/561880.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.ujrpwh.asia/arts/882906.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.ujrpwh.asia/arts/562581.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.ujrpwh.asia/arts/947661.Doc

原标题：golang 错误处理最佳实践汇总
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.ujrpwh.asia/arts/533371.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.ujrpwh.asia/arts/051114.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.ujrpwh.asia/arts/714795.Doc

原标题：前后端交互跨域问题完整处理
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.ujrpwh.asia/arts/122839.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.ujrpwh.asia/arts/369942.Doc

原标题：程序预加载加快服务启动速度
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.ujrpwh.asia/arts/428517.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.ujrpwh.asia/arts/996474.Doc

原标题：golang es 分页深分页性能优化
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.ujrpwh.asia/arts/726748.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.ujrpwh.asia/arts/671164.Doc

原标题：golang 系统设计防爬虫简单策略
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.ujrpwh.asia/arts/917513.Doc

原标题：浮点计算精度错误处理方案
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.ujrpwh.asia/arts/808286.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.ujrpwh.asia/arts/940396.Doc

原标题：编译打包产物依赖分析解读
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.ujrpwh.asia/arts/133699.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.ujrpwh.asia/arts/348099.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.ujrpwh.asia/arts/439806.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.ujrpwh.asia/arts/603912.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.ujrpwh.asia/arts/563098.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.ujrpwh.asia/arts/718728.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.ujrpwh.asia/arts/640762.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.ujrpwh.asia/arts/304327.Doc

原标题：golang 信号捕获程序退出处理
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.ujrpwh.asia/arts/493852.Doc

原标题：golang csv 读写批量数据处理
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.ujrpwh.asia/arts/274652.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.ujrpwh.asia/arts/319815.Doc

原标题：golang k8s 节点污点容忍度配置
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.ujrpwh.asia/arts/066587.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.ujrpwh.asia/arts/105863.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.ujrpwh.asia/arts/183258.Doc

原标题：golang 系统设计读写分离架构示例
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.ujrpwh.asia/arts/603522.Doc

原标题：服务健康检查告警监控体系
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.ujrpwh.asia/arts/696589.Doc

原标题：golang mysql 字符集排序规则设置
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.ujrpwh.asia/arts/469870.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.ujrpwh.asia/arts/017607.Doc

原标题：golang mysql 分表自增 id 方案
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.ujrpwh.asia/arts/204639.Doc

三、实战开发｜Practice
原标题：golang 系统设计本地缓存与分布式缓存
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.ujrpwh.asia/arts/684610.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.ujrpwh.asia/arts/344332.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.ujrpwh.asia/arts/054444.Doc

原标题：包管理器依赖冲突解决方案
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.ujrpwh.asia/arts/087814.Doc

原标题：golang 项目目录分层规范设计
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.ujrpwh.asia/arts/541271.Doc

原标题：快速入门简单签名校验实现思路
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.ujrpwh.asia/arts/895200.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.ujrpwh.asia/arts/347171.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.ujrpwh.asia/arts/469619.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.ujrpwh.asia/arts/529792.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.ujrpwh.asia/arts/263774.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.ujrpwh.asia/arts/943351.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.ujrpwh.asia/arts/498652.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.ujrpwh.asia/arts/041402.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.ujrpwh.asia/arts/726449.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.ujrpwh.asia/arts/469625.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.ujrpwh.asia/arts/511745.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.ujrpwh.asia/arts/744145.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.ujrpwh.asia/arts/088838.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.ujrpwh.asia/arts/617775.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.ujrpwh.asia/arts/530194.Doc

原标题：快速上手搭建简易内网测试服务
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.ujrpwh.asia/arts/535287.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.ujrpwh.asia/arts/233947.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.ujrpwh.asia/arts/298394.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.ujrpwh.asia/arts/017246.Doc

原标题：golang redis 客户端业务使用
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.ujrpwh.asia/arts/642994.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.ujrpwh.asia/arts/199215.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.ujrpwh.asia/arts/720909.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.ujrpwh.asia/arts/960832.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.ujrpwh.asia/arts/106210.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.ujrpwh.asia/arts/453272.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.ujrpwh.asia/arts/264972.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.ujrpwh.asia/arts/879544.Doc

原标题：异步任务堆积消费能力优化
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.ujrpwh.asia/arts/854338.Doc

原标题：golang 信号量控制并发数量
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.ujrpwh.asia/arts/239257.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.ujrpwh.asia/arts/214814.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.ujrpwh.asia/arts/772871.Doc

原标题：golang k8s 节点污点容忍度配置
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.ujrpwh.asia/arts/839528.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.ujrpwh.asia/arts/381461.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.ujrpwh.asia/arts/641000.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.ujrpwh.asia/arts/573971.Doc

四、架构设计｜Architecture
原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.ujrpwh.asia/arts/048044.Doc

原标题：Performance：批量导入数据性能优化实践
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.ujrpwh.asia/arts/195958.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.ujrpwh.asia/arts/936671.Doc

原标题：全局本地依赖隔离冲突规避
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.ujrpwh.asia/arts/215330.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.ujrpwh.asia/arts/677818.Doc

原标题：golang 大文件读取内存优化
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.ujrpwh.asia/arts/355000.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.ujrpwh.asia/arts/851851.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.ujrpwh.asia/arts/095125.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.ujrpwh.asia/arts/575944.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.ujrpwh.asia/arts/380077.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.ujrpwh.asia/arts/626817.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.ujrpwh.asia/arts/124659.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.ujrpwh.asia/arts/614796.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.ujrpwh.asia/arts/896577.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.ujrpwh.asia/arts/026982.Doc

原标题：快速上手简单信号处理脚本编写
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.ujrpwh.asia/arts/111384.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.ujrpwh.asia/arts/640026.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.ujrpwh.asia/arts/673985.Doc

?
