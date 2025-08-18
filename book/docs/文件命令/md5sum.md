# md5sum

执行下面的命令，计算指定文件的 md5 值。

```
md5sum file.txt
```

执行下面的命令，使用不同模式计算指定文件的 md5 值。

```
md5sum -b file.txt
md5sum -t file.txt
```

执行下面的命令，计算指定文件的 md5 值，并重定向到另一个文件中。

```
md5sum file.txt > file.md5
```

执行下面的命令，执行 md5 校验。

```
md5sum -c file.md5
```

执行下面的命令，执行 md5 校验，但不显示任何输出，而是用返回码表示成功与否。

```
md5sum -c --status file.md5
echo $?
```

