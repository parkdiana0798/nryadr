最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://zhishi.su9jre.asia/blog/9062974.sHtML

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://zhishi.su9jre.asia/blog/9346372.sHtML

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://zhishi.su9jre.asia/blog/8590270.sHtML

原标题：golang 静态编译缩小镜像体积
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://zhishi.su9jre.asia/blog/7579976.sHtML

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://zhishi.su9jre.asia/blog/0034054.sHtML

原标题：版本升级服务启动失败处理
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://zhishi.su9jre.asia/blog/9627653.sHtML

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://zhishi.su9jre.asia/blog/4165102.sHtML

原标题：数据库分表路由写入分片修正
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://zhishi.su9jre.asia/blog/3553369.sHtML

原标题：新手指南：本地多版本环境共存配置
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://zhishi.su9jre.asia/blog/8862832.sHtML

原标题：Performance：数据库索引优化常见错误案例
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://zhishi.su9jre.asia/blog/4609244.sHtML

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://zhishi.su9jre.asia/blog/4903609.sHtML

原标题：golang 系统设计分库分表本地测试调试技巧
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://zhishi.su9jre.asia/blog/6125726.sHtML

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://zhishi.su9jre.asia/blog/8835821.sHtML

原标题：golang 系统设计消息队列解耦削峰
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://zhishi.su9jre.asia/blog/4144506.sHtML

原标题：golang html 模板渲染简单示例
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://zhishi.su9jre.asia/blog/0145831.sHtML

原标题：Git 仓库瘦身加快克隆下载速度
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://zhishi.su9jre.asia/blog/6689698.sHtML

原标题：Architecture：静态资源分发CDN整体架构思路
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://zhishi.su9jre.asia/blog/9482069.sHtML

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://zhishi.su9jre.asia/blog/4623894.sHtML

原标题：golang 系统设计数据库基准压测简单思路
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://zhishi.su9jre.asia/blog/4966429.sHtML

原标题：实践：消息队列死信处理业务落地实践
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://zhishi.su9jre.asia/blog/5671676.sHtML

原标题：从零搭建简单Mock接口服务
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://zhishi.su9jre.asia/blog/0787150.sHtML

原标题：SourceMap 生成线上报错定位
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://zhishi.su9jre.asia/blog/3121466.sHtML

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://zhishi.su9jre.asia/blog/4102518.sHtML

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://zhishi.su9jre.asia/blog/0016188.sHtML

原标题：HTTP 状态码请求头完整梳理
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://zhishi.su9jre.asia/blog/2624377.sHtML

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://zhishi.su9jre.asia/blog/2991752.sHtML

原标题：包管理器依赖缓存清理
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://zhishi.su9jre.asia/blog/8540053.sHtML

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://zhishi.su9jre.asia/blog/6424814.sHtML

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://zhishi.su9jre.asia/blog/0346132.sHtML

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://zhishi.su9jre.asia/blog/8248206.sHtML

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://zhishi.su9jre.asia/blog/7490122.sHtML

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://zhishi.su9jre.asia/blog/1161428.sHtML

原标题：nodejs 单元测试 jest 实操教程
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://zhishi.su9jre.asia/blog/7436569.sHtML

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://zhishi.su9jre.asia/blog/2387523.sHtML

原标题：开发记录：批量接口请求并发控制实践
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://zhishi.su9jre.asia/blog/0537763.sHtML

原标题：避坑：版本升级之后项目直接无法启动
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://zhishi.su9jre.asia/blog/3049917.sHtML

原标题：Security：业务操作审计日志安全留存
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://zhishi.su9jre.asia/blog/3549102.sHtML

原标题：Git 分支管理多人协作实战教程
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://zhishi.su9jre.asia/blog/9071083.sHtML

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://zhishi.su9jre.asia/blog/9623125.sHtML

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://zhishi.su9jre.asia/blog/3794316.sHtML


二、踩坑排错｜Troubleshooting
原标题：CPU 亲和性配置负载均衡调度
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://zhishi.su9jre.asia/blog/1103160.sHtML

原标题：golang 系统设计线上故障排查完整流程
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://zhishi.su9jre.asia/blog/2513804.sHtML

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://zhishi.su9jre.asia/blog/3863129.sHtML

原标题：缓存过期策略优化防业务故障
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://zhishi.su9jre.asia/blog/9058901.sHtML

原标题：Docker Compose 一键搭建本地栈
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://zhishi.su9jre.asia/blog/5507786.sHtML

原标题：部署实践：服务器防火墙安全组配置实践
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://zhishi.su9jre.asia/blog/2957322.sHtML

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://zhishi.su9jre.asia/blog/8516350.sHtML

原标题：golang 链路追踪简易实现方案
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://zhishi.su9jre.asia/blog/8382765.sHtML

原标题：golang base64 编码解码实操
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://zhishi.su9jre.asia/blog/0606272.sHtML

原标题：golang 数据库慢查询监控实现
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://zhishi.su9jre.asia/blog/0381564.sHtML

原标题：定时任务周期调度 demo 开发
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://zhishi.su9jre.asia/blog/0021496.sHtML

原标题：GitHub 项目提交推送完整流程讲解
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://zhishi.su9jre.asia/blog/2109424.sHtML

原标题：express 中间件开发业务实践
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://zhishi.su9jre.asia/blog/3930805.sHtML

原标题：新手指南：如何读懂开源项目报错日志
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://zhishi.su9jre.asia/blog/5688184.sHtML

原标题：调试工具断点调试变量查看技巧
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://zhishi.su9jre.asia/blog/6747490.sHtML

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://zhishi.su9jre.asia/blog/0539949.sHtML

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://zhishi.su9jre.asia/blog/5541710.sHtML

原标题：服务启动依赖顺序配置正确
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://zhishi.su9jre.asia/blog/4189570.sHtML

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://zhishi.su9jre.asia/blog/5340125.sHtML

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://zhishi.su9jre.asia/blog/9315738.sHtML

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://zhishi.su9jre.asia/blog/5315316.sHtML

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://zhishi.su9jre.asia/blog/8115335.sHtML

原标题：golang 分布式上下文传递方案
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://zhishi.su9jre.asia/blog/4163868.sHtML

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://zhishi.su9jre.asia/blog/8294249.sHtML

原标题：golang proto 默认值坑点梳理
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://zhishi.su9jre.asia/blog/0208931.sHtML

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://zhishi.su9jre.asia/blog/2927644.sHtML

原标题：golang es 分词器选型业务适配
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://zhishi.su9jre.asia/blog/3337161.sHtML

原标题：快速启动：本地运行开源项目排障清单
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://zhishi.su9jre.asia/blog/9591492.sHtML

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://zhishi.su9jre.asia/blog/1275621.sHtML

原标题：开发记录：批量接口请求并发控制实践
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://zhishi.su9jre.asia/blog/4786741.sHtML

原标题：nodejs redis 缓存业务实战
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://zhishi.su9jre.asia/blog/1271825.sHtML

原标题：golang 系统设计多租户数据隔离方案
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://zhishi.su9jre.asia/blog/2005536.sHtML

原标题：golang cron 定时任务防并发执行
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://zhishi.su9jre.asia/blog/0461208.sHtML

原标题：golang 系统设计接口参数防篡改校验
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://zhishi.su9jre.asia/blog/3108317.sHtML

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://zhishi.su9jre.asia/blog/2310904.sHtML

原标题：网关集成鉴权限流日志一体化
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://zhishi.su9jre.asia/blog/6461710.sHtML

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://zhishi.su9jre.asia/blog/3465979.sHtML

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://zhishi.su9jre.asia/blog/3827455.sHtML

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://zhishi.su9jre.asia/blog/2358513.sHtML

原标题：排错：HTTPS证书过期导致接口调用失败
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://zhishi.su9jre.asia/blog/3305755.sHtML

三、实战开发｜Practice
原标题：内网测试服务搭建团队调试
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://zhishi.su9jre.asia/blog/1119539.sHtML

原标题：golang 系统设计接口频率限制业务落地
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://zhishi.su9jre.asia/blog/0720514.sHtML

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://zhishi.su9jre.asia/blog/5656581.sHtML

原标题：Architecture：API网关核心能力与组件拆分
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://zhishi.su9jre.asia/blog/7767205.sHtML

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://zhishi.su9jre.asia/blog/5527352.sHtML

原标题：复盘总结：系统压测报告模板与分析思路
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://zhishi.su9jre.asia/blog/6649142.sHtML

原标题：跨平台换行符统一异常修复
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://zhishi.su9jre.asia/blog/3605134.sHtML

原标题：CI/CD 流水线自动构建部署落地
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://zhishi.su9jre.asia/blog/0727954.sHtML

原标题：golang mysql 死锁排查步骤讲解
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://zhishi.su9jre.asia/blog/6640340.sHtML

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://zhishi.su9jre.asia/blog/5978021.sHtML

原标题：golang mongodb 文档结构设计原则
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://zhishi.su9jre.asia/blog/3350994.sHtML

原标题：golang redis 大 key 识别处理方案
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://zhishi.su9jre.asia/blog/8181538.sHtML

原标题：golang 系统设计开源项目 release 发布流程
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://zhishi.su9jre.asia/blog/0042502.sHtML

原标题：golang kafka 消息顺序性保证方案
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://zhishi.su9jre.asia/blog/5225708.sHtML

原标题：golang 数据库连接泄露排查
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://zhishi.su9jre.asia/blog/3872532.sHtML

原标题：实战：数据库explain执行计划分析实操演练
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://zhishi.su9jre.asia/blog/9339544.sHtML

原标题：golang 系统设计第三方接口 mock 单元测试
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://zhishi.su9jre.asia/blog/9651247.sHtML

原标题：Practice：实现请求body重复读取中间件实践
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://zhishi.su9jre.asia/blog/4469944.sHtML

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://zhishi.su9jre.asia/blog/3031940.sHtML

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://zhishi.su9jre.asia/blog/2962724.sHtML

原标题：golang 链路 traceId 透传中间件
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://zhishi.su9jre.asia/blog/4974382.sHtML

原标题：项目实践：多环境配置管理组件设计与实现
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://zhishi.su9jre.asia/blog/6658713.sHtML

原标题：webpack chunk 分包策略详解
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://zhishi.su9jre.asia/blog/3424629.sHtML

原标题：golang defer panic 异常处理
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://zhishi.su9jre.asia/blog/7199703.sHtML

原标题：DevOps：日志标准输出容器日志收集方案
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://zhishi.su9jre.asia/blog/9777202.sHtML

原标题：新手快速上手 Git 版本控制实操指南
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://zhishi.su9jre.asia/blog/6333728.sHtML

原标题：Nginx 缓冲区调优大文件上传
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://zhishi.su9jre.asia/blog/2727465.sHtML

原标题：排错：前端缓存304异常更新不及时
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://zhishi.su9jre.asia/blog/6433100.sHtML

原标题：Practice：实现限流之后友好业务返回处理
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://zhishi.su9jre.asia/blog/3068285.sHtML

原标题：Docker 容器时区错误修复方案
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://zhishi.su9jre.asia/blog/5580196.sHtML

原标题：跨域偶现失败配置修复
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://zhishi.su9jre.asia/blog/2913561.sHtML

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://zhishi.su9jre.asia/blog/8979211.sHtML

原标题：golang 系统设计内部服务熔断降级配置思路
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://zhishi.su9jre.asia/blog/0435000.sHtML

原标题：golang 系统设计多租户数据隔离方案
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://zhishi.su9jre.asia/blog/7506548.sHtML

原标题：开发记录：批量接口请求并发控制实践
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://zhishi.su9jre.asia/blog/2212700.sHtML

原标题：开发代理服务网络限制解决
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://zhishi.su9jre.asia/blog/9130901.sHtML

原标题：golang 系统设计 ci 流水线安全管控思路
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://zhishi.su9jre.asia/blog/5017643.sHtML

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://zhishi.su9jre.asia/blog/6761422.sHtML

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://zhishi.su9jre.asia/blog/3960602.sHtML

原标题：golang 表单文件大小限制配置
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://zhishi.su9jre.asia/blog/7872093.sHtML

四、架构设计｜Architecture
原标题：Nginx 透传真实客户端 IP 配置
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://zhishi.su9jre.asia/blog/4552024.sHtML

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://zhishi.su9jre.asia/blog/9681065.sHtML

原标题：实战：数据库explain执行计划分析实操演练
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://zhishi.su9jre.asia/blog/5010334.sHtML

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://zhishi.su9jre.asia/blog/2319737.sHtML

原标题：golang 集成测试启动测试数据库
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://zhishi.su9jre.asia/blog/3771121.sHtML

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://zhishi.su9jre.asia/blog/3813927.sHtML

原标题：golang redis pipeline 批量操作
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://zhishi.su9jre.asia/blog/6350543.sHtML

原标题：golang 系统设计布隆过滤器原理与落地
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://zhishi.su9jre.asia/blog/2380684.sHtML

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://zhishi.su9jre.asia/blog/9477245.sHtML

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://zhishi.su9jre.asia/blog/6384913.sHtML

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://zhishi.su9jre.asia/blog/5310088.sHtML

原标题：安全实践：最小权限原则数据库账号管控
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://zhishi.su9jre.asia/blog/7424082.sHtML

原标题：方案设计：分布式锁失效风险架构层面规避
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://zhishi.su9jre.asia/blog/2940655.sHtML

原标题：实战：基于内存实现简单消息广播组件
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://zhishi.su9jre.asia/blog/9110908.sHtML

原标题：文件句柄上限调整上传随机失败
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://zhishi.su9jre.asia/blog/0127347.sHtML

原标题：内网测试服务搭建团队调试
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://zhishi.su9jre.asia/blog/1637310.sHtML

原标题：CI 流水线超时时间延长配置
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://zhishi.su9jre.asia/blog/4885185.sHtML

原标题：golang redis 位图用户签到统计
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://zhishi.su9jre.asia/blog/0862169.sHtML

?
