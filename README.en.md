<h1 align="center">Vulntarget 👋</h1>

<p align="center"><a href="./Readme.md">简体中文</a> | <strong>English</strong></p>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/crow821/vulntarget/forks">
    <img src="https://img.shields.io/github/forks/crow821/vulntarget?style=flat-square" alt="Vulntarget forks" />
  </a>
  <a href="https://github.com/crow821/vulntarget/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/crow821/vulntarget" alt="GPL-3.0 license" />
  </a>
  <a href="https://github.com/crow821/vulntarget/stargazers">
    <img src="https://img.shields.io/github/stars/crow821/vulntarget?style=flat-square" alt="Vulntarget stars" />
  </a>
  <a href="https://github.com/crow821/vulntarget/issues">
    <img src="https://img.shields.io/github/issues/crow821/vulntarget?style=flat-square" alt="Vulntarget issues" />
  </a>
  <a href="https://github.com/crow821/vulntarget/pulls">
    <img src="https://img.shields.io/github/issues-pr/crow821/vulntarget?style=flat-square" alt="Vulntarget pull requests" />
  </a>
</p>

> Last updated: April 2, 2026

# 1. Disclaimer

**The `vulntarget` lab series is intended only for security professionals to practice penetration testing. The information provided is for reference when testing or maintaining websites, servers, and other systems for which you are responsible. Do not use these materials to access any computer system without authorization. Users are solely responsible for any direct or indirect consequences or losses arising from their use of these materials.**

**The `vulntarget` team reserves the right to modify, remove, and interpret this lab series. Use for other purposes requires authorization.**

<h2>Do not conduct penetration testing without authorization!</h2>

# 2. About the labs

`vulntarget` was originally started by Friday Lab (星期五实验室) and maintained by a community of security enthusiasts as a comprehensive hands-on lab. From `vulntarget-n` onward, the series has been maintained solely by Crow Security (乌鸦安全).

Except for `vulntarget-o`, the labs aim to use no more than 16 GB of memory so that they can be reproduced on a local machine.

If you find the project useful, please give it a star. `vulntarget` is open source, and your lab designs are welcome.

The linked setup guides and write-ups are currently in Chinese.

# 3. Lab setup guides

| Lab | Topics | Designer(s) | Setup guide | Online reference |
| :--- | :--- | :--- | :--- | :--- |
| vulntarget-p | IPv6; MySQL data recovery | crow | [View guide](./vulntarget/target_build/vulntarget-p.html) | [View article](https://mp.weixin.qq.com/s/_NvcPLB3cTVzKH4-wFsb7g) |
| vulntarget-o | VMware vCenter lab environment | crow | [View guide](./vulntarget/target_build/vulntarget-o.html) | [View article](https://mp.weixin.qq.com/s/1i8LCsgy6OG0cpieJ4kRGw) |
| vulntarget-n | Ransomware incident response and forensics | crow | [View guide](./vulntarget/target_build/vulntarget-n.html) | [View article](https://mp.weixin.qq.com/s/ZO-SXw5rvpLrjmcjcN9_6w) |
| vulntarget-m | Java in-memory web shell incident response; Nacos; Shiro; Fastjson; attack and defense lab | lemono, crow | [View guide](./vulntarget/target_build/vulntarget-m.html) | [View article](https://mp.weixin.qq.com/s/lXFQ3xUAD-Yn_-8hMhjrcQ) |
| vulntarget-L | Industrial control systems; chained TotoLink and Tenda RCE; chained Exchange RCE; certificate-based domain privilege escalation; internal network traffic proxying; antivirus evasion | Fariy | [View guide](./vulntarget/target_build/vulntarget-l.html) | [View article](https://mp.weixin.qq.com/s/tXSjXIDG1mLpVxzZui31Nw) |
| vulntarget-k | XXL-JOB Admin RCE; unauthorized Nacos access; Spring Cloud Gateway RCE; Redis; internal network traffic proxying | mortals | [View guide](./vulntarget/target_build/vulntarget-k.html) | [View article](https://mp.weixin.qq.com/s/3TOLSUaKfIOFlo3j-0IEFA) |
| vulntarget-j | FastAdmin command execution, file upload, and directory traversal; antivirus bypass; browser forensics | ju2i | [View guide](./vulntarget/target_build/vulntarget-j.html) | [View article](https://mp.weixin.qq.com/s/-h65qdfCcTe_8c0Tvmb10A) |
| vulntarget-i | SQL injection; file read and upload; connecting a MSSQL host without direct internet access; browser data extraction; tunneling and proxying | 小树林开炮手 | [View guide](./vulntarget/target_build/vulntarget-i.html) | [View article](https://mp.weixin.qq.com/s/-W2Rp9wKmwus40eMzo8WRQ) |
| vulntarget-h | SQL injection; file inclusion; command execution; antivirus evasion; tunneling and proxying | Macchiato | [View guide](./vulntarget/target_build/vulntarget-h.html) | [View article](https://mp.weixin.qq.com/s/AGmqroovR1EZN-QKnpSfDQ) |
| vulntarget-g | Industrial control systems: embedded HMI software, ForceControl, LAquis, and more | CyPher, XXP | [View guide](./vulntarget/target_build/vulntarget-g.html) | [View article](https://mp.weixin.qq.com/s/uxoUqsWCBwiG_69ORJ8RAw) |
| vulntarget-f | Zimbra, Kibana, Nexus, and other vulnerability exploitation; tunneling and proxying; privilege escalation | mortals, null | [View guide](./vulntarget/target_build/vulntarget-f.html) | [View article](https://mp.weixin.qq.com/s/t_vxF2EivycI_1WEjunEIg) |
| vulntarget-e | Older versions of Sunlogin; constrained delegation; antivirus evasion | 小树林开炮手, mortals | [View guide](./vulntarget/target_build/vulntarget-e.html) | [View article](https://mp.weixin.qq.com/s/QWpkYf56oFvNdlumNo6fMA) |
| vulntarget-d | 74CMS; FRP tunneling; antivirus evasion; privilege escalation | mortals, crow | [View guide](./vulntarget/target_build/vulntarget-d.html) | [View article](https://mp.weixin.qq.com/s/gjQnMcBXUbtYc2C2FCfEhQ) |
| vulntarget-c | Laravel; antivirus evasion; privilege escalation | mortals | [View guide](./vulntarget/target_build/vulntarget-c.html) | [View article](https://mp.weixin.qq.com/s/cisoqDnsHqyzCFdx-eG5TQ) |
| vulntarget-b | CMS; domain controller environment; antivirus evasion | mortals | [View guide](./vulntarget/target_build/vulntarget-b.html) | [View article](https://mp.weixin.qq.com/s/S3aiKN_IIhxWRyizAb8zLg) |
| vulntarget-a | Domain controller environment | mortals | [View guide](./vulntarget/target_build/vulntarget-a.html) | [View article](https://mp.weixin.qq.com/s/uxwbnVOxkR8OBkkY9WW6aQ) |

# 4. Lab write-ups

| Lab | Tester(s) | Write-up | Online reference |
| :--- | :--- | :--- | :--- |
| vulntarget-p | crow | [View write-up](./vulntarget/write_up/vulntarget-p-write-up.html) | [View article](https://mp.weixin.qq.com/s/lY4cfXV-I49RUOF9-4YP2g) |
| vulntarget-o | crow | [View write-up](./vulntarget/write_up/vulntarget-o-write-up.html) | [View article](https://mp.weixin.qq.com/s/IjcURvYxbvMvBXHbxCi4aA) |
| vulntarget-n | crow | [View write-up](./vulntarget/write_up/vulntarget-n-write-up.html) | [View article](https://mp.weixin.qq.com/s/k8tXFKLK9Ky0J4_uPfOd3A) |
| vulntarget-m | lemono, crow | [View write-up](./vulntarget/write_up/vulntarget-m-write-up.html) | [View article](https://mp.weixin.qq.com/s/YxZqgd6Hjz3QcYCPAGpAGg) |
| vulntarget-l | Fariy | [View write-up](./vulntarget/write_up/vulntarget-l-write-up.html) | [View article](https://mp.weixin.qq.com/s/3W5GXNjV4uiZBkjMSuCNLQ) |
| vulntarget-k | null, foxcookie, ju2i, cypher | [View write-up](./vulntarget/write_up/vulntarget-k-write-up.html) | [View article](https://mp.weixin.qq.com/s/LHq8O2F-r6rbhVW84Q4KEg) |
| vulntarget-j | cypher, xxp, ju2i, foxcookie | [View write-up](./vulntarget/write_up/vulntarget-j-write-up.html) | [View article](https://mp.weixin.qq.com/s/6_j38gpvTfCVDTcCYizCYA) |
| vulntarget-i | Cypher, ju2i, 小树林开炮手 | [View write-up](./vulntarget/write_up/vulntarget-i-write-up.html) | [View article](https://mp.weixin.qq.com/s/jHeErfr3P4XgfYPG9Ocgng) |
| vulntarget-h | CyPher, XXP, mortals | [View write-up](./vulntarget/write_up/vulntarget-h-write-up.html) | [View article](https://mp.weixin.qq.com/s/TXd_SaJMdVZeMVxNgPg2uw) |
| vulntarget-g | CyPher, XXP, mortals | [View write-up](./vulntarget/write_up/vulntarget-g-write-up.html) | [View article](https://mp.weixin.qq.com/s/BOACc1p6cnIJAj0pzeY2wg) |
| vulntarget-f | mortals, null, 1ncludeSteven, XXP, ju2i | [View write-up](./vulntarget/write_up/vulntarget-f-write-up.html) | [View article](https://mp.weixin.qq.com/s/5SOJ-hzrn9_HyUZrZkOjhA) |
| vulntarget-e | mortals, 小树林开炮手, CyPher, XXP, Macchiato | [View write-up](./vulntarget/write_up/vulntarget-e-write-up.html) | [View article](https://mp.weixin.qq.com/s/eh8SXkgcSQjLkFEjNkkfHw) |
| vulntarget-d | mouse, crow, mortals | [View write-up](./vulntarget/write_up/vulntarget-d-write-up.html) | [View article](https://mp.weixin.qq.com/s/gjQnMcBXUbtYc2C2FCfEhQ) |
| vulntarget-c | mouse, crow, mortals | [View write-up](./vulntarget/write_up/vulntarget-c-write-up.html) | [View article](https://mp.weixin.qq.com/s/cisoqDnsHqyzCFdx-eG5TQ) |
| vulntarget-b | mouse, ZeroP, mortals, CyPher, 4nth0ny | [View write-up](./vulntarget/write_up/vulntarget-b-write-up.html) | [View article](https://mp.weixin.qq.com/s/S3aiKN_IIhxWRyizAb8zLg) |
| vulntarget-a | crow, jiuq, CyPher, mouse, mortals | [View write-up](./vulntarget/write_up/vulntarget-a-write-up.html) | [View article](https://mp.weixin.qq.com/s/uxwbnVOxkR8OBkkY9WW6aQ) |

# 5. Download

## vulntarget-a ~ vulntarget-p

Choose either download source:

- Baidu Netdisk: [Download](https://pan.baidu.com/s/1sv9qdioNF4PTUliix5HEfg) — extraction code: `2dwq`
- Quark Cloud Drive: [Download](https://pan.quark.cn/s/e65bf3efbf0b?pwd=GHgE) — extraction code: `GHgE`

# 6. Contact

If you have comments or suggestions, email `crow_821@163.com`.

WeChat public account: **乌鸦安全 (Crow Security)**

<img src="crowsec.jpg" width="30%" alt="Crow Security WeChat account QR code" />

# Stars

[![Vulntarget star history](https://api.star-history.com/svg?repos=crow821/vulntarget&type=Date)](https://www.star-history.com/?repos=crow821%2Fvulntarget&type=date)

# License

Copyright © 2025 [crow821](https://github.com/crow821)

This project is licensed under the [GNU General Public License v3.0](https://github.com/crow821/vulntarget/blob/master/LICENSE).
