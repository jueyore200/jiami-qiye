# Racknerd 美国洛杉矶 DC02 VPS 评测报告

Racknerd（简称 RN）是成立于 2019 年的国外 VPS 厂商，主打低价格、大流量的产品，其数据中心分布在美国洛杉矶、圣何塞、达拉斯、芝加哥以及荷兰阿姆斯特丹等地。该厂商的工单回复迅速，服务态度良好，在业内颇受好评，尤其在国内外都有不错的口碑，是低价 VPS 厂商中的推荐之一。

今天要评测的产品是 Labor Day Promo – 3GB KVM，这款 VPS 以性价比著称，可选洛杉矶和圣何塞机房，其中圣何塞会绕道洛杉矶，而洛杉矶则走中国北京 4837 直连出口。配置为 3 核 CPU、3GB 内存、45GB SSD 存储、6500GB 月流量、1Gbps 带宽速率。流量还可免费翻倍，年付价格仅为 24.28 美元，两年付 47.06 美元，性价比十分突出。

---

👉 [【建议收藏】2025年Racknerd最新优惠套餐整理汇总 - 每日更新可用活动优惠](https://bit.ly/Rack_Nerd)

---

## 流量翻倍方法

只需在指定论坛帖子中按照提供的模板回复，即可申请翻倍流量。以下是具体操作步骤：

1. 注册账号并注明注册意图，例如 "Hello, I would like to double the bandwidth"。
2. 验证邮箱，并等待管理员审核通过。
3. 按照模板在帖子内回复申请。

**模板示例：**
plaintext
Hello, I would like to double the bandwidth.
Order Number: #邮件中提供的订单号
Invoice ID:   #邮件中提供的发票编号
Thanks!


## 系统信息

以下是 VPS 的系统信息简报：

plaintext
OS Release: Debian GNU/Linux "Buster" 10.1 (x86_64)
CPU Model: Intel Xeon E5-2690 @ 2.90GHz
CPU Cores: 3 vCPU
Memory: 2.93 GB RAM
Disk Space: 43.35 GB
Network Bandwidth: 1Gbps
Virtualization Type: KVM


## 硬件性能测试

CPU 和内存性能测试结果如下：

plaintext
**CPU性能测试**
1 核心测试分数：822
3 核心测试分数：2453

**内存性能测试**
单线程读取速度：15727 MB/s
单线程写入速度：11631 MB/s


磁盘读写速度表现如下：

plaintext
**磁盘性能**
10MB-4K 块：写入速度 31.9 MB/s，读取速度 36.6 MB/s
100MB-1M 块：写入速度 1.2 GB/s，读取速度 1.2 GB/s


## 网络状况

Speedtest 网络速度测试结果：

plaintext
默认节点：上传速度 62.61 MB/s，下载速度 52.25 MB/s，延迟 44.78 毫秒
中国南京联通：上传速度 8.47 MB/s，下载速度 3.74 MB/s，延迟 168.16 毫秒
中国广州电信：上传速度 0.30 MB/s，下载速度 13.43 MB/s，延迟 158.17 毫秒
香港 CSL：上传速度 9.75 MB/s，下载速度 43.83 MB/s，延迟 153.37 毫秒


## 总结

这款 Racknerd VPS 的性能表现较为稳定，虽然 CPU 性能略低于行业平均水平，但 IO 和内存性能优秀。三网直连的配置对国内用户较为友好，其中联通采用北京出口的 4837。网络速度表现中规中矩，对建站来说完全足够。价格方面，相对于其他同类厂商，这款 VPS 以低价高流量赢得较大优势。

另外，Racknerd 的售后服务值得肯定，问题工单处理效率较高，用户体验良好。整体来看，这款 VPS 是性价比颇高、值得考虑的选择。