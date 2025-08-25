# scp

执行下面的命令，下载指定的文件。

```
scp kuriv@192.168.10.233:/home/kuriv/file.txt .
```

执行下面的命令，下载指定的目录。

```
scp -r kuriv@192.168.10.233:/home/kuriv/dir .
```

执行下面的命令，上传指定的文件。

```
scp newfile.txt kuriv@192.168.10.233:/home/kuriv/
```

执行下面的命令，上传指定的目录。

```
scp -r newdir kuriv@192.168.10.233:/home/kuriv/
```

