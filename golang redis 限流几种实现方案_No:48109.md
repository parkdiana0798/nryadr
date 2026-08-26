最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang redis 限流几种实现方案
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.3hxem0.asia/blog/371440.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.3hxem0.asia/blog/666957.Doc

原标题：零基础理解前后端简单交互流程
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.3hxem0.asia/blog/152334.Doc

原标题：文件批量导入导出功能实现
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.3hxem0.asia/blog/581300.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.3hxem0.asia/blog/030644.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.3hxem0.asia/blog/985706.Doc

原标题：golang 系统设计读写分离架构示例
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.3hxem0.asia/blog/412196.Doc

原标题：golang mongodb 聚合管道实操案例
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.3hxem0.asia/blog/966087.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.3hxem0.asia/blog/181951.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.3hxem0.asia/blog/381287.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.3hxem0.asia/blog/386805.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.3hxem0.asia/blog/530844.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.3hxem0.asia/blog/048652.Doc

原标题：RPC 接口字段增减兼容处理
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.3hxem0.asia/blog/928108.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.3hxem0.asia/blog/862339.Doc

原标题：静态资源 404 路径打包修复
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.3hxem0.asia/blog/075795.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.3hxem0.asia/blog/634699.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.3hxem0.asia/blog/318962.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.3hxem0.asia/blog/301495.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.3hxem0.asia/blog/266596.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.3hxem0.asia/blog/101991.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.3hxem0.asia/blog/120603.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.3hxem0.asia/blog/896447.Doc

原标题：golang 信号量控制并发数量
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.3hxem0.asia/blog/929021.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.3hxem0.asia/blog/572448.Doc

原标题：golang prometheus 告警规则编写
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.3hxem0.asia/blog/485925.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.3hxem0.asia/blog/215753.Doc

原标题：golang 单元测试 mock http 请求
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.3hxem0.asia/blog/934408.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.3hxem0.asia/blog/896588.Doc

原标题：从零学习简单分页逻辑实现思路
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.3hxem0.asia/blog/881473.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.3hxem0.asia/blog/885587.Doc

原标题：API 大版本不兼容平滑迁移
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.3hxem0.asia/blog/561333.Doc

原标题：CI 流水线构建失败日志排查
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.3hxem0.asia/blog/605514.Doc

原标题：时间精度统一业务判断修复
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.3hxem0.asia/blog/221577.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.3hxem0.asia/blog/561587.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.3hxem0.asia/blog/745519.Doc

原标题：前端静态缓存更新生效处理
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.3hxem0.asia/blog/533382.Doc

原标题：golang 系统设计读写分离架构示例
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.3hxem0.asia/blog/333576.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.3hxem0.asia/blog/370446.Doc

原标题：golang redis 主从复制哨兵原理
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.3hxem0.asia/blog/263282.Doc


二、踩坑排错｜Troubleshooting
原标题：调优方案：服务实例扩容，水平扩展性能
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.3hxem0.asia/blog/419034.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.3hxem0.asia/blog/482445.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.3hxem0.asia/blog/343170.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.3hxem0.asia/blog/153908.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.3hxem0.asia/blog/120351.Doc

原标题：批量操作分批处理防止 OOM
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.3hxem0.asia/blog/851408.Doc

原标题：JWT 令牌过期异常处理
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.3hxem0.asia/blog/318112.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.3hxem0.asia/blog/698848.Doc

原标题：golang k8s devops 流水线简单思路
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.3hxem0.asia/blog/457471.Doc

原标题：golang 布隆过滤器实现去重
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.3hxem0.asia/blog/300035.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.3hxem0.asia/blog/304632.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.3hxem0.asia/blog/426138.Doc

原标题：图片上传预览格式大小处理
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.3hxem0.asia/blog/406612.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.3hxem0.asia/blog/157227.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.3hxem0.asia/blog/333618.Doc

原标题：golang 开发环境快速搭建指南
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.3hxem0.asia/blog/952800.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.3hxem0.asia/blog/075242.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.3hxem0.asia/blog/664977.Doc

原标题：golang 系统设计分布式事务几种方案
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://book.3hxem0.asia/blog/017577.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://book.3hxem0.asia/blog/675796.Doc

原标题：文件句柄耗尽资源泄露处理
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.3hxem0.asia/blog/923604.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.3hxem0.asia/blog/616844.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.3hxem0.asia/blog/756828.Doc

原标题：nodejs redis 缓存业务实战
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.3hxem0.asia/blog/479385.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.3hxem0.asia/blog/660771.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.3hxem0.asia/blog/476392.Doc

原标题：文件句柄耗尽资源泄露处理
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.3hxem0.asia/blog/153508.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.3hxem0.asia/blog/963503.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.3hxem0.asia/blog/380403.Doc

原标题：多实例部署 Session 共享方案
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.3hxem0.asia/blog/224663.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.3hxem0.asia/blog/529214.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.3hxem0.asia/blog/699369.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.3hxem0.asia/blog/396869.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.3hxem0.asia/blog/529285.Doc

原标题：golang docker 网络模式桥接 host
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.3hxem0.asia/blog/307051.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.3hxem0.asia/blog/231836.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.3hxem0.asia/blog/962277.Doc

原标题：golang mongodb 文档结构设计原则
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.3hxem0.asia/blog/055402.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.3hxem0.asia/blog/487095.Doc

原标题：OOMKilled 容器被杀完整排查
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.3hxem0.asia/blog/883806.Doc

三、实战开发｜Practice
原标题：rebase 操作防止代码丢失
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.3hxem0.asia/blog/304217.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.3hxem0.asia/blog/598544.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.3hxem0.asia/blog/007613.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.3hxem0.asia/blog/113921.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.3hxem0.asia/blog/647768.Doc

原标题：入门实践：本地简单代理服务搭建
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.3hxem0.asia/blog/334437.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.3hxem0.asia/blog/660002.Doc

原标题：golang mongodb 聚合管道实操案例
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.3hxem0.asia/blog/379771.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.3hxem0.asia/blog/934221.Doc

原标题：golang mysql 存储过程简单使用
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.3hxem0.asia/blog/348803.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.3hxem0.asia/blog/111869.Doc

原标题：golang 链路 traceId 透传中间件
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.3hxem0.asia/blog/072704.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.3hxem0.asia/blog/583072.Doc

原标题：golang 系统设计多级缓存架构落地
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.3hxem0.asia/blog/974168.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.3hxem0.asia/blog/353067.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.3hxem0.asia/blog/212321.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.3hxem0.asia/blog/473072.Doc

原标题：golang gorm 批量插入性能调优
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.3hxem0.asia/blog/635637.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.3hxem0.asia/blog/204660.Doc

原标题：golang 系统设计灰度发布实现思路
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.3hxem0.asia/blog/316850.Doc

原标题：golang k8s liveness readiness 探针
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.3hxem0.asia/blog/232633.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.3hxem0.asia/blog/921076.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.3hxem0.asia/blog/266521.Doc

原标题：多线程线程安全脏数据规避
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.3hxem0.asia/blog/962632.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.3hxem0.asia/blog/463229.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.3hxem0.asia/blog/899465.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.3hxem0.asia/blog/640520.Doc

原标题：golang es 高亮搜索结果实现方案
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.3hxem0.asia/blog/719842.Doc

原标题：golang es 高亮搜索结果实现方案
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.3hxem0.asia/blog/885587.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.3hxem0.asia/blog/492786.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.3hxem0.asia/blog/163633.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.3hxem0.asia/blog/541291.Doc

原标题：零基础理解幂等性基础概念与场景
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.3hxem0.asia/blog/689224.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.3hxem0.asia/blog/541154.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.3hxem0.asia/blog/598939.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.3hxem0.asia/blog/824243.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.3hxem0.asia/blog/294361.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.3hxem0.asia/blog/634503.Doc

原标题：消息队列生产消费模型入门
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.3hxem0.asia/blog/189585.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.3hxem0.asia/blog/194481.Doc

四、架构设计｜Architecture
原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.3hxem0.asia/blog/094178.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.3hxem0.asia/blog/608818.Doc

原标题：nodejs redis 缓存业务实战
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.3hxem0.asia/blog/160776.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.3hxem0.asia/blog/426058.Doc

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.3hxem0.asia/blog/546202.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.3hxem0.asia/blog/274806.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.3hxem0.asia/blog/090931.Doc

原标题：消息消费重试次数限制防爆炸
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.3hxem0.asia/blog/500969.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.3hxem0.asia/blog/675158.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.3hxem0.asia/blog/422809.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.3hxem0.asia/blog/518801.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.3hxem0.asia/blog/143796.Doc

原标题：golang mysql 分表自增 id 方案
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.3hxem0.asia/blog/936763.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.3hxem0.asia/blog/741137.Doc

原标题：golang es 分页深分页性能优化
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.3hxem0.asia/blog/149068.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.3hxem0.asia/blog/164590.Doc

原标题：业务错误码完整落地实践
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.3hxem0.asia/blog/318428.Doc

原标题：golang k8s ingress 路由域名转发
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.3hxem0.asia/blog/571464.Doc

?
