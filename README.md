# outline代码
outline官方地址：https://getoutline.org/

服务器上使用的代码：

1： sudo -i

2： curl -sS https://get.docker.com/ | sh

3：systemctl start docker

4：systemctl enable docker

5：systemctl status docker

6：wget -qO- https://raw.githubusercontent.com/Jigsaw-Code/outline-server/master/src/server_manager/install_scripts/install_server.sh | bash

在电脑上下载安装 outline 管理端 （地址就是他们主页）
outline1


然后在想要使用的平台上下载相应的客户端（地址依旧是他们主页）
outline2

谷歌云防火墙规则添加 （位置在谷歌云 VPC网络-防火墙）
点击添加新规则，然后按照一下这个设置好。这样 SSR 设置任何端口都可以使用。并且后续不需要再来防火墙规则做设置了。缺点是 所有端口开放。当然也会有一些危险。

<img>https://github.com/Fredbrookyang/freessl/blob/master/daima1/3.png<img>
