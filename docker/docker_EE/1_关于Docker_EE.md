#企业基础版

使用Docker EE版本，你可以部署Docker企业引擎灵活的管理你的容器工作负载。你可以在Windows、Linux、预置或者云管理工作负载。
Docker EE基础版有企业相关的SLAs协议，提供24个月的维护升级。

#企业标准版和升级版

Docker EE 标准版包括基础般的所有功能，并且扩展增加了私有镜像管理，集成了镜像签名策略，并且支持Kubernetes和Swarm的集群管理。
Docker EE 升级版提供一站式并允许你扩展基于Node的RBAC策略，镜像升级策略，镜像映像，扫描镜像漏洞。

#支持的平台

可安装Docker EE的操作系统。

Platform				x86_64/amd64	IBM Power (ppc64le)	IBM Z (s390x)
CentOS					yes	 	 
Oracle Linux				yes	 	 
Red Hat Enterprise Linux		yes		yes			yes
SUSE Linux Enterprise Server		yes		yes			yes
Ubuntu					yes		yes			yes
Microsoft Windows Server 2016		yes	 	 
Microsoft Windows Server 1709		yes	 	 
Microsoft Windows Server 1803		yes

#Docker认证的基础设施

Docker认证基础设施是Docker允许的部署Docker EE一系列基础设施。每一个Docker允许的基设包含依赖体系、动态模板、第三方解决方案。

Platform			Docker Enterprise Edition
VMware				yes
Amazon Web Services		yes
Microsoft Azure			yes
IBM Cloud			Coming soon

#Docker EE发行周期

每一个企业发行版本提供24个月的维护周期，并且在此期间收集安全和紧急bug修复。
Docker API版本独立于Docker平台版本。我们缓慢的和保守的严格保持API的向后兼容性和过时的APIs和特性。我们会在过时之后三个稳定版本版后移除它们。Docker 1.13增强了通过使用不同版本的API在客户端和服务器端的互通性，包括动态特性交涉。
