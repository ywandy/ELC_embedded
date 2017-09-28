## 需要 
1. Ubuntu虚拟机 
2. 树莓派 
## 内容 
#### Linux常用指令 
1. Linux 文件/文件夹 的打开删除罗列增添  
   ls cd mkdir mv cp touch cat echo 
2. Linux 下常用文本编辑  
    vim nano 
3. Linux 系统资源查看和管理  
    free uptime htop ifconfig ip insmod modprobe systemctl uname  lscpu  
4. Linux Ubuntu 发行版软件包管理器  
    apt apt-get dpkg  
#### 用于嵌入式Linux开发的常用工具 
1. 串口调试工具  
    minicom  
2. 远程连接工具  
    ssh telenet scp  
3. 编译器和交叉编译工具链  
    一般编译器是 gcc g++  
    交叉编译工具链前缀是 arm-linux- 
4. 自动化构建工具  
    make cmake  
5. 源代码版本管理  
    git  
#### 项目演示  
从零开始搭建环境，交叉编译运行一个点亮led程序在树莓派  
