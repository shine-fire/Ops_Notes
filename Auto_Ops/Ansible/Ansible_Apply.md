# Ansible Application Scenarios



1.Windows补丁升级脚本开发（推荐）-定期推送指定的更新包给windows服务器安装。

2.防火墙配置检查-检查Linux与Windows的防火墙配置情况，防止异常开启导致服务异常。

3.指定软件安装情况（推荐）-检查指定软件是否安装。

4.操作系统健康检查脚本（推荐）-合规检查脚本用于上线合规检查，系统上线后定期执行健康检查脚本提前发现问题。

5.文件系统扩容（推荐）-执行扩容脚本，一键扩展文件系统大小，避免误操作导致数据误删。

6.自动化文件系统扩容-收到监控告警后，执行脚本连接Vmware增加虚拟磁盘，然后连接操作系统进行自动扩容。

7.进程管理-记录主机的当前进程命令和启动时间等内容，输出到excel报表用于记录和分析之前的进程状况。

8.安全漏洞扫描（推荐）-扫描主机当前系统安装的rpm包和最新源匹配信息，确认是否存在安全漏洞，并输出到excel报表上。

9.配置YUM源（推荐）-根据主机版本信息，自动生成开发和生产环境的机器的YUM配置。

10.密码管理（推荐）-可定期更换主机用户密码。

11.用户管理（推荐）-用于非特权实现用户增加、删除、创建目录、修改权限等。

12.限制用户提权-限制用户su、sudo、设置ssh执行权限。

13.Windows映射盘检查-检查Windows节点是否存在映射盘。

14.关机维护检查脚本-用于关机维护重启前与重启后检查，避免出现重启过程中异常hung住的情况。

15.Prometheus监控主机的服务发现功能（推荐）-通过vcenter的API和Prometheus服务发现功能，扫描对象版本的Windows和Linux机器并自动添加Prometheus的监控主机中。

16.Prometheus的Linux和Windows的exporter批量安装（推荐）-通过Playbook批量安装Prometheus监控用的Agent端。

17.CMDB管理-收集对象虚拟机和物理机的信息，如IP，版本，磁盘信息，挂载点，用户名，CPU，内存，序列号等信息，写入到CMDB管理系统当中。