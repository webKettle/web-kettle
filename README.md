软件说明

### ** [点击跳转使用手册->演示版本](http://49.232.185.81:8080/web-etl-docs) **
> 任务管理
![任务管理](https://raw.githubusercontent.com/webKettle/web-kettle/main/%E6%88%AA%E5%9B%BE/%E8%AE%BE%E8%AE%A1%E5%99%A8-%E4%BB%BB%E5%8A%A1%E7%AE%A1%E7%90%86.png)
> 设计器
![任务管理](https://raw.githubusercontent.com/webKettle/web-kettle/main/%E6%88%AA%E5%9B%BE/%E8%AE%BE%E8%AE%A1%E5%99%A8%E6%96%B0%E5%8A%9F%E8%83%BD.jpg)
![任务管理](https://raw.githubusercontent.com/webKettle/web-kettle/main/%E6%88%AA%E5%9B%BE/%E8%AE%BE%E8%AE%A1%E5%99%A8-%E8%BD%AC%E6%8D%A2.png)

![任务管理](https://raw.githubusercontent.com/webKettle/web-kettle/main/%E6%88%AA%E5%9B%BE/%E8%AE%BE%E8%AE%A1%E5%99%A8-%E8%BD%AC%E6%8D%A2-%E7%BB%84%E4%BB%B6%E5%8F%B3%E9%94%AE%E5%8A%9F%E8%83%BD.png)
![任务管理](https://raw.githubusercontent.com/webKettle/web-kettle/main/%E6%88%AA%E5%9B%BE/job%E6%88%AA%E5%9B%BE.png)

1. 本系统基于kettle 9 引擎改造为web-kettle 目前的最新版本在之前的基础上基于客户的需求做了很多功能优化，生产环境比较稳定。

2. 目前已经做了输入、输出、转换、应用、流程、脚本、查询等150多个转换组件以及工作50多个组件，可按需根据业务定制组件

3. 本系统功能集成调度平台 和 web-kettle流程设计器直接在浏览器中拖拉拽节点配置属性，然后通过调度模块实现完美调度，支持分布式、集群、前置机部署 ；

4. 由于资源库形式维护起来方便，但是执行效率极其低下，尤其多人操作ETL任务的时候会锁库，脚本模式完美规避这个问题，而且解决了数据库每个脚本单独配置，采用目录形式管理多人协作很方便。时长较长任务支持后台执行，刷新的时候会重现当前任务状态，无需客户端一直等待。

5. 深入研究过kettle 源码，优化部分bug。但是无法做出客户端全部交互效果，不过基本上很接近，简单易用代码简洁，很容易进行二次开发扩展。

6. 技术框架 spring boot 、mybatis 、vue、element-ui

7. 本项目到现在已经是接近3年，生产环境也部署过上百个节点，再配合自带的调度平台，开源作为完整的一套ETL解决方案，或者集成到自己的业务系统中。

## 如果有合作需要，请联系邮箱：598762549@qq.com
使用说明
** 使用方式和客户端kettle相似 ，只是阉割了部分cs端的一些操作 **
