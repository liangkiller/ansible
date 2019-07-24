site: 综合common.yml,node_ini.yml,install_mysql.yml,mysql_rep.yml,mysql_cdhuser.yml,install_cdh.yml
parted.yml: 分区硬盘,读取参数all.yml
mkfs.yml: 格式化分区,读取参数all.yml
common.yml: 设置hosts,iptables,epel镜像,yum开发环境及必要工具;读取参数all.yml
node_ini.yml: 初始化CDH节点,安装java,ntp,优化系统,,ssh 互联;读取参数cdh.yum和all.yml
install_mysql.yml: 安装mysql;读取参数mysql.yum和all.yml
mysql_rep.yml: mysql主从设置;读取参数mysql.yum和all.yml
mysql_cdhuser.yml: 创建mysql的cdh用户;读取参数mysql.yum和all.yml
install_cdh.yml: 安装cdh的主从,读取参数cdh.yum和all.yml
manager_mysql.yml: mysql服务的启动,停止,重启
manager_cdh.yml: cdh服务的启动,停止,重启
remove.yml: 删除mysql,chd
test.yml: 测试用