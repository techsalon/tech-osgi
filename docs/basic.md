OSGi的基本概念
=========

#### 概念
**OSGi(Open Services Gateway initiative)**：
- 开放服务网关协议，是由OSGi Allinance制定的Java动态模块化规范。 
- The Dynamic Module System	For	Java：模块化的开发Java应用；模块化的部署Java应用；动态管理模块。

#### 发展轨迹
- 1999年3月，OSGi联盟(非盈利性质)成立，目标是建立家庭网关，并通过互联网向家庭网络提供各种服务；
- 2000年发布OSGi	Service	PlaYorm	V	1.0
- 2001年发布V2.0
- 2003年发布V3.0
- 2005年发布V4.0
- 2007年发布V4.1
- 2009年发布OSGi R4.2版核心规范，从此处开始重心转向**企业级**应用
- 2010年3月发布企业级规范，添加了远程服务、Blueprint以及JNDI、JDBC、JPA等大量与Java	EE相关技术的规范
- 2011年发布OSGi R4.3核心规范
- 2012年7月发布OSGi R5核心规范和企业级规范，包括了基于OSGi技术的模块仓库系统，统一了Equinox	P2、OBR等相关技术
- 2014年7月发布OSGi	R6核心规范，增加注解、数据传输对象等技术

#### 典型应用(里程碑事件)
- BMW汽车的应用控制系统，这套系统主要用来控制汽车上的音箱、灯光等等设备，总共由1000多个Bundle构成，但BMW汽车的应用控制系统启动时间却只需要3.5秒
- Eclispe：Eclipse V3.0开始采用OSGi，同时推出eclipse社区的开源实现**Equinox**
- WebSphere
- Apache：karaf、servicemix、camel
- Siemens、Cisco、NASA、Adobe CS2

#### OSGi实现
- Equinox
- Felix
- Knopflerfish