>本工程师学用来学习unity的完整工程demo-ufps，并对项目做分拆研究
>涉及的插件包括


# 任务流程

1. 搭建环境unity2017+rider2017
2. 研究下KBengin
>KB是开源的c++ Python，支持热更新，客户端只有一个mmorpg
3. 研究photon server与pun(Photon Unity Networking）的区别
>photon server：是本地部署版本,选择ON-PREMISE,目前Unity3d  client版本v4.1.1.15,server版本v4.0.29.11263.exe，按部署机器个数收费。单台机器一个月最高1100元

>pun：是photon的云服务,服务器部署在photon的云端，按流量收费。

> photon Unity Networking： 是对Photon Unity Client做了一层封装，使其用起来更像UnityNetworking,十分方便，就用它了。


4. 研究unity的mvvm架构，以及事件驱动

5. 项目管理十分 有益的插件

> 1 uFrame:MVVM插件
> 2 PoolManager插件：对象池管理插件
> 3 MadLevelManager:关卡管理
> 

## ufps任务拆分

1. 2个小时通读ufps文档
2. 2个小时通过add-one 与mufps的文档
3. ufps的GameManager系统，PoolManager系统.，预计4个小时 
4. ufps第一人称改为第三人称，控制器使用add one,包括背部镜头以及持枪镜头。预计16个小时
5. upfs的枪械系统，研究修改枪械，子弹生成，子弹伤害，以及货品获取。预计8个小时
6. upfs的phton端同步机制。