# 内网穿透

## 参考教程
https://ding-doc.dingtalk.com/doc#/kn6zg7/hb7000


# pierced
钉钉内网穿透

TCP 穿透需要在数据库里面执行：
GRANT ALL PRIVILEGES ON *.* TO root@'%' IDENTIFIED BY '123456';
FLUSH PRIVILEGES;
数据库连接命令：
mysql -h vaiwan.com -u root -p -P 1234 //端口号地址
