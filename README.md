# make-google-ip-make-google-hosts-
你需要一台境外的，443，80端口未被封锁和占用的vps


You need an outside China, 443,80 port is not blocked and occupied vps.


然后安装xinetd


Then install xinetd.


在/etc/xinetd.d中创建文件'https','http',并且分别复制以下内容到这两个文件中


Create  files named 'https' and 'http' in /etc/xinetd.d, and were content to copy the following two files.


下一步，重启xinetd

Next step,restart your xinetd service.

最后，修改你的Google hosts,将有关google字段的ip全部指向你的vps ip(字段中带有rxx-xxxxxxxx的除外)

Finally, modify your Google hosts, the relevant fields ip google all point to your vps ip (except rxx-xxxxxxxx field with)
