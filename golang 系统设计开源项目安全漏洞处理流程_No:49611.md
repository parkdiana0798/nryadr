最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目安全漏洞处理流程
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：www.share.sqchenguang.cn/Article/details/046723.shtml

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：www.share.sqchenguang.cn/Article/details/260304.shtml

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：www.share.sqchenguang.cn/Article/details/006458.shtml

原标题：golang 系统设计熔断降级架构讲解
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：www.share.sqchenguang.cn/Article/details/059539.shtml

原标题：数据库排序规则统一结果一致
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：www.share.sqchenguang.cn/Article/details/582650.shtml

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：www.share.sqchenguang.cn/Article/details/493023.shtml

原标题：golang mysql 行锁表锁场景区分
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：www.share.sqchenguang.cn/Article/details/919449.shtml

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：www.share.sqchenguang.cn/Article/details/572938.shtml

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：www.share.sqchenguang.cn/Article/details/905432.shtml

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：www.share.sqchenguang.cn/Article/details/298167.shtml

原标题：golang 系统设计内存高占用排查思路
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：www.share.sqchenguang.cn/Article/details/425216.shtml

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：www.share.sqchenguang.cn/Article/details/164081.shtml

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：www.share.sqchenguang.cn/Article/details/769047.shtml

原标题：golang 系统设计定时任务失败重试告警实现
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：www.share.sqchenguang.cn/Article/details/277641.shtml

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：www.share.sqchenguang.cn/Article/details/244262.shtml

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：www.share.sqchenguang.cn/Article/details/866360.shtml

原标题：golang gitlab ci 配置自动构建镜像
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：www.share.sqchenguang.cn/Article/details/342973.shtml

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：www.share.sqchenguang.cn/Article/details/864926.shtml

原标题：golang 系统设计性能优化通用思路方法论
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：www.share.sqchenguang.cn/Article/details/440940.shtml

原标题：开发记录：分布式ID生成器实现与压力测试
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：www.share.sqchenguang.cn/Article/details/926023.shtml

原标题：布隆过滤器误判问题修正
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：www.share.sqchenguang.cn/Article/details/724188.shtml

原标题：TCP 心跳检测清理僵死连接
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：www.share.sqchenguang.cn/Article/details/528861.shtml

原标题：golang 系统设计数据库基准压测简单思路
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：www.share.sqchenguang.cn/Article/details/482047.shtml

原标题：golang k8s 节点污点容忍度配置
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：www.share.sqchenguang.cn/Article/details/024494.shtml

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：www.share.sqchenguang.cn/Article/details/414878.shtml

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：www.share.sqchenguang.cn/Article/details/415548.shtml

原标题：golang 系统设计限流服务架构讲解
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：www.share.sqchenguang.cn/Article/details/617073.shtml

原标题：golang docker 网络模式桥接 host
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：www.share.sqchenguang.cn/Article/details/202400.shtml

原标题：开发代理服务网络限制解决
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：www.share.sqchenguang.cn/Article/details/167778.shtml

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：www.share.sqchenguang.cn/Article/details/614896.shtml

原标题：golang 数据库批量更新性能优化
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：www.share.sqchenguang.cn/Article/details/904015.shtml

原标题：golang 系统设计分库分表中间件思路
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：www.share.sqchenguang.cn/Article/details/920778.shtml

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：www.share.sqchenguang.cn/Article/details/790018.shtml

原标题：文件句柄耗尽资源泄露处理
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：www.share.sqchenguang.cn/Article/details/201209.shtml

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：www.share.sqchenguang.cn/Article/details/943992.shtml

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：www.share.sqchenguang.cn/Article/details/376052.shtml

原标题：消息队列消费堆积扩容处理
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：www.share.sqchenguang.cn/Article/details/899682.shtml

原标题：golang es 更新文档注意版本冲突
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：www.share.sqchenguang.cn/Article/details/639258.shtml

原标题：内网测试服务搭建团队调试
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：www.share.sqchenguang.cn/Article/details/889448.shtml

原标题：HelloCI：理解持续集成基础工作流程
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：www.share.sqchenguang.cn/Article/details/177646.shtml


二、踩坑排错｜Troubleshooting
原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：www.share.sqchenguang.cn/Article/details/737093.shtml

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：www.share.sqchenguang.cn/Article/details/890352.shtml

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：www.share.sqchenguang.cn/Article/details/618462.shtml

原标题：golang 系统设计压测数据构造方法实现
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：www.share.sqchenguang.cn/Article/details/267389.shtml

原标题：新手向：配置项目eslint/prettier代码格式化
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：www.share.sqchenguang.cn/Article/details/481874.shtml

原标题：数据库事务 ACID 原理讲解
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：www.share.sqchenguang.cn/Article/details/260191.shtml

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：www.share.sqchenguang.cn/Article/details/141496.shtml

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：www.share.sqchenguang.cn/Article/details/539533.shtml

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：www.share.sqchenguang.cn/Article/details/521269.shtml

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：www.share.sqchenguang.cn/Article/details/163674.shtml

原标题：Architecture：BFF后端聚合层架构适用场景
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：www.share.sqchenguang.cn/Article/details/455366.shtml

原标题：golang redis 缓存穿透解决方案
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：www.share.sqchenguang.cn/Article/details/895850.shtml

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：www.share.sqchenguang.cn/Article/details/600663.shtml

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：www.share.sqchenguang.cn/Article/details/127981.shtml

原标题：golang html 模板渲染简单示例
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：www.share.sqchenguang.cn/Article/details/104600.shtml

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：www.share.sqchenguang.cn/Article/details/027966.shtml

原标题：设计思考：分布式ID系统架构选型对比
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：www.share.sqchenguang.cn/Article/details/771305.shtml

原标题：golang 系统设计 rest http 方法使用原则
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：www.share.sqchenguang.cn/Article/details/000116.shtml

原标题：Docker 多阶段构建镜像瘦身
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：www.share.sqchenguang.cn/Article/details/881802.shtml

原标题：部署实践：数据库迁移脚本版本管理实践
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：www.share.sqchenguang.cn/Article/details/208408.shtml

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：www.share.sqchenguang.cn/Article/details/314789.shtml

原标题：golang 系统设计分布式锁不同场景选型对比
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：www.share.sqchenguang.cn/Article/details/749766.shtml

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：www.share.sqchenguang.cn/Article/details/189215.shtml

原标题：正则表达式优化 CPU 占满问题
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：www.share.sqchenguang.cn/Article/details/305284.shtml

原标题：golang 大文件 http 下载服务
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：www.share.sqchenguang.cn/Article/details/597031.shtml

原标题：OOMKilled 容器被杀完整排查
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：www.share.sqchenguang.cn/Article/details/041673.shtml

原标题：golang 信号捕获程序退出处理
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：www.share.sqchenguang.cn/Article/details/330546.shtml

原标题：架构笔记：数据库连接池架构参数调优思路
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：www.share.sqchenguang.cn/Article/details/880285.shtml

原标题：零基础理解进程、线程基础概念区别
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：www.share.sqchenguang.cn/Article/details/711808.shtml

原标题：极简 API 网关路由转发实现
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：www.share.sqchenguang.cn/Article/details/005351.shtml

原标题：nodejs 日志轮转生产环境配置
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：www.share.sqchenguang.cn/Article/details/072593.shtml

原标题：golang 互斥锁读写锁并发安全
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：www.share.sqchenguang.cn/Article/details/576152.shtml

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：www.share.sqchenguang.cn/Article/details/185251.shtml

原标题：Performance：大事务拆分，减少锁持有时间
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：www.share.sqchenguang.cn/Article/details/375244.shtml

原标题：golang 系统设计参数校验统一处理方案
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：www.share.sqchenguang.cn/Article/details/304742.shtml

原标题：记一次升级操作系统内核引发服务不稳定
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：www.share.sqchenguang.cn/Article/details/206361.shtml

原标题：golang 系统设计回调签名校验防伪造实现
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：www.share.sqchenguang.cn/Article/details/901769.shtml

原标题：golang 系统设计 webhook 回调处理架构
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：www.share.sqchenguang.cn/Article/details/392009.shtml

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：www.share.sqchenguang.cn/Article/details/993810.shtml

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：www.share.sqchenguang.cn/Article/details/063883.shtml

三、实战开发｜Practice
原标题：golang zap 日志按日期切割方案
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：www.share.sqchenguang.cn/Article/details/052600.shtml

原标题：文件分片上传断点续传功能
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：www.share.sqchenguang.cn/Article/details/134288.shtml

原标题：golang es 更新文档注意版本冲突
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：www.share.sqchenguang.cn/Article/details/559880.shtml

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：www.share.sqchenguang.cn/Article/details/966590.shtml

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：www.share.sqchenguang.cn/Article/details/426323.shtml

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：www.share.sqchenguang.cn/Article/details/626172.shtml

原标题：golang 单例模式实现几种方式
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：www.share.sqchenguang.cn/Article/details/233623.shtml

原标题：项目实践：定时任务防重复执行落地实践
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：www.share.sqchenguang.cn/Article/details/863299.shtml

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：www.share.sqchenguang.cn/Article/details/452105.shtml

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：www.share.sqchenguang.cn/Article/details/185175.shtml

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：www.share.sqchenguang.cn/Article/details/373589.shtml

原标题：记一次字符集编码不一致乱码问题全排查
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：www.share.sqchenguang.cn/Article/details/948434.shtml

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：www.share.sqchenguang.cn/Article/details/151637.shtml

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：www.share.sqchenguang.cn/Article/details/785625.shtml

原标题：静态博客部署 GitHub Pages 教程
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：www.share.sqchenguang.cn/Article/details/757663.shtml

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：www.share.sqchenguang.cn/Article/details/859859.shtml

原标题：排错：静态资源404，打包路径配置错误
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：www.share.sqchenguang.cn/Article/details/799807.shtml

原标题：网关集成鉴权限流日志一体化
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：www.share.sqchenguang.cn/Article/details/069516.shtml

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：www.share.sqchenguang.cn/Article/details/422933.shtml

原标题：golang 系统设计故障演练简单落地思路方法论
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：www.share.sqchenguang.cn/Article/details/373990.shtml

原标题：golang 系统设计数据脱敏架构实现
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：www.share.sqchenguang.cn/Article/details/475095.shtml

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：www.share.sqchenguang.cn/Article/details/820895.shtml

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：www.share.sqchenguang.cn/Article/details/126953.shtml

原标题：golang 数据库连接泄露排查
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：www.share.sqchenguang.cn/Article/details/561281.shtml

原标题：排错：前端缓存304异常更新不及时
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：www.share.sqchenguang.cn/Article/details/012292.shtml

原标题：golang docker compose 完整语法
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：www.share.sqchenguang.cn/Article/details/638392.shtml

原标题：安全实践：防止重放攻击接口签名方案
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：www.share.sqchenguang.cn/Article/details/237946.shtml

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：www.share.sqchenguang.cn/Article/details/785278.shtml

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：www.share.sqchenguang.cn/Article/details/895138.shtml

原标题：零基础理解依赖管理与包管理器
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：www.share.sqchenguang.cn/Article/details/229276.shtml

原标题：方案设计：分布式分页查询架构难点处理
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：www.share.sqchenguang.cn/Article/details/272125.shtml

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：www.share.sqchenguang.cn/Article/details/088067.shtml

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：www.share.sqchenguang.cn/Article/details/932656.shtml

原标题：golang 优雅处理数据库事务
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：www.share.sqchenguang.cn/Article/details/992658.shtml

原标题：时间精度统一业务判断修复
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：www.share.sqchenguang.cn/Article/details/566655.shtml

原标题：实践：静态站点自动化部署到GitHubPages
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：www.share.sqchenguang.cn/Article/details/031736.shtml

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：www.share.sqchenguang.cn/Article/details/234100.shtml

原标题：开发记录：分布式锁超时业务安全处理实践
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：www.share.sqchenguang.cn/Article/details/858110.shtml

原标题：手写简易 RPC 服务通信原型
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：www.share.sqchenguang.cn/Article/details/890396.shtml

原标题：方案对比：定时任务框架选型与架构对比
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：www.share.sqchenguang.cn/Article/details/456512.shtml

四、架构设计｜Architecture
原标题：HelloEnv：多操作系统环境变量配置汇总
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：www.share.sqchenguang.cn/Article/details/201414.shtml

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：www.share.sqchenguang.cn/Article/details/376985.shtml

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：www.share.sqchenguang.cn/Article/details/564313.shtml

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：www.share.sqchenguang.cn/Article/details/370744.shtml

原标题：设计思考：分布式会话架构选型对比
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：www.share.sqchenguang.cn/Article/details/260476.shtml

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：www.share.sqchenguang.cn/Article/details/995069.shtml

原标题：golang 系统设计传输加密 tls 配置要点
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：www.share.sqchenguang.cn/Article/details/042440.shtml

原标题：golang 优雅停机服务关闭实现
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：www.share.sqchenguang.cn/Article/details/763397.shtml

原标题：API 大版本不兼容平滑迁移
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：www.share.sqchenguang.cn/Article/details/485738.shtml

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：www.share.sqchenguang.cn/Article/details/113399.shtml

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：www.share.sqchenguang.cn/Article/details/693595.shtml

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：www.share.sqchenguang.cn/Article/details/052566.shtml

原标题：方案设计：分布式分页查询架构难点处理
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：www.share.sqchenguang.cn/Article/details/772536.shtml

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：www.share.sqchenguang.cn/Article/details/988169.shtml

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：www.share.sqchenguang.cn/Article/details/595201.shtml

原标题：全量回归测试提升代码质量
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：www.share.sqchenguang.cn/Article/details/834652.shtml

原标题：golang 系统设计内部服务调用超时设置要点
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：www.share.sqchenguang.cn/Article/details/319573.shtml

原标题：git stash 代码暂存切换分支
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：www.share.sqchenguang.cn/Article/details/269505.shtml

?
