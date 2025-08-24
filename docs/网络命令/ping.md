# ping

执行下面的命令，测试与指定网站的连通性。

```
ping www.google.com
```

执行下面的命令，测试指定次数与指定网站的连通性。

```
ping -c 4 www.google.com
```

执行下面的命令，测试指定次数与指定网站的连通性，并添加时间间隔。

```
ping -c 4 -i 3 www.google.com
```

执行下面的命令，设置指定数据包大小和生存时间。

```
ping -s 1024 -t 255 www.google.com
```

