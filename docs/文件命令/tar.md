# tar

执行下面的命令，打包当前目录下所有文本文件。

```
tar -cvf file.tar *.txt
```

执行下面的命令，打包当前目录下所有文本文件，同时进行压缩。

```
tar -zcvf file.tar.gz *.txt
```

执行下面的命令，解压文件到当前目录。

```
tar -zxvf file.tar.gz
```

执行下面的命令，解压文件到指定目录下。

```
tar -zxvf file.tar.gz -C dir
```

执行下面的命令，列出压缩包中的内容。

```
tar -tf file.tar.gz
```

