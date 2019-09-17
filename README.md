# 简单创建一个自己的vps服务

## 选择购买一个vps服务器
- 我这里选择了[vultr](https://www.vultr.com/)，你也可以用我的[邀请链接](https://www.vultr.com/?ref=7615364)。
***

## 选择服务器类型
- ![avatar](/img/a.png)
- ![avatar](/img/b.png)
- ![avatar](/img/c.png)
- 我这里选择的是澳大利亚服务器，Ubuntu系统，价格根据你的情况选择，选择后点击'Deploy Now'创建。
***

## 准备工作
- ![avatar](/img/d.png)
- 等待一分钟左右，服务器会创建完成，然后先测试生成的IP是否可用（我用的是19的系统）。
- 复制IP，windows系统 Win+R 打开运行，输入cmd打开命令行 输入ping '你的IP'
- ![avatar](/img/e.png)
- 这个是可用的状态，如果显示请求超时，就是IP被封了，这时先不要销毁当前服务器，直接创建三至五个(这样可以避免IP重复，vultr是按小时收费，所以创建一个新的服务器花费很少)，或者换一个地区，然后再测试IP是否被封。
***

## 安装shadowsocks
- 打开Xshell，链接你的服务器
- ![avatar](/img/g.png)
- 依次输入apt-get update和apt-get install shadowsocks，安装shadowsocks
- ![avatar](/img/h.png)
- 输入ssserver，查看所有设置选项
- ![avatar](/img/i.png)
- 输入 ssserver -p 3000 -k 123456 -d start
- ![avatar](/img/j.png)
- 现在，你已经成功创建一个vps了。当前vps的IP:139.180.164.98 端口(port):3000 密码:123456。
***

## 下载shadowsocks
- [shadowsocks github地址](https://github.com/shadowsocks/shadowsocks-windows/releases)
- [windows版](https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.1.6/Shadowsocks-4.1.6.zip)
- ![avatar](/img/k.png)
- 下载后解压，双击打开填写服务器地址，端口，密码，然后确定。
- 右键点击shadowsocks图标，选择系统代理，PAC模式可以跳过国内不需要代理的IP，帮你节省流量。现在你可以观看油管和google了。
- 手机版及其他版本，可以翻墙打开[flyzy](https://www.flyzy2005.com/fan-qiang/shadowsocks/ss-clients-download/)的博客进行选择下载。
***

## 最后
- 不用的vps一定要销毁，不要暂停，这样也会收费。
- 你也可以用我的[邀请链接](https://www.vultr.com/?ref=7615364)，以便我能获得一些奖励。
