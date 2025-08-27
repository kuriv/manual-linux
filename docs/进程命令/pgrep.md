# pgrep

执行下面的命令，查找指定进程的 PID 。

```
pgrep ssh
```

执行下面的命令，查找指定用户启动的指定进程的 PID 。

```
pgrep -u kuriv ssh
```

执行下面的命令，查找指定进程的名称和 PID 。

```
pgrep -l ssh
```

执行下面的命令，使用正则表达式查找指定进程的 PID 。

```
pgrep '^ssh'
```

