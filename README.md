Linux.Apache-PHP-MySQL
======================
http://www.cnblogs.com/rainisic/archive/2012/05/23/Linux_Apache2_4_Install.html
http://www.cnblogs.com/rainisic/archive/2012/05/23/2515131.html

PHP configure：
sudo ./configure --prefix=/usr/local/php --with-apxs2=/usr/local/apache/bin/apxs --with-config-file-path=/usr/local/php/etc

中间出现提醒：libxml2未安装
  使用sudo apt-get install libxml2 安装失败；sudo apt-get install update后重试成功。
