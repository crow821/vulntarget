

<h1 align="center">Welcome to Vulntarget 👋</h1>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/crow821/github-profile-readme-generator/fork" target="blank">
	<img src="https://img.shields.io/github/forks/crow821/vulntarget?style=flat-square" alt="vulntarget forks"/>
  </a>
  <a href="https://github.com/crow821/vulntarget/blob/master/LICENSE" target="blank">
    <img alt="License: GPL--3.0 License" src="https://img.shields.io/github/license/crow821/Vulntarget" />
  </a>
  <a href="https://github.com/crow821/github-profile-readme-generator/stargazers" target="blank">
	<img src="https://img.shields.io/github/stars/crow821/vulntarget?style=flat-square" alt="vulntarget stars"/>
  </a>
  <a href="https://github.com/crow821/github-profile-readme-generator/issues" target="blank">
	<img src="https://img.shields.io/github/issues/crow821/vulntarget?style=flat-square" alt="vulntarget issues"/>
  </a>
  <a href="https://github.com/crow821/github-profile-readme-generator/pulls" target="blank">
	<img src="https://img.shields.io/github/issues-pr/crow821/vulntarget?style=flat-square" alt="vulntarget pull-requests"/>
  </a>


> 更新时间：2026.03.29

# 1. 免责声明 

**`vulntarget`靶场系列仅供安全专业人员练习渗透测试技术，此靶场所提供的信息只为网络安全人员对自己所负责的网站、服务器等（包括但不限于）进行检测或维护参考，未经授权请勿利用靶场中的技术资料对任何计算机系统进行入侵操作。利用此靶场所提供的信息而造成的直接或间接后果和损失，均由使用者本人负责。**

**`vulntarget`靶场系列拥有对此靶场系列的的修改、删除和解释权限，未经授权，不得用于其他！！！**
​

<h1 ><font color='red'>未授权，不渗透！！！</font></h1>



# 2. 靶场介绍

`vulntarget` 最初由`星期五实验室`发起，早期作为综合性实战靶场由网络安全爱好者共同维护。目前，从 `vulntarget-n` 开始，该靶场由` crow` 单独负责维护。

`vulntarget`整体的大小尽量控制在`16G`内存以内（`vulntarget-o`除外），主要是为了确保每个人都能够在本机对环境进行复现。

欢迎多多`star`。。。

`vulntarget`是一个开源的靶场，也欢迎提交您的设计！



# 3. 靶场设计搭建

| 靶场名称     | 搭建类型                                                     | 设计人员              | 搭建教程                                                | 线上参考                                                     |
| :----------- | :----------------------------------------------------------- | :-------------------- | :------------------------------------------------------ | :----------------------------------------------------------- |
| vulntarget-p | ipv6、mysql数据恢复技术                                      | crow                  | 待补充                                                  | 待补充                                                       |
| vulntarget-o | VMware vCenter 靶场环境                                      | crow                  | [点击查看](./vulntarget/target_build/vulntarget-o.html) | [点击查看](https://mp.weixin.qq.com/s/1i8LCsgy6OG0cpieJ4kRGw) |
| vulntarget-n | 勒索病毒应急、取证                                           | crow                  | [点击查看](./vulntarget/target_build/vulntarget-n.html) | [点击查看](https://mp.weixin.qq.com/s/ZO-SXw5rvpLrjmcjcN9_6w) |
| vulntarget-m | java内存马应急、nacos、shiro、fastjson、攻防一体靶场         | lemono、crow          | [点击查看](./vulntarget/target_build/vulntarget-m.html) | [点击查看](https://mp.weixin.qq.com/s/lXFQ3xUAD-Yn_-8hMhjrcQ) |
| vulntarget-L | 工控相关、totolink组合RCE、tenda RCE、Exchange组合RCE、证书域提权、内网流量代理、免杀技术 | Fariy                 | [点击查看](./vulntarget/target_build/vulntarget-l.html) | [点击查看](https://mp.weixin.qq.com/s/tXSjXIDG1mLpVxzZui31Nw) |
| vulntarget-k | xxl-job-admin RCE、nacos未授权、springcloudgateway RCE、redis、内网流量代理 | mortals               | [点击查看](./vulntarget/target_build/vulntarget-k.html) | [点击查看](https://mp.weixin.qq.com/s/3TOLSUaKfIOFlo3j-0IEFA) |
| vulntarget-j | fastadmin命令执行、文件上传、目录遍历、bypass杀软、浏览器取证 | ju2i                  | [点击查看](./vulntarget/target_build/vulntarget-j.html) | [点击查看](https://mp.weixin.qq.com/s/-h65qdfCcTe_8c0Tvmb10A) |
| vulntarget-i | sql注入、文件读取、文件上传、内网不出网上线mssql主机、浏览器读取、隧道代理等 | 小树林开炮手          | [点击查看](./vulntarget/target_build/vulntarget-i.html) | [点击查看](https://mp.weixin.qq.com/s/-W2Rp9wKmwus40eMzo8WRQ) |
| vulntarget-h | sql注入、文件包含、命令执行，免杀等漏洞利用、隧道代理等      | Macchiato             | [点击查看](./vulntarget/target_build/vulntarget-h.html) | [点击查看](https://mp.weixin.qq.com/s/AGmqroovR1EZN-QKnpSfDQ) |
| vulntarget-g | 工控类型：嵌入式HMI软件、力控软件、LAquis等                  | CyPher、XXP           | [点击查看](./vulntarget/target_build/vulntarget-g.html) | [点击查看](https://mp.weixin.qq.com/s/uxoUqsWCBwiG_69ORJ8RAw) |
| vulntarget-f | zimbra、kibana、nexes等漏洞利用、隧道代理、提权              | mortals、null         | [点击查看](./vulntarget/target_build/vulntarget-f.html) | [点击查看](https://mp.weixin.qq.com/s/t_vxF2EivycI_1WEjunEIg) |
| vulntarget-e | 低版本向日葵、约束委派、免杀                                 | 小树林开炮手、mortals | [点击查看](./vulntarget/target_build/vulntarget-e.html) | [点击查看](https://mp.weixin.qq.com/s/QWpkYf56oFvNdlumNo6fMA) |
| vulntarget-d | 74cms、frp穿透、免杀、提权                                   | mortals、crow         | [点击查看](./vulntarget/target_build/vulntarget-d.html) | [点击查看](https://mp.weixin.qq.com/s/gjQnMcBXUbtYc2C2FCfEhQ) |
| vulntarget-c | Laravel、免杀、提权                                          | mortals               | [点击查看](./vulntarget/target_build/vulntarget-c.html) | [点击查看](https://mp.weixin.qq.com/s/cisoqDnsHqyzCFdx-eG5TQ) |
| vulntarget-b | cms、域控环境、免杀                                          | mortals               | [点击查看](./vulntarget/target_build/vulntarget-b.html) | [点击查看](https://mp.weixin.qq.com/s/S3aiKN_IIhxWRyizAb8zLg) |
| vulntarget-a | 域控环境                                                     | mortals               | [点击查看](./vulntarget/target_build/vulntarget-a.html) | [点击查看](https://mp.weixin.qq.com/s/uxwbnVOxkR8OBkkY9WW6aQ) |

# 4. 靶场参考write up

| 靶场名称     | 测试人员                                      | 参考 write up                                                | 线上参考                                                     |
| :----------- | :-------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| vulntarget-p | crow                                          | 待更新                                                       | 待更新                                                       |
| vulntarget-o | crow                                          | [点击查看](./vulntarget/write_up/vulntarget-o-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/IjcURvYxbvMvBXHbxCi4aA) |
| vulntarget-n | crow                                          | [点击查看](./vulntarget/write_up/vulntarget-n-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/k8tXFKLK9Ky0J4_uPfOd3A) |
| vulntarget-m | lemono、crow                                  | [点击查看](./vulntarget/write_up/vulntarget-m-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/YxZqgd6Hjz3QcYCPAGpAGg) |
| vulntarget-l | Fariy                                         | [点击查看](./vulntarget/write_up/vulntarget-l-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/3W5GXNjV4uiZBkjMSuCNLQ) |
| vulntarget-k | null、foxcookie、ju2i、cypher                 | [点击查看](./vulntarget/write_up/vulntarget-k-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/LHq8O2F-r6rbhVW84Q4KEg) |
| vulntarget-j | cypher、xxp、ju2i、foxcookie                  | [点击查看](./vulntarget/write_up/vulntarget-j-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/6_j38gpvTfCVDTcCYizCYA) |
| vulntarget-i | Cypher、ju2i、小树林开炮手                    | [点击查看](./vulntarget/write_up/vulntarget-i-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/jHeErfr3P4XgfYPG9Ocgng) |
| vulntarget-h | CyPher、XXP、mortals                          | [点击查看](./vulntarget/write_up/vulntarget-h-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/TXd_SaJMdVZeMVxNgPg2uw) |
| vulntarget-g | CyPher、XXP、mortals                          | [点击查看](./vulntarget/write_up/vulntarget-g-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/BOACc1p6cnIJAj0pzeY2wg) |
| vulntarget-f | mortals、null、1ncludeSteven、XXP、ju2i       | [点击查看](./vulntarget/write_up/vulntarget-f-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/5SOJ-hzrn9_HyUZrZkOjhA) |
| vulntarget-e | mortals、小树林开炮手、CyPher、XXP、Macchiato | [点击查看](./vulntarget/write_up/vulntarget-e-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/eh8SXkgcSQjLkFEjNkkfHw) |
| vulntarget-d | mouse、crow、mortals                          | [点击查看](./vulntarget/write_up/vulntarget-d-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/gjQnMcBXUbtYc2C2FCfEhQ) |
| vulntarget-c | mouse、crow、mortals                          | [点击查看](./vulntarget/write_up/vulntarget-c-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/cisoqDnsHqyzCFdx-eG5TQ) |
| vulntarget-b | mouse、ZeroP、mortals、CyPher、4nth0ny        | [点击查看](./vulntarget/write_up/vulntarget-b-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/S3aiKN_IIhxWRyizAb8zLg) |
| vulntarget-a | crow、jiuq、CyPher、mouse、mortals            | [点击查看](./vulntarget/write_up/vulntarget-a-write-up.html) | [点击查看](https://mp.weixin.qq.com/s/uxwbnVOxkR8OBkkY9WW6aQ) |

# 5. 靶场下载

## vulntrarget-a~vulntarget-p

下载地址：

百度云

链接: https://pan.baidu.com/s/1sv9qdioNF4PTUliix5HEfg 提取码: 2dwq 

夸克网盘：

链接：https://pan.quark.cn/s/e65bf3efbf0b?pwd=GHgE  提取码：GHgE

# 6. 联系我们

如果你有任何意见或建议，可以直接联系我

邮箱：`crow_821#163.com`（#-->@）

**公众号：`乌鸦安全`**

<img src="crowsec.jpg" width="30%" height="30%" />

# stars



![Stargazers over time](https://starchart.cc/crow821/vulntarget.svg)

# License

Copyright © 2025 [crow821](https://github.com/crow821)

本项目遵循协议：[GPL--3.0 License](https://github.com/crow821/vulntarget/blob/master/LICENSE)

