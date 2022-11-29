# divertALLconn
修改divertTCPconn,支持根据源ip过滤，可以用于端口复用

## 使用方法

`.\divertTCPConn_new.exe 80 1080 debug`  
所有80端口进来的转到1080 显示日志  
`.\divertTCPConn_new.exe 80 1080`  
不显示日志  
`.\divertTCPConn_new.exe 80 1080 192.168.30.160 debug`  
只把源ip为192.168.30.160的入站流量转到1080 显示日志  
`.\divertTCPConn_new.exe 80 1080 192.168.30.160`  
