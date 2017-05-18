# Docker
## Docker Component
Docker mainly consists of the following:
* Docker Client
* Docker Daemon
* Docker Images
* Docker Registry
* Docker Container

### Docker Client
Docker提供给客户的用户端. Docker Client提供给用户一个终端, 用户输入Docker提供的命令来管理本地或者远程的服务器

### Docker Daemon
Docker服务的守护进程. 每台服务器(物理机或虚拟机)上只要安装的Docker的环境,基本上就跑了一个后台程序Docker Daemon, Docker Daemon会接收Docker Client发货来的指令, 并对服务器进行具体的操作

### Docker Images
俗称Docker的镜像.这个看不懂,暂时可以认为这个就像我们要给电脑安装系统用的系统盘 里面有操作系统的程序, 并且还有一些系统盘在系统的基础上还装了Microsoft Office 做成一张只读的CD

### Docker Registry
大概就是Docker Images的repo 类似git的仓库一样 用来管理Docker Images, 提供Docker Images的上传下载和浏览等 并且提供安全账号管理 可以管理只有私人可见的私人Image. 就像git的仓库一样 docker也提供的官方Registry叫做[Dock Hub](hub.Docker.com).
