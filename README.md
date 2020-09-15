Visit [our official web site](https://www.naver.com) for more information and [Latest updates on Pinpoint](https://www.naver.com)

## Latest Release (2020/09/09)
We're happy to announce the release of Pinpoint v2.1.0. Please check the release note at
(https://github.com/naver/pinpoint/releases/tag/v2.1.0)

The current stable version is [v2.1.0.](https://naver.com)

## Live Demo
Take a quick look at Pinpoint with our [demo!](https://www.naver.com)


## PHP, PYTHON
Pinpoint also supports application written in PHP, Python. [Check-out our agent repository](https://naver.com)

##About Pinpoint
**Pinpoint** is an Apm (Application Performance Management) tool for large-scale distributed systems written in java/[PHP](https://naver.com)/PYTHON.
inspired by [Dapper](https://naver.com), Pinpoint provides a solution to help analyze the overall structure of the system and how components within them are interconnected by tracing transactions across distributed applications.

You should definitely check **PinPoint** out if you want to
+ understand your [application topology](https://naver.com) at a glance
+ monitor your application in  _Real-Time_
-   gain  _code-level visibility_  to every transaction
-   install APM Agents  _without changing a single line of code_
-   have minimal impact on the performance (approximately 3% increase in resource usage)

## Getting Started
+ [Quick-start guide](http://www.naver.com) for simple test run of Pinpoint
+ [Installation guide](https://naver.com) for further instruction
## Overview
Services nowadays often consist of many different components, communicating amongst themselves as well as making API calls to external services. How each and every transaction gets executed is often left as a blackbox. Pinpoint traces transaction flows between these components and provides a clear view to identify problem areas and potential bottlenecks.  
For a more intimate guide, please check out our [Introduction to Pinpoint](https://www.naver.com) video clip

+ **ServerMap**-   Understand the topology of any distributed systems by visualizing how their components are interconnected. Clicking on a node reveals details about the component, such as its current status, and transaction count.
 -   **Realtime Active Thread Chart**  - Monitor active threads inside applications in real-time.
    
+   **Request/Response Scatter Chart**  - Visualize request count and response patterns over time to identify potential problems. Transactions can be selected for additional detail by  **dragging over the chart**.![duck](https://github.com/naver/pinpoint/blob/master/doc/images/ss_server-map.png?raw=true)
+  **CallStack** - Gain code-level visibility to every transaction in a distributed environment, identifying bottlenecks and points of failure in a single view.

![duck](https://github.com/naver/pinpoint/blob/master/doc/images/ss_call-stack.png?raw=true)

+ **Inspector** - View additional details on the application such as CPU usage, Memory/Garbage Collection, TPS, and JVM arguments.
![duck](https://github.com/naver/pinpoint/blob/master/doc/images/ss_inspector.png?raw=true)

## Supported Modules
+ JDK 6+
+ [Tomcat 6/7/8/9](https://github.com/naver/pinpoint/tree/master/plugins/tomcat),  [Jetty 8/9](https://github.com/naver/pinpoint/tree/master/plugins/jetty),  [JBoss EAP 6/7](https://github.com/naver/pinpoint/tree/master/plugins/jboss),  [Resin 4](https://github.com/naver/pinpoint/tree/master/plugins/resin),  [Websphere 6/7/8](https://github.com/naver/pinpoint/tree/master/plugins/websphere),  [Vertx 3.3/3.4/3.5](https://github.com/naver/pinpoint/tree/master/plugins/vertx),  [Weblogic 10/11g/12c](https://github.com/naver/pinpoint/tree/master/plugins/weblogic),  [Undertow](https://github.com/naver/pinpoint/tree/master/plugins/undertow)
-   Spring, Spring Boot (Embedded Tomcat, Jetty, Undertow), Spring asynchronous communication
-   Apache HTTP Client 3.x/4.x, JDK HttpConnector, GoogleHttpClient, OkHttpClient, NingAsyncHttpClient, Akka-http, Apache CXF
-   Thrift Client, Thrift Service, DUBBO PROVIDER, DUBBO CONSUMER, GRPC
-   ActiveMQ, RabbitMQ, Kafka
-   MySQL, Oracle, MSSQL(jtds), CUBRID, POSTGRESQL, MARIA
-   Arcus, Memcached, Redis([Jedis](https://github.com/naver/pinpoint/blob/master/plugins/redis),  [Lettuce](https://github.com/naver/pinpoint/tree/master/plugins/redis-lettuce)), CASSANDRA, MongoDB, Hbase, Elasticsearch
-   iBATIS, MyBatis
-   DBCP, DBCP2, HIKARICP, DRUID
-   gson, Jackson, Json Lib, Fastjson
-   log4j, Logback, log4j2
## Compatibility
Java version required to run Pinpoint:
Pinpoint Version | Agent | Collector | Web|
-------------------  | ------- | ----------- | -----|
1.5.x | 6-8 | 7-8| 7-8|
1.6.x | 6-8 | 7-8 | 7-8|
1.7.x | 6-8 | 8 | 8|
1.80 | 6-10 | 8 | 8|
1.8.1+| 6-10| 8 | 8|
2.0.x | 6-13 | 8| 8|
2.1.x | 6-14 | 8 | 8|

## Community
[Github issues](https://www.naver.com)
[Google group](https://www.naver.com)
[Gitter](https://naver.com)

## License
Pinpoint is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/naver/pinpoint/blob/master/LICENSE) for full license text.

```
Copyright 2018 NAVER Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
