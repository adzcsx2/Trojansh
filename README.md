# Trojansh
Trojan分解自动安装脚本

==========================================================

支持：centos7+/debian9+/ubuntu16.04+

网站：www.v2rayssr.com （已开启禁止国内访问）

YouTube频道：波仔分享

==========================================================

本Trojan安装代码 www.v2rayssr.com 首发

为了适合新手小伙伴，本代码分解三部分：

新机器需要:
`sudo apt update`
`sudo apt upgrade`

`apt install socat `

BBRplus加速(需要运行2次，一次下载后重启，下载过程中，选项全部选右边的。重启后再次运行选中协议)

`wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh`

step1:

`wget -N --no-check-certificate "https://raw.githubusercontent.com/adzcsx2/Trojansh/master/trojan1.sh" && chmod +x trojan1.sh && ./trojan1.sh`

step2:
设置默认证书
`acme.sh --set-default-ca --server letsencrypt`

`wget -N --no-check-certificate "https://raw.githubusercontent.com/adzcsx2/Trojansh/master/trojan2.sh" && chmod +x trojan2.sh && ./trojan2.sh`

step3:

`wget -N --no-check-certificate "https://raw.githubusercontent.com/adzcsx2/Trojansh/master/trojan3.sh" && chmod +x trojan3.sh && ./trojan3.sh`
