# traceroute

执行下面的命令，追踪本地数据包到指定网站的传输路径。

```
traceroute www.google.com
```

执行下面的命令，设置指定的跳数。

```
traceroute -m 3 www.google.com
```

执行下面的命令，只显示 IP 地址，不显示主机名。

```
traceroute -n www.google.com
```

执行下面的命令，设置指定的探测包个数。

```
traceroute -q 4 www.google.com
```

执行下面的命令，设置指定的探测包等待响应时间。

```
traceroute -w 3 www.google.com
```

执行下面的命令，设置指定的发送端口。

```
traceroute -p 6888 www.google.com
```

执行下面的命令，直接发送到网络相连主机。

```
traceroute -r www.google.com
```

