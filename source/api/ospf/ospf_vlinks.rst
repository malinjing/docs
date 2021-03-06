配置OSPF虚连接
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

======================  =========  =========================== ====================
参数名称                 是否必选    参数类型及范围                参数含义
======================  =========  =========================== ====================
IP                      否
======================  =========  =========================== ====================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接输入IP地址，或点击执行即可。

返回结果
+++++++++++++++++++++++++++++++++++++++


GET
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++

======================  =========  =========================== ====================
参数名称                 是否必选    参数类型及范围                参数含义
======================  =========  =========================== ====================
IP                      否
======================  =========  =========================== ====================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接输入IP地址，或点击执行即可。

返回结果
+++++++++++++++++++++++++++++++++++++++

PATCH
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++

======================  =========  =========================== ====================
参数名称                 是否必选    参数类型及范围                参数含义
======================  =========  =========================== ====================
IP                      否
AreaID
TransmitArea
HelloInterval
RetransmitInteral
RouterDeadInterval
TransmitDelay
AuthSimplePasswd
KeyID
Password
StartTime
EndTime
MaxTimeDrift
======================  =========  =========================== ====================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "AreaID": "0.0.0.0",
   "TransmitArea": "0.0.0.1",
   "HelloInterval": 40,
   "RetransmitInteral": 40,
   "RouterDeadInterval": 40,
   "TransmitDelay": 40,
   "AuthSimplePasswd": "",
   "AuthMD5s": [
     {
       "KeyID": 10,
       "Password": "",
       "StartTime": "",
       "EndTime": "",
       "MaxTimeDrift": 3600
     }
   ]
 }


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
IP                      否
AreaID
TransmitArea
HelloInterval
RetransmitInteral
RouterDeadInterval
TransmitDelay
AuthSimplePasswd
KeyID
Password
StartTime
EndTime
MaxTimeDrift
======================  =========  =========================== ====================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "AreaID": "0.0.0.0",
   "TransmitArea": "0.0.0.1",
   "HelloInterval": 40,
   "RetransmitInteral": 40,
   "RouterDeadInterval": 40,
   "TransmitDelay": 40,
   "AuthSimplePasswd": "",
   "AuthMD5s": [
     {
       "KeyID": 10,
       "Password": "",
       "StartTime": "",
       "EndTime": "",
       "MaxTimeDrift": 3600
     }
   ]
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
IP                      否
AreaID
TransmitArea
HelloInterval
RetransmitInteral
RouterDeadInterval
TransmitDelay
AuthSimplePasswd
KeyID
Password
StartTime
EndTime
MaxTimeDrift
======================  =========  =========================== ====================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "AreaID": "0.0.0.0",
   "TransmitArea": "0.0.0.1",
   "HelloInterval": 40,
   "RetransmitInteral": 40,
   "RouterDeadInterval": 40,
   "TransmitDelay": 40,
   "AuthSimplePasswd": "",
   "AuthMD5s": [
     {
       "KeyID": 10,
       "Password": "",
       "StartTime": "",
       "EndTime": "",
       "MaxTimeDrift": 3600
     }
   ]
 }


返回结果
+++++++++++++++++++++++++++++++++++++++

