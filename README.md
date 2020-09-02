# dbm_lite
This project meant to provide useful scripts for DB maintance and management, to make work easier and interesting...
Till now, it includes only scripts for Oracle, which I used for years,share it with you, and will continue to add more...or even MySQL
Most of scripts are tested in Linux and part of Unix(Solaris,AIX,HP-UX),but not completely tested,sorry not tested in Windows yet.

##How to Start
1.you need to have a DBA account
2.use script settdb.sh for DB login details registry
3.run scripts whatever you want if there are
##如何使用脚本
1.上传脚本至服务器端，并授权可执行权限(chmod u+x *.sh)。13
2.使用dba账户密码运行settdb.sh,脚本会设置当前shell会话的若干个变量以便记住账号密码和连接的目标库。
3.settdb.sh提示运行成功后就可以直接运行其他脚本进程维护操作
