配置拥塞管理
=======================================

DELETE
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
==================  =========   =========================   ============================
参数名称             是否必选     参数类型及范围                 参数含义
==================  =========   =========================   ============================
QId                 是
==================  =========   =========================   ============================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接输入QId ，点击执行即可。

返回结果
+++++++++++++++++++++++++++++++++++++++


GET
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
==================  =========   =========================   ============================
参数名称             是否必选     参数类型及范围                 参数含义
==================  =========   =========================   ============================
QId                 是          string，q0～“q7
==================  =========   =========================   ============================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接输入QId，或直接点击执行即可。

返回结果
+++++++++++++++++++++++++++++++++++++++

PATCH
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
==================  =========   =========================   ============================
参数名称             是否必选     参数类型及范围                 参数含义
==================  =========   =========================   ============================
QId                 是          string，q0～“q7
Weight
==================  =========   =========================   ============================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "Weight": 0
 }


返回结果
+++++++++++++++++++++++++++++++++++++++


POST
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
==================  =========   =========================   ============================
参数名称             是否必选     参数类型及范围                 参数含义
==================  =========   =========================   ============================
QueueNumber         否          
Weight
==================  =========   =========================   ============================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "QueueNumber": 0,
   "Weight": 0
 }


返回结果
+++++++++++++++++++++++++++++++++++++++

PUT
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
==================  =========   =========================   ============================
参数名称             是否必选     参数类型及范围                 参数含义
==================  =========   =========================   ============================
QueueNumber                 
Weight
==================  =========   =========================   ============================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "QueueNumber": 0,
   "Weight": 0
 }


返回结果
+++++++++++++++++++++++++++++++++++++++



