## 安装pip软件包
```
https://raw.github.com/pypa/pip/master/contrib/get-pip.py
https://bootstrap.pypa.io/get-pip.py

下载并安装
# wget [url]
# python get-pip.py

确定pip的安装路径
# find / -name pip
/usr/local/python27/bin/pip	# 默认被安装了python27的路径下.
/usr/local/python27/lib/python2.7/site-packages/pip
/root/.cache/pip

添加pip环境变量
# echo "PATH=/usr/local/python27/bin/:\$PATH" > /etc/profile.d/pip.sh
# source /etc/profile

查看pip当前版本
# pip -V
pip 8.1.2 from /usr/local/python27/lib/python2.7/site-packages (python 2.7)