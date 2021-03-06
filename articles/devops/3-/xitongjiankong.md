# 系统监控
操作路径：首页->【系统管理】->【系统监控】

在Grid选择框选择集群进行监控。显示的界面如下。

![](/articles/devops/3-/images/image54.png)
  
图 系统监控首页

在此界面可查看所有集群的总览信息，包括负载，内存，网络等状况。

您可以直接通过集群管理界面点击【查看监控】按钮查看对应集群监控信息。

在上方的Grid中选择集群，可查看对应集群的监控信息。选中集群后，继续在后方选择节点，可查看节点的监控详细信息。
 
 ![](/articles/devops/3-/images/image55.png)
 
图 可选择集群和节点

点击上方的时间选择按钮，可快速查看过去对应时间的监控状况。

在监控页面中，任何时刻点击图表，都可以放大该图表查看详细信息。

## 系统预警

iuap运维平台集成Nagios预警系统。进入Nagios点击战略视图（Tactical Overview）后预警界面显示如图：
 
 ![](/articles/devops/3-/images/image56.png)
 
图 系统预警

在该界面可总览当前的主机、服务等监控预警状况。

在页面左侧可选择按主机、按服务、按集群或按服务组查看预警，点击【按主机】后界面如下图所示。
 
 ![](/articles/devops/3-/images/image57.png)
 
图 按主机展示预警状态

在预警页面，绿色代表健康，黄色代表未知，红色代表报警。通过对预警进行相应的配置，可使预警系统在主机或服务达到预警阀值时进行短信或邮件报警等操作。

当前默认的预警阀值具体配置见此附件： 

## 预警配置

在nagiosQL中配置预警参数，见附件图：
 
 ![](/articles/devops/3-/images/image59.png)
 
图 nagiosQL首页

该系统为第三方中间件，可依照nagiosQL官方网站说明进行配置。
