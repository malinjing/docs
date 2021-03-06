配置LACP端口优先级
=======================================

接口描述
---------------------------------------



URL
+++++++++++++++++++++++++++++++++++++++
http://192.168.1.36:8080/public/v1/

.. note::

    192.168.1.36为要配置的设备IP地址。

支持格式
+++++++++++++++++++++++++++++++++++++++
JSON

DELETE
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
==================  =========   =========================   ============================
参数名称             是否必选     参数类型及范围                 参数含义
==================  =========   =========================   ============================
Intf                是
==================  =========   =========================   ============================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接输入接口名称执行即可。

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
Intf                否
==================  =========   =========================   ============================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接点击执行，或者输入指定接口名称执行。

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
Intf                是
Priority            否
==================  =========   =========================   ============================


注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "Priority": 10
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
Intf                是
Priority            否
==================  =========   =========================   ============================


注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "Intf": 10,
   "Priority": 10
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
Intf                是
Priority            否
==================  =========   =========================   ============================


注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "Intf": 10,
   "Priority": 10
 }


返回结果
+++++++++++++++++++++++++++++++++++++++

