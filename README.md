# oc-subdomain 概述
ocybers 的子域名搜集模块

# oc-subdomain 功能
### 多通道子域名信息搜集：
- 接入近 多种API 接口，通过第三方平台获取子域名信息，包括 ip138、rapiddns、virustotal(v2) 等免费接口，以及 fofa、hunter、virustotal(v3) 等付费接口。
- 支持 baidu、bing、sougou 等搜索引擎获取子域名信息。
- 支持有状态和无状态子域名枚举，兼顾准确度和效率。

### 原子能力
- 支持命令行工具使用。
- 提供 API 封装，支持任务启动、暂停、重启和中止等操作。
- 提供 Go 包，支持能力集成。
