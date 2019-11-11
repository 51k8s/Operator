# Operator

Operator是管理特定应用程序的控制器，通过扩展kubernetes api以软件的方式帮助kubernetes用户创建，配置和管理复杂有状态的应用程序实例。
它建立在基本的Kubernetes资源和控制器概念的基础上，它包含管理特定应用程序的操作以及实现常见任务的自动化。

## The Operator Framework
Operator Framework是一个开源项目，提供开发人员和Kubernetes运行时工具，使我们能够加速operator的开发。
operator Framework包括：
##### Operator SDK
使开发人员能够基于他们的专业知识构建operator，而无需了解Kubernetes API的复杂性。
##### Operator lifecycle manager
监督Kubernetes集群中运行的所有operator（及其相关服务）的安装，更新和管理整个生命周期。
##### Operator Metering
Operator Metering（未来几个月加入）：为提供专业服务的operator启用使用情况报告。
