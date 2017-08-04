配置LLDP指定类型的TLV
=======================================

GET
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
无。

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
直接点击执行即可。

返回结果
+++++++++++++++++++++++++++++++++++++++


PATCH
---------------------------------------

请求结构
+++++++++++++++++++++++++++++++++++++++


请求参数
+++++++++++++++++++++++++++++++++++++++
======================  =========  =========================== ==================================
参数名称                 是否必选    参数类型及范围                参数含义
======================  =========  =========================== ==================================
PortVlan                否         false、true                 Port VLAN TLV。
SystemName              否         false、true                 System Name TLV
ManagementAddress       否         false、true                 Management Address TLV
MacPhyCfg               否         false、true                 MAC/PHY Configuration/Status TLV
PortDescription         否         false、true                 Port Description TLV
SystemCapability        否         false、true                 System Capabilities TLV
SystemDescription       否         false、true                 System Description TLV
======================  =========  =========================== ==================================

注意事项
+++++++++++++++++++++++++++++++++++++++
无。

调用样例
+++++++++++++++++++++++++++++++++++++++
调用样例如下::

 {
   "PortVlan": true,
   "SystemName": true,
   "ManagementAddress": true,
   "MacPhyCfg": true,
   "PortDescription": true,
   "SystemCapability": true,
   "SystemDescription": true
 }


返回结果
+++++++++++++++++++++++++++++++++++++++