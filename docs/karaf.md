Karaf简介
=========
#### 简介
**Karaf**是Apache旗下的一个开源项目。它是一个基于**OSGi的运行环境**，Karaf提供了一个**轻量级的OSGi容器**，可以用于部署各种组件、应用程序。
Karaf提供了很多特性用于帮助开发者和用户更加灵活的部署应用：
- 热部署
- 动态配置
- 几种日志处理系统
- 本地系统集成
- 可编程扩展控制台
- ssh远程访问
- 内置安装认证机制等等。

同时Karaf作为一款成熟而且优秀的OSGi运行环境以及容器已经被诸多Apache项目作为基础容器：
- Apache Geronimo
- Apache ServiceMix
- Fuse ESB

Karaf在**性能、功能和稳定性**上都是个不错的选择。

#### 使用
##### karaf前台启动

    windows：bin\karaf.bat
    linux：bin/karaf

##### karaf后台启动

    windows：bin\start.bat
    linux：bin/start.sh

##### bundle相关命令

    bundle:list                       列明安装的bundle及状态，无参数
    bundle:install                  安装bundle。示例   bundle:install file:/opt/test.jar 
    bundle:start                    启动bundle，参数为bundle id
    bundle:stop                    停止bundle，参数为bundle id

##### feature相关命令

    feature:list                       显示可用feature列表及状态
    feature:repo-list             显示可用的仓库列表，一个仓库可能包含多个feature
    feature:repo-add           增加feature仓库。示例    feature:repo-add mvn:org.apache.cxf.karaf/apache-cxf/2.7.7/xml/features
    feature:repo-remove    移除指定feature仓库，参数为仓库id
    feature:install                  安装指定的feature，参数为feature名称
    feature:uninstall              卸载指定feature ，参数为feature名称   
    feature:info                      查看指定feature信息 ，参数为feature名称   


##### web相关命令，安装war feature后有此相关命令

    web:list                              显示web应用列表及其状态
    web:start                           启动相应的web应用
    web:stop                           停止相应的web应用

##### http相关命令   

    http:list                             显示servlets的详细信息