# dd

执行下面的命令，拷贝并生成一个指定大小的新文件。

```
dd if=/dev/zero of=file.txt bs=500M count=1
```

执行下面的命令，拷贝指定文件的前指定字节。

```
dd if=file.txt of=newfile.txt bs=50 count=1
```

执行下面的命令，拷贝指定文件，并将所有字符转换为大写。

```
dd if=file.txt of=newfile.txt conv=ucase
```

执行下面的命令，由标准输入设备读入字符串，并将字符串转换成小写后，再输出到标准输出设备。

```
dd conv=lcase
```

