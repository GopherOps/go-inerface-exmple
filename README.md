# go-interface-exmple
```
# 而后在模板配置文件中调用变量
# grep -E "(^Listen|^ServerName)"   /files/httpd.conf
Listen {{ http_port }}
ServerName {{ server_name }}
```
