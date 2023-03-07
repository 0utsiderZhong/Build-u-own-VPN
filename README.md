# build-u-own-VPN

<h1>OpenVPN搭建VPS服务器</h1>

**1:FinalShell下载：** <br>
https://www.hostbuf.com/t/988.html<br>
具体版本可根据自己的系统下降即可

**2:OpenVPN搭建：**<br>
 (1)安装wget： <br>
   ①apt update<br>
   ②apt-get install wget<br>
 (2)搭建代码： <br>
   wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh
 
**3:OpenVPN客户端下载链接：**<br>
https://openvpn.net/vpn-client/

**4:OpenVPN和V2ray的区别：**<br>

VPN使用场景:              登陆公司服务器，副业：翻墙<br>
V2Ray使用场景:            翻墙、科学上网<br>

VPN隐私:                  保护个人隐私的能力强<br>
V2Ray隐私:                没什么保护<br>

VPN加密协议:              传统的加密协议：PPTP、L2TP 、OpenVPN、Cisco AnyConnect<br>
V2Ray加密协议:            自行研发的 VMess 协议<br>

VPN服务器配置:            墙外配置VPN服务器<br>
V2Ray服务器配置:          墙内、外都要配置V2Ray 服务器<br>

VPN翻墙能力:              要看VPN服务商的实力<br>
V2Ray翻墙能力:            强、天生就是为了翻墙<br>

VPN翻墙后速度:            理论上会下降、实际要看服务商的实力<br>
V2Ray翻墙后速度:          理论上不会下降、或者下降很少。实际上还是要看服务商的实力<br>

VPN被防火墙发现并干掉:    比较容易｜Cisco AnyConnect是个例外、国内不封<br>
V2Ray被防火墙发现并干掉:  不容易<br>

Resource from: https://www.youtube.com/watch?v=WjHscXTpsl4


<h1>OpenVPN如何避免IP被墙</h1>
**1**<br>
先购买一个便宜的VPS：<br>
https://hostalk.net/deals.html<br>

**2**<br>
然后添加域名DNS解析，跑wss脚本，教程：<br>
https://1024.day/d/1916  <br>

**3**<br>
最后前置IP就可以填写 http://cloudflare.com 或者 CF IP 来翻墙了。<br>
这样也相对来说安全得多。<br>
