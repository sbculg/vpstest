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
```
  2) IO<br>
```
wget -qO- git.io/superbench.sh | bash
```


<br>
<br>
秋水逸冰: https://github.com/Puuoi/SS-R-4in1
