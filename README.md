# OUTLINE代码
outline官方地址：https://getoutline.org/

服务器上使用的代码：

代码1： 
<pre><code>sudo -i</code></pre>

代码2： 
<pre><code>curl -sS https://get.docker.com/ | sh</code></pre>

代码3：<pre><code>systemctl start docker</code></pre>

代码4：<pre><code>systemctl enable docker</code></pre>

代码5：<pre><code>systemctl status docker</code></pre>

代码6：<pre><code>wget -qO- https://raw.githubusercontent.com/Jigsaw-Code/outline-server/master/src/server_manager/install_scripts/install_server.sh | bash</code></pre>

在电脑上下载安装 outline 管理端 （地址就是他们主页）
outline1
![linear](https://github.com/Fredbrookyang/freessl/blob/master/daima1/38570402-56fcdae4-3d20-11e8-9f86-580c34adc83d.png)

然后在想要使用的平台上下载相应的客户端（地址依旧是他们主页）
outline2
![linear](https://github.com/Fredbrookyang/freessl/blob/master/daima1/38570513-9b6ec7fa-3d20-11e8-9018-dfea764e36a9.png)
谷歌云防火墙规则添加 （位置在谷歌云 VPC网络-防火墙）
点击添加新规则，然后按照一下这个设置好。这样 SSR 设置任何端口都可以使用。并且后续不需要再来防火墙规则做设置了。缺点是 所有端口开放。当然也会有一些危险。

![linear](https://github.com/Fredbrookyang/freessl/blob/master/daima1/3.png)
