
1.hosts所在文件夹：

Windows 系统hosts位于 C:\Windows\System32\drivers\etc\hosts

Android（安卓）系统hosts位于 /etc/hosts

Mac（苹果电脑）系统hosts位于 /etc/hosts

iPhone（iOS）系统hosts位于 /etc/hosts

Linux系统hosts位于 /etc/hosts

绝大多数Unix系统都是在 /etc/hosts

2.注意：

Google、Gmail、维基百科、Twitter、Facebook等必须请用https加密方式打开,一般这些网站都是SSL加密链接，如：

谷歌学术：https://scholar.google.com/

谷歌：https://www.google.com/ncr

谷歌香港：https://www.google.com.hk/ncr

Twitter：https://twitter.com/?lang=zh-cn

3.修改hosts后生效方法：

Windows开始 -> 运行 -> 输入cmd -> 在CMD窗口输入  ipconfig /flushdns

Linux终端输入  sudo rcnscd restart

systemd发行版，请使用命令  sudo systemctl restart NetworkManager

Mac OS X终端输入  sudo killall -HUP mDNSResponder

Android  开启飞行模式 -> 关闭飞行模式

长期更新！
