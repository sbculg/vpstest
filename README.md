# vpstest
vps新环境测试脚本
<br>



1、路由回程测试：<br>
```
wget https://raw.githubusercontent.com/sbculg/vpstest/master/testrace.sh <br>
bash testrace.sh
```

<br>

2、生成测试文件<br>
```
dd if=/dev/zero of=500M.test bs=1M count=500
```

<br>

3、简易下载脚本<br>
```
wget https://raw.githubusercontent.com/sbculg/vpstest/master/pythonhttp.sh
```

<br>

4、VPS测试脚本<br>
  1) CPU<br>
```
wget -O- https://raw.githubusercontent.com/sbculg/vpstest/master/LemonBenchIntl.sh | bash
curl -fsL https://ilemonra.in/LemonBenchIntl | bash -s fast

```


  2) IO<br>
```
wget -qO- git.io/superbench.sh | bash
```

<br>

5、 bbr/bbrplus/bbr2/锐速
不卸载内核
```
wget -N --no-check-certificate "https://github.000060000.xyz/tcpx.sh" && chmod +x tcpx.sh && ./tcpx.sh
```
或
```
wget -N "https://github.000060000.xyz/tcpx.sh" && chmod +x tcpx.sh && ./tcpx.sh
```
卸载内核
```
wget -N --no-check-certificate "https://github.000060000.xyz/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
```
或
```
wget -N "https://github.000060000.xyz/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
```
<br>

6、 宝塔面板删除强制验证
```
rm -f /www/server/panel/data/bind.pl
```
<br>

7、NF、Ytb流媒体检测
```
bash <(curl -sSL "https://github.com/CoiaPrant/MediaUnlock_Test/raw/main/check.sh")
```
<br>
<br>
秋水逸冰: https://github.com/Puuoi/SS-R-4in1
