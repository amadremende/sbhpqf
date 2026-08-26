最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Performance：大事务拆分，减少锁持有时间
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.2l9ikw.asia/blog/322410.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.2l9ikw.asia/blog/874456.Doc

原标题：服务健康检查告警监控体系
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.2l9ikw.asia/blog/017935.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.2l9ikw.asia/blog/666843.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.2l9ikw.asia/blog/990251.Doc

原标题：快速入门异步编程基础模型
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.2l9ikw.asia/blog/264309.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.2l9ikw.asia/blog/418606.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.2l9ikw.asia/blog/071047.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.2l9ikw.asia/blog/122341.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.2l9ikw.asia/blog/822111.Doc

原标题：golang redis 五种数据结构实战
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.2l9ikw.asia/blog/863923.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.2l9ikw.asia/blog/316145.Doc

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.2l9ikw.asia/blog/046066.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.2l9ikw.asia/blog/689855.Doc

原标题：跨平台 uniapp 多端开发实操
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.2l9ikw.asia/blog/996184.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.2l9ikw.asia/blog/025714.Doc

原标题：零基础理解依赖管理与包管理器
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.2l9ikw.asia/blog/111757.Doc

原标题：golang gin 静态资源访问配置
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.2l9ikw.asia/blog/785617.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.2l9ikw.asia/blog/587166.Doc

原标题：golang 分布式锁 redis 实现
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.2l9ikw.asia/blog/603296.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.2l9ikw.asia/blog/205118.Doc

原标题：入门实践：简单批量处理脚本编写
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.2l9ikw.asia/blog/672417.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.2l9ikw.asia/blog/927384.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.2l9ikw.asia/blog/310889.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.2l9ikw.asia/blog/774449.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.2l9ikw.asia/blog/788959.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.2l9ikw.asia/blog/871011.Doc

原标题：MySQL 慢查询索引优化实战
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.2l9ikw.asia/blog/922511.Doc

原标题：golang gin 框架接口开发实战
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.2l9ikw.asia/blog/608151.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.2l9ikw.asia/blog/386629.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.2l9ikw.asia/blog/560634.Doc

原标题：golang alertmanager 钉钉告警推送
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.2l9ikw.asia/blog/823369.Doc

原标题：golang minio 分片上传断点续传
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.2l9ikw.asia/blog/642580.Doc

原标题：重复提交幂等防护再次讲解
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.2l9ikw.asia/blog/119666.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.2l9ikw.asia/blog/904709.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.2l9ikw.asia/blog/756944.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.2l9ikw.asia/blog/631740.Doc

原标题：golang 链路 traceId 透传中间件
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.2l9ikw.asia/blog/220336.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.2l9ikw.asia/blog/301401.Doc

原标题：文件句柄耗尽资源泄露处理
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.2l9ikw.asia/blog/590285.Doc


二、踩坑排错｜Troubleshooting
原标题：方案对比：同步调用vs异步消息业务选型
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.2l9ikw.asia/blog/907322.Doc

原标题：golang 系统设计分布式配置中心思路
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.2l9ikw.asia/blog/384399.Doc

原标题：golang gin 静态资源访问配置
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.2l9ikw.asia/blog/329641.Doc

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.2l9ikw.asia/blog/075088.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.2l9ikw.asia/blog/464610.Doc

原标题：分布式 ID 生成器高并发实现
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.2l9ikw.asia/blog/789241.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.2l9ikw.asia/blog/542871.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.2l9ikw.asia/blog/548443.Doc

原标题：golang k8s helm chart 简单编写
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.2l9ikw.asia/blog/157774.Doc

原标题：实践：数据库回滚点业务调试实践
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.2l9ikw.asia/blog/592635.Doc

原标题：CI 持续集成自动构建流程
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.2l9ikw.asia/blog/134630.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.2l9ikw.asia/blog/941044.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.2l9ikw.asia/blog/976815.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.2l9ikw.asia/blog/011439.Doc

原标题：golang 重试退避机制代码实现
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.2l9ikw.asia/blog/986330.Doc

原标题：golang git 提交信息规范校验
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.2l9ikw.asia/blog/139787.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.2l9ikw.asia/blog/447741.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.2l9ikw.asia/blog/618857.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.2l9ikw.asia/blog/593284.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.2l9ikw.asia/blog/754582.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.2l9ikw.asia/blog/344666.Doc

原标题：服务健康检查监控接口开发
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.2l9ikw.asia/blog/567990.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.2l9ikw.asia/blog/934392.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.2l9ikw.asia/blog/633002.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.2l9ikw.asia/blog/991112.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.2l9ikw.asia/blog/668118.Doc

原标题：golang etcd watch 监听配置变更
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.2l9ikw.asia/blog/835299.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.2l9ikw.asia/blog/649833.Doc

原标题：nodejs 内存溢出问题排查修复
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.2l9ikw.asia/blog/783666.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.2l9ikw.asia/blog/719874.Doc

原标题：静态资源 404 路径打包修复
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.2l9ikw.asia/blog/399068.Doc

原标题：golang 分库分表简单路由实现
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.2l9ikw.asia/blog/159257.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.2l9ikw.asia/blog/645988.Doc

原标题：git stash 代码暂存切换分支
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.2l9ikw.asia/blog/503847.Doc

原标题：golang csv 读写批量数据处理
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.2l9ikw.asia/blog/576352.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.2l9ikw.asia/blog/304188.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.2l9ikw.asia/blog/889136.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.2l9ikw.asia/blog/502270.Doc

原标题：HTTPS 证书过期更新操作
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.2l9ikw.asia/blog/904280.Doc

原标题：快速上手调试工具定位简单代码错误
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.2l9ikw.asia/blog/308174.Doc

三、实战开发｜Practice
原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.2l9ikw.asia/blog/083312.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.2l9ikw.asia/blog/393087.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.2l9ikw.asia/blog/190211.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.2l9ikw.asia/blog/220214.Doc

原标题：零基础理解HTTP常用请求头与状态码
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.2l9ikw.asia/blog/203266.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.2l9ikw.asia/blog/591341.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.2l9ikw.asia/blog/179209.Doc

原标题：eslint prettier 代码规范落地
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.2l9ikw.asia/blog/375151.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.2l9ikw.asia/blog/155654.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.2l9ikw.asia/blog/467432.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.2l9ikw.asia/blog/980801.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.2l9ikw.asia/blog/305511.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.2l9ikw.asia/blog/481883.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.2l9ikw.asia/blog/767770.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.2l9ikw.asia/blog/934867.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.2l9ikw.asia/blog/381060.Doc

原标题：golang es bool 查询条件组合技巧
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.2l9ikw.asia/blog/507492.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.2l9ikw.asia/blog/088706.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.2l9ikw.asia/blog/565281.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.2l9ikw.asia/blog/338228.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://book.2l9ikw.asia/blog/496245.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.2l9ikw.asia/blog/754740.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.2l9ikw.asia/blog/719144.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.2l9ikw.asia/blog/944511.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.2l9ikw.asia/blog/289015.Doc

原标题：上传接口跨域配置特殊适配
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.2l9ikw.asia/blog/734028.Doc

原标题：实战：Redis管道批量操作性能优化实践
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.2l9ikw.asia/blog/909536.Doc

原标题：golang mysql exists in 性能对比
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.2l9ikw.asia/blog/866526.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.2l9ikw.asia/blog/643555.Doc

原标题：Redis 分布式锁高并发安全实现
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.2l9ikw.asia/blog/151446.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.2l9ikw.asia/blog/082791.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.2l9ikw.asia/blog/577467.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.2l9ikw.asia/blog/644489.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.2l9ikw.asia/blog/316607.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.2l9ikw.asia/blog/263598.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.2l9ikw.asia/blog/259199.Doc

原标题：单元测试用例编写入门实操
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://book.2l9ikw.asia/blog/675735.Doc

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://book.2l9ikw.asia/blog/530882.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.2l9ikw.asia/blog/887854.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.2l9ikw.asia/blog/560844.Doc

四、架构设计｜Architecture
原标题：入门实践：使用模板快速生成项目脚手架
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.2l9ikw.asia/blog/962095.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.2l9ikw.asia/blog/533092.Doc

原标题：新手指南：本地多版本环境共存配置
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.2l9ikw.asia/blog/804290.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.2l9ikw.asia/blog/973449.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.2l9ikw.asia/blog/148724.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.2l9ikw.asia/blog/233266.Doc

原标题：CLI 工具进度条交互效果开发
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.2l9ikw.asia/blog/963008.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.2l9ikw.asia/blog/889475.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.2l9ikw.asia/blog/414853.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.2l9ikw.asia/blog/003437.Doc

原标题：golang 系统设计读写分离架构示例
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.2l9ikw.asia/blog/970393.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.2l9ikw.asia/blog/823551.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.2l9ikw.asia/blog/624452.Doc

原标题：限流组件计数器令牌桶模式实现
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.2l9ikw.asia/blog/843420.Doc

原标题：golang mysql 分表自增 id 方案
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.2l9ikw.asia/blog/566408.Doc

原标题：服务熔断防止故障级联传播
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.2l9ikw.asia/blog/858430.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.2l9ikw.asia/blog/382635.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.2l9ikw.asia/blog/944770.Doc

?
