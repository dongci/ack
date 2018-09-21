ack-tools

ack其实就是ubuntu中的egrep工具，但centos在没有这个安装包。

# 下载安装
cd /tmp
git clone https://github.com/dongci/ack.git
cd ack && tar xzf ack.tar.gz -C /usr/bin/

# 测试一下
cd /var/log
ack 'error'     
