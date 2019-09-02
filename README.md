项目介绍
===
>项目主要是用来学习spring cloud和分布式事务的消息驱动和事件溯源模型。包含config server、eureke server.
主要用到的技术有spring cloud、eureka、mysql、MongoDB、redis、kafka.

## 1.项目架构
* common 公共类，主要包含实体类和util
* configserver config server
* eurekaserver eureka server
* user service user
* distributed try => commit => cancel

### 1.1.common
> 项目定义了公共返回值，数据库mysql和MongoDB实体类等等
### 1.2.configserver
> config server 统一配置中心
### 1.3.user
> user服务。用户服务，主要使用了mybatis。在配置上，Mapper支持xml和JavaBean。<br />
>* JavaBean动态sql，既可以通过**\<script>**标签
>来拼写动态SQL，也可以通过provider来写，主要是使用@SelectProvider、@UpdateProvider等来实现，type为provider类，method为方法。
> ??Provider既可以使用StringBuffer等形式去拼接，也可以使用<strong>SQL</strong>这个类来拼接，
>* logback [logback大致使用教程参考这个blog](https://juejin.im/post/5b128f326fb9a01e8b7814c4#heading-5)

#### 2.个人信息
> * [csdn blog](https://blog.csdn.net/naxieren1992)
> * email **1623631899@qq.com**

