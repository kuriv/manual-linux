# chattr

执行下面的命令，为指定的文件添加限制，防止其被修改。

```
sudo chattr +i file.txt
```

执行下面的命令，为指定的文件删除限制。

```
sudo chattr -i file.txt
```

执行下面的命令，为指定的文件添加限制，只允许追加内容。

```
sudo chattr +a file.txt
```

执行下面的命令，为指定目录中所有文件添加限制，防止其被修改。

```
sudo chattr -R +i dir
```

