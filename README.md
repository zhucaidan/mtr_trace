# mtr_trace
检测VPS回程国内三网路由，用法：

curl -L https://raw.githubusercontent.com/zhucaidan/mtr_trace/main/mtr_trace.sh -o mtr_trace.sh && ./mtr_trace.sh

支持的线路为：电信CN2 GT，电信CN2 GIA，联通169，电信163，联通9929，移动CMI

电信目标IP：

#深圳电信：
./besttrace 58.60.188.222

mtr -c 100 --report 58.60.188.222

#上海电信：
./besttrace 202.96.209.133

mtr -c 100 --report 202.96.209.133

#北京电信：
./besttrace 219.141.136.12

mtr -c 100 --report 219.141.136.12

联通目标IP：

#深圳联通：
./besttrace 210.21.196.6

mtr -c 100 --report 210.21.196.6

#上海联通：
./besttrace 210.22.97.1

mtr -c 100 --report 210.22.97.1

#北京联通：
./besttrace 202.106.50.1

mtr -c 100 --report 202.106.50.1

移动目标IP：

#深圳移动：
./besttrace 120.196.165.24

mtr -c 100 --report 120.196.165.24

#上海移动：
./besttrace 211.136.112.200

mtr -c 100 --report 211.136.112.200

#北京移动：
./besttrace 221.179.155.161

mtr -c 100 --report 221.179.155.161
