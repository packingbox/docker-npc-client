# docker-npc-client
执行命令

docker run -d --name npc -e SERVERIP=127.0.0.1:8284 -e VKEY=123 oldiy/npc-client:latest

or

docker run -d --name npc --net=host -e SERVERIP=127.0.0.1:8284 -e VKEY=123 oldiy/npc-client:latest

nps是一款轻量级、高性能、功能强大的内网穿透代理服务器。目前支持tcp、udp流量转发，可支持任何tcp、udp上层协议（访问内网网站、本地支付接口调试、ssh访问、远程桌面，内网dns解析等等……），此外还支持内网http代理、内网socks5代理，可实现在非内网环境下如同使用vpn一样访问内网资源和设备的效果。
