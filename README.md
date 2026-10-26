# Linux-CourseTasks
在这个里面做一些课程设计的记录，软件为Ubuntu 64-bit - VMware Workstation

其实在做这个课设之前，我想的是安装todesk这个软件，从而通过虚拟机和自己的电脑相连，这样复制粘贴一些代码较为方便
但是我后来放弃了，因为直接下一个Google浏览器就能解决所有问题。
# 🌐 Ubuntu 终端安装 Google Chrome 指南
## 📦 安装步骤
在 Ubuntu 终端中，首先使用 `wget` 命令从官方链接下载 `.deb` 安装包：
```bash
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
接着通过 apt 命令完成安装
sudo apt install ./google-chrome-stable_current_amd64.deb
安装后，输入 google-chrome 或在系统的应用菜单中即可启动浏览器

通过Google浏览器，你是不能访问国内某些ai网站的，只能通过中转的方式（如baidu.com等等这些国内的网页）
我下载Google浏览器主要是为了用Deepseek或者豆包，这里有一个好处，Deepseek你同时在2个浏览器登陆并且使用是不会产生系统互斥的问题的
这种linux系统的虚拟机的终端的话，复制粘贴和电脑的方式不同，它是Ctrl+Shift+C/V

