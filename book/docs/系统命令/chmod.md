# chmod

执行下面的命令，将指定文件设置为所有人可读取。

```
sudo chmod a+r file.txt
```

执行下面的命令，将当前目录下所有文件及其递归目录文件设置为所有人可读取。

```
sudo chmod -R a+r *
```

执行下面的命令，将指定文件设置为仅文件拥有者可执行。

```
sudo chmod u+x file.txt
```

执行下面的命令，将指定文件设置为所有人可读可写可执行。

```
sudo chmod a+r,a+w,a+x file.txt
sudo chmod 777 file.txt
```

