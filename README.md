# JDataFlow Platfrom

JDP is an enterprise ***Core Data & Core AI*** stream analysis platfrom, the full name of JDP is `JDataFlow Platfrom`，Analyze flow data . JDP is not a framework, but a complete solution, mainly includes：

- Basic concept: `JDP` based on Streaming Analytics Visualization architecture
- Development tools: `Ambari`, based on the Ambari source extension, JDP is better integrated with Ambari.
- The basic structure: `JDP` core is based on high-performance distributed relational database construction, supporting triceratops of data-second responsiveness.
- Core features: `JDP` Core Data & Core AI:
    + Core Data provides highly visual stream data analysis.
    + Core AI provides AI capabilities on distributed systems.

- Basic operation and maintenance: out of the box, visual operation and maintenance management system `Ambari Manager`:
    + Provide core service management and configuration center functions to ensure the stability and reliability of the cluster.
    + Manage large-scale distributed systems simply and efficiently, just need to pay attention on business applications.

![JDataFlow](http://www.fusionlab.cn/zh-cn/docs/intro/img/JDataFlow-Pratfrom.png)

## Design Principles

- Internet of Things(IoT), connects everything’s  era.Data is processed in the flow
- JDP flow analysis platform, simple and high performance data analysis, Core Data follows the principle of distributed system design
- Follow the existing service system of company.  seamlessly blend into existing enterprise data center systems that could directly interact with data.

## 特性

- One-stop solution: Out of the box & simple & easy to use.
- High performance: teraflops of data-second response, providing PB-level data storage.
- Scalability :  Large-scale deployment, up to several hundred clusters.
- Visualization: Visual data collection, data storage, data analysis, data reporting.
- Reliability: The cluster provides a copy-tolerant mechanism, so hardware failures do not cause data loss.
- Simple operation and maintenance: log, monitoring, alarm, configuration, and service stack management.
- Easy to use: Provides standard SQL, drag and drop data analysis.

## JDP Development plan for 3.0.0.0 

* R & D Plan

![](https://github.com/fusionlabcn/jdp/raw/master/img/jdp-3-0-0-0-develop-plan.png)

* Test Plan

![](https://github.com/fusionlabcn/jdp/raw/master/img/jdp-3-0-0-0-testing.png)

* Project List

| Name | explain | address |  status | remark | 
| :--- | :----: | :----: | :----: | :----: |
| jdp-package | JDP Ecosystem Package Management Tools | [Github](https://github.com/fuslab/jdp-package) | ok |  :seedling: |
| jdp | JDP for roadmap | [Github](https://github.com/fuslab/jdp) | ok |  :seedling: |
| jdp-select | JDP Ecosystem Package Core Tools | [Github](https://github.com/fuslab/jdp-select) | ok |  :seedling: |
| jdp-ambari-mpack | JDP Ecosystem Management Platform | [Github](https://github.com/fuslab/jdp-ambari-mpack) | ok |  :seedling: |
| Ambari | JDP Stack in Ambari | [Github](https://github.com/fuslab/ambari) | ok |  :seedling: |

## JDP Development plan for 3.1.0.0 

* R & D Plan

![](https://github.com/fusionlabcn/jdp/raw/master/img/jdp-3-1-0-0-develop-plan.png)

* Test Plan

![](https://github.com/fusionlabcn/jdp/raw/master/img/jdp-3-1-0-0-testing.png)

* Project List

| Name | explain | address |  status | remark | 
| :--- | :----: | :----: | :----: | :----: |
| jdp-package | JDP Ecosystem Package Management Tools | [Github](https://github.com/fuslab/jdp-package) | ok |  :seedling: |
| jdp-select | JDP Ecosystem Package Core Tools | [Github](https://github.com/fuslab/jdp-select) | ok |  :seedling: |
| Ambari | JDP Stack in Ambari | [Github](https://github.com/fuslab/ambari) | ok |  :seedling: |

Note: The jdp-ambari-mpack and jdp-ambari projects will be merged in `3.1.0.0`, and only one project will exist in the future.

## JDP Development plan for 3.1.1.0 

### R & D Plan

* Add Hadoop 3.1.1
* Add Spark 2.4.0
* Add Hbase 2.0.2
* Add Livy 0.5.0
* Add Flink 1.7.0

### Test Plan

* Add Hadoop 3.1.1 (done)
* Add Spark 2.4.0  (done)
* Add Hbase 2.0.2 (done)
* Add Livy 0.5.0 (done)
* Add Flink 1.7.0 (Not tested)

### Project List

| Name | explain | address |  status | remark | 
| :--- | :----: | :----: | :----: | :----: |
| jdp-package | JDP Ecosystem Package Management Tools | [Github](https://github.com/fuslab/jdp-package) | release |  :seedling: |
| jdp-select | JDP Ecosystem Package Core Tools | [Github](https://github.com/fuslab/jdp-select) | release |  :seedling: |
| Ambari | JDP Stack in Ambari | [Github](https://github.com/fuslab/ambari) | release |  :seedling: |
| FusionDB | JDP Core FusionDB | [Github](https://github.com/FusionDB/fusiondb) | incubator |  :seedling: |

Note: JDP 3.1.1.0 version, incubator core components ` FusionDB ` and ` CoreAI `，details access [fusionlab](http://www.fusionlab.cn)

## JDP Development plan for 3.2.0.0 

### R & D Plan

* Add FusionDB 0.1.0
* Add CoreAI 0.1.0

### Test Plan

* Add FusionDB 0.1.0
* Add CoreAI 0.1.0

### Project List

| Name | explain | address |  status | remark | 
| :--- | :----: | :----: | :----: | :----: |
| jdp-package | JDP Ecosystem Package Management Tools | [Github](https://github.com/fuslab/jdp-package) | release |  :seedling: |
| jdp-select | JDP Ecosystem Package Core Tools | [Github](https://github.com/fuslab/jdp-select) | release |  :seedling: |
| Ambari | JDP Stack in Ambari | [Github](https://github.com/fuslab/ambari) | release |  :seedling: |
| FusionDB | JDP Core FusionDB | [Github](https://github.com/FusionDB/fusiondb) | incubator |  :seedling: |

Note: JDP 3.2.0.0 version, release core components ` FusionDB ` and ` CoreAI `，details access [fusionlab](http://www.fusionlab.cn)

## Reporting issues

We use [GitHub Issues](https://github.com/fuslab/jdp/issues) to track community reported issues. You can also contact the community for getting answers.

## Development

项目列表，涉及的相关项目版本，全都统一为`branch-3.1.0.0`，jdp-package除外，拥有相关prefix，suffix需保持一致。
比如：jdp-3.1.0.0需具备版本一致性。

需要开启统称为`branch-3.1.0.0`分支以此为基础进行开发。最终release版本之前，可通`branch-3.1.0.0`分支发布带rc后缀的版本，比如rc1,rc2等。

新特性开发，可开启带develop关键字的分支，每个roadmap特性都会以pr的形式提到`branch-3.1.0.0`中，最终版本合并到master，并且打进行tag发布。

- {project_name}-number(unique)-feature-{describe}

bugfix开发，相关问题修复，需开启带有bugfix-{describe}关键字的分支，测试通过以pr的形式提给`branch-3.1.0.0`。

- {project_name}-number(unique)-bugfix-{describe}

commit信息，开发新特性和问题修复，严格以全英文方式提交信息，尽量让每一个pr都能清楚描述解决的问题或新特性。

文档编写

> 1. 新特性的开发，需在文档项目中，编写详细的设计文档，设计文档评审通过，开始实现功能。
> 2. 每个新特性开发合并`branch-3.1.0.0`，需要编写相关使用文档，每次提交CI持续集成会自动部署为一个静态网站，只需专注编写文档。整个文档严格遵守markdown语法规范，文档内容描述需通俗易懂，易于理解。

。。。。
