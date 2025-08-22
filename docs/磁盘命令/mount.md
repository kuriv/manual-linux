# mount

执行下面的命令，查看当前系统中挂载的所有文件系统信息。

```
mount
```

执行下面的命令，查看指定类型挂载的文件系统。

```
mount -t tmpfs
```

执行下面的命令，将 U 盘挂载到指定目录。

```
sudo fdisk -l | grep sd
sudo mount /dev/sdb /mnt/udisk
```

执行下面的命令，使用只读模式挂载。

```
sudo mount -o ro /dev/sdb /mnt/udisk
```

