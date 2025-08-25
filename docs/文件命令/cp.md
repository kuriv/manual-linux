# cp

执行下面的命令，复制指定文件。

```
cp file.txt newfile.txt
```

执行下面的命令，若目标文件已存在，则询问是否覆盖。

```
cp -i file.txt newfile.txt
```

执行下面的命令，若目标文件已存在，则直接覆盖。

```
cp -r file.txt newfile.txt
```

执行下面的命令，若目标文件已存在，则在覆盖之前备份。

```
cp -b file.txt newfile.txt
```

执行下面的命令，复制指定目录。

```
cp -r dir newdir
```

执行下面的命令，复制指定目录，并且保留源目录所有文件属性一致。

```
cp -a dir1 dir2
```

