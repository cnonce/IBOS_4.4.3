# IBOS_4.4.3
Installation package：
http://ibosupgrade.oss-cn-hangzhou.aliyuncs.com/release/pro/v4.4.3/IBOS_4.4.3_Pro_20180109162650_install.zip

In the installation interface, the company's full name is not filtered, resulting in cross-site scripting vulnerability

poc：<script>alert(/xss/)</script>
![](http://t1.aixinxi.net/o_1c9obspd21ql1980u4me2mhv5a.png-j.jpg)

After the installation is complete, visit Personal Office -> Contacts and trigger cross-site scripting vulnerability
![](http://t1.aixinxi.net/o_1c9obt5bmb9n1b3r1sp4ntkc23a.png-j.jpg)
![](http://t1.aixinxi.net/o_1c9obte6ihm11c03rjcgi1u4la.png-j.jpg)
