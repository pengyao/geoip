==================================
TAOBAO CNNIC
==================================

* Taobao IP查询接口: http://ip.taobao.com


依据 *cnnic/cnnic_24.txt* 文件，利用Taobao提供的IP接口进行IP归属地查询

* *taobao_cnnic.txt* 为查询结果，格式为"IP(/24)|对应CNNIC原始IP段|查询结果|IP(/24)|区域|省份|市|县|ISP名称|国家ID|区域ID|省ID|市ID|县ID|ISP ID"，以"|"作为分隔符，空或者"-1"标识当前结果未知, "查询结果"列为0表示通过Taobao IP查询接口查询成功，非0表示查询失败. 查询日期为: 2012-10



