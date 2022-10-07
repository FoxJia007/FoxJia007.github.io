再配置activemq的jdbc链接mysql持久化的过程中出现的bug

​	第一个是再大多数情况下出现的问题，即url中没有显示的表示useSSL=false

​	另一个是再配置root的远程权限的过程中，密码为新设置的密码，和原来的root密码不相同

​	且再user表中的密码栏的名字由password再 mysql5.7 版本就已经改为另一个名字authentication_string



配置zookeeper过程中遇到的几个bug



zkServer集群启动的过程中，一直处于standalong状态，可能是由于僵尸进程的缘故，查看2181端口是否被之前的zk占用而无法清除，采用重启可以解决问题



分发使用xsync脚本的时候出现的JAVA_Home找不到的问题

​	  解决办法去/bin目录下找到zkEnv.sh中加上JAVA_HOME的显示说明

免密登录

​	（使用ssh的密钥和指令配合使用）