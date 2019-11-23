关闭端口
- netstat -nao | findstr "8080" 查询占用端口的线程
- taskkill -pid 线程 -f
