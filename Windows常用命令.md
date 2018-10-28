根据pid查询进程占用端口
```
netstat -ano | grep ${pid} -a
```
统计指定目录下文件夹个数
```
当时查看c盘根目录实际是11个文件夹, 但返回结果是10
dir /b d:\aaa | find /v /c "::"
```
统计当前目录下 文件个数
```
dir /b /a-d | find /v /c ""
```
