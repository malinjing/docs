配置接口sFlow
=======================================

DELETE
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
============    =========  ================   ==================
参数名称         是否必选    参数类型及范围       参数含义
============    =========  ================   ==================
Intf
============    =========  ================   ==================


注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接输入接口编号，点击执行即可。

返回结果
+++++++++++++++++++++++++++++++++++++++


GET
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
============    =========  ================   ==================
参数名称         是否必选    参数类型及范围       参数含义
============    =========  ================   ==================
Intf            否
============    =========  ================   ==================


注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接输入接口编号，或直接点击执行。

返回结果
+++++++++++++++++++++++++++++++++++++++

PATCH
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
=======================   =========  ================   ==================
参数名称                   是否必选    参数类型及范围       参数含义
=======================   =========  ================   ==================
Intf
Enabled
IngressSamplingRate
EgressSamplingRate
PollingInterval
HeaderLength
=======================   =========  ================   ==================


注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "Enabled": true,
   "IngressSamplingRate": 2000,
   "EgressSamplingRate": 2000,
   "PollingInterval": 0,
   "HeaderLength": 128
 }

返回结果
+++++++++++++++++++++++++++++++++++++++

POST
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
=======================   =========  ================   ==================
参数名称                   是否必选    参数类型及范围       参数含义
=======================   =========  ================   ==================
Intf
Enabled
IngressSamplingRate
EgressSamplingRate
PollingInterval
HeaderLength
=======================   =========  ================   ==================


注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "Intf": 10,
   "Enabled": true,
   "IngressSamplingRate": 2000,
   "EgressSamplingRate": 2000,
   "PollingInterval": 0,
   "HeaderLength": 128
 }

返回结果
+++++++++++++++++++++++++++++++++++++++


PUT
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
=======================   =========  ================   ==================
参数名称                   是否必选    参数类型及范围       参数含义
=======================   =========  ================   ==================
Intf
Enabled
IngressSamplingRate
EgressSamplingRate
PollingInterval
HeaderLength
=======================   =========  ================   ==================


注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "Intf": 10,
   "Enabled": true,
   "IngressSamplingRate": 2000,
   "EgressSamplingRate": 2000,
   "PollingInterval": 0,
   "HeaderLength": 128
 }

返回结果
+++++++++++++++++++++++++++++++++++++++



