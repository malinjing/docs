配置OSPF
=======================================

GET
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
无

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接点击执行即可。

返回结果
+++++++++++++++++++++++++++++++++++++++


POST
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++

======================  =========  =========================== ====================
参数名称                 是否必选    参数类型及范围                参数含义
======================  =========  =========================== ====================
AreaID                  是                                     区域ID
AreaType                否                                     区域类型
IPRange
DefaultLSA
DefaultLSAMetric
Summaries
======================  =========  =========================== ====================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++

调用样例如下::

 {
   "AreaID": "0.0.0.0",
   "AreaType": "normal",
   "Advertise": [
     {
       "IPRange": "1.1.1.0/24"
     }
   ],
   "NotAdvertise": [
     {
       "IPRange": "1.1.1.0/24"
     }
   ],
   "DefaultLSA": false,
   "DefaultLSAMetric": 10,
   "Summaries": false
 }


返回结果
+++++++++++++++++++++++++++++++++++++++


PUT
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++

======================  =========  =========================== ====================
参数名称                 是否必选    参数类型及范围                参数含义
======================  =========  =========================== ====================
AreaID                  是                                     区域ID
AreaType                否                                     区域类型
IPRange
DefaultLSA
DefaultLSAMetric
Summaries
======================  =========  =========================== ====================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "AreaID": "0.0.0.0",
   "AreaType": "normal",
   "Advertise": [
     {
       "IPRange": "1.1.1.0/24"
     }
   ],
   "NotAdvertise": [
     {
       "IPRange": "1.1.1.0/24"
     }
   ],
   "DefaultLSA": false,
   "DefaultLSAMetric": 10,
   "Summaries": false
 }

返回结果
+++++++++++++++++++++++++++++++++++++++