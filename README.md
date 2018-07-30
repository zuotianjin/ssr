1.购买VPS服务器
VPS服务器需要选择国外的，首选国际知名的vultr，速度不错、稳定且性价比高。
vultr注册地址：https://www.vultr.com
注册并邮件激活账号，充值后即可购买服务器。充值方式是PayPal或支付宝

2.部署VPS服务器
Windows用户请看：
购买服务器后，需要部署一下。因为你买的是虚拟东西，而且又远在国外，我们需要一个叫 Git Bash 的软件来远程部署。
官方免费下载地址：https://git-scm.com/download
打开 git bash 软件，粘贴代码
ssh root@你的服务器ip地址
成功登陆服务器

3.安装ssr软件
粘贴代码
wget -N --no-check-certificate https://softs.fun/Bash/ssr.sh && chmod +x ssr.sh && bash ssr.sh
4.安装bbr加速
粘贴代码

wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh
  chmod +x bbr.sh
  ./bbr.sh
5.本地安装 ssr服务器
Windows SSR客户端 点击下载地址 https://github.com/shadowsocksr-backup/shadowsocksr-csharp/releases
MacOS SSR客户端 点击下载地址 https://github.com/shadowsocksr-backup/ShadowsocksX-NG/releases
Linux SSR客户端点击下载地址 https://github.com/erguotou520/electron-ssr/releases
安卓 SSR客户端 点击下载地址 https://github.com/shadowsocksr-backup/shadowsocksr-android/releases/download/3.4.0.8/shadowsocksr-release.apk
