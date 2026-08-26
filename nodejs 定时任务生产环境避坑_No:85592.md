最新前沿技术资讯

一、入门教程｜Getting Started
原标题：nodejs 定时任务生产环境避坑
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.icrkyw.asia/arts/191566.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.icrkyw.asia/arts/113207.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.icrkyw.asia/arts/636375.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.icrkyw.asia/arts/718532.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.icrkyw.asia/arts/302092.Doc

原标题：golang docker 容器资源限制设置
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/080931.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.icrkyw.asia/arts/002729.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.icrkyw.asia/arts/275394.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.icrkyw.asia/arts/851590.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.icrkyw.asia/arts/046530.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.icrkyw.asia/arts/411962.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.icrkyw.asia/arts/477925.Doc

原标题：系统文件描述符上限调大
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.icrkyw.asia/arts/535829.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.icrkyw.asia/arts/500258.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.icrkyw.asia/arts/784284.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.icrkyw.asia/arts/146948.Doc

原标题：hosts 配置本地回环访问修复
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.icrkyw.asia/arts/309642.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.icrkyw.asia/arts/270058.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.icrkyw.asia/arts/530541.Doc

原标题：开发测试生产多环境配置区分
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.icrkyw.asia/arts/778019.Doc

原标题：golang 系统设计定时任务分布式锁
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.icrkyw.asia/arts/292974.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.icrkyw.asia/arts/447192.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.icrkyw.asia/arts/303919.Doc

原标题：golang 大文件 http 下载服务
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.icrkyw.asia/arts/925506.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.icrkyw.asia/arts/526751.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.icrkyw.asia/arts/785185.Doc

原标题：从零学习简单分页逻辑实现思路
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.icrkyw.asia/arts/126018.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.icrkyw.asia/arts/851254.Doc

原标题：静态资源 404 路径打包修复
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/428426.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/890407.Doc

原标题：时间同步修复令牌提前过期
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.icrkyw.asia/arts/660228.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.icrkyw.asia/arts/710652.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.icrkyw.asia/arts/361373.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.icrkyw.asia/arts/228187.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.icrkyw.asia/arts/910351.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.icrkyw.asia/arts/349369.Doc

原标题：golang redis 过期 key 监听业务
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.icrkyw.asia/arts/357019.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.icrkyw.asia/arts/308722.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.icrkyw.asia/arts/010895.Doc

原标题：golang 容器健康检查接口开发
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.icrkyw.asia/arts/410469.Doc


二、踩坑排错｜Troubleshooting
原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.icrkyw.asia/arts/974274.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.icrkyw.asia/arts/314312.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.icrkyw.asia/arts/609422.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.icrkyw.asia/arts/590911.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.icrkyw.asia/arts/188003.Doc

原标题：golang 项目 go mod 依赖管理
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.icrkyw.asia/arts/473941.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.icrkyw.asia/arts/630233.Doc

原标题：入门实践：简单批量处理脚本编写
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.icrkyw.asia/arts/506245.Doc

原标题：Performance：数据库join优化，大表join规避
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.icrkyw.asia/arts/506673.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.icrkyw.asia/arts/201380.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.icrkyw.asia/arts/590503.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.icrkyw.asia/arts/265631.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.icrkyw.asia/arts/049596.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.icrkyw.asia/arts/340617.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.icrkyw.asia/arts/445168.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.icrkyw.asia/arts/495534.Doc

原标题：golang 项目环境变量加载方案
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.icrkyw.asia/arts/529334.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.icrkyw.asia/arts/878752.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.icrkyw.asia/arts/202614.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.icrkyw.asia/arts/281906.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.icrkyw.asia/arts/781451.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.icrkyw.asia/arts/673022.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.icrkyw.asia/arts/299299.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.icrkyw.asia/arts/157741.Doc

原标题：nodejs 多进程任务分发处理
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.icrkyw.asia/arts/976045.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.icrkyw.asia/arts/893276.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.icrkyw.asia/arts/670763.Doc

原标题：多规则数据脱敏组件开发
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.icrkyw.asia/arts/783309.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.icrkyw.asia/arts/677785.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.icrkyw.asia/arts/746788.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.icrkyw.asia/arts/132966.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.icrkyw.asia/arts/979909.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.icrkyw.asia/arts/695944.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.icrkyw.asia/arts/851888.Doc

原标题：golang base64 编码解码实操
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.icrkyw.asia/arts/009678.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.icrkyw.asia/arts/236969.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.icrkyw.asia/arts/364882.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.icrkyw.asia/arts/225129.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.icrkyw.asia/arts/616530.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.icrkyw.asia/arts/744130.Doc

三、实战开发｜Practice
原标题：快速上手阅读开源项目源码的入门思路
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.icrkyw.asia/arts/500587.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.icrkyw.asia/arts/558196.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.icrkyw.asia/arts/557085.Doc

原标题：开源项目构建失败排查步骤
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.icrkyw.asia/arts/209207.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.icrkyw.asia/arts/509194.Doc

原标题：文件读写与异常捕获代码示例
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.icrkyw.asia/arts/411492.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.icrkyw.asia/arts/676804.Doc

原标题：golang websocket 消息广播实现
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.icrkyw.asia/arts/238840.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.icrkyw.asia/arts/294177.Doc

原标题：hosts 配置本地回环访问修复
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.icrkyw.asia/arts/230052.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.icrkyw.asia/arts/534310.Doc

原标题：请求工具封装统一异常处理
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.icrkyw.asia/arts/080891.Doc

原标题：浮点计算精度错误处理方案
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.icrkyw.asia/arts/750012.Doc

原标题：golang 批量任务协程控制防雪崩
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.icrkyw.asia/arts/076206.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.icrkyw.asia/arts/832722.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.icrkyw.asia/arts/208039.Doc

原标题：golang 系统设计分库分表中间件思路
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.icrkyw.asia/arts/365755.Doc

原标题：依赖版本冲突兼容修复方案
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.icrkyw.asia/arts/799162.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.icrkyw.asia/arts/339866.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.icrkyw.asia/arts/647954.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.icrkyw.asia/arts/853032.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.icrkyw.asia/arts/646606.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.icrkyw.asia/arts/198191.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.icrkyw.asia/arts/310240.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.icrkyw.asia/arts/188495.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.icrkyw.asia/arts/065494.Doc

原标题：golang mock 单元测试编写技巧
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.icrkyw.asia/arts/561233.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.icrkyw.asia/arts/341314.Doc

原标题：golang redis 锁超时业务处理
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.icrkyw.asia/arts/700836.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.icrkyw.asia/arts/644808.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.icrkyw.asia/arts/871474.Doc

原标题：异步编程 Promise 执行流程解析
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.icrkyw.asia/arts/720059.Doc

原标题：golang redis pipeline 批量操作
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.icrkyw.asia/arts/268355.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.icrkyw.asia/arts/535456.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.icrkyw.asia/arts/906500.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.icrkyw.asia/arts/551900.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.icrkyw.asia/arts/945219.Doc

原标题：时间精度统一业务判断修复
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.icrkyw.asia/arts/708353.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.icrkyw.asia/arts/599585.Doc

原标题：批量操作分批处理防止 OOM
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.icrkyw.asia/arts/813921.Doc

四、架构设计｜Architecture
原标题：golang 系统设计链路追踪架构简单讲解
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.icrkyw.asia/arts/482631.Doc

原标题：golang defer panic 异常处理
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.icrkyw.asia/arts/913149.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.icrkyw.asia/arts/755737.Doc

原标题：消息消费重试次数限制防爆炸
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.icrkyw.asia/arts/190699.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.icrkyw.asia/arts/137581.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.icrkyw.asia/arts/208750.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.icrkyw.asia/arts/859068.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.icrkyw.asia/arts/369905.Doc

原标题：golang docker 部署 mysql 注意事项
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.icrkyw.asia/arts/797087.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.icrkyw.asia/arts/684482.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.icrkyw.asia/arts/518393.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.icrkyw.asia/arts/157767.Doc

原标题：rebase 操作防止代码丢失
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.icrkyw.asia/arts/081995.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.icrkyw.asia/arts/128297.Doc

原标题：全量回归测试提升代码质量
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.icrkyw.asia/arts/805618.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.icrkyw.asia/arts/106514.Doc

原标题：前端国际化多语言方案落地
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.icrkyw.asia/arts/423027.Doc

原标题：golang docker 容器资源限制设置
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.icrkyw.asia/arts/112001.Doc

?
