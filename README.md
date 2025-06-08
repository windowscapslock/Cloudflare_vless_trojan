# Cloudflare-workers/pages代理脚本【目前版本：25.5.4】
### 1、本项目仅支持本地化部署
### 2、本项目配置都为本地化编辑，不使用订阅器、订阅转换等第三方外链引用
### 3、无需担心节点订阅信息被订阅器作者或者订阅转换作者后台查看
--------------------------------
## 脚本特色：
#### 1、懒人小白专用！默认节点都为CF官方IP，无需频繁更新订阅获取客户端优选IP
#### 2、为减少新手小白额外的成本，本项目不推荐使用自定义域名，如果你一定要用自定义域名，也可以
#### 3、当在CF点击部署按钮后，可直接手搓节点或者使用分享链接，最多设置一个uuid/密码，其他不用改
#### 4、Workers方式：支持vless+ws+tls、trojan+ws+tls、vless+ws、trojan+ws代理节点
#### 5、Pages方式：支持vless+ws+tls、trojan+ws+tls代理节点
#### 6、支持单节点链接、聚合通用节点链接、聚合通用节点订阅、sing-box节点订阅、clash节点订阅
#### 7、虽然仅乱码混淆版可用，但只有修改uuid/密码时才必须使用变量
#### 8、VLESS仅nat64套壳版将自动填充proxyip，无需且不支持proxyip设置，由[badafans](https://github.com/badafans)提供代码
-------------------------------------------------------------

----------------------------------------------------------------------
### 代码来源：[ca110us](https://github.com/ca110us/epeius)、[emn178](https://github.com/emn178/js-sha256/blob/master/src/sha256.js)、[3Kmfi6HP](https://github.com/3Kmfi6HP/EDtunnel)、[badafans](https://github.com/badafans/Cloudflare-IP-SpeedTest)、[XIU2](https://github.com/XIU2/CloudflareSpeedTest)
### 声明：所有代码来源于Github社区，并通过ChatGPT进行整合
