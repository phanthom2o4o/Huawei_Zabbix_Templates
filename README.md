# Huawei_Zabbix_Templates
Here are same Zabbix 5 EXTRA Templates for same Huawei devices like 

- Switches Series S57xx and Series S67xx
- Router Series NEx0 

Intstall Procedure :

- For Template to Optical Modules Info and Template Extra Inventory : Just import the template
- For Template Net Huawei VRP SNMPv2 - BGP : First Import the BGP ValueMap, after import the template and put the script "asname" on your 
  Zabbix's external script dir ( usually /usr/lib/zabbix/externalscripts on deb/ubuntu install )
   
