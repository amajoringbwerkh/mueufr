最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计压测环境隔离避免影响生产
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.u7m9gx.asia/arts/906946.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.u7m9gx.asia/arts/348278.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/868560.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.u7m9gx.asia/arts/678400.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.u7m9gx.asia/arts/385523.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/491492.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/731382.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.u7m9gx.asia/arts/944054.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.u7m9gx.asia/arts/444166.Doc

原标题：Nginx 请求头大小上限调整
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.u7m9gx.asia/arts/563018.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.u7m9gx.asia/arts/315234.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.u7m9gx.asia/arts/504692.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.u7m9gx.asia/arts/353659.Doc

原标题：golang ci 流水线单元测试集成测试
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.u7m9gx.asia/arts/392654.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.u7m9gx.asia/arts/381460.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.u7m9gx.asia/arts/383966.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.u7m9gx.asia/arts/611659.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.u7m9gx.asia/arts/429858.Doc

原标题：Git LFS 大文件推送失败解决
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.u7m9gx.asia/arts/126060.Doc

原标题：golang 配置热更新不重启服务
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.u7m9gx.asia/arts/822407.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.u7m9gx.asia/arts/319712.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.u7m9gx.asia/arts/951626.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.u7m9gx.asia/arts/522184.Doc

原标题：CORS 跨域问题多种解决方案
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.u7m9gx.asia/arts/354522.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.u7m9gx.asia/arts/551852.Doc

原标题：golang 单例模式实现几种方式
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.u7m9gx.asia/arts/567071.Doc

原标题：手写简易 RPC 服务通信原型
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.u7m9gx.asia/arts/899620.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.u7m9gx.asia/arts/911099.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.u7m9gx.asia/arts/376704.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.u7m9gx.asia/arts/157496.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.u7m9gx.asia/arts/204392.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.u7m9gx.asia/arts/464159.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.u7m9gx.asia/arts/765940.Doc

原标题：浏览器缓存强制刷新方案
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/677792.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.u7m9gx.asia/arts/961878.Doc

原标题：golang channel 通道并发处理
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.u7m9gx.asia/arts/777300.Doc

原标题：golang github actions 缓存依赖提速
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.u7m9gx.asia/arts/382585.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.u7m9gx.asia/arts/422511.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.u7m9gx.asia/arts/414606.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.u7m9gx.asia/arts/577965.Doc


二、踩坑排错｜Troubleshooting
原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.u7m9gx.asia/arts/958607.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.u7m9gx.asia/arts/848146.Doc

原标题：DNS 解析异常第三方调用故障
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.u7m9gx.asia/arts/393772.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.u7m9gx.asia/arts/111928.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.u7m9gx.asia/arts/783614.Doc

原标题：浮点计算精度错误处理方案
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.u7m9gx.asia/arts/831140.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.u7m9gx.asia/arts/082895.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.u7m9gx.asia/arts/812696.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.u7m9gx.asia/arts/945825.Doc

原标题：大事务拆分防止连接池耗尽
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.u7m9gx.asia/arts/316992.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.u7m9gx.asia/arts/593492.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.u7m9gx.asia/arts/530763.Doc

原标题：浏览器内存泄漏排查前端页面
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.u7m9gx.asia/arts/890734.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.u7m9gx.asia/arts/206219.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.u7m9gx.asia/arts/382522.Doc

原标题：golang alertmanager 钉钉告警推送
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.u7m9gx.asia/arts/061825.Doc

原标题：golang yaml 解析配置加载实操
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.u7m9gx.asia/arts/131062.Doc

原标题：数据库连接及时关闭连接泄漏
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.u7m9gx.asia/arts/198466.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.u7m9gx.asia/arts/702623.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.u7m9gx.asia/arts/072185.Doc

原标题：golang 系统设计延迟队列业务实现
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.u7m9gx.asia/arts/261546.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.u7m9gx.asia/arts/123084.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/934270.Doc

原标题：golang base64 编码解码实操
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.u7m9gx.asia/arts/042967.Doc

原标题：容器资源限制防止宿主机过载
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.u7m9gx.asia/arts/578033.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.u7m9gx.asia/arts/759473.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.u7m9gx.asia/arts/392999.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.u7m9gx.asia/arts/779789.Doc

原标题：CI 持续集成自动构建流程
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.u7m9gx.asia/arts/315567.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.u7m9gx.asia/arts/531552.Doc

原标题：golang defer panic 异常处理
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.u7m9gx.asia/arts/936835.Doc

原标题：后端登录鉴权模块完整开发
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.u7m9gx.asia/arts/437103.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.u7m9gx.asia/arts/501976.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.u7m9gx.asia/arts/979480.Doc

原标题：golang mysql 读写分离简单实现
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.u7m9gx.asia/arts/942913.Doc

原标题：多套环境灵活切换配置方案
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.u7m9gx.asia/arts/310402.Doc

原标题：定时任务重复执行分布式锁
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.u7m9gx.asia/arts/375210.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.u7m9gx.asia/arts/994921.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.u7m9gx.asia/arts/420986.Doc

原标题：golang docker compose 部署 minio
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.u7m9gx.asia/arts/486950.Doc

三、实战开发｜Practice
原标题：Practice：实现异步任务结果查询回调实践
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.u7m9gx.asia/arts/005034.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.u7m9gx.asia/arts/564180.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.u7m9gx.asia/arts/159254.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.u7m9gx.asia/arts/424033.Doc

原标题：零基础理解依赖管理与包管理器
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.u7m9gx.asia/arts/166329.Doc

原标题：数值类型溢出错乱问题修复
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.u7m9gx.asia/arts/907795.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.u7m9gx.asia/arts/931626.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.u7m9gx.asia/arts/779644.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.u7m9gx.asia/arts/853222.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.u7m9gx.asia/arts/251376.Doc

原标题：项目依赖安全扫描漏洞防范
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.u7m9gx.asia/arts/789117.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.u7m9gx.asia/arts/566226.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.u7m9gx.asia/arts/673265.Doc

原标题：零基础理解依赖管理与包管理器
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.u7m9gx.asia/arts/312825.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.u7m9gx.asia/arts/219889.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.u7m9gx.asia/arts/154776.Doc

原标题：golang redis 大 key 识别处理方案
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.u7m9gx.asia/arts/382810.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/012589.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.u7m9gx.asia/arts/514632.Doc

原标题：golang kafka 消息丢失重复消费
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.u7m9gx.asia/arts/167864.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.u7m9gx.asia/arts/421471.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.u7m9gx.asia/arts/671083.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.u7m9gx.asia/arts/727367.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.u7m9gx.asia/arts/902156.Doc

原标题：golang mongodb 文档结构设计原则
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.u7m9gx.asia/arts/993850.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.u7m9gx.asia/arts/469412.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.u7m9gx.asia/arts/530374.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.u7m9gx.asia/arts/763425.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.u7m9gx.asia/arts/048635.Doc

原标题：从零搭建简单Mock接口服务
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.u7m9gx.asia/arts/259117.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.u7m9gx.asia/arts/918150.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.u7m9gx.asia/arts/735078.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.u7m9gx.asia/arts/861638.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.u7m9gx.asia/arts/937887.Doc

原标题：灰度发布策略服务平滑升级
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.u7m9gx.asia/arts/382480.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.u7m9gx.asia/arts/467719.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.u7m9gx.asia/arts/090575.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.u7m9gx.asia/arts/375417.Doc

原标题：版本升级服务启动失败处理
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/964494.Doc

原标题：golang k8s 基础概念 pod deployment
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.u7m9gx.asia/arts/272072.Doc

四、架构设计｜Architecture
原标题：Hands‑on：模板渲染引擎最小原型实现
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.u7m9gx.asia/arts/836680.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.u7m9gx.asia/arts/313312.Doc

原标题：golang mysql exists in 性能对比
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.u7m9gx.asia/arts/240683.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.u7m9gx.asia/arts/948808.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.u7m9gx.asia/arts/629317.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.u7m9gx.asia/arts/735281.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.u7m9gx.asia/arts/782645.Doc

原标题：慢查询分析索引调优数据库实战
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.u7m9gx.asia/arts/494076.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.u7m9gx.asia/arts/338213.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.u7m9gx.asia/arts/327167.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.u7m9gx.asia/arts/850586.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.u7m9gx.asia/arts/597318.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.u7m9gx.asia/arts/322346.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.u7m9gx.asia/arts/532921.Doc

原标题：前端打包产物体积压缩优化
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/689834.Doc

原标题：golang kafka offset 提交策略
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.u7m9gx.asia/arts/519090.Doc

原标题：golang 熔断降级简易组件开发
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.u7m9gx.asia/arts/123790.Doc

原标题：golang kafka 重试机制配置实操
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.u7m9gx.asia/arts/529834.Doc

?
