## 产品架构图

网管社区版通过基于 SNMP 协议，对基础架构层的网络设备进行性能、Syslog、Trap 和设备信息的采集。经由后台处理分析后入库并展示给上层用户，供用户进行各场景的使用。
对于某些辅助功能，如配置下发，ping 工具等，则通过 SSH，TELNET 或者 PING 工具对纳管的设备进行数据传输和下发。

![](../assets/image034.png)
