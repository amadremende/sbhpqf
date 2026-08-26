最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.pb0hct.asia/arts/081694.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.pb0hct.asia/arts/101991.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.pb0hct.asia/arts/188621.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.pb0hct.asia/arts/850259.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.pb0hct.asia/arts/257085.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/215391.Doc

原标题：golang 多协程任务池并发控制
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.pb0hct.asia/arts/903148.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.pb0hct.asia/arts/152555.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.pb0hct.asia/arts/274832.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/270224.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.pb0hct.asia/arts/537534.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.pb0hct.asia/arts/960942.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.pb0hct.asia/arts/530601.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.pb0hct.asia/arts/750553.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.pb0hct.asia/arts/203166.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.pb0hct.asia/arts/074038.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.pb0hct.asia/arts/947432.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.pb0hct.asia/arts/181695.Doc

原标题：Git 代码冲突正确处理方式
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.pb0hct.asia/arts/441544.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/826559.Doc

原标题：golang mongodb 文档结构设计原则
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.pb0hct.asia/arts/500294.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.pb0hct.asia/arts/269702.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.pb0hct.asia/arts/485672.Doc

原标题：分布式任务调度集群原型开发
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.pb0hct.asia/arts/563952.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.pb0hct.asia/arts/081773.Doc

原标题：golang 灰度权重流量分发简单实现
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.pb0hct.asia/arts/787955.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.pb0hct.asia/arts/507355.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.pb0hct.asia/arts/589106.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/121763.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.pb0hct.asia/arts/296654.Doc

原标题：本地数据库开发环境搭建指南
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.pb0hct.asia/arts/183283.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/997003.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.pb0hct.asia/arts/179394.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.pb0hct.asia/arts/490658.Doc

原标题：读懂开源项目 README 实用技巧
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.pb0hct.asia/arts/509183.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.pb0hct.asia/arts/644365.Doc

原标题：golang 限流熔断降级完整示例
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.pb0hct.asia/arts/002391.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.pb0hct.asia/arts/677811.Doc

原标题：动态定时任务业务调度实现
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/904611.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/415648.Doc


二、踩坑排错｜Troubleshooting
原标题：golang es 映射 mapping 设计避坑
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.pb0hct.asia/arts/938175.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.pb0hct.asia/arts/392542.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/539965.Doc

原标题：环境变量不生效问题修复
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.pb0hct.asia/arts/692730.Doc

原标题：golang k8s helm chart 简单编写
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.pb0hct.asia/arts/884414.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.pb0hct.asia/arts/808629.Doc

原标题：分布式任务调度集群原型开发
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.pb0hct.asia/arts/040424.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.pb0hct.asia/arts/233032.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.pb0hct.asia/arts/529735.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/276665.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.pb0hct.asia/arts/457745.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.pb0hct.asia/arts/263342.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.pb0hct.asia/arts/054872.Doc

原标题：Docker 网络模式容器互通设置
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/207402.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.pb0hct.asia/arts/444742.Doc

原标题：nodejs http 服务性能调优实战
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.pb0hct.asia/arts/332520.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.pb0hct.asia/arts/023507.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.pb0hct.asia/arts/036821.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.pb0hct.asia/arts/838775.Doc

原标题：nodejs 跨域中间件配置细节
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.pb0hct.asia/arts/611709.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.pb0hct.asia/arts/959134.Doc

原标题：Fork 开源项目同步上游代码
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.pb0hct.asia/arts/117848.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.pb0hct.asia/arts/073421.Doc

原标题：CLI 批量处理工具文件操作开发
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.pb0hct.asia/arts/047515.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.pb0hct.asia/arts/159042.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.pb0hct.asia/arts/502237.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/863335.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.pb0hct.asia/arts/536851.Doc

原标题：golang 参数校验业务接口处理
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.pb0hct.asia/arts/072415.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.pb0hct.asia/arts/560675.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.pb0hct.asia/arts/233371.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/065081.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/243823.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.pb0hct.asia/arts/011084.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.pb0hct.asia/arts/570999.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.pb0hct.asia/arts/230002.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.pb0hct.asia/arts/613525.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.pb0hct.asia/arts/126226.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.pb0hct.asia/arts/448524.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.pb0hct.asia/arts/081223.Doc

三、实战开发｜Practice
原标题：git rebase 整理提交历史实操
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.pb0hct.asia/arts/340286.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.pb0hct.asia/arts/909592.Doc

原标题：golang gin 中间件执行顺序讲解
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.pb0hct.asia/arts/082632.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.pb0hct.asia/arts/351991.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/522529.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.pb0hct.asia/arts/535219.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.pb0hct.asia/arts/714187.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/229514.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.pb0hct.asia/arts/992951.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.pb0hct.asia/arts/470950.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.pb0hct.asia/arts/473810.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/046374.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.pb0hct.asia/arts/444299.Doc

原标题：Performance：数据库join优化，大表join规避
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/727697.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.pb0hct.asia/arts/502528.Doc

原标题：golang excel 简单读写操作示例
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/340923.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.pb0hct.asia/arts/714106.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.pb0hct.asia/arts/473060.Doc

原标题：消息队列重复消费业务处理
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.pb0hct.asia/arts/195479.Doc

原标题：设计思考：分布式会话架构选型对比
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.pb0hct.asia/arts/676738.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.pb0hct.asia/arts/539411.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.pb0hct.asia/arts/452079.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.pb0hct.asia/arts/668001.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/331108.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/707486.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.pb0hct.asia/arts/116636.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.pb0hct.asia/arts/957205.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.pb0hct.asia/arts/319678.Doc

原标题：项目目录结构规范化最佳实践
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.pb0hct.asia/arts/531538.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.pb0hct.asia/arts/825870.Doc

原标题：系统时间同步定时任务偏移
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.pb0hct.asia/arts/802967.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/198854.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.pb0hct.asia/arts/413786.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.pb0hct.asia/arts/883377.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.pb0hct.asia/arts/290616.Doc

原标题：WSL 文件权限访问异常修复
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.pb0hct.asia/arts/763427.Doc

原标题：文件锁正确使用避免死锁
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.pb0hct.asia/arts/835759.Doc

原标题：golang docker volume 数据持久化
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.pb0hct.asia/arts/566754.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.pb0hct.asia/arts/432223.Doc

原标题：golang md5 sha 加密工具实现
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/803015.Doc

四、架构设计｜Architecture
原标题：实践：灰度流量切分简易实现方案
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.pb0hct.asia/arts/006753.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.pb0hct.asia/arts/870439.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.pb0hct.asia/arts/433948.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.pb0hct.asia/arts/203795.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/162550.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.pb0hct.asia/arts/899112.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/758261.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.pb0hct.asia/arts/021202.Doc

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.pb0hct.asia/arts/928013.Doc

原标题：端口占用释放资源重启服务
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.pb0hct.asia/arts/297890.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/802745.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.pb0hct.asia/arts/825638.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/343951.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.pb0hct.asia/arts/343128.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.pb0hct.asia/arts/540498.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.pb0hct.asia/arts/198204.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.pb0hct.asia/arts/881301.Doc

原标题：golang docker 网络模式桥接 host
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.pb0hct.asia/arts/498371.Doc

?
