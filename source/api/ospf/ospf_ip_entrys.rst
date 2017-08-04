配置OSPF IP Entrys
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

======================  ===========  ===========================  ====================
参数名称                是否必选     参数类型及范围                 参数含义
======================  ===========  ===========================  ====================
Vif
AreaID
IP
LinkType
Enabled
HelloInterval
Metric
PassiveLoopback
PassiveHost
Priority
RetransmitInteral
RouterDeadInterval
TransmitDelay
Neighbours IP
Neighbours RouterID
AuthSimplePasswd         否
AuthMD5s KeyID
Password
StartTime 
EndTime
MaxTimeDrift
SubVifs Vif
IP 
Metric
======================  ===========  ===========================  ====================




注意事项
+++++++++++++++++++++++++++++++++++++++


调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "Vif": "vlan10",
   "AreaID": "0.0.0.0",
   "IP": "10.10.10.1",
   "LinkType": "broadcast",
   "Enabled": true,
   "HelloInterval": 40,
   "Metric": 15,
   "PassiveLoopback": false,
   "PassiveHost": false,
   "Priority": 10,
   "RetransmitInteral": 40,
   "RouterDeadInterval": 40,
   "TransmitDelay": 40,
   "Neighbours": [
     {
       "IP": "1.1.1.1",
       "RouterID": "192.168.1.1"
     }
   ],
   "AuthSimplePasswd": "",
   "AuthMD5s": [
     {
       "KeyID": 10,
       "Password": "",
       "StartTime": "",
       "EndTime": "",
       "MaxTimeDrift": 3600
     }
   ],
   "SubVifs": [
     {
       "Vif": "vlan10.1",
       "IP": "20.20.20.1",
       "Metric": 1
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
参数名称                是否必选   参数类型及范围                参数含义
======================  =========  =========================== ====================
Vif
AreaID
IP
LinkType
Enabled
HelloInterval
Metric
PassiveLoopback
PassiveHost
Priority
RetransmitInteral
RouterDeadInterval
TransmitDelay
Neighbours IP
Neighbours RouterID
AuthSimplePasswd         
AuthMD5s KeyID
Password
StartTime 
EndTime
MaxTimeDrift
SubVifs Vif
IP 
Metric
======================  ========= =========================== ====================


注意事项
+++++++++++++++++++++++++++++++++++++++


调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "Vif": "vlan10",
   "AreaID": "0.0.0.0",
   "IP": "10.10.10.1",
   "LinkType": "broadcast",
   "Enabled": true,
   "HelloInterval": 40,
   "Metric": 15,
   "PassiveLoopback": false,
   "PassiveHost": false,
   "Priority": 10,
   "RetransmitInteral": 40,
   "RouterDeadInterval": 40,
   "TransmitDelay": 40,
   "Neighbours": [
     {
       "IP": "1.1.1.1",
       "RouterID": "192.168.1.1"
     }
   ],
   "AuthSimplePasswd": "",
   "AuthMD5s": [
     {
       "KeyID": 10,
       "Password": "",
       "StartTime": "",
       "EndTime": "",
       "MaxTimeDrift": 3600
     }
   ],
   "SubVifs": [
     {
       "Vif": "vlan10.1",
       "IP": "20.20.20.1",
       "Metric": 1
     }
   ]
 }

返回结果
+++++++++++++++++++++++++++++++++++++++