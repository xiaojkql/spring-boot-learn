## docker基本使用
进入命令行: docker bash: docker exec -it mysql bash
退出命令行: 如果要退出bash有2种操作：1）Ctrl + d 退出并停止容器；2）Ctrl + p + q 退出并在后台运行容器

[配置阿里云加速](https://blog.csdn.net/shijiujiu33/article/details/90540031)
[开机自动启动](https://www.cnblogs.com/liubiaos/p/10600513.html)

### mysql
启动： docker run -p 3306:3306 --name mysql02 -e MYSQL_ROOT_PASSWORD=123456 -d mysql
登录mysql； mysql -u root -proot 设置的密码为 root
select host,user,plugin,authentication_string from mysql.user;
ALTER USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY 'newpassword'; #更新一下用户的密码 root用户密码为newpassword
