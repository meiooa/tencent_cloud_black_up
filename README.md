forked from fungjcode/python_tools

# Qcloud_Snapshot 腾讯云轻量云快照自动备份脚本
安装环境
pip install -i https://mirrors.tencent.com/pypi/simple/ --upgrade tencentcloud-sdk-python

修改 Qcloud_Snapshot.py 中的参数
![image](https://user-images.githubusercontent.com/40904945/160871969-abeff654-261b-4c79-81c4-5d730825104b.png)

在 /etc/crontab 中添加一行，意思是每三天执行一次 。user 换成你的用户，/p/a/t/h 换成你的脚本地址

0 3 */3 * *  user /usr/bin/python /p/a/t/h/Qcloud_Snapshot.py

# Qcloud_TrafficPackages
腾讯云轻量云流量监控，超标自己关机
