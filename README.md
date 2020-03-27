# TODO Network Development

## 目标

建立开箱即用的网络基础设施，涵盖三层到七层网络编程环境

## 内容

- [ ] 准备使用 asyncdispatch 作为基础 io 引擎，不使用 asyncnet、asynchttpserver、httpclient、net；使用 nativesockets。建立一个 io 框架，包含 net 模块 (tcp socket 和 tcp server)、datagram 模块 (udp socket)、tls 模块 (tls tcp socket 和 tls tcp server)、http 模块 (HTTP client、HTTP server)、https 模块 (tls http client 和 tls http server)、裁剪测试优化 asyncdispatch、websocket 模块

- [ ] 建立 http 工具包 cookie、session (简单测试环境)、formdata、openauth、jwt

- [ ] 建立 mysql、postgresql、mongodb、redis 等主流数据库连接器，支持常规请求查询、数据流、超大结果数据集、连接池

- [ ] 建立 high-level web server 框架，支持 ioc、aop/intecepter、valadation、logging、testing、mocking？ (spring-boot/mvc style)

- [ ] 建立 high-level sql framework 依赖注入框架

- [ ] 发布 IMCP 即时通信协议，建立 server、client、web client、android client

- [ ] 建立 QUIC server、client

- [ ] 建立 MQTT broker、client

- [ ] 建立一个文档网站，包含 api documentation、教程列表、关键例子列表、benchmark 链接列表、问题链接列表，把所有 network 相关的内容和依赖代码库相关资料链接在一起

## 要求

- github 建立 iocrate org，只存放一个 org 组织说明库和其他决定发布的代码库，不存放任何其他无关的库
- 每个代码库经过多个严格测试，基准测试，在多个平台/环境测试
- 每个代码库有 api documentation
- 每个代码库有 step by step 的使用说明
- 有关键例子演示说明
- 每个代码库能及时反馈 issures 以及修复 bugs
- 每个代码库有维护者
- 文档和网站有中文和英文两个版本




