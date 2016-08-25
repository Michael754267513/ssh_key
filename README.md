# ssh_key
ssh批量免key小工具

所有机器的账号密码和ssh端口号都要一致
命令工具 sshkey

安装目录    --  /usr/local/sshkey/
配置文件    --  /etc/config

配置文件说明:
sshkey.conf 

localuser = root			本地需要ssh的用户
remoteuser = devops			远程被管理用户
password = test				远程密码
sshport = 22				ssh端口号

remotehosts 				远程主机列表

10.69.32.104
10.69.32.105


############
配置完毕使用sshkey 自动同步拷贝
