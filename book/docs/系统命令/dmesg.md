# dmesg

执行下面的命令，显示开机信息。

```
sudo dmesg | less
```

执行下面的命令，显示开机信息，并过滤出相关内容。

```
sudo dmesg | grep -i memory
sudo dmesg | grep -i dma
sudo dmesg | grep -i usb
sudo dmesg | grep -i tty
```

执行下面的命令，显示信息级别。

```
sudo dmesg -x
```

执行下面的命令，只输出指定级别的信息。

```
sudo dmesg --level=err,warn
```

执行下面的命令，显示时间戳。

```
sudo dmesg -T
```

执行下面的命令，显示原始数据。

```
sudo dmesg -r
```

执行下面的命令，清空缓冲区中的日志数据。

```
sudo dmesg -c
```

